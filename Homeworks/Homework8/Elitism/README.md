# Elitism

Алгоритмия e станала много елитна държава и всеки ден населението й расте! Държавният глава се интересува от гражданите си и наема статистици да следят за различни показатели на населението.

Един показател, който иска да знае е медиана на състоянието. Това е число, което разделя населението на две равни части - едната част има повече пари в сметката си, от това число, а другата по-малко.

Бивайки много популярна държава, следенето на този показател е трудно, тъй като всеки ден нов гражданин се преселва в Алгоритмия. Помогнете на статистиците като след всеки нов регистриран гражданин отпечатате на стандартния изход медианата.

### Input Format

Първият ред на стандартния вход съдържа едно цяло число N (брой граждани).

Следват N на брой цели положителни числа a0, .., aN-1, всяко на нов ред (парите на поредния гражданин).

### Constraints

1 <= N <= 5 * 10^5 <br>
0 <= ai <= 2^24

### Output format

След всеки регистриран гражданин, отпечатайте на нов ред на стандартния изход обновената статистика с точност до първия знак след десетичната запетая (с точност до 10^-1).

### Sample Input 0

10 <br>
1 <br>
2 <br>
3 <br>
4 <br>
5 <br>
6 <br>
7 <br>
8 <br>
9 <br>
10

### Sample Output 0

1.0 <br>
1.5 <br>
2.0 <br>
2.5 <br>
3.0 <br>
3.5 <br>
4.0 <br>
4.5 <br>
5.0 <br>
5.5

### Sample Input 1

4 <br>
3 <br>
11 <br>
4 <br>
2

### Sample Output 1

3.0 <br>
7.0 <br>
4.0 <br>
3.5