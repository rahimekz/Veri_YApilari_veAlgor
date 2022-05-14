# Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

## Sort Gösterimi 
          
[16,21,11,8,12,22]
           
Diziyi ikiye bölüyoruz.

[16,21,11]                [8,12,22]

Tekrar ikiye bölüyoruz.

[16,21]       [11]        [8,12]        [22]

tek eleman klana kadar bölmemiz gerekiyor.
                
[16]    [21]    [11]       [8]    [12]    [22]

Bölme işleminin tamamladığımız için artık birleştirebiliriz.

[16,21]   [11]             [8,12]   [22]

Sıralayarak birleştirmeye devam edebiliriz.

[11,16,21]                [8,12,22] 

So hali bu şekilde olmuş oluyor.

**[8,11,12,16,21,22]**


## Bİg-O gösterimi

O(n*(logn) olarak gösterilir.

https://www.patika.dev/tr
