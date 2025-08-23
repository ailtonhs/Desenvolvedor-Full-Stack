# Como exibir horas e datas em HTML?

O **time** elemento é usado para representar um momento específico no tempo.

Aqui está um exemplo usando o **time** elemento para representar vintecentas horas, ou oito horas da noite.
```html
<p>The reservations are for <time datetime="20:00">20:00 </time></p>
```
O **datetime** atributo é usado para traduzir datas e horas em um formato legível por máquina.

Isso é importante porque ajuda nos resultados dos mecanismos de busca e auxilia o navegador a processar informações de data e hora de forma mais eficaz.

O valor do **datetime** atributo deve ser um ano válido, um mês válido, uma hora válida, uma data local, uma data global ou uma sequência de duração válida.

Aqui está outro exemplo de uso do elemento de tempo para representar uma data específica:
```html
  The graduation will be on <time datetime="2024-06-15T15:00">June 15</time>
```
O valor do **datetime** atributo está no formato ISO 8601. ISO 8601 é um padrão internacional para representar datas e horas.

A primeira parte desse valor é o ano, o mês e o dia. O "T" maiúsculo no valor é um separador entre a data e a hora.

As mil e quinhentas horas seriam três da tarde.

Sempre que você precisar representar eventos, datas de publicação ou compromissos, é melhor usar o **time** elemento .

