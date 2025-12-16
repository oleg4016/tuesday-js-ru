![Tuesday js visual novels engine](https://repository-images.githubusercontent.com/233020914/1b3240ff-9db8-4163-92ba-f86e81d10967)

# Tuesday JS visual novel engine 

Простой и бесплатный веб-редактор визуальных новелл с открытым исходным кодом, который можно использовать в браузере. Он написан на JavaScript без использования каких-либо сторонних библиотек и не требует установки дополнительного программного обеспечения. Движок использует стандартные элементы HTML5 документа, такие как div и img. Это позволяет использовать любой медиаформат поддерживаемый браузерами включая векторную графику svg, gif-анимацию и стили css.
Есть версии редактора доступные для Android устройств и настольных компьютеров. Все версии полностью совместимы друг с другом и имеют одинаковый интерфейс.


> Run in browser: https://kirilllive.github.io/tuesday-js/translate/en_tuesday_visual.html

Download builds for macOS, Windows, Android, Web
-------------------------
> GitHub: https://github.com/Kirilllive/tuesday-js/releases

> Boosty: https://boosty.to/kirilllive


Tutorials
-------------------------
> EN - [A quick tutorial to create a visual novel ](https://kirilllive.github.io/tuesday-js/doc_editor.html#quick_tutorial)

> JA - [Tuesday JSでビジュアルノベルを作ってみよう](https://kirilllive.github.io/tuesday-js/doc_editor.html#quick_tutorial_ja)

> ES - [Una guía rápida para crear una novela visual](https://kirilllive.github.io/tuesday-js/doc_editor.html#quick_tutorial_es)

> RU - [Краткое руководство по созданию визуальной новеллы](https://kirilllive.github.io/tuesday-js/doc_editor.html#quick_tutorial_ru)

> PT - [Um guia rápido para criar uma visual novel](https://kirilllive.github.io/tuesday-js/doc_editor.html#quick_tutorial_pt)



# Visualization

Редактор отображает структуру сценария со всеми элементами, такими как параметры диалога и последствия выбора. Это облегчает навигацию и редактирование сценария.

![Tuesday JS script structure](screenshots/script_structure.jpg)


# Scene editor
Позволяет расположить все элементы по своим местам. Он также показывает, как будет выглядеть сцена на разных экранах. 
В макете сцены вы можете использовать стандартные параметры HTML как проценты, пиксели или сантиметры, чтобы лучше адаптировать сцену к различным экранам.	

![Tuesday JS scene editor](screenshots/scene_editor.jpg)


# Translate tool
Встроенный инструмент редактирования перевода позволяет быстро добавлять новый перевод и отредактировать все тексты в вашем проекте, не выходя из редактора. Кроме того, он отображает количество выполненного переводова для каждого языка.

![Tuesday JS preview](screenshots/translate_tool.jpg)


# Preview

Предварительный просмотр позволяет запустить проект с определенной точки в сценарии с выбранной локализацией.

![Tuesday JS preview](screenshots/preview.jpg)


# JSON
    
Сценарий истории сохраняется в структуре JSON. Практически любой язык программирования может работать с этим форматом что позволяет вам перенести ваш сценарий на другой движок или платформу. 
Редактор имеет встроенный инструмент для работы с JSON это позволит вам отредактировать все содержимое истории или только выбранный элемент.

![Tuesday JS json edit](screenshots/json_edit.jpg)


# ASCII art
Движок адаптирован для использования ASCII-графики. С ее помощью вы сможете разнообразить тексты изображениями и узорами составленых из текстовых символов.

![Tuesday JS preview](screenshots/ascii_art.jpg)


# Localization

Tuesday JS предоставляет обширные возможности для адаптации историй на другие языки. 
Вы можете локализировать перевод практически любого элемента проекта, включая текст и графику. 
Функция предварительного просмотра позволяет запускать проект на выбранном языке. 
Все тексты могут быть экспортированы в файл csv таблицы для редактирования или добавления локализаций в другом редакторе.
 
![Tuesday JS localization](screenshots/localization.jpg)


# System requirements for desktop version / Системные требования для настольной версии

CPU: x86_64

RAM: 512 MB

Minimum OS version:
- Windows 7 
- MacOS 10.13 (Apple Silicon / Intel)
- Debian 11
- Ubuntu 20.04


# Warning for Android version / Предупреждение для версии Android.

Minimum Android version: 5.1 / Минимальная версия Android: 5.1.
Если у вас возникли проблемы с файлами на Android 10 и выше, то вам необходимо указать "Разрешить доступ для управления всеми файлами" в настройках приложения в разделе "Разрешения".

If you have problems with files on Android 10 and higher, then you need to specify 'Allow access to manage all files' in the application settings in 'Permissions' section.

![Tuesday JS error access files on Android](tutorial_img/android_settings.png)


![Tuesday JS visual novels engine Akihabara 秋葉原](screenshots/20201202_122259.jpg)
Цель Tuesday JS - сделать разработку проекта не более сложной, чем работа в офисной программе для проведения презентаций, и не требующей от пользователя специальных навыков.

The goal of Tuesday JS is to make project development no more difficult than working in an office program to make presentations, and does not require special skills from the user.



[Japanes translation and adaptation by Onigi](https://twitter.com/onigi123)

[Russian translation and adaptation by LolerFox](https://twitter.com/LolerFox)

[Spanish translation and adaptation by Suki Novels](https://twitter.com/Suki_Novels)

[Portuguese translation and adaptation by Sarah Camargo](https://www.linkedin.com/in/sarah-carolina-camargo/)

[China translation and adaptation by jymusic0663](https://github.com/jymusic0663/)
