  <table border="1" cellspacing="0" cellpadding="5">
    <thead>
      <tr>
        <th colspan="2" class="toggle-header" id="toggleHomework">Домашние задания по Java</th>
      </tr>
    </thead>
    <tbody id="homeworkSection">
      <tr>
        <td><a href="https://github.com/pmirov/HomeWork_1" target="_blank">Домашнее задание #1</a></td>
        <td>Задание на тему: Переменные, условия, циклы, массивы, методы</td>
      </tr>
      <tr>
        <td><a href="https://github.com/pmirov/HomeWork2" target="_blank">Домашнее задание #2</a></td>
        <td>Задание на тему: Объектно-ориентированное программирование</td>
      </tr>
      <tr>
        <td><a href="https://github.com/pmirov/HomeWork2" target="_blank">Домашнее задание #3</a></td>
        <td>Подробная документация и учебные материалы по веб-технологиям.</td>
      </tr>
    </tbody>
    
    <!-- Раздел для курсового проекта по C# -->
    <tbody>
      <tr>
        <th colspan="2">Курсовой проект по C#</th>
      </tr>
      <tr>
        <td><a href="https://github.com/pmirov/HomeWork_1" target="_blank">Курсовой проект C#</a></td>
        <td>Тема курсового проекта: Переменные, условия, циклы, массивы, методы</td>
      </tr>
    </tbody>
    
    <!-- Раздел для курсового проекта по HTML/CSS -->
    <tbody>
      <tr>
        <th colspan="2">Курсовой проект по HTML/CSS</th>
      </tr>
      <tr>
        <td><a href="https://github.com/pmirov/HomeWork_1" target="_blank">Курсовой проект HTML/CSS</a></td>
        <td>Тема курсового проекта: Переменные, условия, циклы, массивы, методы</td>
      </tr>
    </tbody>
    
    <!-- Раздел для курсового проекта по Java -->
    <tbody>
      <tr>
        <th colspan="2">Курсовой проект по Java</th>
      </tr>
      <tr>
        <td><a href="https://github.com/pmirov/HomeWork_1" target="_blank">Курсовой проект Java</a></td>
        <td>Тема курсового проекта: Переменные, условия, циклы, массивы, методы</td>
      </tr>
    </tbody>
  </table>

  <script>
    // Получаем ссылку на заголовок и секцию с домашними заданиями
    const toggleHeader = document.getElementById('toggleHomework');
    const homeworkSection = document.getElementById('homeworkSection');

    // Функция для переключения видимости раздела
    toggleHeader.addEventListener('click', function() {
      if (homeworkSection.style.display === 'none') {
        homeworkSection.style.display = '';
      } else {
        homeworkSection.style.display = 'none';
      }
    });
  </script>
