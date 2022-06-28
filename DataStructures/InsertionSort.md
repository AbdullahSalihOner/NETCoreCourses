# INSERTION SORT PROJECT

[22,27,16,2,18,6] -> Insertion Sort

   1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
   2. Big-O gösterimini yazınız.
   3. Time Complexity;

      Average case: Aradığımız sayının ortada olması,

      Worst case: Aradığımız sayının sonda olması, 

      Best case: Aradığımız sayının dizinin en başında olması
   4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


   5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

   # Answer 1
     [22,27,16,2,18,6]
            ↓
     [2,27,16,22,18,6]
            ↓
     [2,6,16,22,18,27]
            ↓(no change in this step because of 16 is bigger than left numbers and smaller tha right numbres same time.)
     [2,6,16,22,18,27]
            ↓
     [2,6,16,18,22,27]
            ↓(no change in this step because of 22 is bigger than left numbers and smaller tha right numbres same time.)
     [2,6,16,18,22,27]

# Answer 2
    O(n²) → n=6 => (6²) → O(36) 

# Answer 3
        Average Case : Big O(n^2) =Big O(36)
        Woest Case : Big O(n^2) = Big O(36)
        Best Case  : Big O(n)= Big O(6)
# Answer 4
    Average Case ( because  18 is at middle)

# Answer 5
     [7,3,5,8,2,9,4,15,6]
            ↓
     [2,3,5,8,7,9,4,15,6]
            ↓
     [2,3,5,8,7,9,4,15,6]
            ↓(no change in this step because of 3 is bigger than left numbers and smaller tha right numbres same time.)
     [2,3,4,8,7,9,5,15,6]
            ↓
     [2,3,4,5,7,9,8,15,6]


   