# Отправить шаблонное сообщение с файлом

{% hint style="info" %}
Данная статья в качестве примера рассматривает отправку роботом шаблонного сообщения с изображением, но принцип работы робота подходит также и под отправку шаблона с документом, аудио- или видеофайлом.
{% endhint %}

Для того, чтобы отправлять сообщения с файлом с помощью робота, выполните следующие действия:

{% stepper %}
{% step %}
#### Скопируйте шаблон с изображением из приложения Whatsabi.

Вставьте ссылку на изображение: прямую или с помощью параметра DISK\_<mark style="color:red;">ID</mark>, где <mark style="color:red;">ID</mark> - это ID файла на Битрикс.Диске, а затем нажмите кнопку "Скопировать шаблон".

{% hint style="success" %}
Воспользуйтесь [данной инструкцией](../nastroika-otpravki-faila-v-zavisimosti-ot-istochnika.md#ukazanie-id-otpravlyaemogo-faila), чтобы узнать, где взять ID файла на Битрикс.Диске.
{% endhint %}

<figure><img src="../../.gitbook/assets/Скриншот 21.08.25_03.46.34.png" alt=""><figcaption></figcaption></figure>

В буфер обмена будет скопировано следующее:

> \[template=ru]<mark style="color:red;">kartinka</mark>\[/template]\[header=image]<mark style="color:green;">DISK\_3283</mark>\[/header]

В данном случае <mark style="color:red;">kartinka</mark> - название шаблона, а <mark style="color:green;">DISK\_3283</mark> - ссылка на изображение, хранящееся на Битрикс.Диске, которое будет отправлено вместе с сообщением.
{% endstep %}

{% step %}
#### В карточке лида перейдите на вкладку "Роботы".&#x20;

<figure><img src="../../.gitbook/assets/Скриншот 21.08.25_05.00.08.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Нажмите "+ Создать", затем выберите стадию, на которую необходимо добавить робота, далее в меню выберите "Другие роботы" -> \[Whatsabi] Отправить сообщение.

<figure><img src="../../.gitbook/assets/Скриншот 21.08.25_05.04.09.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### В настройках робота укажите линию (1), через которую будут отправляться сообщения с изображением, вставьте переменную контакта (2), затем вставьте скопированный ранее шаблон в поле "Текст сообщения" (3).&#x20;

При необходимости измените остальные настройки, выставленные по умолчанию, и нажмите кнопку "Сохранить".

<figure><img src="../../.gitbook/assets/Скриншот 21.08.25_05.44.09.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Сообщение, полученное клиентом в WhatsApp, имеет следующий вид:

<figure><img src="../../.gitbook/assets/image (290).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Настройка робота завершена.
{% endstep %}
{% endstepper %}



