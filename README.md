# JDBC-recuperar-dados
Utilizando o JDBC, é possível recuperar dados de um banco de dados relacional de forma eficiente 
e flexível, permitindo a obtenção das informações necessárias para análise ou exibição no aplicativo.
## Interfaces utilizadas: <br>
o Connection <br>
o Statement <br>
o ResultSet <br>
    &nbsp; &nbsp; - first( ) *[move para posição 1, se houver]*<br>
    &nbsp; &nbsp; - beforeFirst( ) *[move para posição 0]*<br>
    &nbsp; &nbsp; - next( ) *[move para o próximo, retorna false se já estiver no último]*<br>
    &nbsp; &nbsp; - absolute(int) *[move para a posição dada, lembrando que dados reais começam em 1]*<br>
## Checklist:<br>
✓ Usar o script SQL para criar a base de dados "coursejdbc"<br>
✓ Fazer um pequeno programa para recuperar os departamentos<br>
✓ Na classe DB, criar métodos auxiliares estáticos para fechar  Connection, ResultSet e Statement<br>
