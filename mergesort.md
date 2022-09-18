# **Proje 2 Merge Sort**


Dizi, tek eleman kalana kadar ikiye bölünür.

[16,21,11,8,12,22] -> Merge Sort

Adım 1: [16,21,11 | 8,12,22]

Adım 2: [16,21 | 11 | 8 | 12,22]

Adım 3: [16 | 21 | 11 | 8 | 12 | 22]

Bölme işlemi bittikten sonra, tekli elemanlar ikili ikili birleştirilir ve en küçük eleman başa gelecek şekilde sıralanır.

Adım 4: [16,21 | 11 | 8 | 12,22]

Adım 5: [11,16,21 | 8,12,22]

Adım 6: [8,11,12,16,21,22]



**Big O Notation** 

Merge Sort'un Big-O-Notation'ı O(nlog(n)) 'dir.' Dizinin uzunluğu (n) kadar işlem yapılır. Bu yüzden O(6*(log6)) olacaktır.




