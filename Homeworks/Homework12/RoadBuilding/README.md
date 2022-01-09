# Road building

Имате дадени N града номерирани с чисалта от 1 до N и M двупосочни пътя, които ги свързват. Нито един от тези пътища все още не е простроен. Вие трябва да изберете N-1 от тях, такива че е възможно да се достигне от всеки едни град до всеки друг посредством тях. Освен това построяването на всеки път ви коства C1 усилие и ви носи C2 печалба за всяка единица усилие похарчена за построяването на пътя (цялостната печалба от построяването на един път е C1*C2).

От вас се иска да намерите тези N-1 пътя свързващи градовете, чието построяване ще ви коства минимално усилие. Ако има повече от една възможност, тогва искатe да имате максимална печалба.

### Input Format

На първият ред от входа ще са ви дадени целите числа N и M.

Следват M реда с по 4 цели числа:
- ai, bi - номерата на върховете, които са свързани от поредния път
- C1i, C2i - усилието и печалбата за единица усилие за съответния път 

### Constraints

1 <= N, M <= 2 * 10^5 <br>
1 <= ai, bi <= N <br>
1 <= C1i <= 10^17 <br>
-10^17 <= C2i <= 10^17

### Output format

Отпечатайте N-1 реда, съдържащи индексите на пътищата които сте избрали да бъдат построени. <br>
Aко има повече от едно решение, можете да отпечатате, което и да е от тях.

### Sample Input 0

3 3 <br>
1 2 1 7 <br>
2 3 3 2 <br>
1 3 2 3

### Sample Output 0

1 <br>
3