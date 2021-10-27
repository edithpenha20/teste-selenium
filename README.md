## Teste de Ponta a Ponta com Selenium

### Em que consiste a aplicação...
Esta aplicação consiste em um sistema de leilões, no qual as pessoas podem cadastrar leilões ou dar lances para comprar produtos. Onde:

- Para cadastrar um leilão ou dar um lance, é necessário fazer login na aplicação;
- Existe um usuário previamente cadastrado com o nome "fulano" e a senha "pass".
- Ao inserirmos os dados de login seremos levados de volta à tela de leilão, mas com algumas opções a mais;
- Ao cadastrar um leilão, não podemos dar um lance, somente editá-lo;
- Se for um leilão criado por outro usuário, poderemos dar lances;
- Ao preencher o campo "Novo lance" e clicarmos em "Dar lance!" a página será atualizada e o novo lance será exibido na listagem;
- Se tentarmos submeter um novo lance, receberemos um erro - pois não deve ser possível que um mesmo usuário dê dois lances na sequência.

___________

### Tecnologias utilizadas:
- Java 8 (ou versões superiores);
- Maven 3.6.3 ou versões superiores;
- Spring Data JPA;
- Spring Web;
- Spring Boot;
- Thymeleaf.

### Testes que foram realizados

 - testes relativos à funcionalidade de login;
 - testes no cadastro de leilão;
 - boas práticas de programação nos testes com Selenium usando Page Objects que são utilizadas para armazenar toda a manipulação da API do Selenium e nas classes de teste somente a API do JUnit.
