# Merge Sort

## Soru 1 

[16,21,11,8,12,22] dizinin sort türüne göre aşamalarını yazınız.

* Dizi ikiye ayrılır 

​       [16,21,11]       [8,12,22] 

* Ayrılan dizilerde kendi içinde ikiye ayrılır.

  [16,21] [11]      [8,12] [22]

* Tek eleman kalana kadar parçalama işlemi devam eder.

  [16] [21] [11]     [8] [12] [22]

* Karşılaştırma yapılarak diziler kendi içinde küçükten büyüğe doğru sıralanır

  [11,16,21]    [8,12,22]

* Tekrar karşılaştırma yapılarak dizi küçükten büyüğe doğru sıralanır

  [8,11,12,16,21,22]

  ## Soru 2

  Big-O gösterimini yazınız.

  2^x = logn 

  logn = x

  O(n*logn)