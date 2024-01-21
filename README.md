ben her şeyin çok başındayım, nasıl yapacağımı bilmiyorum, öğrnediğim çok az şey var :(  öğrenmek için burda değil miyiz ?

user_input = input("enter ten numbers :")
my_list = list(user_input)
my_list


swap fonksiyonu 
def swap (arr , x , y):
    temp = arr[x]
    arr[x] = arr[y]
    arr[y] = temp

    
my_list = [10, 30, 60, 20, 80, 40]
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0,n-i-1):
            if arr[j] > arr[j+1]:
                arr[j],arr[j+1] = arr[j+1],arr[j]
bubble_sort(my_list)
my_list
[10,20,30,40,60,80]
