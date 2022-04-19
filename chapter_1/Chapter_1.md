# Stack

## 1. LIFO (last in first out) : 疊起來的椅子

 ## 2. Operations

* Push :  放進去。
* Pop   : 拿出來。
* Peep : (偷看)，查看資料。

## 3.System Stack

####  (1) Call function

## 4. Stack Implemented on Linked List

 ## 5. Expression Evaluation

### **電腦直接按照順序做即可完成運算**

* 前序
* 中序
* 後續

#### *Ex.*     a / b - c + d * e - a * c     <kbd>&rarr;</kbd>    a b / c - d e * + a c * 



# Queue

## 1. FIFO (first in firstout) : 一群人排隊買票 

## 2. Operations

* front
* back
* pop
* push



# 4/14 Class Note

## List : 元素可以重複

## Set : 集合，元素不能有重複的數

## Bag : 元素可以重複，有排序

## 1.  API 

**程式與程式之間的介面**

## 2. Self-Referential Structures

```c
typedef struct list{
    char data;
    list* link;	//	(X) list link
}
```

- 記憶體的位址為**一個整數**空間

## 3.  linked list 另類的printf方式

```c
for(; ptr; ptr = ptr->link){
    printf("%4d", ptr->data);
    printf("\n");
}
```

## 4-1. Dynamically Linked Stacks

​	利用temp

## 4-2. Dynamically Linked Queues

* #### 除非必要，stack、queue 沒有一定要用 linked list

* #### 例如資料量複雜且龐大

## Draw poly_nodes :

| coef | expon | link |
| ---- | ----- | ---- |

## 5. Circularly Linked List

​	**頭尾相接**



