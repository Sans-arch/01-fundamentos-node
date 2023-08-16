# Descrição

No Node, toda porta de entrada e saída é automaticamente uma STREAM
O chunk de uma stream nunca poderá estar num formato primitivo, temos que
trabalhar com o formato de buffer.
Stream de escrita vai receber dados de uma Stream de leitura e vai fazer
alguma coisa com esses dados.
Por exemplo, o process.stdout é uma Stream de Escrita, é uma stream que processa dados.
Stream de escrita PROCESSA o dado, nunca vai retornar o dado ou transformar em outra coisa.
Stream de transformação serve para transformar um dado em outro.
Stream Duplex pode ter tanto o método de leitura quanto o de escrita, ou seja, pode fazer
qualquer tipo de operação, tanto leitura quanto escrita.
