## Зависимости
   ```bash
    pip install -r requirements.txt
  ```
После проверьте что всё установленно
   ```bash
       pip list
  ```

## Что было сделано -
+ Сбор данных: Извлечены цитаты с указанного сайта.
+ Собранные данные: Сохранены в формате JSON.

## Откуда были получены данные -
С сайта https://quotes.toscrape.com/

## Как осуществлялся сбор -
+ Инструменты: Использовался Python с библиотеками requests и BeautifulSoup для выполнения HTTP-запросов и парсинга HTML-кода.
+ Процесс:
1. Отправлен GET-запрос к URL сайта.
2. Получен HTML-код страницы.
3. С помощью BeautifulSoup проанализирован HTML-код для извлечения цитат, авторов и тегов.
4. Собранные данные сохранены в структуре словаря и экспортированы в JSON-файл.

## Почему был выбран тот или иной метод/инструмент, а не другой
+ Requests: Удобная библиотека для выполнения HTTP-запросов, которая позволяет легко получать данные с веб-страниц.
+ BeautifulSoup: Эффективный инструмент для парсинга HTML и XML документов, который позволяет легко извлекать нужные данные.
+ JSON: Формат, удобный для хранения и обмена данными, легко читаемый и поддерживаемый многими языками программирования.