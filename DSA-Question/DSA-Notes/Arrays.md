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
