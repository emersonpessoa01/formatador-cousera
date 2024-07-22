# Tarefa avaliada por colega: Formas de Tratamento

Crie uma interface chamada FormatadorNome que possui o método String formatarNome(String nome, String sobrenome).

Crie uma classe chamada Autoridade que possui atributos como nome, sobrenome e uma instância de FormatadorNome. Essa classe deve possuir um método getTratamento() que delega a formatação do nome para a instância de FormatadorNome.

Crie a seguintes implementações da interface FormatadorNome:

  - Informal: retorna somente o primeiro nome

  - Respeitoso: deve receber em seu construtor a informação se é masculino ou feminino, e retornar "Sr." ou "Sra." seguido do sobrenome

  - ComTítulo: deve receber em seu construtor o título e retornar o título seguido de nome e sobrenome. Exemplo: "Magnífico Pedro Cabral"

### Crie testes de unidade que fazem os testes da classe Autoridade com cada uma das implementações da interface. 

<details><summary>Visão geral dos critérios de avaliação</summary>
Serão verificados se os itens pedidos no enunciado foram cumpridos. Procure entregar um código organizado pois isso também será avaliado. 
</details>

<details><summary>Métodos Equals e hashCode</summary>
O método equals() é utilizado para a comparação de objetos. Ele é definido na classe Object e pode ser sobrescrito em qualquer classe que possua uma lógica diferente. 
  
O método hashCode() também é definido na classe Object e retorna o código hash de um objeto, que é utilizado em várias classes que implementam estruturas de dados. Ele precisa obedecer a seguinte regra: quando o método equals() retornar true, o retorno de hashCode() desses objetos precisa ser igual. Mas se o retorno do hashCode() for igual, não  necessariamente os objetos são iguais, ou seja, o equals() pode retornar  true ou false.   

É importante respeitar essa regra para que algumas classes como HashSet e HashMap funcionem corretamente!
</details>
