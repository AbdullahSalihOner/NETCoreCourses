# MERGE SORT PROJECT

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.


# Answer 1

          [16,21,11,8,12,22]

     [16,21,11]        [8,12,22]

    [16] [21,11]      [8,12] [22]

    [16] [21] [11]  [8] [12] [22]

     [16,21] [11]    [8,12] [22]

        [11,16,21]   [8,12,22]

          [8,12,11,16,21,22]

# Answer 2

O(nlogn) = O(6log6)