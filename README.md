<p align="center">
  <img src="logos/eh-logo.svg" alt="Exception Hunters logo"/>
</p>
<br />

# Что будем делать (31 июля 2020)
1) Продолжим верстать "Super Host"

# Что сделали сегодня
1) Продолжили верстать "Super Host" (продолжили секцию 'intro')
2) Изучили различные виды позиционирования (relative, absolute)
3) Изучили псевдо теги ::before и ::after

# Ключевые моменты урока
1) Если мы хотим свободно размещать элементы на странице, абсолютно так как мы хотим, то нужно использовать 
<pre>
  position: absolute;
</pre>

2) когда мы прописываем стиль "position: absolute;" то мы его только включаем. Для того чтобы начать размещать элементы небходима также задать явные стили расположения:
<pre>
  top: 10px;
  left: 55px
</pre>

3) Начало системы отсчета окна браузера находится в верхнем левом углу, а положительные оси идут сверху-вниз и слева-направо
4) Если мы хотим абсолютно позиционировать ребенка внутри родителя, то родителю необходимо прописать стиль:
<pre>
  position: relative;
</pre>
иначе абсолютное позицонирование произойдет относительно глобального экрана браузера.
5) Кроме обычных тегов существуют еще псевдо теги. Их нет в html файле но они рендерятся браузером. Для того что бы создать псевдотег в css прописываем стили, например так:
<pre>
  .box::before {
    content: "";
    background-image: url(/images/done.png);
    height: 16px;
    width: 16px;
    position: absolute;
  }
</pre>
стиль content: ""; обязателен, иначе ничего работать не будет. 

<br />
<br />
<br />
<p align="center">
  <img with="100" height="100" src="logos/html-5.svg" alt="html-logo"/>
  <img with="100" height="100" src="logos/css.svg" alt="css-logo"/>
  <img with="100" height="100" src="logos/javascript.svg" alt="js-logo"/>
  <img with="100" height="100" src="logos/react.svg" alt="react-logo"/>
  <img with="100" height="100" src="logos/redux.svg" alt="redux-logo"/>
  <img with="100" height="100" src="logos/firebase.svg" alt="firebase"/>
  <img with="100" height="100" src="logos/graphql.svg" alt="graphql"/>
  <img with="100" height="100" src="logos/redux-saga.svg" alt="redux-saga-logo"/>
  <img with="100" height="100" src="logos/material-ui-1.svg" alt="material-ui-logo"/>
</p>
