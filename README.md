# Программа для расчета параметров треугольника 
## Описание
Эта программа, написанная на C++, вычисляет следующие параметры треугольника:
- Периметр
- Площадь по формуле Герона

Также, эта программа выполняет проверку на тавнобедренность.

## Функции
- findTriangleSide - вычисляет длину стороны по заданным точкам M1, M2
- findTrianglePerimeter - вычисляет периметр по данным сторонам
- findTriangleArea - вычисляет площадь треугольника по формуле герона
- isIsoscelesTriangle - проверяет треугольник на равнобедренность

## Пользование программой
После запуска программы введите координаты трех точек ( (1, 2.345) ()). Если ввод будет некорректный, то программа выдаст не верный результат.
Пример ввода:
- 1 2.345 43.34 98.3 34, 4

## Установка
1. Склонируйте репозиторий `git clone https://github.com/xxaqurm/Lab1`
2. Скомпилируйте файл: `g++ path/to/repository/main.cpp -o main`
3. Запусти программу:
    - main.exe (windows)
    - ./main   (Linux/MacOS)
