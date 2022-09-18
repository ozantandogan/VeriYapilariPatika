# **Proje1 - Insertion Sort**


İkinci elemandan başlayarak elemanın kendinden önceki elemanlarla karşılaştırılması ve büyük elemanın sağa doğru kayması.

[22,27,16,2,18,6]

Adım 1:

[16,22,27,2,18,6]

Adım 2:

[2,16,22,27,18,6]

Adım 3 :

[2,16,18,22,27,6]

Adım 4 : 

[2,6,16,18,22,27]

## **Big-O-Notation**

(n-1)+(n-2)+(n+3)+...+1 = (n(n-1))/2 = n^2 

Sonuç : O(n^2)

## **Time Complexity**

Best Case : Dizinin sıralı olması. n

Worst Case : Dizinin tersten sıralı olması : n^2

Average Case : Dizinin normal dağılımı : n^2

Dizi sıralandıktan sonra 18 sayısı dizinin ortalarında olur.Bu sebeple Average Case kapsamına girer.



### [7,3,5,8,2,9,4,15,6] 

Adım 1 : [3,7,5,8,2,9,4,15,6] 

Adım 2 : [3,5,7,8,2,9,4,15,6] 

Adım 3 : [2,3,5,7,8,9,4,15,6]

Adım 4 : [2,3,4,5,7,8,9,15,6]