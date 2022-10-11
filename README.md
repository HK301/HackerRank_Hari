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
    
Question 2:
Counter Game : Bit Manipulation
def counterGame(n):
    # Write your code here
    setbits = bin(n-1).count('1')
    if setbits%2 == 1:
        return "Louise"
    return "Richard"
