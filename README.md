# SUP Console flash programmator
## _Tudo o que é apresentado aqui é feito por você, por sua própria conta e risco._

Programador simples de memória flash paralela

- Construído com preços acessíveis Arduino Mega 2560
- Detalhes adicionais mínimos
- Fácil de repetir

## Possibilidades

- Apagar, ler e escrever chip de memória K5L2731CAA-D770 ou similar
- Контроль процесса передачи данных между компьютером и программатором
- Контроль процесса записи данных на Flash
- Световая индикация процессов (Запись, Чтение, Стирание, Ошибка)
- Можно определить поведение кнопок (Через исходный код прошивки)
- Можно выводить информацию о процессе на дисплей программатора (Через исходный код прошивки)
- Высокая скорость работы: до 1Mbit/S (Можно и выше, но производительность микроконтроллера не позволяет поднять скорость)

## Установка проекта

Необходим Python не ниже версии 3.9.10. Все операции описаны для ОС Windows с установленным GitBash.
- Необходимо выполнять от имени администратора.

Клонируем репозиторий с GIT:

```sh
git clone git@github.com:Promolife/sup_console_programmator.git
```
Заходим в директорию проекта

```sh
cd sup_console_programmator
```
Устанавливаем и активируем виртуальное окружение

```sh
python -m venv venv
source venv/Scripts/activate
```

Обновляем pip и устанавливаем зависимости

```sh
python -m pip install --upgrade pip
pip install pyserial
```

Готово! Можно начинать использовать.
