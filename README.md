# T23_338a Зміни в контрагентах

* [ ] Змінити відображення Emoji символу статусу контрагента: в статусі контрагента повиннен відображатись тільки статус СЕБ, загальний статус (що складається зі статусу СЕБ та Валідації) не відображати.
* [ ] Контрагентів розділяти на 3-ри групи `Резидент`, `Не резидент`, `Спеціальний контрагент`
  * Значення `Спеціальний контрагент` не доступне під час створення/редагування, а встановлюється тільки з форми у процесі `Валідація контрагентів`
* [ ] Статус контрагента відображати як:  
  ` ` - Пусто (виключно для спеціальних контрагентів)  
  `⬜` - Відсутній (для нових контрагентів)  
  `⏳` - На перевірці (СЕБ)  
  `✔️` - Без зауважень (СЕБ)  
  `⚠️` - Із зауваженнями (СЕБ)  
  `⛔` - НЕ РЕКОМЕНДОВАНО (СЕБ)  
  `🧊` - Заключення застаріло (СЕБ)  
  `🚫` - Контрагент не використовується
* [ ] Розробити фільтр (механізм фільтрації) контрагентів, що не можуть бути використані в процесах ЕЛМИ, не допускати контрагентів, що:
  * `⬜` - Відсутній (для нових контрагентів)    
  * `🧊` - Заключення застаріло (СЕБ)  
  * `🚫` - Контрагент не використовується

* [ ] Застосувати фільтр у всіх процесах Елми де використовуються контрагенти
* [ ] Обновити процес і механізм валідації контрагентів
  * [ ] ...
* [ ] Обновити процес моніторингу контрагентів
  * [ ] У користувачів є скарги на помилку визначення часу дії заключення СЕБ - перевірити, за необхідності виправити  
  * [ ] Відсилати відповідальним за контрагента особам сповіщення про закінчення дії заключення СЕБ
