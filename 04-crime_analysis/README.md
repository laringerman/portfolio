# Анализ преступлений в Сырограде
## Описание проекта
Город Сыроград известен своей фабрикой сыра — лучший сыр в мире производится именно здесь. Этот сыр обладает  выдающимися характеристиками: он имеет большой срок хранения и уникальный вкус. Из-за этого он недоступен большинству граждан города.  
  
 После производства, сыр развозится по складам, которые находятся в разных районах города. Каждый склад надежно охраняем. Однако, в последние 2 года участились случаи кражи сыра со склада. Полицейские не смогли понять ни по какой логике происходят кражи (например, почему в одном районе краж больше, чем в другом), ни можно ли предсказать, где будет следующая кража.  
  
 Однако, в ходе очередного сыскного мероприятия выяснилось, что в некоторых районах, где происходили кражи, также были разбиты  фонари. Полицейские предположили, что между фактами кражи и хулиганства есть какая-то взаимосвязь.  
 Начальник полицейского участка города Сыроград предоставил нам датасет.  
  
**Цель исследования**  
 Статистически значимо снизить количество краж в районах города.

## Инструменты

`Python` `Pandas` `Matplotlib` `Scipy`


## Выводы

- Для всех складов есть основание полагать, что взаимосвязь (корреляция) между количеством полицейских и количеством охраны статистически значима. Можем предположить, что охраны, как и полицейских, больше в неблагоприятных районах.
- Есть основание полагать, что взаимосвязь (корреляция) между количеством фонарей в районе и процентом раскрытых преступлений по уничтожению фонарей в районе статистически значима. Можем предположить, что чем больше в районе фонарей, тем заметнее преступники, и тем проще их поймать.
- Только для одного склада, а именно Колбасовы в районе Приморский есть основание полагать, что взаимосвязь (корреляция) между количеством полицейских в районе и процентом раскрытых преступлений по уничтожению фонарей в районе статистически значима. Причем коэффициент корреляции отрицательный, что может говороить об обратной зависимости: чем меньше полицейских в районе, тем лучше раскрываются преступления. Для остальных складов нет основания полагать, что взаимосвязь (корреляция) между количеством полицейских в районе и процентом раскрытых преступлений по уничтожению фонарей в районе статистически значима.

  
**Рекомендации**  
Есть основания полагать, что для увеличения раскрываемости преступлений  необходимо увеличивать количество фонарей в районе.  
Также есть основание полагать, что увеличение количества полицейских не приведет к увеличению процента раскрытия преступлений.

## [Cмотреть ход решения](https://github.com/laringerman/data_analyst_portfolio/blob/main/04-crime_analisys/cheesegrad.ipynb)
