# Patika Veri Yapıları ve Algoritmalar Dersi Merge Sort Projesi

## Proje2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

```
[16,21,11,8,12,22]

1.aşama   [16,21,11]        [8,12,22]
2.aşama  [16]  [21,11]     [8]  [12,22]
3.aşama  [16] [21] [11]    [8] [12] [22]
4.aşama  [16]  [11,21]     [8]  [12,22]
5.aşama   [11,16,21]        [8,12,22]
6.aşama       [8,11,12,16,21,22]

Big-O: O(n*logn)
```