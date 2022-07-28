# Insertion-Sort-Proje
Proje 1
[22,27,16,2,18,6] -> Insertion Sort
Aşamaları: 
[22,27,16,2,18,6]
[2,27,16,22,18,6] : Aralarındaki en küçüğü bulup en başa yazıyoruz ve ilk sıradaki sayı ile yerlerini değiştiriyoruz.
[2,6,16,22,18,27] : İlk sıradaki sayı sıralı en küçük sayı olduğu için bir sonraki en küçük sayıyı bulmak için de aynı işlemi yapıyoruz.
[2,6,16,18,22,27] : En son hali ise böyle oluyor.
Big-O gösterimi:
n+(n-1)+(n-2)...+1  = n.n+1/2 = O(n^2) ----> Worst Case
O(n^2) ----> Average Case
O(n) ----> Best Case
Time Complexity:
Worst Case: [27,22,18,16,6,2]
Best Case: [2,6,16,18,22,27]
Dizi sıralandıktan sonra 18 sayısı dizinin ortanca değeri olduğu için Average Case'dir.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
... dizi bu şekilde devam eder.
