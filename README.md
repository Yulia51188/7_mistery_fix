# Решатель квадратных уравнений

Скрипт `quadratic_equation.py` содержит функцию `get_roots(a, b, c)`, которая вычисляет действительные корни квадратного уравнения, заданного коэффициентоами `a, b, c`. Скрипт `test.py` содержит тестовые данные для проверки функции `get_roots` для разных значений дискриминанта.

# Как использовать

Используте функцию `get_roots(a, b, c)` из модуля `quadratic_equation.py` для вычисления действительных корней квадратного уравнения, заданного вещественными коэффициентами `a, b, c`. Функция возвращает два значения корней.

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск скрипта с тестовыми данными из терминала Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```
Запуск на Windows происходит аналогично.

Вызов функции `get_roots(a, b, c)` из модуля `quadratic_equation.py`:

    from quadratic_equation import get_roots
    
    root1, root2 = get_roots(1, 2, 3)


# Цели проекта

Код создан в учебных целях, в рамках учебного курса по web-разработке ― [DEVMAN.org](https://devman.org)
