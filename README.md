# Исследование TED-конференций

## Описание проекта

В данном проекте были проанализированы данные о выступлениях на TED-конференциях с целью выявления ключевых тенденций в тематике выступлений, распределении выступлений по странам и годам, а также исследованы эмоциональные реакции аудитории (смех и аплодисменты). Данные включают различные метрики, такие как количество просмотров, количество смеха и аплодисментов, и продолжительность выступлений, что позволило оценить популярность и эмоциональный отклик на выступления.

Для визуализации и анализа данных был использован инструмент Tableau, с помощью которого были построены четыре интерактивных дашборда:

1. История выступлений: Исследование распределения выступлений по странам и годам, а также по тематикам.
2. Тематики выступлений: Анализ популярных тематик выступлений и распределение их по странам.
3. Авторы выступлений: Исследование профессиональных областей авторов и их влияния на количество просмотров.
4. Эмоции и популярность: Анализ взаимосвязи между эмоциональной реакцией аудитории (аплодисменты) и популярностью выступлений.

## Цель проекта

Основная цель проекта — изучить динамику выступлений TED, понять, какие тематики вызывают наибольший интерес аудитории, и как аудитория реагирует на выступления. В частности, интерес представляет связь между популярностью выступлений (количество просмотров) и эмоциональной реакцией аудитории (аплодисменты и смех). Исследование также выявляет страны, наиболее активно принимающие участие в конференциях, и тематики, доминирующие в разных регионах мира.

## Используемые данные

В проекте использованы следующие наборы данных:
- Данные выступлений (id выступления, название, описание, дата записи, длительность, просмотры, основная тематика, язык, смех и аплодисменты);
- Справочник конференций (страна проведения, название конференции);
- Справочник авторов (имя автора, профессия, описание).

## Основные выводы

1. География выступлений: 
   - Большинство выступлений TED проводятся в США (53.3%), за ними следуют Канада (18.0%) и Великобритания (15.5%). Эти три страны занимают лидирующие позиции в организации конференций и предоставляют площадки для выступлений на самые разнообразные темы.

2. Популярные категории:
   - Наиболее популярные категории выступлений включают "Наука", "Культура" и "Технологии". В каждой из этих тематик было проведено множество выступлений, и они имеют наиболее широкую аудиторию. Наука является лидером среди тем с долей 20.6% от всех выступлений.
   - Тематика "Наука" также лидирует в разных странах, включая Канаду (24.2%), Великобританию (21.5%) и США (19.4%), что подтверждает глобальный интерес к научным темам.

3. Тематические изменения со временем:
   - В период с 2020 по 2021 годы в топ-10 категорий остались только три ключевые направления: "Технологии", "Общество" и "Глобальные проблемы", что свидетельствует о смещении интереса аудитории к этим темам на фоне глобальных изменений в мире.

4. Эмоциональные реакции аудитории:
   - Категория "Развлечения" вызывает больше всего аплодисментов, тогда как "Глобальные события" — меньше всего. Самое аплодируемое выступление принадлежит Сесиль Ричардс и посвящено социальным переменам.
   - "Развлечения" также лидируют по количеству смеха в выступлениях, в то время как выступления на тему "Глобальные события" имеют наименьший уровень юмора. Самое смешное выступление: "Культура" от Маза Джобрани.

5. Продолжительность и популярность выступлений:
   - Не обнаружено связи между длительностью выступления и количеством просмотров. Самое популярное выступление — "Убивают ли школы креативность?", в то время как самое длительное — "Три секрета успеха Netflix". Это говорит о том, что популярность выступления не зависит от его продолжительности.

6. Авторы выступлений:
   - Среди профессий авторов выступлений преобладают писатели, журналисты, артисты и предприниматели. Эти профессиональные группы вносят значительный вклад в разнообразие тем на TED.
   - В среднем, 89.3% авторов имеют по одному выступлению. Рекордсмен по количеству выступлений — Ханс Рослинг с 10 выступлениями.
   - В категории "Дизайн" лидер по количеству выступлений — Том Вуец. Однако его выступление "Learn to use the 13th-century astrolabe" оказалось наименее просматриваемым среди всех его работ.

7. Эмоции и популярность:
   - Явной корреляции между количеством аплодисментов и популярностью выступления по количеству просмотров не обнаружено. Однако в таких тематиках, как "Дизайн" и "Технологии", наблюдается тенденция, что большее количество аплодисментов соответствует большему числу просмотров.
   - Наибольшее количество аплодисментов (25) получил доклад "The political progress women have made — and what's next", который относится к категории "Прочее".
   - Тематика "Наука" является наиболее популярной по общему числу просмотров, которое достигает 1.6 миллиарда, что подтверждает высокий интерес аудитории к научным темам.

## Презентация проекта

Презентация исследования TED-конференций доступна на Tableau Public по следующей ссылке: [Ссылка на презентацию](https://public.tableau.com/shared/KGDHYBW8S?:display_count=n&:origin=viz_share_link)
