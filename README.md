https://github.com/Garbovskayaaa/russian-travel.git

# Одностраничный сайт с удобным интерфейсом для разных устройств.  **Путешествие по России**

>"Сайт создан на основе реальной поздки протяженностью 20 000 км

##  Вы ознакомитесь с интересными местами, которые стоит посетить: **Куршская коса**, **Кольский**, **Алтай**, **Байкал**, **Карелия**.

### 1) Сайт оформлен в CSS.
### 2) Применен компонентный подход БЭМ
### 3) Применены медиазапросы для разных разрешений экранов: 320px, 768px, 1024px и 1280px.
### 4) Используется склаживание шрифтов.
### 5) Ссылки реализованы через псевдокласс :hover и при нажатии открываются в новом окне.

### 1) Блок **`page`**
+  Для `page` установлена минимальная и максимальная высота/ширина, элементы выравнены по центру, установлен цвет фона, стиль шрифта и применяется оптимизация при рендеринге текста.

### 2) Секция **`header`**
+  Для **`intro`** применен display: flex.

### 3) Секция **`photo-grid`**
+ Применен display: grid; с абсолютным пизиционирование. В зависимости от разрешения экрана кол-во строк и колонок меняется. Так же менеются размеры фотографий.

### 4) Секция **`place`**
+ Применен display: grid с созданием визуального шаблона сетки.
+  Ссылки. Используется псевдокласс :hover с примененим opacity и transition. При наведении ссылка становится тусклой.

### 5) Секция **`cover`**
+ Фотография. Используется псевдокласс :hover с примененим opacity и transition. При наведении фото становится тусклым.

### 6) Блок **`footer`**
+ для разрешений от 320px Применен display: flex.,  space-between;
+ для разрешения 320px Применен display: flex., column;
+ Навигация. Используется псевдокласс :hover, при наведении ссылки становятся тусклыми.


### Планы по доработке проекта
1) В секции **`footer`** навигацию реализовать через iFrame, для удобства работы с сайтом (без переходов по другим сайтам)
2) Все фото на сайте реализовать с псевдоклассом :hover
