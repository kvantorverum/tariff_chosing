# Создание рекомандательной системы для предложения пользователю телекоммуникационной компании перехода на новый тариф
Рекомендация по выбору тарифа для клиентов телекоммуникационной компании
К нам обратилась телекоммуникационная компания с просьбой рассчитать рекомендации для пользователей по переходу на актуальные тарифы. В компании есть два новых тарифа - smart и ultra. Ряд клиентов уже перешли на них. Компания предоставила сведения о поведении клиентов, которым понравились эти тарифы. 

Большая часть клиентов еще пользуются устаревшими тарифами. Компании будет выгодно, если они перейдут на новые. Перед нами поставлена задача обучить модель, которая будет по поведению пользователя определять, какой из новых тарифов ему лучше подойдет и тогда она сможет сделать более эффективную и таргетную рекламу.

## Описание данных
Каждый объект в наборе данных — это информация о поведении одного пользователя за месяц. Известно:
* сalls — количество звонков,
* minutes — суммарная длительность звонков в минутах,
* messages — количество sms-сообщений,
* mb_used — израсходованный интернет-трафик в Мб,
* is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).
