# Patika.dev Insertion Sort Projesi
Insertion Sort Patika.dev bitirme projesi

a)[22,27,16,2,18,6] -> Insertion Sort

a.1 - Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

a.2 - Big-O gösterimini yazınız.

a.3 - Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

a.4 - Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

b) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# a.1) AŞAMALAR

[22,27,16,2,18,6]  -----> (n)

[2,27,16,22,18,6]  -----> (n-1)

[2,6,16,22,18,27]  -----> (n-2)

[2,6,16,18,22,27]  -----> (n-3)

# a.2) Big-O Gösterimi

BEST Case: O(n)

WORST Case: O(n²) = n + (n-1) + (n-2)...+ 1

AVERAGE Case: O(n²)

# a.3) Time Complexity

Best case ---->  [2,6,16,18,22,27]

Worst case --->  [22,27,16,2,18,6]

Averaged case ---> [2,27,16,22,18,6]

# a.4) 18 Sayısının Durumu 

Averaged Case

# b) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı

[2|,3,5,8,7,9,4,15,6]

[2,3|,5,8,7,9,4,15,6]

[2,3,4|,8,7,9,5,15,6]

[2,3,4,5|,7,9,8,15,6]

www.patika.dev
