# Описание проекта - Анализ работы стартапа по продаже продуктов питания


## Данные

<p><b>Таблица logs_exp(каждая запись в логе — это действие пользователя, или событие):</b></p>

<ul>
    <li>EventName — название события;</li>
    <li>DeviceIDHash — уникальный идентификатор пользователя;</li>
    <li>EventTimestamp — время события;</li>
    <li>ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.</li>
</ul>

## Задача

На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования 

## Используемые библиотеки
*A/B-тестирование, Python, Pandas, Matplotlib, Seaborn, Plotly, событийная аналитика, продуктовые метрики, проверка статистических гипотез, визуализация данных*