<!DOCTYPE html>
<html lang="ru">
<head>
<body>
<h2>Homework 12.3</h2>
<h3>Расчет параметров кластера</h3>
<table cellspacing="0" boreder="1">
	<tr>
		<td><b>Наименование</b></td>
		<td><b>На одну ноду</b></td>
		<td><b>Число нод</b></td>
		<td><b>Всего</b></td>
		<td><b>Коэф резервирования</b></td>
		<td><b>Итого</b></td>
	</tr>
	<tr>
		<td  colspan=5  align="center" valign=middle bgcolor="#FFFFFF"><b>Дисковые ресурсы</b></td>
		<td  bgcolor="#FFFFFF"><b>232,5</b></td>
	</tr>
	<tr>
		<td>БД</td>
		<td>20</td>
		<td>3</td>
		<td >60</td>
		<td>1,5</td>
		<td>90</td>
	</tr>
	<tr>
		<td>Кэш</td>
		<td>20</td>
		<td>3</td>
		<td >60</td>
		<td>1,5</td>
		<td >90</td>
	</tr>
	<tr>
		<td>Фронт</td>
		<td >1</td>
		<td>5</td>
		<td>5</td>
		<td>1,5</td>
		<td >7,5</td>
	</tr>
	<tr>
		<td>Бэк</td>
		<td>3</td>
		<td>10</td>
		<td>30</td>
		<td>1,5</td>
		<td>45</td>
	</tr>
	<tr>
		<td colspan=5 align="center" valign=middle bgcolor="#FFFFFF"><b>Ядра CPU</b></td>
		<td bgcolor="#FFFFFF" sdval="63"><b>63</b></td>
	</tr>
	<tr>
		<td>БД</td>
		<td >8</td>
		<td>3</td>
		<td>24</td>
		<td>1,5</td>
		<td>36</td>
	</tr>
	<tr>
		<td>Кэш</td>
		<td >1</td>
		<td>3</td>
		<td>3</td>
		<td>1,5</td>
		<td >4,5</td>
	</tr>
	<tr>
		<td>Фронт</td>
		<td >1</td>
		<td>5</td>
		<td>5</td>
		<td>1,5</td>
		<td >7,5</td>
	</tr>
	<tr>
		<td>Бэк</td>
		<td >1</td>
		<td  >10</td>
		<td  >10</td>
		<td>1,5</td>
		<td >15</td>
	</tr>
	<tr>
		<td  colspan=5 align="center" valign=middle bgcolor="#FFFFFF"><b>RAM(ОЗУ)</b></td>
		<td  bgcolor="#FFFFFF" ><b>45,375</b></td>
	</tr>
	<tr>
		<td>БД</td>
		<td >4</td>
		<td>3</td>
		<td >12</td>
		<td>1,5</td>
		<td >18</td>
	</tr>
	<tr>
		<td>Кэш</td>
		<td >4</td>
		<td>3</td>
		<td >12</td>
		<td>1,5</td>
		<td >18</td>
	</tr>
	<tr>
		<td>Фронт</td>
		<td>0,05</td>
		<td>5</td>
		<td>0,25</td>
		<td>1,5</td>
		<td>0,375</td>
	</tr>
	<tr>
		<td>Бэк</td>
		<td>0,6</td>
		<td>10</td>
		<td>6</td>
		<td>1,5</td>
		<td>9</td>
	</tr>
    </table>
    
    
<h3>Расчет общесистемных параметров</h3>
    <table cellspacing="0" boreder="1">
	<tr>
		<td><b>Наименование</b></td>
		<td ><b>На одну ноду</b></td>
		<td  ><b>Число нод</b></td>
		<td ><b>Всего</b></td>
	</tr>
	<tr>
		<td  colspan=3 align="center" valign=middle bgcolor="#FFFFFF"><b>Дисковые ресурсы</b></td>
		<td  bgcolor="#FFFFFF" ><b>640</b></td>
	</tr>
	<tr>
		<td>Master node</td>
		<td >100</td>
		<td>3</td>
		<td >300</td>
	</tr>
	<tr>
		<td>Worker node</td>
		<td  >100</td>
		<td>3</td>
		<td  >300</td>
	</tr>
	<tr>
		<td>ОС</td>
		<td  >10</td>
		<td >1</td>
		<td  >10</td>
	</tr>
	<tr>
		<td>Centralized monitoring</td>
		<td>20</td>
		<td >1</td>
		<td>20</td>
	</tr>
	<tr>
		<td>Centralized logging</td>
		<td  >10</td>
		<td >1</td>
		<td  >10</td>
	</tr>
	<tr>
		<td  colspan=3  align="center" valign=middle bgcolor="#FFFFFF"><b>Ядра CPU</b></td>
		<td  bgcolor="#FFFFFF" ><b>14</b></td>
	</tr>
	<tr>
		<td>Master node</td>
		<td 2</td>
		<td>3</td>
		<td >6</td>
	</tr>
	<tr>
		<td>Worker node</td>
		<td >1</td>
		<td>3</td>
		<td>3</td>
	</tr>
	<tr>
		<td>ОС</td>
		<td >1</td>
		<td >1</td>
		<td >1</td>
	</tr>
	<tr>
		<td>Centralized monitoring</td>
		<td  >2</td>
		<td >1</td>
		<td  >2</td>
	</tr>
	<tr>
		<td>Centralized logging</td>
		<td  >2</td>
		<td >1</td>
		<td  >2</td>
	</tr>
	<tr>
		<td  colspan=3 align="center" valign=middle bgcolor="#FFFFFF"><b>RAM(ОЗУ)</b></td>
		<td  bgcolor="#FFFFFF" ><b>26</b></td>
	</tr>
	<tr>
		<td>Master node</td>
		<td  >2</td>
		<td>3</td>
		<td >6</td>
	</tr>
	<tr>
		<td>Worker node</td>
		<td >1</td>
		<td>3</td>
		<td>3</td>
	</tr>
	<tr>
		<td>ОС</td>
		<td >1</td>
		<td >1</td>
		<td >1</td>
	</tr>
	<tr>
		<td>Centralized monitoring</td>
		<td>5</td>
		<td >1</td>
		<td>5</td>
	</tr>
	<tr>
		<td>Centralized logging</td>
		<td>11</td>
		<td >1</td>
		<td>11</td>
	</tr>
</table>
<h3>ИТОГО</h3>
<br>RAM: 71,375 Gb
<br>CPU:77 Ядер
<br>HDD: 872.5 Gb
</pre>
</div>
</div>
</body>
</html>