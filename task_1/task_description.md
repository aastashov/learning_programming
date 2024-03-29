# Игра "Угадай число" (Guess the Number)

### Описание задачи:

Вашей задачей является разработка программы "Угадай число". Игра должна быть консольной, где компьютер загадывает
случайное число, а пользователь пытается его угадать. Программа должна предоставлять подсказки пользователю о том, было
ли его предположение слишком большим, слишком маленьким или верным.

### Требования:

1. Генерация случайного числа:
    - Программа должна генерировать случайное число из определенного диапазона (например, от 1 до 100).
2. Ввод и валидация пользовательского ввода:
    - Пользователь должен иметь возможность вводить числа с клавиатуры.
    - Программа должна проверять введенные данные на корректность (число, а не текст или символ).
3. Сравнение чисел и вывод подсказок:
    - Если введенное число больше загаданного, программа должна выводить сообщение "Слишком много. Попробуйте еще раз!".
    - Если введенное число меньше загаданного, программа должна выводить сообщение "Слишком мало. Попробуйте еще раз!".
    - Если введенное число равно загаданному, программа должна выводить сообщение "Поздравляю! Вы угадали!" и
      завершаться.
4. Ограничение на количество попыток:
    - Установите максимальное количество попыток (например, 10).
    - Если пользователь не угадал число за отведенное количество попыток, программа должна сообщить загаданное число и
      завершиться.
5. Организация кода:
    - Код должен быть структурирован и разделен на функции, например, функцию для генерации числа, функцию для ввода
      данных и функцию для сравнения чисел.
6. Дополнительные возможности (по желанию):
    - Добавьте возможность выбора уровня сложности (например, легкий, средний, сложный).
    - Записывайте статистику игрока, такую как количество попыток, и предоставляйте ей доступ после окончания игры.

Пример использования программы:

```bash
Добро пожаловать в игру "Угадай число"!
Компьютер загадал число от 1 до 100.

Введите вашу догадку: 50
Слишком много. Попробуйте еще раз!

Введите вашу догадку: 25
Слишком мало. Попробуйте еще раз!

...

Введите вашу догадку: 42
Поздравляю! Вы угадали!
```
