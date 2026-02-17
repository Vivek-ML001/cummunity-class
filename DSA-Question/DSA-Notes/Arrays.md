# Array Questions

## 1. Largest Element
Find the maximum value in array.

```java
int max = arr[0];
for(int i=1;i<arr.length;i++){
    if(arr[i] > max){
        max = arr[i];
    }
}

```

## **2. Find Missing Number**

### **Question**
Given an array containing numbers from **1 to n+1** with one number missing, find the missing number.

**Example:**  
`[1,2,4,5] → Missing = 3`

### **Solution**

```java
int n = arr.length + 1;
int expectedSum = n * (n + 1) / 2;

int actualSum = 0;
for(int num : arr){
    actualSum += num;
}

int missing = expectedSum - actualSum;

``` 
