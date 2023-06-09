# LCA
____
Маша уже вдоволь насмотрелась на свое бинарное дерево поиска, но напоследок решила провести еще одно исследование: она заметила, что у любых двух различных вершин в дереве всегда можно найти в дереве такую, которая их соединяет и путь от которой до этих вершин минимальный среди всех возможных. Например, на рисунке ниже для вершин 10 и 26 таковой является 19.
![image](https://user-images.githubusercontent.com/120199924/235907740-78966e1c-d484-48e0-baf9-7f5cb900c066.png)

Маша назвала такую вершину "наименьший общий предок". Оказывается, что весь остальной мир называет ее точно также (или LCA). Маша задумалась, что бы в ее особом дереве для двух произвольных выбранных вершин мог бы означать этот самый "наименьший общий предок". Для этого она решила собрать какую-нибудь статистику, а для этого, как водится, нужно написать и сам алгоритм поиска этой вершины. Помогите ей в этом.

## Формат ввода
В первой строке входных данных указана высота дерева (это значение не превосходит20). Во второй строке указаны два числа: вершины, для которых требуется найти LCA. В третьей строке разделенные пробелом перечислены значения из дерева так, что 
i-й элемент последовательности является родителем для i∗2-го и i∗2+1-го элементов (при условии нумерации с1). Если у вершины нет потомка, то вместо числа на соответствующем месте записано "-".

## Формат вывода
Программа должна вывести ровно одно число: содержимое LCA для двух вершин из входных данных.
