# Quick-Sorter
QuickSorter is a Java class that provides methods to perform quick sort algorithm on an array list of comparable objects. This class includes four different pivot selection strategies for the quick sort algorithm: first element, random element, median of three random elements, and median of three elements.

## Pivot Strategies ##
QuickSorter provides four different pivot selection strategies that can be used with the timedQuickSort method:

FIRST_ELEMENT
The FIRST_ELEMENT strategy selects the first element in the array list as the pivot.

RANDOM_ELEMENT
The RANDOM_ELEMENT strategy selects a random element in the array list as the pivot.

MEDIAN_OF_THREE_RANDOM_ELEMENTS
The MEDIAN_OF_THREE_RANDOM_ELEMENTS strategy selects three random elements in the array list, calculates the median of the three, and uses it as the pivot.

MEDIAN_OF_THREE_ELEMENTS
The MEDIAN_OF_THREE_ELEMENTS strategy selects the first, middle, and last elements in the array list, calculates the median of the three, and uses it as the pivot.

## Usage ##

In IDE terminal:
1. javac Main.java QuickSorter.java
2. java Main  
