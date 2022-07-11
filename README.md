# Insertion_Sort

```python
def insertionSort(arr):
   for i in range(1, len(arr)):
      key = arr[i] #get each element
      j = i-1
      while j >= 0 and key &lit; arr[j] : #keep shifting until reaching index 0 or getting an element smaller than key
         arr[j + 1] = arr[j]
         j=j-1
      arr[j + 1] = key
```

## Proje 1

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

* (22 |27 16 2 18 6)
* (22 27 |16 2 18 6)
* (16 22 27 |2 18 6)
* (2 16 22 27 |18 6)
* (2 16 18 22 27 |6)
* (2 6 16 18 22 27)

2. Big-O 
O(n^2)

3.Time Complexity: 

Average case: 
O(n^2)
Worst case:
O(n^2)
Best case: 
O(n)

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Average case

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

* (7 |3 5 8 2 9 4 15 6)
* (3 7 |5 8 2 9 4 15 6)
* (3 5 7 |8 2 9 4 15 6)
* (3 5 7 8 |2 9 4 15 6)

