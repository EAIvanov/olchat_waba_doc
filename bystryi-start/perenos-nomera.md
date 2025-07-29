# Перенос WABA от другого провайдера

Если вы ранее использовали номер WABA через другого провайдера, вы можете осуществить перенос номера. Для этого понадобится доступ к номеру WABA и аккаунту Facebook\*, к которому привязан бизнес-аккаунт Meta\* с нужным номером WABA.

{% hint style="warning" %}
При переносе номера шаблоны, которые были привязаны к WABA, мигрируют вместе с номером в приложение.
{% endhint %}

### Отключение 2FA

Для начала процесса переноса номера к другому провайдеру, необходимо выполнить отключение двухфакторной аутентификации (2FA, two-factor authentication). Для этого выполните следующие действия:

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
{% endstepper %}

{% hint style="info" %}
Создайте личный кабинет в GupShup, если еще не зарегистрированы, затем создайте новое приложение. Подробная инструкция по регистрации в Gupshup доступна по [ссылке](registraciya-v-gupshup/).
{% endhint %}

### Перенос номера

Чтобы перенести номер от другого провайдера, выполните следующие действия:

{% stepper %}
{% step %}
#### При создании приложения в GupShup, на этапе "Let\`s get started" выберите "Migrate a live phone number", затем нажмите "Continue".

Перейти к данному этапу получится после нажатия кнопки "Go Live".

<figure><img src="../.gitbook/assets/Скриншот 29.07.25_10.20.46.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Следуйте дальнейшей инструкции, выбрав или создав аккаунт. Далее создайте профиль под номер.

<figure><img src="../.gitbook/assets/Скриншот 29.07.25_10.26.05.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Необходимо указывать тот же WhatsApp Display Name, какой использовался у предыдущего оператора в личном кабинете.
{% endhint %}
{% endstep %}

{% step %}
#### Добавьте номер, который переносится.

<figure><img src="../.gitbook/assets/Скриншот 29.07.25_10.44.45.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Скриншот 29.07.25_10.45.40.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### При успешном переносе, в GupShup станет доступен следующий шаг. Здесь необходмо также выбрать номер, который переносится, далее нажать "Confirm".

<figure><img src="../.gitbook/assets/Скриншот 29.07.25_10.47.40.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Перенос номера завершен.
{% endstep %}
{% endstepper %}

### Подключение партнёра и получение ключа API

Следуйте инструкции:

{% embed url="https://waba.docs.olchat.io/bystryi-start/sozdanie-i-nastroika-prilozheniya-whatsapp-v-gupshup#dobavlenie-partnyora" %}

После этого переходите к установке приложения:

{% embed url="https://waba.docs.olchat.io/ustanovka-i-nastroika-prilozheniya-v-bitriks24/ustanovka-prilozheniya" %}



_(\*) Meta, Facebook — признана экстремистской организацией на территории РФ._
