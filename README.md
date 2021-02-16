# Visualizing Sorting Algorithms
These two programs use pygame to visualiie the insertion sort and selection sort algorithms respectively. Each column is a class in a list. A sorting algorithm organizes it and it is displayed on the screen.

## selection_sort.py
The unsorted elements are in white and the sorted elements are in yellow. The cursor (orange) goes through all of the unsorted columns. When the cursor finds the shortest element, it hihglights it in green. Once the cursor reaches the end, the program swaps the next unsorted element and the green element.
![](images/selection_sort.GIF)

## insertion_sort.py
The unsorted elements are in white and the sorted elements are in yellow. The cursor (orange) starts at the first unsorted element. It then traverses the list backwards until it finds a spot where the element to the left of it is shorter than the orange element and taller on the right side.
![](images/insertion_sort.GIF)

