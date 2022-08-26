# Курсовой проект

## Содержание:

### Решение СЛАУ методом Монте-Карло


## Инструкция по работе

При помощи Makefile:

```
make
make run
```

Синтаксис:

```
./solution [путь к файлу] -p [точность] -[тип метода]     
```

Описание:

| ТИП МЕТОДА |                          ОПИСАНИЕ                      |
|:-----------:|:------------------------------------------------------------:|
|     -a      |   Метод Монте-Карло с поглощающей вероятностью перехода   |
|     -n      | Метод Монте-Карло с вероятностью непоглощающего перехода |

Очистить:

```
make clean
```