<h1>Портфолио: аналитик данных </h1>
<h2>Обо мне</h2>
Привет! Меня зовут Мария, я начинающий аналитик данных. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<h2>Навыки и технологии</h2>
<ul>
  <li>Инструменты анализа данных: SQL, Excel:</li>
  <li>Языки программирования и библиотеки: Python, Pandas, math</li>
  <li>Системы управления базами данных: MySQL, PostgreSQL</li>
  <li>Средства визуализации данных: PowerBi, Matplotlib, seaborn</li>
  <li>Инструменты для машинного обучения: scikit-learn, TensorFlow</li>
</ul>
<h2>Проекты</h2>
Проект 1: Калькулятор юнит-экономики онлайн-школы
<p>Что нужно было сделать:</p>
<ul>
 <li>Собирать с нуля калькулятор юнит-экономики.</li>
 <li>Настраивать визуализацию и условное форматирование калькулятора.</li>
</ul>
План решения задачи по сборке калькулятора:
<ul>
<li>Проанализировать исторические данные и собрать с помощью сводных таблиц различные показатели. Провести расчет сложных композитных показателей(LTL, TR, CAC). Свести воедино полученную информацию по юнит-экономике и рассчитать доли статей.</li>
<li>Теперь перейдем к сборке калькулятора. Расчитываем показатели "как есть" и какие они могут быть.</li>
<li>Визуализируем получившийся результат.</li>
</ul>
<p>Вывод:</p>
<p>Мы сделали универсальный аналитический инструмент — калькулятор юнит-экономики. По которому мы сможем оценить, как изменение того или иного показателя повлияет на нашу экономику.</p>
Проект 2: Моделирование изменения балансов студентов
<p>Что нужно было сделать:</p>
Смоделировать изменение балансов студентов. 
<p>План решения задачи:</p>
<ul>
 <li>Узнаем, когда была первая транзакция для каждого студента. </li>
 <li>Соберем таблицу с датами за каждый календарный день 2016 года.</li>
 <li>Узнаем, за какие даты имеет смысл собирать баланс для каждого студента.</li>
 <li>Найдем все изменения балансов, связанные с успешными транзакциями. </li>
 <li>Найдем баланс студентов, который сформирован только транзакциями.  </li>
 <li>Найдем изменения балансов из-за прохождения уроков. </li>
 <li>По аналогии с уже проделанным шагом для оплат создадим CTE для хранения кумулятивной суммы количества пройденных уроков.  </li>
 <li>Создадим CTE balances с вычисленными балансами каждого студента.</li>
 <li> Посмотрим, как менялось общее количество уроков на балансах студентов.</li>
</ul>
<p>Вывод:</p>
В результате мы получили запрос, который собирает данные о балансах студентов за каждый "прожитый" ими день.
