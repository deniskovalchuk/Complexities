# Bubble sort

<b>Сортировка простыми обменами, сортиро́вка пузырько́м</b> (англ. bubble sort) — простой алгоритм сортировки. Для понимания и реализации этот алгоритм — простейший, но эффективен он лишь для небольших массивов.

<p>Алгоритм состоит из повторяющихся проходов по сортируемому массиву. За каждый проход элементы последовательно сравниваются попарно и, если порядок в паре неверный, выполняется обмен элементов. Проходы по массиву повторяются N − 1 раз или до тех пор, пока на очередном проходе не окажется, что обмены больше не нужны, что означает — массив отсортирован. При каждом проходе алгоритма по внутреннему циклу, очередной наибольший элемент массива ставится на своё место в конце массива рядом с предыдущим «наибольшим элементом», а наименьший элемент перемещается на одну позицию к началу массива («всплывает» до нужной позиции, как пузырёк в воде, отсюда и название алгоритма).</p>

<h2>Image</h2>
<img src="https://gist.githubusercontent.com/deniskovalchuk/ffcff1289e8b0209d47fb7336dfce5c0/raw/3b91aca95fc89a2e53c296ff1b9a1baf98f78dab/bubble_sort.png">

<h2>Complexities</h2>
<div>
<table>
  <tr align="center">
    <td>Best</td>
    <td>Average</td>
    <td>Worst</td>
    <td>Space Complexity</td>
  </tr>
  <tr align="center">
    <td>Ω(n)</td>
    <td>O(n^2)</td>
    <td>O(n^2)</td>
    <td>O(1)</td>
  </tr>
</table>
</div>

<h2>References</h2>
<a href="https://ru.wikipedia.org/wiki/%D0%A1%D0%BE%D1%80%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B0_%D0%BF%D1%83%D0%B7%D1%8B%D1%80%D1%8C%D0%BA%D0%BE%D0%BC">wikipedia.org</a>.