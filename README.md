# Merge Sort Project

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre asamalarını :

 Listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüyoruz.
[16,21,11,8,12,22]

```
* 1  [16,21,11,]     [8,12,22]
* 2 '[16] [21,11]'   '[8] [12,22]'
* 3 '[16] [11] [21]' '[8] [12] [22]'
* 4 '[11,16,21]'     '[8,12,22]'
* 5  [8,11,12,16,21,22]
```

## Big-O gösterimini

Her bir listeyi böldüğümüzden dolayı n kadar işlem olacagından ve bu işlemi logn kere yaptıgımızdan
o(nlogn)
