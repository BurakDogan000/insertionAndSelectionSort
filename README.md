# InsertionSort

[22,27,16,2,18,6] => InsertionSort 

Step 1 : [22,27,16,2,18,6] => 22 sub-array.<br>
Step 2 : [22,27,16,2,18,6] => 22, 27 sub-array.<br>
Step 3 : [16,22,27,2,18,6] => 16, 22, 27 sub-array.<br>
Step 4 : [2,16,22,27,18,6] => 2, 16, 22, 27 sub-array.<br>
Step 5 : [2,16,18,22,27,6] => 2, 16, 18, 22, 27 sub-array.<br>
Step 6 : [2,6,16,18,22,27] => array sorted

#### Big-O Notation:

n + (n-1) + (n-2) + (n-3) + (n-4) + 1 -----> (n * (n+1)) / 2 -----> (n^2) * n / 2 -----> O(n^2)

#### Time Complexity:

Dizi sıralandıktan sonra 18 sayısı average-case kapsamına girer.

# SelectionSort

[7,3,5,8,2,9,4,15,6] => SelectionSort

Step 1 : [2,3,5,8,7,9,4,15,6]<br>
Step 2 : [2,3,5,8,7,9,4,15,6]<br>
Step 3 : [2,3,4,8,7,9,5,15,6]<br>
Step 4 : [2,3,4,5,7,9,8,15,6]<br>
Step 5 : [2,3,4,5,6,9,8,15,7]
