<h1 class="title">Двоякие числа (27%)</h1>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 27%</b></p>
<p>Трёхчлен a + bx + сy от двух переменных x и y однозначно определяется коэффициентами a, b и c. Написать программу, которая по заданным a, b и c выводит соответствующий трёхчлен, записанный с использованием алгебраических соглашений:</p>
<ul>
    <li>коэффициент при члене, содержащем переменную, опускается, если его модуль равен единице;</li>
    <li>член, коэффициент при котором равен нулю, опускается (кроме случая, когда все коэффициенты равны нулю, тогда трехчлен состоит из одной цифры 0);</li>
    <li>знак "+" опускается, если он предшествует отрицательному коэффициенту;</li>
    <li>знак "+" опускается, если он стоит в начале выражения (так называемый унарный плюс);</li>
    <li>знак умножения между коэффициентом и переменной опускается.</li>
</ul>
<p>При этом запрещено менять местами члены.</p>
<h2>Формат ввода</h2>
<p>Во входном файле input.txt через пробел записаны целые коэффициенты a, b и с, каждое из которых не превосходит 30000 по абсолютной величине.</p>
<h2>Формат вывода</h2>
<p>Выходной файл output.txt должен содержать трехчлен, записанный с использованием алгебраических соглашений.</p>
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
        <td>0 2 -1</td>
        <td>2x-y</td>
     </tr>
     <tr>
         <td>3 0 -2</td>
         <td>3-2y</td>
     </tr>
  </tbody>
</table>