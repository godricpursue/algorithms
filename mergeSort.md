# Proje 2 

## [16,21,11,8,12,22] -> Merge Sort

### Dizinin sort türüne göre aşamaları:
```
            [16,21,11,8,12,22]
         [16,21,11]       [8,12,22]    // 2^x = n
    [16] [21,11]            [8,12] [22] //logn
[16] [21] [11]                [8] [12] [22]
    [11] [16,21]            [8,12] [22] // n
         [11,16,21]       [8,12,22]
            [8,11,12,16,21,22]
 ```

## O(nlogn)