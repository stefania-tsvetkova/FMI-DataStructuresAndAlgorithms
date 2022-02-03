# Leafs

Даден ви е е ацикличен насочен граф като списък от ребра. Всеки връх има тежест колкото номера му. Дадени са ви заявки, под формата на номер на връх. За всяка една върнете сбора от всичките тежести на наседниците му.

### Input Format

На първия ред на стандартният вход ще получите броя на ребрата(m) и броя на заявките(t). На следващите m реда ще получите ребрата под формата на две числа - номера на началото на реброто и номера на края му. На следващите t реда ще получите заявки под формата на единствено число - номер на връх, чийто сбор на наследници трябва да върнете.

### Constraints

1 <= m,t <= 200000 <br>
1<= номер на връх <= 200000

### Output format

На отделни редове изкарайте на стандартняит изход отговора за всяка заявка.

### Sample Input 0

4 3 <br>
1 2 <br>
1 3 <br>
2 4 <br>
3 5 <br>
2 <br>
1 <br>
5

### Sample Output 0

4 <br>
14 <br>
0