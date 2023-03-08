# Proje 1

## [22,27,16,2,18,6] -> Insertion Sort

## Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.


### İlk başta dizinin en küçük elemanını buluruz ve daha sonra ilk elemanla yerini değiştirirz.Dizimiz [22,27,16,2,18,6]'dir. 

### 1.aşama [2,27,16,22,18,6]
### 2.aşama [2,6,16,22,18,27] bu dizinin en küçüğü 6dır.Şimdi 2. eleman yani 27 ile 6nın yerini değiştirdik.
### 3.aşama [2,6,16,22,18,27] bu aşamada 16 doğru yerdedir.
### 4 aşama [2,6,16,18,22,27] 18 ile 22 nin yerini değiştirdik ve bu aşama aynı zamanda son aşama oldu. 

## Big-O gösterimini yazınız.
 ### cevap : O(n^2)


## Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız


### Average case: Aradığımız sayının ortada olması
### Worst case: Aradığımız sayının sonda olması
### Best case: Aradığımız sayının dizinin en başında olması.
#### cevap: average casedir.
.



##
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız. 

### İlk başta dizinin en küçük elemanını bulup başa alırız yani
### [2,3,5,8,7,9,4,15,6] sonrasında 2 ve 3 sıralı olduğu için 3. adımdaki yere en küçük eleman olan 4ü yazarız diğer adımlar da bu şekilde devam eder.
### 2.aşama [2,3,4,8,7,9,5,15,6]
### 3.aşama [2,3,4,5,7,9,8,15,6]
### 4.aşama [2,3,4,5,6,9,8,15,7] cevap buraya kadar ama devamı da aşağıdaki şekildedir.
### 5.aşama [2,3,4,5,6,7,8,15,9]
### 6.aşama [2,3,4,5,6,7,8,9,15]


