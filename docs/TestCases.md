base_url = https://sbleskom.ru/

#### TestCase 1. Появление модального окна при открытии
<table>
    <tr>
        <th>Steps</th>
        <th>Expected result</th>
    </tr>
    <tr>
        <td>1. Открыть base_url </td>
        <td>1. Осуществляется переход на главную страницу сайта и появляется модальное окно</td>
    </tr>
</table>


#### TestCase 2. Закрытие модального окна
<table>
    <tr>
        <th>Steps</th>
        <th>Expected result</th>
    </tr>
    <tr>
        <td>1. Открыть base_url </td>
        <td>1. Осуществляется переход на главную страницу сайта и появляется модальное окно</td>
    </tr>
    <tr>
        <td>2. Нажать на крестик в правом углу модального окна </td>
        <td>2. Модальное окно закрывается</td>
    </tr>
</table>

#### TestCase 3. Появление элемента popup при переходе на сайт
<table>
    <tr>
        <th>Steps</th>
        <th>Expected result</th>
    </tr>
    <tr>
        <td>1. Открыть base_url </td>
        <td>1. Осуществляется переход на главную страницу сайта и появляется элемент popup в нижнем правом углу</td>
    </tr>
</table>

#### TestCase 4. Сворачивание элемента popup
<table>
    <tr>
        <th>Steps</th>
        <th>Expected result</th>
    </tr>
    <tr>
        <td>1. Открыть base_url </td>
        <td>1. Осуществляется переход на главную страницу сайта и появляется модальное окно</td>
    </tr>
    <tr>
        <td>2. Нажать на крестик в левом углу элемента popup</td>
        <td>2. Элемент popup сворачивается</td>
    </tr>
</table>

#### TestCase 5. Разворачивание элемента popup
<table>
    <tr>
        <th>Steps</th>
        <th>Expected result</th>
    </tr>
    <tr>
        <td>1. Нажать на свернутый элемент popup в нижней левой части эрана</td>
        <td>1. Элемент popup разворачивается</td>
    </tr>
</table>

#### TestCase 6. Наличие кнопки меню в хеддере
###### Element: header
###### Subelement: кнопка меню
<table>
    <tr>
        <th>Steps</th>
        <th>Expected result</th>
    </tr>
    <tr>
        <td>1. Открыть base_url </td>
        <td>1. Осуществлется переход на главную старницу сайта с кнопкой меня в левой части хеддера</td>
    </tr>
</table>

