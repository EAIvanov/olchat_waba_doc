---
hidden: true
---

# Перенос номера с провайдером GupShup

Если вы ранее использовали номер WABA через провайдера GupShup и были клиентом другой компании-интегратора, вы можете осуществить перенос номера в OLChat. Для этого понадобится доступ к номеру WABA и аккаунту Facebook\*, к которому привязан бизнес-аккаунт Meta\* с нужным номером WABA.

{% hint style="warning" %}
При смене компании-интегратора на OLChat, созданные шаблоны в GupShup автоматически подгрузятся в OLChat WABA при условии настройки линии на ранее используемый с другим интегратором номер телефона.
{% endhint %}

### Отключение 2FA

Для начала процесса переноса подключенного к GupShup номера в OLChat, необходимо выполнить отключение двухфакторной аутентификации (2FA, two-factor authentication). Для этого выполните следующие действия:

{% stepper %}
{% step %}
#### Перейдите в [WhatsApp Manager](https://business.facebook.com/latest/whatsapp_manager/overview/), затем выберите необходимый для переноса номер телефона.

<figure><img src="../.gitbook/assets/Скриншот 29.07.25_10.08.49.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Выберите вкладку "Двухшаговая проверка", затем нажмите "Отключить двухшаговую проверку".

<figure><img src="../.gitbook/assets/Скриншот 29.07.25_10.09.43.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### На привязанный e-mail придёт письмо с ссылкой для отключения 2FA. Перейдите по ней и подтвердите отключение.

<figure><img src="../.gitbook/assets/Скриншот 29.07.25_10.11.14.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Отключение 2FA завершено.
{% endstep %}
{% endstepper %}

### Перенос номера

Чтобы перенести номер от другой компании-интегратора, выполните следующие действия:

{% stepper %}
{% step %}
#### Необходимо обратиться в чат технической поддержки компании-интегратора, услугами которой вы пользовались ранее. Текст сообщения приведён ниже, он является примером:

>> Добрый день! Нам необходимо освободить номер WABA (_<mark style="color:red;">ваш номер телефона</mark>_). Отправьте, пожалуйста, тикет в поддержку GupShup на удаление приложения (app).
{% endstep %}

{% step %}
#### Удалите приложение, привязанное к переносимому номеру, в личном кабинете компании-интегратора, услугами которой вы пользовались ранее.
{% endstep %}

{% step %}
#### Воспользуйтесь [инструкцией ](https://waba.docs.olchat.io/bystryi-start/sozdanie-i-nastroika-prilozheniya-whatsapp-v-gupshup#dobavlenie-prilozheniya-whatsapp-v-kabinete-gupshup)по созданию и настройке приложения WhatsApp в GupShup.&#x20;
{% endstep %}

{% step %}
#### На этапе подключения приложения WhatsApp к аккаунту Meta\*, выберите "Действующий номер" и завершите подключение, следуя инструкции.
{% endstep %}

{% step %}
#### Воспользуйтесь [инструкцией ](../ustanovka-i-nastroika-prilozheniya-v-bitriks24/ustanovka-prilozheniya.md)по установке приложения OLChat WABA.
{% endstep %}

{% step %}
#### Подключите открытую линию и коннектор, воспользовавшись данной [инструкцией](../ustanovka-i-nastroika-prilozheniya-v-bitriks24/podklyuchenie-konnektora.md).
{% endstep %}

{% step %}
#### Настройте открытую линию согласно данной [инструкции](../ustanovka-i-nastroika-prilozheniya-v-bitriks24/nastroika-otkrytoi-linii.md).

#### Перенос номера завершён, можно приступать к работе!
{% endstep %}
{% endstepper %}

_(\*) Meta, Facebook — признана экстремистской организацией на территории РФ._
