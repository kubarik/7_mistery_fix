# Решатель квадратных уравнений

Демонстрация процесса тестирования с помощью модуля **unittest**.
Поиск корней квадратного уровнения по заданным коэффициентам.

# Как использовать

Импортируемые модули
```python
from quadratic_equation import get_roots
```

Для получения значения корней квадратного уравнения выполняется функция
модуля **quadratic_equation**:

```python
get_roots(a, b, c)
```
где
a - старший коэффициент,
b - киэфициент при x,
c - свободный член.

Например:
```python
root1, root2 = get_roots(1, -2, 1)
```

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

