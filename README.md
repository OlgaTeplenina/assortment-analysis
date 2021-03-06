# Дипломная работа "Анализ ассортимента сети ортосалонов"

Здесь вы можете ознакомиться с [кодом,](https://github.com/OlgaTeplenina/assortment-analysis/blob/main/%D0%94%D0%B8%D0%BF%D0%BB%D0%BE%D0%BC%D0%BD%D0%B0%D1%8F_%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0.ipynb) а здесь с [отчётом](https://github.com/OlgaTeplenina/assortment-analysis/blob/main/%D0%94%D0%B8%D0%BF%D0%BB%D0%BE%D0%BC%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0.pdf)

**Проблема:** ассортиментные матрицы ортосалонов не соответствуют текущим продажам, вследствие чего может быть нехватка или избыток товара в салоне.  

**Цель:** разработать рекомендации по изменению матриц и работе с ассортиментом в ортосалонах “XXX”. 

**Задачи:**
* провести предобработку данных;
* обновить существующий классификатор ортоизделий;
* выбрать временной период для анализа;
* выявить ассортимент, который будет участвовать в анализе;
* провести анализ ассортимента методом Дибба-Симкина в разрезе категорий изделий и в разрезе ортосалонов;
* соотнести нормативы со средними месячными продажами и оценить их корректность, 
* выявить товары, которые можно убрать из текущего ассортимента; 
* подготовить отчёты с результатами анализа для каждого ортосалона.

**Объект:** ассортимент ортосалонов. 

**Предмет:** ассортиментные матрицы ортосалонов в разрезе категорий и салонов.

**Гипотезы для проверки:**

 * При корректировке нормативов коэффициент оборачиваемости салона уменьшится.  
 * Существует группа товаров, повышение цен на которые ведет к увеличению прибыли без риска для спроса.

**Результат:**

В ходе работы был проведён анализ ассортиментных матриц сети орстосалонов “XXX”. 

На этапе предобработки данных был откорректирован и обновлён классификатор ортопедических изделий, были выявлены изделия с некорректным названием или задвоенным кодом ГЕС. 

Основная часть работы состояла из 2 блоков. Первый блок - анализ ассортимента по методу Дибба-Симкина, результатом которого является отчёт для стейкхолдеров в разрезе ортосалонов и групп классификатора. Изделия разделены на 4 группы, каждой из которых соответствуют свои рекомендации. Результаты также можно увидеть в виде графиков.

Второй блок - это соотношение средних месячных продаж и нормативов. Результатом является отчёт для стейкхолдеров: для каждого ортосалона даны рекомендации по изменению нормативов. Решение об применении рекомендаций принимает стейкхолдер (менеджер отдела ортопедии организации “YYY”), подкрепляя своим экспертным мнением в области особенностей ортопедических изделий.

Написанный для анализа код можно использовать для аналогичного анализа в будущем, что сократит трудозатраты стейкхолдеров. В настоящее время анализ нормативов проводится в Microsoft Excel, что имеет следующие неудобства: медленная работа программы из-за большого объёма данных, ручное склеивание таблиц (ВПР), большая вероятность пропустить ошибки в данных.
