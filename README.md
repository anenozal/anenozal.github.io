Проект посвящен кроссфит-клубу «Hot Heads». Целью сайта является представление клуба на просторах интернета, привлечение клиентов и предоставление информации о клубе в доступной форме.
Для создания сайта использовались HTML и CSS.
Для того, чтобы сделать страницу адаптивной, были использованы относительные единицы измерения (vw) и медиазапросы. Были прописаны следующие медиазапросы:
1) 320-480px (мобильная версия)
2) 480-767px
3) 768-1024 px
4) от 1468 px
Запрос для промежутка 1024-1468 px прописан не был, так как он соответствует размеру рабочего монитора, т.е. изначально все размеры задавались именно для него.
Для позиционирования элементов на странице были использованы флексбоксы, поэтому далее мы будем говорить о выстраивании элементов в «колонку» или в «ряд».
В отличие от всех остальных запросов, в первом для удобства пользователя элементы перестраиваются в колонки: экран довольно узок. Также здесь значительно увеличены шрифты. Хэдер и футер уменьшены в размерах – некоторые элементы скрыты, – это сделано для того, чтобы не приходилось слишком долго прокручивать страницу. Также в футере не дублируется меню. К скрытым элементам также относятся слайдер и картинки-бэкграунды, такой ход предпринят для сокращения времени загрузки страницы. Также здесь отключена анимация.
В последующих медиазапросах элементы выстраиваются в ряд.
Во втором запросе (480-768px) хэдер и футер также несколько видоизменены: в хэдере скрыта часть с адресом, в футере скрыто меню. Данная трансформация была предпринята по причине ограниченной ширины экрана. Для первой страницы было ограничено количество изображений, отображаемых в слайдере.
В третьем запросе (768-1024 px) незначительным трансформациям подвержены размеры элементов. Здесь хэдер и футер отображаются полностью.
Для четвертого запроса характерно уменьшение шрифта. Также для страниц, наполненных преимущественно текстом, ограничивается ширина блока, чтобы сохранить возможность адекватного чтения информации.
Переход между страницами осуществляется с помощью ссылок. Для перехода на страницу с формой записи из хедера и футера форме был присвоен идентификатор.
Для создания фона на некоторых страницах был использован gradient. Также он был использован для придания объемности меню. Для выделения объектов и придания объемности тексту были использованы box-shadow и text-shadow(страницы 5 и 1 соответственно).
На странице 4 была использована анимация, которую мы назвали float. Она реализована с помощью с помощью keyframes: прописано 3 шага ¬ 0%, 50%, 100%. На втором шаге элемент продвигаеся вверх по оси Y с помощью transform:translatY, а затем возвращается в исходное положение. Задано бесконечное количество повторений. Один круг движений осуществляется за 1,6 сек.
Также анимация использована на странице 3 (bounce-in). Она реализована с помощью с помощью keyframes: прописано 8 шагов ¬ 25%, 40%, 50%, 60%, 70%, 80%, 90%, и 100%. Для каждого из шагов прописано изменение размеров элемента с помощью transform: scale.
Также к эффектам можно отнести подчеркивание меню футера при наведении курсора и изменение расстояния между буквами в меню хэдэра (с 4 запроса ввиду ограниченной ширины экрана).
Проверка работоспособности была осуществлена в следующих браузерах:
Internet Explorer (10,11), Opera, Google Chrome, Microsoft Edge, Safari.