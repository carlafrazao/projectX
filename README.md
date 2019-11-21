# ProjectX

Esse projeto serve como modelo de automação usando Selenium e C#.

Execução

É necessário fazer o download deste repositório para ujm repositório local. 

Para que seja executado de forma paralela, é necessário selecionar esta opção no próprio VS. Esta configuração se extende à execução automática usando o Azure Devops, caso utilize o mesmo para intergação contínua.

Observações:

- Para que os testes sejam executados em determinado browser, é necessário passar o browser desejado, tais como Firefox, Chrome e IE.
  Nesta versão não é possível abrir e fechar browsers diferentes ao mesmo tempo. Considere utilizar um de cada vez.
- Na classe Reporter existem duas variáveis que precisam ser alteradas para que o report seja criado na pasta certa. São reportPath: pra onde você deseja enviar o relatório e a extentConfigPath: o caminho do seu arquivo de configuração XML.

Sabendo disso, basta executar os testes para gerar o relatório.

V1.0
