## Для кого и чего это нужно?
**Цель:** Данный репозиторий в первую очередь предназначен для организации всей информации о кубах как с точки зрения разворачивания сервера, так и с точки зрения конечного пользователя то есть игрока.

**_Введение_**: Все что описано ниже направлено на одну простую цель - заставить всю охапку модов работать и **запускаться с одной кнопки** и при этом затратить как можно **меньше нервных клеток с вашей стороны**, ниже изложена структура текущего документа 

Документ разделен на две логические части, которые слабо связаны между собой:
### [Раздел для игроков](#раздел-для-игроков):

**Содержание раздела:**  
  - Детальный гайд с картинками для самых маленьких о том как установить себе нужный модпак.
  - Информация о сборках
### [Раздел для того кто разворачивает сервер](#раздел-для-того-кто-разворачивает-сервер).

**Описание раздела**: специальный раздел для меня (Абобы-хостера) который будет дополнен, в него не имеет смысла смотреть обычным игрокам

# Раздел для игроков
## Установка для настоящих пиратов.
По обыкновению для погружения в мир квадратных голов нужно загрузить и установить [лаунчер кубов: T-Launcher](https://tlauncher.org/)
>[!CAUTION]
>Пожалуйста во время установки будьте внимательны и не поставьте себе "Амиго бразуер" вместе с лаунчером кубов (сейчас амиго претерпел метаморфозы и превратился в OperaGx, но сути дела это не меняет)!
### Установщик модов CurseForge
Вторым важным моментом является лаунчер модпаков, а именно [curseForge](https://www.curseforge.com/download/app).
> Я предпочитаю версию Standalone, overWolf страшная помойка, не вижу смысла ее себе ставить в здаром уме.
> ![image](https://github.com/user-attachments/assets/e99a8787-583c-40d8-891a-67e8043b8831)

Следующим важным шагом будет поиск нужного нам модпака на просторах CurseForge, который включает следующие шаги:
- Вписываем назване модпака в верхнюю строку поиска, описание используемых сборок описано в соответствующем разделе
- Выбираем поиск по модпакам(второй прямоугольник чуть ниже)
- После того как нашли нужный нам модпак жмем Install
>   ![image](https://github.com/user-attachments/assets/de552864-a8d0-4621-b6d0-c90927c1d87d)

Далее переходим в раздел My Modpacks и томно ждем пока все установится. После окончания установки кликаем на установленный модпак:
> ![image](https://github.com/user-attachments/assets/c007b94a-ead3-4bb1-a44b-7d4ac219cc01)

Затем мы проваливаемся в соответствующий раздел и жмем на три точечки как на скриншоте и выбираем - "Open Folder", чтобы скопировать все нужные нам моды в директорию(папку), которую увидет наш лаунчер майнкрафта (T-launcher)
![image](https://github.com/user-attachments/assets/1d19ca41-a6b5-4985-9927-3451bd6e2ab4)
#### Папка с прелястями
В итоге мы должны увидеть как это ни странно обычную папку с кучей вложенных папок, пример ниже на скриншоте
> ![image](https://github.com/user-attachments/assets/6d3cef42-df4b-49e1-8b92-b2f84b337b42)
#Из этой папки нам в дальнейшем нужно будет скопировать все файлы[^1]
[^1]: можно использовать сочетание клавиш Ctrl + A и Ctrl + C соответственно :)

На этом манипуляции с CurseForge окончены, теперь переходим непосредственно к лаунчеру кубиков.

### Самый страшный грех детства T-laucnher
Осталось дело за малым, показать куда смотреть лаунчеру, чтобы все работало. 

Для этого переходим в настройки, на скриншоте они справа снизу.
![image](https://github.com/user-attachments/assets/b054eb3e-a9ec-493c-afc1-972a702f09e6)

И меняем папку на [папку с прелястями](#папка-с-прелястями), которая получена в результате взаимодействия с CurseForge, это необходимо для того, чтобы лаунчер понял откуда брать моды и чего еще не хватает для полноценного запуска майнкрафта.
![image](https://github.com/user-attachments/assets/20a44cdd-6435-4a5a-bce0-2bedd4e061cc)
>[!WARNING]
> Каждый раз когда вы ставите сборку - вы меняете папку в настройках t-launcher на нужную вам, то есть ту которая соответствует сборке.

#### Указываем параметры важные для установки, удаляем лишнее если нужно
В рамках установки важно указать **нужную версию майнкрафта**, все остальное подтянется автоматически.  
Получить эту информацию можно из [раздела с текущими сборками](url).  
При этом версию для установки мы выбираем **Forge**  

>[!CAUTION]
>Не ставьте версию CurseForgeOptifine она ломает большинство сборок, лучше самостоятельно доустановите Optifine если в этом есть необходимость.

![image](https://github.com/user-attachments/assets/45f2ea52-758d-4372-bf90-26f396166cb9)

#### Улучшение, которые радуют глаз
Формально у вас уже есть готовая версия с которой можно играть, но если вы смешарик и у вас не калькулятор вместо компьютера то настоятельно рекомендуется установить еще один мод - [**"OptiFine"**](#установка-optifine). \
Опционально можно еще установить [**ResourcePack**](#установка-resourcepack)
##### Установка Optifine
>[!WARNING]
>Иногда Optifine невозможно установить в силу того что он ломает другие моды, статус возможности установки Optifine можно найти в разделе со сборками
[Переходим на официальный сайт](https://optifine.net/downloads) и находим нужную нам версию, сначала minecraft-а, затем уже Forge. \
Получить эту информацию можно из [раздела с текущими сборками](url)  
Также там можно получить информацию о том возможно ли установить Optifine на конкретной сборке.
>[!TIP]
>Если нет совпадения по Forge версия в версию
##### Установка ResourcePack
Для чего он нужен?  
Глобально ресурс пак здорового человека должен улучшать разрешения текстур и делать картинку приятнее глазу, более детально можете самостоятельно погуглить что из него можно выжать.

>[!TIP]
>Учитывайте тот факт, что ресурс пак не встанет без Optifine, это значит что если Optifine не поддерживается сборкой, то Resource Pack тоже невозможно будет установить.
>
>Получить нужную вам версию можно просто загуглив что-то по типу - "майнкрафт <Версия> Resource Pack", лично мой выбор ресурспак- **Faithful**

## Раздел с текущими сборками
**Описание:** в данном разделе указаны все сборки, их статус и [важная информация для установки](#укзываем-параметры-важные-для-установки).

### DawnCraft - Echoes of Legends
- [ ] Статус сборки
- **Версия Minecraft**: 1.18.2
- **Версия Forge:** 40.2.17
- **Дополнительная информация:** Необходимо удалить мод - **"1.18.2netherskeletons4.8.jar"** из папки mods, иначе сборка не запускается.
### Industrial village
- [ ] Статус сборки
- **Версия Minecraft**: 1.20.1
- **Версия Forge:** 47.3.0
- **Дополнительная информация:**
- [Ссылка на сборку](https://www.curseforge.com/minecraft/modpacks/industrial-village/files/5897194)
