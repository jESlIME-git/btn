# BTN это кодировщик и декодировщик любого файла по паролю написанный на golang

## Использование
Достаточно скачать файл(в завасимости от Вашей ОС) из папки src и использовать в коммандной строке:

```bash
> ./btn
Key:  example
File: example.txt
```
Или с использованием аргументов коммандной строки:
```bash
> ./btn -f example.txt -k example
```

## Краткое описание аргументов коммандной строки
### --file или -f
Используется для указания файла для кодировки.
### --key или -k 
Используется для указания ключа кодировки, может быть любой длинны. Ключём может служить и файл, к примеру `-k file:key.txt`.
### --output или -o
Используется для указания выходного файла(ВНИМАНИЕ! Перезапишет любой файл без вопросов, будте осторожны!).
### --help или -h
Для получения этого меню помощи, но только в консоли.
