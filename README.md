# GULP-STARTER

---

Данная сборка используется в некоторых моих проектах. 

## Применяемые плагины

### HTML

* gulp-file-include – добавляет в html возможность шаблонизации;
* gulp-htmlmin – минифицирует (сжимает) html-файл;
* gulp-size – показывает размер html-файла;
gulp-webp-html – добавляет конструкцию `<picture></picture>`  в html-документ с добавлением туда изображения формата webp;

### CSS

* gulp-concat – объединение всех файлов стилей в один. После добавления в файловый поток принимает в себя имя конечного файла, который он должен вернуть.
* gulp-cssimport – заменяет директивы импорт на их содержимое.
* gulp-autoprefixer – добавляет свойства с вендорными префиксами там, где они нужны, чтобы обеспечить совместимость наших стилей со старыми браузерами;
* gulp-csso – сжатие (минификация) css-файлов;
* gulp-shorthand – заменяет все возможные свойства на их краткие формы;
* gulp-group-css-media-queries – группирует медиа-запросы;
* gulp-webp-css - добавляет конструкцию @supports с подключением файла в формате webp, если его поддерживает браузер;

### SASS

Для работы с препроцессором SASS установлены 2 пакета: gulp-sass и компилятор sass. Для SASS используются те же плагины, что и для CSS.

### Оптимизация изображений

* gulp-imagemin – оптимизирует изображения. Для каждого формата изображений можно задать свои настройки, но у данного плагина изменять их нет необходимости;
* gulp-newer – этот плагин выступает вроде некоторого фильтра, который пропускает дальше себя только те файлы, которые либо ещё не были обработаны, либо были изменены с момента последней обработки;

### Работа со шрифтами

* gulp-fonter – конвертирует шрифты.
* gulp-ttf2woff2 - конвертирует шрифты в формат woff2, так как gulp-fonter этот формат не поддерживает

---

Данную сборку можно запускать в двух режимах: разработки и продакшена. Режим разработки запускается с помошью команды __npm start__, а режим продакшена - __npm run build__.