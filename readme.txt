# Адаптивный макет

Продолжительность: 6 часов

В этом проекте вы создадите адаптивный макет для мобильных устройств с
использованием HTML и CSS. Макет должен демонстрировать понимание адаптивного
дизайна, подстраиваясь под малые, средние и большие размеры экрана.

Сначала вы напишете CSS для оформления страницы для небольшого мобильного
устройства. Затем, используя медиа-запросы, вы добавите точки остановки, чтобы
настроить макет для более широких экранов планшетов и настольных компьютеров.

Как и в предыдущих проектах, вы отправите готовую работу через GitHub.

ПРИМЕЧАНИЕ: Программа по веб-разработке предназначена для обучения вас HTML, CSS
и JavaScript, а также позволяет вам практиковаться и демонстрировать свое
мастерство в этих основных строительных блоках Интернета. По этой причине
избегайте использования таких фреймворков, как Bootstrap, Foundation, Skeleton и
т. д., для этого проекта. Несмотря на то, что вы можете в конечном итоге
использовать подобные фреймворки профессионально, вам все равно нужно знать и
уметь реализовывать проекты с вашими собственными знаниями HTML, CSS и
JavaScript. Кроме того, не отправляйте проекты, основанные на серверных
технологиях, таких как PHP или Ruby on Rails.

## Шаги

### Подготовка

Чтобы подготовиться к этому проекту, вам нужно убедиться, что вы выполнили и
поняли эти шаги.

1. Загрузите файлы проекта. Мы предоставили вам три файла:
   - responsive-website_mobile.png — это пример того, как макет должен выглядеть
     на мобильном телефоне шириной 320 пикселей.
   - responsive-website_tablet.png — это пример того, как макет должен выглядеть
     на планшете шириной не менее 768 пикселей.
   - responsive-website_desktop.png — это пример того, как макет должен
     выглядеть на экране шириной не менее 1024 пикселей.

2. Изучите Chrome DevTools.
   - Следуйте инструкциям по трем ссылкам на DevTool в ресурсах проекта, чтобы
     узнать, как использовать Chrome DevTools.
   - Chrome DevTools — это мощный инструмент для понимания того, как HTML и CSS,
     которые вы пишете, отображаются на странице. Вы можете использовать
     DevTools для поиска проблем и диагностики проблем, которые могут возникнуть
     при создании этого проекта и будущих проектов.

### Инструкции по проекту

Чтобы завершить этот проект, следуйте приведенным ниже инструкциям. Если
застряли, задайте вопрос в сообществе.

1. Создайте файловую структуру:
   - Создайте файлы index.html и styles.css.
   - Создайте папку с именем css и поместите в нее файл styles.css. Имя папки не
     должно быть с заглавной буквы.
   - Свяжите файл styles.css с index.html.

2. Создайте макет, используя подход mobile first:
   - Убедитесь, что файл HTML включает метатег `viewport` в заголовке документа.
     См. эту
     [ссылку](https://developers.google.com/speed/docs/insights/ConfigureViewport#overview),
     чтобы понять, почему и как добавить этот тег.
   - Посмотрите на предоставленный макет для _мобильного устройства_ и добавьте
     ту же информацию в шапку, заголовки, содержимое и подвал в файл index.html.
     - Используйте предоставленные изображения для изображений галереи
       портфолио, показанных в макетах.
     - Используйте для текста шрифт из [Google Fonts](https://fonts.google.com).
     - Используйте CSS, чтобы оформить макет в соответствии с предоставленным
       мобильным макетом. Убедитесь, что ваш мобильный дизайн соответствует
       макету с размером экрана 320 пикселей.

3. Когда у вас будет все готово для мобильного макета, используйте
   медиа-запросы, чтобы добавить точки остановки, чтобы настроить макет для
   более широких экранов планшетов и настольных компьютеров.
   - Подберите дизайн, который должен выглядеть на планшетном устройстве шириной
     768 пикселей и на экране рабочего стола шириной 1024 пикселя.
   - Используйте подход, ориентированный на мобильные устройства, написав свои
     медиа-запросы, используя свойство `min-width` в вашем CSS.

4. После того, как все ваши точки останова будут установлены, дважды проверьте,
   соответствует ли ваш макет трём макетам.
   - Дизайн не обязательно должен быть точным, но общий интервал и расположение
     элементов должны соответствовать дизайну макетов для мобильных устройств,
     планшетов и компьютеров.
   - Не стесняйтесь заменять изображение профиля и менять текст, но макеты
     должны соответствовать макетам.

5. Свяжите свое меню навигации с правильными разделами страницы, используя
   идентификаторы для ссылки на теги `a`.

6. Убедитесь, что ваш код действителен, пропустив его через валидатор HTML и
   CSS.
   - Ссылки на валидаторы можно найти в ресурсах проекта. Это поможет вам
     обнаружить любые ошибки, которые могут быть в вашем коде.
   - Есть несколько исключений, которые вам не нужно исправлять:
     - Не беспокойтесь о каких-либо предупреждениях, нам просто нужно, чтобы вы
       проверили возможные ошибки.
     - Если валидатор CSS отмечает использование `calc`, префиксов поставщиков
       или псевдоэлементов/псевдоклассов, эти ошибки следует игнорировать.
     - Если средство проверки HTML помечает использование вертикальной черты
       ('|') в ссылках/URL-адресах шрифтов Google, эту ошибку также можно
       игнорировать.

7. Прежде чем отправить свой проект на проверку, убедитесь, что вы можете
   отметить все пункты в контрольном списке отправки студенческого проекта.
   Контрольный список разработан, чтобы помочь вам убедиться, что вы выполнили
   требования и что ваш проект завершен и готов к отправке!

ПРИМЕЧАНИЕ. Хорошей практикой является проверка вашего проекта на
кросс-браузерную совместимость. Убедиться, что он выглядит и правильно работает
в нескольких (по крайней мере, трех) браузерах, является важной частью того,
чтобы быть первоклассным разработчиком. Если вы хотите, оставьте комментарий
рецензенту проекта о том, в каком браузере (ах) был проверен проект, чтобы
убедиться, что они видят вещи так, как вы их разработали.

### Дополнительный кредит

Чтобы получить оценку «превосходит», вы можете расширить проект следующими
способами:

1. Добавьте на страницу дополнительный раздел, например, раздел навыков. Не
   забудьте создать рабочую ссылку на новый раздел в меню навигации.
2. Добавьте не менее ДВУХ дополнительных элементов, чтобы придать дополнительный
   стиль и улучшить портфолио:
   - Новый цвет фона для навигации и/или основных разделов сайта.
   - Измените цвет хотя бы одного фрагмента текста.
   - Добавьте один дополнительный шрифт Google, который используется на
     странице.
   - Любые дополнительные стили для ссылок (например, границы, состояния
     наведения).
3. При создании панели навигации используйте
   [элемент `nav`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav)
   для дополнительной структуры и семантической разметки.

ПРИМЕЧАНИЕ:

- Чтобы получить оценку «Превосходит ожидания» за этот проект, вам необходимо
  выполнить **каждый** пункт из этого раздела. См. рубрику на вкладке «Как вы
  будете оцениваться» выше, чтобы узнать, как вы будете оцениваться.
- Если вы претендуете на оценку «превосходит ожидания», рекомендуется указать
  это в примечаниях к отправке.
- Проходные баллы являются окончательными. Если вы попытаетесь получить оценку
  «Превосходит ожидания», но пропустите элемент и получите оценку «Соответствует
  ожиданиям», второго шанса у вас не будет. Исключения могут быть сделаны для
  элементов, которые были неправильно оценены при рассмотрении.

### Ресурсы проекта

- https://validator.w3.org/#validate_by_input
- https://jigsaw.w3.org/css-validator/#validate_by_input
- https://developers.google.com/speed/docs/insights/ConfigureViewport
- https://developers.google.com/fonts/docs/getting_started
- https://web.dev/responsive-web-design-basics
- https://developer.mozilla.org/ru/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox
- https://css-tricks.com/snippets/css/a-guide-to-flexbox
- https://www.sketchingwithcss.com/samplechapter/cheatsheet.html

### Критерии оценки
