### 1 задача.

Во входном файле input.txt в первой строке через пробел записаны два целых числа M, N ∈ [0,10000]. В следующих M строках записано по N символов - матрица размера M x N (формат см. в примере). Необходимо написать консольное приложение, выводящее символы из матрицы, из которых составляется строка "OneTwoTrip" (регистр символа при составлении слова значения не имеет), и их индексы в соответствующем порядке в столбик через точку с запятой в следующем виде: "СИМВОЛ - (m, n);" либо вывести "Impossible", если это невозможно сделать. Один элемент матрицы при составлении строки можно использовать только один раз. Корректность входных данных гарантируется.

Пример:
input.txt:

3 4

nOe1

Two2

Trip

output.txt (один из возможных):

o - (1, 2);

n - (0, 0);

e - (0, 2);

T - (1, 0);

w - (1, 1);

O - (0, 1);

T - (2, 0);

r - (2, 1);

i - (2, 2);

p - (2, 3);

оценка: 3 балла

### 2 задача.

Дан массив длинной n, нужно написать функцию, которая возвращает сумму всех положительных чисел.
пример: [1,-4,7,12] => 1 + 7 + 12 = 20

оценка: 1 балл

### 3 задача.

Нужно написать функцию, которая вернет кол-во вхождений подстроки в строке.
пример: строка "Lorem ipsum dolor sit amet, consectetur amet elit." подстрока "amet", функция должна вернуть 2

оценка: 1 балл

### 4 задача.

вам будет предоставлена строка, в которой могут быть смешанные буквы верхнего и нижнего регистра, и ваша задача - преобразовать эту строку только в нижний регистр или только в верхний регистр на основе:
если строка содержит одинаковое количество прописных и строчных букв, преобразовать строку в строчные иначе в прописные

оценка: 1 балл

### 5 задача.

Петя и Вася часто играют в различные логические игры. Недавно Петя поведал Васе о новой игре «Быки и коровы» и теперь они играют в эту игру сутками. Суть игры очень проста: Петя загадывает четырехзначное число, состоящее из различных цифр. Вася отгадывает задуманное Петей число, перебирая возможные варианты. Каждый раз Вася предлагает вариант своего числа, а Петя делает Васе подсказку: сообщает количество быков и коров, после чего Вася с учетом подсказки продолжает отгадывание числа до тех пор, пока не отгадает. Быки – это количество цифр в предложенном Васей числе, совпадающих по значению и стоящих в правильной позиции в задуманном Петей числе. Коровы – количество цифр, совпадающих по значению, но находящихся в неверной позиции. Например, если Петя задумал число 5671, а Вася предложил вариант 7251, то число быков равно 1 (только цифра 1 на своем месте), а число коров равно 2 (только цифры 7 и 5 не на своих местах). Петя силен в математике, но даже он может ошибаться. Помогите Пете написать программу, которая бы по загаданному Петей и предложенному Васей числам сообщала количество быков и коров.

В единственной строке входного файла INPUT.TXT записано два четырехзначных натуральных числа A и B через пробел, где А – загаданное Петей число, а В – предложенный Васей вариант.

В выходной файл OUTPUT.TXT нужно вывести два целых числа через пробел — количество быков и коров.

пример:

№	INPUT.TXT	

1)	5671 7251

2)	1234 1234

3)	2034 6234	

OUTPUT.TXT

1 2

4 0

2 1

оценка: 2 балла

### 6 задача.

Нужно написать функцию которая будет возвращать валиден ли пароль. Требования к сложности пароля:
* содержит прописные и строчные буквы.
* содержит цифры
* минимальная длинна 6 символов

оценка: 1 балл
