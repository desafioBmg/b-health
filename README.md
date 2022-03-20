# B-Health
Você é o novo tech lead da squad que cuida do sistema de agendamento de exames, que está com os seguintes problemas:

1) Diariamente todos os hospitais enviam via FTP um arquivo para atualizar os exames, que são processados por um robô que faz a classificação e inclusão no banco de dados. Neste processo ocorrem diversos erros, como processamento de arquivos muito grandes, concorrência de I/O, falha no upload/download do arquivo, que deixam os exames desatualizados. Ficou definido com os hospitais que a comunicação não deverá mais ser feito por arquivos.
   - Qual solução você daria para essa integração? Descreva a solução e a arquitetura que você faria.
   * [Solução 01](./Solucao01/Solucao01.md "Solução 01")

2) Existe um front-end que o cliente final pode agendar exames, realizar o pagamento e consultar os dados do hospital. Da forma que foi construída, cada consulta dos exames abre uma conexão com o banco e nosso banco permite até 100 conexões simultâneas. Com novos hospitais sendo integrados, hoje já tem mais de 1000 usuários acessando o site ao mesmo tempo, com muitas reclamações de performance e erros de consulta. 
   - Qual solução você daria para que suporte o aumento contínuo de usuários simultâneos, sem envolver alguma alteração de hardware (servidores e bancos)? Descreva a solução e a arquitetura que você faria.
   * [Solução 02](./Solucao02/Solucao02.md "Solução 02")

3) Pensando nas soluções propostas dos itens anteriores, quais boas práticas você aplicaria no processo de entrega em produção, pensando nos conceitos de disponibilidade, qualidade e segurança?
   * [Solução 03](./Solucao03/Solucao03.md "Solução 03")

## Algumas informações extras:

- Para os desenhos de solução, você pode utilizar ferramentas como draw.io ou lucidchart ou até o Paint.
- A documentação pode ser entregue em um arquivo texto ou Word.
- Não é necessário codificar as soluções, mas caso tenha interesse, podem ser desenvolvidas em qualquer linguagem ou framework.
- Para entrega das suas respostas, faça um fork desse repositório, comite os desenhos e documentações da solução e faça um pull request para avaliação

Boa sorte.