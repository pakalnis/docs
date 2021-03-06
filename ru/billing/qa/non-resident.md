# Вопросы по работе с нерезидентами РФ


#### Могу ли я стать клиентом Яндекс.Облака, если являюсь нерезидентом РФ? {#non-resident}

Да, можете, но только если являетесь организацией. 


#### С резидентами каких стран вы сотрудничаете? {#countries}

Заключить договор и создать платежный аккаунт могут резиденты стран, перечисленных в списке ниже. 

{% include [non-resident-countries](../_includes/non-resident-countries.md) %}


#### Будет ли предоставлен договор на оказание и оплату услуг? {#contract}

{% include [contract-qa](../_includes/contract-qa.md) %}

#### Какие способы оплаты я могу использовать? {#payment-types}

Организации-нерезиденты РФ могут пополнять лицевой счет и оплачивать потребленные ресурсы с помощью [банковской карты](../payment/payment-methods-card-business.md) или [перевода средств с расчетного счета](../payment/payment-methods-business.md).


#### В какой валюте нерезиденты РФ могут оплачивать услуги Яндекс.Облако? {#currency}

Нерезиденты РФ могут оплачивать услуги Яндекс.Облака только в долларах США ($), независимо от страны, в которой проживают.

#### Какие документы будут мне предоставлены после оплаты услуг? {#documents}

Яндекс.Облако формирует [счет на оплату](../concepts/bill.md) для организаций-нерезидентов РФ. Копия счета отправляется на электронную почту владельца платежного аккаунта в начале следующего отчетного периода. 


#### Как учитываются налоги при оплате услуг? {#taxes}

Налоги и сборы страны, в которой зарегистрирована организация-нерезидент РФ, не добавляются к стоимости услуг на странице [детализации](../operations/check-charges.md) и не входят в итоговую сумму счета на оплату. 

Все налоги и сборы, предусмотренные законодательством страны проживания, нерезидент РФ выплачивает самостоятельно. 

#### Почему платежный аккаунт был создан в статусе PAYMENT_NOT_CONFIRMED?  {#pending-status}

Для активации платежного аккаунта нерезидента РФ необходимо подтверждение менеджеров Яндекс.Облака. 

После того, как вы нажмете кнопку **Активировать** на странице **Создание аккаунта**, платежный аккаунт будет создан в статусе `PAYMENT_NOT_CONFIRMED`. На вашу почту, указанную в аккаунте Яндекса или Яндекс.Коннекта, будет отправлено письмо с описанием дальнейших действий. Активация может занять до трех рабочих дней.

#### Почему после создания платежного аккаунта я не получил письмо с описанием дальнейших действий?  {#account-notification}

Активация платежного аккаунта может занять до трех рабочих дней.
Если в течение этого времени вы так и не получили письмо, отправьте запрос на электронную почту [cloud_docs@support.yandex.ru](mailto:cloud_docs@support.yandex.ru).

В запросе укажите полное название организации и идентификатор облака (cloud ID), а также прикрепите документы:
- Копию свидетельства о регистрации организации (с переводом на английский или русский язык).
- Копию доверенности представителя организации, если вы являетесь представителем (с переводом на английский или русский язык).