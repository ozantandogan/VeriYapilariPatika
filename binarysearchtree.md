# **Binary Search Tree**

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin ilk elemanı olan 7, roottur.

Elemanlar root'tan büyükse sağına, küçükse soluna gelecek şekilde ağaçlandırma yapılır.

Adım 1:                        

                        7
                    5  
                     
Adım 2:

                       7
                    5  
                 1  
                   
Adım 3 :

                        7
                     5     8
                  1     
                   
Adım 4 :

                        7
                     5     8
                  1    3
                   
Adım 5 :

                        7
                     5     8
                  1    6
                    3     
                         
Adım 6 :

                        7
                     5     8
                  1    6
                0   3     
                
Adım 7 :


                        7
                     5     8
                  1    6     9
                0   3 
                          
Adım 8: 

                        7
                     5     8
                  1    6     9
                0   3 
                      4     
                      
Adım 9: 

                        7
                     5     8
                  1    6     9
                0   3 
                  2   4     