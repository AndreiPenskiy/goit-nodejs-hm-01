# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list
https://monosnap.com/file/FSb3iT0ERYoPiicSGk50fVTCuTAvMd

# Получаем контакт по id

node index.js --action get --id 5
https://monosnap.com/file/D8Oz4P45lkwtr34uuYL8EhoILzeIi1

# Добавялем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/V8fr1xdjwNZ3DSTkQdk19mkxJtnmB6

# Удаляем контакт

node index.js --action remove --id=3
https://monosnap.com/file/a4OFo8okflfk7md0xwo58JAxnQIim1
