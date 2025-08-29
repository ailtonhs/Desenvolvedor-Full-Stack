# Para que servem as tabelas HTML e para que não devem ser usadas?

As tabelas HTML não são tão usadas hoje em dia como antigamente. Mas, como desenvolvedor front-end, você ainda deve estar familiarizado com elas. As tabelas foram uma das primeiras maneiras que os desenvolvedores tiveram de exibir dados em um navegador, lá na década de 1990.

Aqui está um exemplo de código usado para gerar uma tabela do Bureau of Labor Statistics dos EUA:
```html
<table id="quickfacts">
  <thead>
    <tr>
      <th colspan="2">Quick Facts: Software Developers, Quality Assurance Analysts, and Testers</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2023 Median Pay</th>
      <td>
        $130,160 per year
        <br>$62.58 per hour
      </td>
    </tr>
    <tr>
      <th>Typical Entry-Level Education</th>
      <td>Bachelor's degree</td>
    </tr>
    <tr>
      <th>Work Experience in a Related Occupation</th>
      <td>None</td>
    </tr>
    <tr>
      <th>On-the-job Training</th>
      <td>None</td>
    </tr>
    <tr>
      <th>Number of Jobs, 2022</th>
      <td>1,795,300</td>
    </tr>
    <tr>
      <th>Job Outlook, 2022-32</th>
      <td>25% (Much faster than average)</td>
    </tr>
    <tr>
      <th>Employment Change, 2022-32</th>
      <td>451,200</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th>If this table had a footer it would be here.</th>
    </tr>
  </tfoot>
</table>
```
Como você pode ver, há um **table** elemento principal com um **id** conjunto definido como **quickfacts**. Dentro dele, a tabela tem um elemento de cabeçalho, **thead**, um elemento de corpo, **tbody**, e um elemento de rodapé, **tfoot**.

Os elementos cabeçalho, corpo e rodapé da tabela podem conter, cada um, um certo número de linhas de tabela. **tr** E cada linha da tabela pode conter um cabeçalho de tabela **th** que rotula os dados dessa linha. Ele também pode conter um certo número de células de dados individuais, chamadas dados da tabela **td**.

Aqui está a tabela mais simples que podemos criar, incluindo todos esses elementos:
```html
<table>
  <thead>
    <tr>
      <th>The title of this table</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>First Row</th>
      <td>
        First Data Cell
      </td>
    </tr>
    <tr>
      <th>Second Row</th>
      <td>
        Second Data Cell
      </td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th>The footer of this table, which might contain date of publication, author credits, or other meta information.</th>
    </tr>
  </tfoot>
</table>
```
Então, como você pode ver, os dados em si estão sempre dentro de um **tr** e dentro desse **tr** elemento há um **th** elemento com um cabeçalho e um **td** elemento com dados.

Alguns sites escolherão usar **divs** para criar suas próprias tabelas em vez de usar o **table** elemento mais apropriado.

Embora seja possível exibir dados tabulares usando **div** elementos genéricos, ainda é melhor usar o **table** elemento .

Há muitos anos, os desenvolvedores usavam um **table** para posicionar elementos que não eram dados em uma página web. Isso nunca foi considerado uma prática recomendada. Mas você pode encontrar algumas bases de código em que tabelas ainda são usadas dessa forma.

Hoje em dia, os desenvolvedores usam CSS flexbox e grid para fazer o layout de seus designs. O freeCodeCamp abordará essas ferramentas em detalhes mais tarde.

Por enquanto, use apenas tabelas HTML para o propósito original: exibir dados tabulares.

