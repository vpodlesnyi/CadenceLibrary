# CadenceLibrary
Библиотека компонентов для проектов в Cadence OrCAD Allegro.
Состоит из файлов:
- how-to-install папка содержит инструкцию по интеграции базы данных;
- pads папка содержит набор контактных площадок (для создания необходим PadStack Editor);
- step папка содержит набор step-моделей компонентов; 
- symbols папка содержит footpint компонентов;
- Template list of elements содержит листы перечня элементов по ГОСТ;
- Template of sheets содержит листы схемы Э3 по ГОСТ;
- MOP44.DBC для подключения в системе базы данных;
- MOP44.MDB база данных компонентов в формате Access;
- MOP44.OLB содержит УГО компонентов.

Подключение папок с pad, symbol:
User Preference Editor -> Paths -> Library
Указать путь до папки с pad падами в padpath;
             до папки с psm падов в psmpath;
             до папки с step моделями в steppath.
             
Подключение 3Д моделей:
Setup -> Step Package Mapping -> Library

Распределение слоев:
- Package Geometry/Silkscreen_Top - шелкография на верхнем слое;
- Package Geometry/Silkscreen_Bottom - шелкография на нижнем слое;
- Package Geometry/Assembly_Top - контур компонента для КД на верхнем слое;
- Package Geometry/Assembly_Bottom - контур компонента для КД на верхнем слое;

- pads папка содержит набор контактных площадок;
- step папка содержит набор step-моделей компонентов; 
- symbols папка содержит footpint компонентов;
- Template list of elements содержит листы перечня элементов по ГОСТ;
- Template of sheets содержит листы схемы Э3 по ГОСТ;
- MOP44.DBC для подключения в системе базы данных;
- MOP44.MDB база данных компонентов в формате Access;
- MOP44.OLB содержит УГО компонентов.
