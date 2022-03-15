# Merge Sort Projesi 
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
# Big-O: O(nlogn)

Başlangıç:[16,21,11,8,12,22]

Sort1 = [16,21,11] - [8,12,22]

Sort2 = [16,21] - [11] - [8,12,22]

Sort3 = [16] - [21] - [11]-[8,12,22]

Sort4 = [16,21] - [11] - [8,12,22]

Sort5 = [11,16,21] - [8,12,22]

Sort6 = [11,16,21] - [8,12] - [22]

Sort7 = [11,16,21] - [8] - [12] - [22]

Sort8 = [11,16,21] - [8,12] - [22]

Sort9 = [11,16,21] - [8,12,22]

Sort10 =[8,11,12,16,21,22]

SortLast = [8,11,12,16,21,22]
