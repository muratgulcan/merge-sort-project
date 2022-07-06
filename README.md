# MERGE SORT PROJECT

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

|Steps|Divided & Merged Schema|
|:--:|:--:|
| Seçili diziyi sol ve sağ alt dizilere böl   |[16,21,11,8,12,22]|
| Divide-2                                                |[16,21,11] - [8,12,22]|
| Divide-3                                                |[16] - [21,11] - [8] - [12,22]|
| Divide-4                                                |[16] - [21] - [11] - [8] - [12] - [22]|
| Bunları sıralı bir şekilde aynı şekilde birleştirin.          |[16] - [21,11] - [8] - [12,22]|
| Merge-2                                                 |[11,16,21] - [8,12,22]|
| Merge-3                                                 |[8,11,12,16,21,22]|

2. Big-O gösterimini yazınız..
 O(nlogn)
