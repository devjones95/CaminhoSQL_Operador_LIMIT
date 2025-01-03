Temos aqui um exemplo de uso no operador LIMIT no SQL.
<br>
Como o próprio nome já diz, o LIMIT funciona como um delimitador na hora de mostrar o resultado da nossa query.
<br>
Por exemplo:
<br>
SELECT *
FROM actor
LIMIT 10
<br>
Resultado:

![Exemplo 1](https://github.com/user-attachments/assets/b050dc38-08e7-480b-8371-e67f27bf272c)
<br>

Exemplo 2
<br>
SELECT *
FROM actor
LIMIT 5, 10 -- me mostra os 10 resultados A PARTIR do 6º.
<br>
Resultado:

![Exemplo 2](https://github.com/user-attachments/assets/eda64cc0-b6d7-4bf4-b468-587bafa7214c)

