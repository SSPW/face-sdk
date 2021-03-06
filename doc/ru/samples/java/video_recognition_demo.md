# Android Video Recognition

Программа демонстрирует трекинг, детекцию и распознавание лиц из базы.

Для запуска сэмпла установите `video_recognition_demo.apk` на устройство. Для установки сэмпла необходимо разрешить приложению иметь доступ к перечисленным функциям.

<p align="center">
<img width="250" src="../../../img/video_recognition_apk_permissions_en.png"><br>
<b>Разрешения, запрашиваемые при установке video_recognition_demo.apk</b>
</p>

Чтобы добавить лицо в базу для распознавания, в приложении нажмите на кнопку *new person* и введите имя.

<p align="center">
<img width="450" src="../../../img/video_rec_new_person.png"><br>
<b>Добавление лица в базу через приложение</b>
</p>

Результаты трекинга и информация о лице отображаются в окне. В правом верхнем углу окна отображается задетектированное лицо и результат распознавания лица из базы с именем.

В правом нижнем углу находится меню со следующими разделами:
* **new person** – добавить неопознанное лицо в базу
* **settings** – выбрать тип используемой камеры, разрешение изображения, метод, используемый для детекции лиц, а также порог распознавания)
* **quit** – выход из программы

<p align="center">
<img width="450" src="../../../img/video_rec_result.png"><br>
<b>Результат запуска video_recognition_demo.apk</b>
</p>

Исходный код: [examples/android/video_recognition_demo](../../../../examples/android/video_recognition_demo)
