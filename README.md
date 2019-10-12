# VMFToBP
Convert specified placed props in hammer to blocker_passes config

Compiling:
Drag and drop archived project in My Exported Templates folder of Visual Studio.
Then create a project in visual studio using this template and enjoy !
Compile ! :)

Usage:
Make a prop_dynamic prop in hammer and set targetname to -> LinkTo and save your map file.
Then open .vmf file in program and you will get output that you have to put in https://beautifier.io/ and you will get output that
you need to put in addons/sourcemod/data/blocker_passes/<your_map_name>.cfg.
Enjoy !


#VMFToBP
Конвертируйте указанные пропы в хаммере в конфиг карты от плагина Blocker_passes.

Компиляция:
Перенесите архив с исходником в папку My Exported Templates где лежит Visual Studio.
Затем создайте проект по данному шаблону и все ! :)

Использование:
Поместите prop_dynamic в хаммере и задайте ему свойство "Name" на LinkTo и так указывайте каждый проп который нужно поставить на сервере.
Затем сохраните ваш .vmf файл карты и закиньте его в программу. В результате вы получите выход который нужно закинуть в https://beautifier.io/
и скопировать его в файл карты который лежит в папке addons/sourcemod/data/blocker_passes/<имя_карты>.cfg
