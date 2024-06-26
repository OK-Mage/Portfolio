# Data analysis of the games sales of the Strimchik online store / Анализ данных по продажам игр интернет-магазина «Стримчик».

## Цель проекта:
* выявить определяющие успешность игры закономерности, чтобы в дальнейшем сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

## Стек:
* pandas
* datetime
* matplotlib
* scipy, описательня статистика
* аналитик(универсал), data analyst



# Выводы (статус проекта - завершен):
* регион NA (Северная Америка) на первом месте по продажам игр среди регионов (40.13% рынка):
  * популярные платформы: последние версии **PS4** от Sony и **XOne** от Microsoft, также предыдущие версии этих же платформ
  * популярные жанры: **Shooter**(25.1%) и **Sports**(14.9%), **Action** (28.8%) 
  * популярные рейтинги: М((«Mature») — «Для взрослых») - 37.7% и RP - 20.4%
* регион EU (Европа) на втором месте по продажам игр среди регионов (35.96% рынка):
  * популярные платформы: от Sony(**PS4 и PS3**) >50%, на втором месте Microsoft(**XOne и X360**) 1/4 часть
  * популярные жанры:  **Shooter**(22.4%) и **Sports**(15.4%), **Action** (30.1%)
  * популярные рейтинги: М((«Mature») — «Для взрослых») - 37.0%, RP - 20.1%
* регион JP (Япония) на третьем месте по продажам игр среди регионов (12.91% рынка):
  * популярные платформы: последняя версия от Nintendo(**3DS** - 48.%) и предпоследняя от Sony(PS3 - 16.6%), на втором месте другие версии от Sony(PSV и PS4) 
  * популярные жанры: **Role-Playing** (36.3%) и **Action** (28.8%)
  * популярные рейтинги: RP - 60.4% (так как в данных нет данных возрастного рейтинга для Японии), рейтинг T((«Teen») — «Подросткам») - 14.6% 
  
**Стабильные продажи обеспечивают игры**
* для платформ X360(от Microsoft), 2-е место XOne(от Microsoft), PS4(от Sony) и WiiU(от Nintendo), на 3-ем месте с небольшим отставанием платформа Wii(от Nintendo)
* жанра Shooter, Sports для NA, EU. Для JP жанр Role-Playing. Игры в жанре Actions выигрывают по популярности за счет "выстрелившей" одной игры с максимальными продажами за весь период Grand Theft Auto V(почти 50 млн. копий), если рассматривать медианные продажи этого жанра, то он на 7 месте из 12

**На продажи по платформам влияют именно оценки критиков, не пользователей**
* PS4: корреляция с продажами оценки критиков 0.407
* PS3: корреляция с продажами оценки критиков 0.334
* X360: корреляция с продажами оценки критиков 0.350 
* XOne: корреляция с продажами оценки критиков 0.417 

**Проверены гипотезы за актуальный период:**
  * Средние пользовательские рейтинги платформ Xbox One и PC одинаковые. Гипотеза подтвердилась: разница между средними пользовательскими рейтингами платформ PC и XOne статистически незначима.
  * Средние пользовательские рейтинги жанров Action (англ. «действие», экшен-игры) и Sports (англ. «спортивные соревнования») разные. Гипотеза подтвердилась: разница статистически значима.