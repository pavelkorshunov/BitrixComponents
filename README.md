<p># BitrixComponents</p>
<p># Author: Pavel Korshunov</p>

<h2>Папка popup.callback</h2>

<p>Простой Битрикс компонент, для удобного добавления формы обратной связи на странице, со сплывающим окном или без него.<br/>
За основу можно взять почтовый шоблон №7, добавив в тип почтового шаблона дополнительные поля при необходимости:</p>

<ul>
<li>#PHONE#</li>
<li>#PAGE_URL#</li>
</ul>

<p>Позволяет прикреплять файлы к письму и отправлять основные поля, стандартных форм обратной связи.<br/>
Примерный формат письма:</p>

<hr/>
<p>Информационное сообщение сайта #SITE_NAME#</p>
------------------------------------------

<p>Вам было отправлено сообщение через форму обратной связи</p>

<p>Автор: #AUTHOR#<br/>
E-mail автора: #AUTHOR_EMAIL#<br/>
Телефон: #PHONE#<br/>
Url страницы: #PAGE_URL#</p>

<p>Текст сообщения:<br/>
#TEXT#</p>

<p>Сообщение сгенерировано автоматически.</p>

<h2>Папка subscribe.simple</h2>

Простой компонент подписки. Для работы компонента необходим установленный модуль subscribe. Компонент добавляет подписчика в раздел подписчики модуля subscribe.

<h2>Папка instagram.photo</h2>

Компонент для парсинга последних фотографий из инстаграм. Для использования компонента необходимо получить access_token, который потребуется указать в параметрах. Как получить данный токен можно узнать из статьи hard-skills.ru/other/token-v-instagram/
