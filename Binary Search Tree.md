# Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

* İlk önce root seçilir (root 7)

* 7den küçük olanlar sağ tarafa, büyük olanlar sol tarafa yerleştirilir.

  - 5<7 olduğu için sağ tarafa 

  - 1<7 ve 1<5 olduğu için 5in sağ tarafına 

  - 8>7 olduğu için 7nin soluna 

  - 3>1 olduğu için 1in sol tarafına 

  - 6<7 olduğu için sağ tarafa ama 6>5 olduğu için 5in soluna 

  - 0<7 ve 0<1 olduğu için 1in sağ tarafına 

  - 9>7 olduğu için sol tarafa ve 9>8 olduğu için 8in sol tarafına 

  - 4>3 olduğu için 3ün sol tarafına 

  - 2<3 olduğu için 3ün sağ tarafına geçer.

     

  ​                                                                  7

  ​                                                5                                  8                                                      

​                                          1                        6                                        9 

​                                  0             3

​                                             2        4          