## ОПИСАНИЕ ЗАДАЧИ

Сеть бургерных "Красти краб" вышла на рынок России в 2016 году. В 2017 году была запущена тестовая программа динамического ценообразования. Ее участники приобретают блюда сети через специальное приложение, устанавливающее индивидуальные цены для каждого участника на основе разнородных факторов. Теперь, спустя почти 2 года после запуска программы, пришла пора оценить результаты программы лояльности.  
  
На основе имеющихся данных требуется построить отчет в Power BI в соответствии с требованиями, описанными ниже.   


## ВХОДНЫЕ ДАННЫЕ

Исходные данные содержаться в двух файлах 
  
1.	Файл "Клиенты". Содержит данные об участниках программы.    
2.	Файлы "Продажи". Содержит данные о продажах.


## КАКИЕ ОТЧЕТЫ ТРЕБУЕТСЯ ПОЛУЧИТЬ 

НДС равен 18% 
  
### 1. Общий отчет по участникам программы
Необходимо выводить показатели:
1.	Кол-во уникальных покупателей; 
2.	Кол-во покупок (транзакций); 
3.	Средний чек, без НДС; 
4.	Выручки, без НДС. 
  
Необходима возможность фильтровать показатели: 
1.	По городам проживания участников программы; 
2.	По периодам (месяц-год) вступления участника в программу. 
  
Все 4 показателя нужно визуализировать карточками. 
  
### 2.	Отчет по продажам в разрезе точек продаж. 
Необходимо выводить показатели: 
1.	Среднемесячное кол-во покупок (транзакций); 
2.	Средний чек, без НДС; 
3.	Продажи (выручка), без НДС. 
  
Необходима возможность фильтровать показатели: 
1. По городам нахождения ресторанов; 
2. По названиям ресторанов; 
3. По месяцам продаж. 
  
Каждый показатель нужен в виде: 
1. Карточки;  
2. Диаграмм, в разбивке по: 
* городам, для выбранного периода. На выбор названия ресторана, либо города диаграмма не реагирует; 
* ресторанам, для выбранного города. На выбор названия ресторана диаграмма не реагирует; 

Еще нужна визуализация, на которой для каждого города показано распределение выручки между ресторанами данного города в процентах от общей выручки по городу для данного выбранного периода. В подсказке при наведении на область, отображающую долю выручки отдельного ресторана, помимо выручки в этом ресторане, должно отображаться число посетителей и средний чек. 
  
### 3.	Отчет по активности для разных типов клиентов. 
Необходимо выводить показатели: 
1.	Среднемесячное кол-во покупок (транзакций); 
2.	Средний чек, без НДС; 
3.	Средняя цена блюда, без НДС. 
  
Необходима возможность фильтровать показатели: 
1.	По городам нахождения ресторанов; 
2.	По годам; 
3.	Типам клиентов. Возможны три типа клиентов:  
*	Light (меньше 0,5 визитов в месяц за время участия клиента в программе); 
*	Medium (от 0,5 и менее 1,5 визитов в месяц за время участия клиента в программе); 
*	Hard (от 1,5 визитов в месяц за время участия в программе). 
4.	По возрасту клиентов на момент совершения транзакции. Возможны следующие группы: 
*	До 16;  
*	От 16 до 24;
*	От 24 до 35;
*	От 35 до 50;
*	От 50. 
  
Показатели 1-3 нужно выводить в разбивке по месяцам и годам. Визуализация – любая.  
 
Показатель 3 нужно еще выводить в разбивке городов и ресторанов. Визуализация – любая. 
  
### 4. "Свободный" отчет  
В этом отчете можно посчитать и(или) отобразить любые 2-3 показателя с любыми фильтрами в виде любых визуализаций.  

