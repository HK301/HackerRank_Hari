# HackerRank_Hari
Hacker Rank Question and Solutions

Question 1:
Insertion sort-1
def insertionSort1(n, arr):
    # Write your code here
    key = arr[-1]
    i = n-1
    while i > 0 and arr[i-1] > key:
        arr[i] = arr[i-1]
        print(*arr)
        i -= 1
    arr[i] = key
    print(*arr)
