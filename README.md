
-----------------------------------------------------------
**Project description**

-class Logger realises the task
-main function calls SquareMatrix.multiplyTo, which multiplies matrixes and writes log to "log.txt" file
-class LoggerIT tests wirting log to file

-----------------------------------------------------------
**Задание**
1. Написать класс logger для написанного приложения умножения матриц:
"Даны две матрицы A и B размерности NxN. Необходимо вычислить их произведение: матрицу С.
C[i][j] = сумма по k от 1 до N A[i][k]*B[k][j].
Приложение должно логировать в файл название потока и элемент, который рассчитывает сейчас поток
1. Описать класс Singleton.
2. Встроить его применение в многопоточное приложение произведения матриц.
3. Написать тестовый пример, который формирует файл с логом.
4. Если потребуется использовать Singleton в проектной работе, предоставить описание в текстовом файле в GitHub репозитории где конкретно и в какой роли используется этот шаблон.
5. нарисовать диаграмму классов.
