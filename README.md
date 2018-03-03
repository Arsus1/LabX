# LabX
Проект LabX создан для того, чтобы сделать обучение физике максимально интересным. Пользуясь данным продуктом, пользователь не только сможет детально разобрать базовые законы кинематики и динамики, но и научиться программировать. Среда обладает удобным пользовательским интерфейсом, что также способствует качественному обучению. 
 
 
![LabX](img/labe2.png)

# Программирование в среде LabX

Решение физических задач и описание физических процессов в среде LabX, реализуется на языке JavaScript.

Основные функции языка JavaScript:
<H3> 1.	Печать в консоль: </H3>
<pre class="javascript" style="font-family:monospace;"><ol><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">print<span style="color: #009900;">&#40;</span><span style="color: #009900;">&#41;</span><span style="color: #339933;">;</span>  </div></li></ol></pre>
<H3>2.	Создание переменных:</H3>
<pre class="javascript" style="font-family:monospace;"><ol><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #000066; font-weight: bold;">var</span> a <span style="color: #339933;">=</span> <span style="color: #3366CC;">&quot;text&quot;</span><span style="color: #339933;">;</span>  </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #000066; font-weight: bold;">var</span> b <span style="color: #339933;">=</span> <span style="color: #CC0000;">10</span><span style="color: #339933;">;</span>  </div></li></ol></pre>
<em>На имя переменной в JavaScript наложены всего два ограничения.
Имя может состоять из: букв, цифр, символов $ и _
Первый символ не должен быть цифрой.
Так как JavaScript является слабо типизированным языком программирования, при создании переменных не нужно указывать их тип. Достаточно просто присвоить значение.</em>
<h3>3.	Условные операторы:</h3>
<pre class="javascript" style="font-family:monospace;"><ol><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #000066; font-weight: bold;">if</span> <span style="color: #009900;">&#40;</span>year <span style="color: #339933;">&lt;</span> <span style="color: #CC0000;">2018</span><span style="color: #009900;">&#41;</span> <span style="color: #009900;">&#123;</span>  </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">    print<span style="color: #009900;">&#40;</span> <span style="color: #3366CC;">&quot;Это слишком рано..&quot;</span> <span style="color: #009900;">&#41;</span><span style="color: #339933;">;</span>  </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #009900;">&#125;</span> <span style="color: #000066; font-weight: bold;">else</span> <span style="color: #000066; font-weight: bold;">if</span> <span style="color: #009900;">&#40;</span>year <span style="color: #339933;">&gt;</span> <span style="color: #CC0000;">2018</span><span style="color: #009900;">&#41;</span> <span style="color: #009900;">&#123;</span>  </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">    print<span style="color: #009900;">&#40;</span> <span style="color: #3366CC;">&quot;Это поздновато..&quot;</span> <span style="color: #009900;">&#41;</span><span style="color: #339933;">;</span>  </div></li><li style="font-weight: bold; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #009900;">&#125;</span> <span style="color: #000066; font-weight: bold;">else</span> <span style="color: #009900;">&#123;</span>  </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">    print<span style="color: #009900;">&#40;</span> <span style="color: #3366CC;">&quot;Да, точно в этом году!&quot;</span> <span style="color: #009900;">&#41;</span><span style="color: #339933;">;</span>  </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #009900;">&#125;</span>  </div></li></ol></pre> 



<h3>4.	Циклы</h3>
<em>Цикл while:</em>
<pre class="javascript" style="font-family:monospace;"><ol><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">while <span style="color: #009900;">&#40;</span>условие<span style="color: #009900;">&#41;</span> <span style="color: #009900;">&#123;</span>  </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">  <span style="color: #006600; font-style: italic;">// код, тело цикла  </span></div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #009900;">&#125;</span>  </div></li></ol></pre>
<em>Цикл for:</em>
<pre class="javascript" style="font-family:monospace;"><ol><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #000066; font-weight: bold;">for</span> <span style="color: #009900;">&#40;</span>начало<span style="color: #339933;">;</span> условие<span style="color: #339933;">;</span> шаг<span style="color: #009900;">&#41;</span> <span style="color: #009900;">&#123;</span>  </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">  <span style="color: #006600; font-style: italic;">// ... тело цикла ...  </span></div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #009900;">&#125;</span>  </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">&nbsp;</div></li></ol></pre>

<pre class="javascript" style="font-family:monospace;"><ol><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #000066; font-weight: bold;">var</span> i<span style="color: #339933;">;</span>  </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">&nbsp;</div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #000066; font-weight: bold;">for</span> <span style="color: #009900;">&#40;</span>i <span style="color: #339933;">=</span> <span style="color: #CC0000;">0</span><span style="color: #339933;">;</span> i <span style="color: #339933;">&lt;</span> <span style="color: #CC0000;">3</span><span style="color: #339933;">;</span> i<span style="color: #339933;">++</span><span style="color: #009900;">&#41;</span> <span style="color: #009900;">&#123;</span>  </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">  print<span style="color: #009900;">&#40;</span> i <span style="color: #009900;">&#41;</span><span style="color: #339933;">;</span>  </div></li><li style="font-weight: bold; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #009900;">&#125;</span>  </div></li></ol></pre>

Код проектов LabX исполняется в цикле.
<em>(соответственно если вызвать метод print(); в основном теле программы, текст будет печататься в консоль непрерывно)</em>

Для того чтобы задать константы для проекта или напечатать текст один раз в начале выполнения проекта,  в LabX предусмотрен специальный тип комментариев:

<pre class="javascript" style="font-family:monospace;"><ol><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;"><span style="color: #339933;">/</span># </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">print<span style="color: #009900;">&#40;</span><span style="color: #3366CC;">&quot;Начало выполнения программы&quot;</span><span style="color: #009900;">&#41;</span><span style="color: #339933;">;</span>  </div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">#<span style="color: #339933;">/</span> </div></li></ol></pre>

<h3>Служебные константы и объекты системы LabX</h3>
<H4>1. Служебный объект Running:</H4>
Отвечает за цикл симуляции физики.
<em>Функции и методы:</em>
<pre class="javascript" style="font-family:monospace;"><ol><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">Running.<span style="color: #000066; font-weight: bold;">set</span><span style="color: #009900;">&#40;</span><span style="color: #003366; font-weight: bold;">false</span><span style="color: #009900;">&#41;</span><span style="color: #339933;">;</span>  </div></li></ol></pre>
Завершает симуляцию физики.
<pre class="javascript" style="font-family:monospace;"><ol><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">Running.<span style="color: #000066; font-weight: bold;">get</span><span style="color: #009900;">&#40;</span><span style="color: #009900;">&#41;</span><span style="color: #339933;">;</span>  </div></li></ol></pre>
Возвращает состояние цикла симуляции.
<H4>2.	Служебная переменная TIME</H4>
В данной переменной хранится текущее время (в секундах) с начала работы программы.
# Создание физических объектов
В языке программирования LabX предусмотрена возможность создания специальных шарообразных объектов, со следующими атрибутами:
<ul>
 <li>масса</li>
 <li>координаты</li>
 <li>проекции скорости и ускорения на оси координат</li>
 <li>цвет</li>
</ul>

Соответственно:
<ul>
<li><em>m</em> - масса объекта</li>
<li><em>x</em> - координата x объекта</li>
<li><em>y</em> - координата y объекта</li>
<li><em>vx</em> - проекция скорости объекта на ось x</li>
<li><em>vy</em> - проекция скорости объекта на ось y</li>
<li><em>ax</em> - проекция ускорения на ось x</li>
<li><em>ay</em> - проекция ускорения на ось y</li>
</ul>
<table>
 <tr>
  <td><b>Название</b></td>
  <td><b>Расшифровка</b></td>
  <td><b>Цвет</b></td>
  </tr>
  <tr>
    <td>“black”</td>
   <td>Черный</td>
   <td><canvas id="black" width="300" height="225"></canvas>
   <script type="application/javascript">
    function draw() {
      var canvas = document.getElementById('black');
      if (canvas.getContext) {
        var ctx = canvas.getContext('2d');

        ctx.fillStyle = 'rgb(200, 0, 0)';
        ctx.fillRect(10, 10, 50, 50);

        ctx.fillStyle = 'rgba(0, 0, 200, 0.5)';
        ctx.fillRect(30, 30, 50, 50);
      }
    }
  </script>
   </td>
  </tr>
</table>
