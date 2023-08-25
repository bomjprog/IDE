# Проект: Анализ вакансий из HeadHunter
### Описание проекта
Анализ вакансий опубликованных на сайте Headhunter
#### Описание данных
Все необходимые таблицы находятся в схеме public базы данных project_sql
Схема состоит из 5 таблиц:
* vacancies. Таблица хранит в себе данные по вакансиям
![](https://lms-cdn.skillfactory.ru/assets/courseware/v1/837cf6ff79f483e387a16c993634f3e4/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/SQL_pj2_2_2.png)

 * areas. Таблица-справочник, которая хранит код города и его название.
![](https://lms-cdn.skillfactory.ru/assets/courseware/v1/682c2306f3d46a25915a89d4ec7e16ed/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/SQL_pj2_2_3.png)

* employers. Таблица-справочник со списком работодателей.
![](https://lms-cdn.skillfactory.ru/assets/courseware/v1/d2a26db623c75572c71923b57241e038/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/SQL_pj2_2_4.png)

* industries. Таблица-справочник вариантов сфер деятельности работодателей.
![](https://lms-cdn.skillfactory.ru/assets/courseware/v1/2c76bca09937a1a05a9e66d51008e298/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/SQL_pj2_2_5.png)

* employers_industries. Дополнительная таблица, которая существует для организации связи между работодателями и сферами их деятельности.
![](https://lms-cdn.skillfactory.ru/assets/courseware/v1/16ff3df0bb0ddecd922562f3c4bdd32c/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/SQL_pj2_2_6.png)

#### Задача
Провести анализ данных с помощью SQL и Python
#### Содержание
1. знакомство с данными
2. предварительный анализ данных
3. детальный анализ вакансий 
4. анализ работодателей
5. предметный анализ
6. выводы и результаты