# Tales

В этом каталоге содержится размеченный корпус пар <текст – сюжетная линия> из русскоязычных сказок, в котором каждой сказке сопоставлена последовательность сюжетных фраз, составляющих ее сюжетную линию. Обучающий корпус `train_tales.json` содержит 1148 сказок с сайта [www.nukadeti.ru](https://nukadeti.ru), тестовый корпус `test_tales.json` содержит 50 сюжетных линий. 

В файле `train_tales.json` присутствуют следующие поля:
- `id` – идентификатор
- `title` – название
- `url` – url-адрес
- `author` – автор
- `text` – текст
- `desc` – описание
- `tags` – список категорий
- `plot` – сюжетная линия
