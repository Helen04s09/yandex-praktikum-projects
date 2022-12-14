# Описание проекта - Анализ поведения пользователей в мобильном приложении

## Данные

<p><b>Описание данных:</b></p>
<p><b>Таблица <code>mobile_sources:</code></b></p>
<ul>
    <li><code>userId</code> — идентификатор пользователя;</li>
    <li><code>source</code> — источник, с которого пользователь установил приложение.</li>
</ul>
  
<p><b>Таблица <code>mobile_dataset:</code></b></p>
<ul>     
    <li><code>event.time</code> — время совершения;</li>
    <li><code>user.id</code> — идентификатор пользователя;</li>
    <li><code>event.name</code> — действие пользователя.</li>
</ul>
<p><b>Виды действий:</b></p>
<ul>     
    <li><code>advert_open</code> — открыл карточки объявления;</li>
    <li><code>photos_show</code> — просмотрел фотографий в объявлении;</li>
    <li><code>tips_show</code> — увидел рекомендованные объявления;</li>
    <li><code>tips_click</code> — кликнул по рекомендованному объявлению;</li>
    <li><code>contacts_show и show_contacts</code> — посмотрел номер телефона;</li>
    <li><code>contacts_call</code> — позвонил по номеру из объявления;</li>
    <li><code>map</code> — открыл карту объявлений;</li>
    <li><code>search_1—search_7</code> — разные действия, связанные с поиском по сайту;</li>
    <li><code>favorites_add</code> — добавил объявление в избранное.</li>
</ul>

## Задача

<p><li>Проанализировать влияние событий на совершение целевого события</li>
<li>Проанализировать распределение событий по источникам</li>
<li>Проверить статистические гипотезы</li></p>

## Используемые библиотеки
*python, pandas, scikit-learn, matplotlib,seaborn, A/B-тестирование, событийная аналитика, продуктовые метрики, проверка статистических гипотез, визуализация данных*