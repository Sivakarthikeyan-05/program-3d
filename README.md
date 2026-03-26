# program-3d
# 🧪 C Programming Lab
## 📘 Experiment No: 3d
### 🔹
**Date:** 10/3/2026  
**Name:** Sivakarthikeyan
**Register No:** 25017090 

---

## 🎯 AIM
To write a C program to get an array and a element as input and search the element in that array.
---

## 🧠 ALGORITHM
1.Get an array as input from the user.
2.get an element to search.
3.Search the element in that array using for loop.
4.Print the index position of the element.
---

## 💻 PROGRAM

```
#include<stdio.h>
int main()
{
    int num;
    scanf("%d",&num);
    int arr[num];
    for(int i=0;i<num;i++)
    {
        scanf("%d",&arr[i]);
    }
    
    
    for(int i=0;i<num;i++)
    {
        if(arr[i]==5)
        printf("5 is found at position %d",i+1);
    }
}

```

## 🖼️ OUTPUT SCREENSHOT

<img width="834" height="120" alt="image" src="https://github.com/user-attachments/assets/2ff16b88-dec9-4456-bbce-27a1a90e162e" />

---

## ✅ RESULT
: Thus the c program to get an array as input and search an element in that array is executed succesfully.
