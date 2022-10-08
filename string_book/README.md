<h1 class="title">Строки в книге (13%)</h1>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 13%</b></p>
<p>В книге на одной странице помещается K строк. Таким образом, на 1-й странице печатаются строки с 1-й по K-ю, на второй — с (K+1)-й по (2∙K)-ю и т.д. Напишите программу, которая по номеру строки в тексте определяет номер страницы, на которой будет напечатана эта строка, и порядковый номер этой строки на странице.</p>
<h2>Формат ввода</h2>
<p>Входной файл input.txt содержит число K – количество строк, которое печатается на странице, и число N – номер строки (1 ≤ K ≤ 200, 1 ≤ N ≤ 20000).</p>
<h2>Формат вывода</h2>
<p>В выходной файл output.txt выведите два числа – номер страницы, на которой будет напечатана эта строка и номер строки на странице.</p>
<h3>Примеры</h3>
<table class="sample-tests">
  <thead>
     <tr>
        <th>Ввод</th>
        <th>Вывод</th>
     </tr>
  </thead>
  <tbody>
     <tr>
        <td>50 1</td>
        <td>1 1</td>
     </tr>
     <tr>
         <td>20 25</td>
         <td>2 5</td>
     </tr>
     <tr>
          <td>15 43</td>
          <td>3 13</td>
      </tr>
  </tbody>
</table>