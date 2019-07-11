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
- Package Geometry/Silkscreen_Top - шелкография на верхнем слое (толщина линий 0,2 мм);
- Package Geometry/Assembly_Top - контур компонента для обозначения в КД (толщина линий 0,15 мм);
- Package Geometry/Place_Bound_Top - корпус 3d модели компонента;
- Ref Des/Silkscreen_Top - позиционное обозначение(Designator) шелкография на верхнем слое (толщина линий 0,2 мм);
- Ref Des/Assembly_Top - позиционное обозначение(Designator) для обозначения в КД (высота текста 3,5 мм);

- pads папка содержит набор контактных площадок;
- step папка содержит набор step-моделей компонентов; 
- symbols папка содержит footpint компонентов;
- Template list of elements содержит листы перечня элементов по ГОСТ;
- Template of sheets содержит листы схемы Э3 по ГОСТ;
- MOP44.DBC для подключения в системе базы данных;
- MOP44.MDB база данных компонентов в формате Access;
- MOP44.OLB содержит УГО компонентов.
