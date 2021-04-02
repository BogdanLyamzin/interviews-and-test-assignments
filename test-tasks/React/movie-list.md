# Test Task for Intern / Junior Front-End Developer Position @ Youscan

Основная задача тестового не узнать как сильно вы знаете React, а посмотреть насколько хорошо вы сможете разобраться с новыми технологиями в относительно короткий срок. В идеале, на него нужно потратить не более 3 дней. А так - делайте сколько делается, пока мы не закроем вакансию ;)

### Описание

Нужно написать одностраничное приложения для просмотра фильмов с помощью The Movie Database API. 

При открытии приложения, должен отображаться список популярных фильмов с пагинацией или динамической подгрузкой (на выбор). Также на странице должно быть поле для поиска. Когда ты вводишь туда какой-то текст, должны отобразиться фильмы которые ему соответствуют. Для каждого фильма в списке должен отображаться список жанров (названий жанров, не айдишек), к которым он принадлежит.

При клике на карточку с фильмом, должна быть показана страница с детальной информацией об этом фильме и списком рекоммендованых или похожих (можно и то, и то) фильмов к нему.

Также реализуйте возможность добавлять фильмы в избранное как со списка, так и на странице с отдельным фильмом. Список таких фильмов сохраняйте локально (localStorage, например). Предусмотрите просмотр списка с избранными фильмами где-то в приложении и удаление из избранного. Также предусмотрите отображение на карточке с фильмом и его странице информации о том, что этот фильм добавлен в избранное.

### Важно!

1. Вы можете использовать готовые компоненты и/или утилиты. Например, [компонент](https://www.npmjs.com/package/react-infinite-scroll) для ленивой подгрузки или [утилиту](https://github.com/elgerlambert/redux-localstorage) для синхронизации с localStorage. Еще, есть [готовые](http://www.material-ui.com/#/) [библиотеки](https://react-bootstrap.github.io/) [компонентов](https://github.com/nikgraf/belle), которые помогут ускорить разработку.
2. Внешний вид приложения тоже оценивается. Попробуйте продумать интерфейс пользователя и его взаимодействие с приложением / UX
2. По желанию, можете покрыть код необходимым набором тестов
3. Используйте современный JavaScript
4. Добавьте к решению инструкции по запуску проекта и краткое описание решения
5. Выложите куда-то рабочее приложение, например, на GitHub Pages или Heroku
6. По технологиям – на свое усмотрение, из обязательного только React.

### Полезные материалы

**Ссылки с документацией к API:**

 - https://developers.themoviedb.org/3
 - https://developers.themoviedb.org/3/movies/get-popular-movies
 - https://developers.themoviedb.org/3/search/search-movies
 - https://developers.themoviedb.org/3/genres
 - https://developers.themoviedb.org/3/movies/get-movie-details
 - https://developers.themoviedb.org/3/movies/get-movie-recommendations
 
**Можно почитать / посмотреть:**

 - [React Video Course on egghead](https://egghead.io/courses/react-fundamentals)
 - [React Video Course on reacttraining](https://online.reacttraining.com/p/reactjsfundamentals)
 - [Redux Video Course Part 1](https://egghead.io/courses/getting-started-with-redux)
 - [Redux Video Course Part 2](https://egghead.io/courses/building-react-applications-with-idiomatic-redux)
 - [Вебинар по ФП](https://www.youtube.com/watch?v=8nWQCcqUwR0)
 - [Документация Redux](http://redux.js.org/) (рекомендую читать прям как книгу)
 - [Документация React](https://facebook.github.io/react/) (аналогично)
 - [Normalizr](https://github.com/paularmstrong/normalizr)
 - [ImmutableJS](https://facebook.github.io/immutable-js/)
 - [ImmutableJS - хороший доклад](https://www.youtube.com/watch?v=I7IdS-PbEgI&feature=youtu.be)
 - [ES2015](https://learn.javascript.ru/es-modern)
 - [Куча полезностей по Redux](https://github.com/xgrommx/awesome-redux)
 - [Хорошая статья про react-router](https://medium.com/@dabit3/beginner-s-guide-to-react-router-53094349669)
 - [Пример: Sound Redux](https://github.com/andrewngu/sound-redux)
 - [Пример:  Асинхронные запросы в Redux](https://github.com/reactjs/redux/tree/master/examples/async)
 - [Пример:  Пример с роутингом и редаксом](https://github.com/knowbody/redux-react-router-example-app)
 

