# AlgorithmKuznechik

## Описание Работы
    В рамках летней практики в МГТУ им.Баумана я реализовал алгоритм шифрования Кузнечик а также обратный ему алгоритм для проверки корректности его работы.
    Изучение данного алгоритма и его реализация строились на основе статьи https://habr.com/ru/articles/459004/ .
    Помимо реализации самого алгоритма блочного шифрования было добавлено разбиение на блоки входных данных методом простой замены (Electronic Codebook, ECB).

## Использование Алгоритма
    Данные, которые необходимо зашифровать, записываются в файле input.txt.
    Ключи, необходимые для работы алгоритма записываются в переменные key_str_1, key_str_2. Если необходимо заменить исходные ключи, необходимо заменить значения переменных на необходимые.

## Output
    Результат работы программы выводится в консоль, а именно шифротекст и ниже результат обратного алгоритма (Исходный текст).