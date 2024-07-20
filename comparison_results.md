
# Порівняння алгоритмів пошуку підрядка

## Вступ
У цьому дослідженні було порівняно ефективність трьох алгоритмів пошуку підрядка: Боєра-Мура, Кнута-Морріса-Пратта та Рабіна-Карпа на основі двох текстових файлів. Для кожного алгоритму було виміряно час виконання для двох видів підрядків: існуючого та неіснуючого у тексті.

## Методи
Було реалізовано три алгоритми: Боєра-Мура, Кнута-Морріса-Пратта та Рабіна-Карпа. Використовуючи бібліотеку `timeit`, було виміряно середній час виконання кожного алгоритму для двох видів підрядків у двох статтях.

## Результати

| Algorithm           | Article   | Time Existing (s) | Time Non-Existing (s) |
|---------------------|-----------|-------------------|------------------------|
| Boyer-Moore | Article 1 | 0.000009 | 0.000006 |
| Boyer-Moore | Article 2 | 0.000006 | 0.000006 |
| Knuth-Morris-Pratt | Article 1 | 0.000022 | 0.000022 |
| Knuth-Morris-Pratt | Article 2 | 0.000019 | 0.000021 |
| Rabin-Karp | Article 1 | 0.000030 | 0.000023 |
| Rabin-Karp | Article 2 | 0.000023 | 0.000023 |

## Висновки
Для обох статей алгоритм Боєра-Мура виявився найшвидшим як для існуючих, так і для неіснуючих підрядків. Алгоритм Кнута-Морріса-Пратта показав середню ефективність, тоді як алгоритм Рабіна-Карпа був найповільнішим серед трьох. Таким чином, для задачі пошуку підрядка у великих текстах найкраще підходить алгоритм Боєра-Мура.