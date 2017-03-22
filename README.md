# 26.5-Problem-Set
Fundamentals of Java 12.1 &amp; 12.2
Fundamentals of Java, Exercise 12.1

A linear search is called linear because it examines every element to determine if it there or not. 
int search (Object[] a, Object searchValue){
  For (int i = 0; i < a.length; i++)
    If (a[i].equals(searchvalue))
        return 1;
  return -1;
}
78, 85, & 99
int search (Int[] a, Int searchValue){
  For (int i = 0; i < searchValue; i++)
    If (a[i] == searchvalue)
        return 1;
  return -1;
}
The code segment checks an array a to see if it is in ascending order. 

Fundamentals of Java, Exercise 12.2

87654
48765
45876
45687
45678
87654
78654
76854
76584
76548
Selection Sort: # moves = n-1
Bubble Sort: # moves = (n-1) + (n-2) + (n - 3) …+ (n-n)
Insertion Sort: # moves = (n+1)
Void bubbleSort(Object[] a){
    Int k = 0; 
    Boolean exchangeMade = true; 

//Make up to n - 1 passes through array, exit early if no exchanges
//are made on previous pass.

While ((k < a.length -1) && echangeMade){
    exchangeMade = false;
    k++;
    for(int j = 0; j < a.length() - k; j++)
        If (((Comparable)a[j]).compareTo(a[j+1]) > 0){
            swap(a, j, j+1);
            exchangeMade = true;
        }
    }
}
