# Stylus - animate.css
Библиотека animate.css переведенная на `stylus` миксин

Плюсы данного подхода.
  -  Нет нужды подключать всю библиотеку **1759** строк css.
  - Минимально простой синтаксис в использовании

#### INSTALL
`npm i slylus-animate.css -S` или  `yarn add slylus-animate.css`

затем подключите библиотеку в вашу сборку. 
`@import "ваш_путь/node_modules/animate.styl"`

#### Использование
вставьте миксин в блок который хотите анимировать.
```
animate(имя анимации, время анимации)
```
#### Пример
```
.content
	width 90rem
	display block
	font-size 22px
	color #fff
	animate(fadeInOut, 1.5s)
```

Полный список анимаций можно посмотреть на офф сайте.
https://daneden.github.io/animate.css/
