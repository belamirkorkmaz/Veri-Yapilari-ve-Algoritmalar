[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[2,27,16,22,18,6] -> 2 ile 22 yer değiştirir
[2,6,16,22,18,27] -> 6 ile 27 yer değiştirir
[2,6,16,18,22,27] -> 18 ile 22 yer değiştirir
[2,6,16,18,22,27] -> 5. ve 6. sayı sıralamaya uygun olduğu için değişiklik yapılmaz

Big-O gösterimini yazınız.
Dizideki eleman sayısına n dersek ilk adımda n elemanı inceleyip en küçüğü başa yazarız
ikinci aşamada n-1 eleman inceleyip en küçüğü 2. sıraya yazarız
üçüncü aşamada n-2 eleman inceleyip en küçüğü 3. sıraya yazarız 
son elemana gelene kadar bu şekilde ilerleriz
n + (n+1) + (n+2) +...+ 1 kısaca n * (n+1) / 2 = (n^2 * n) / 2 şeklinde yazabiliriz
Big-O Notation'da fonksiyonu domine eden kısmı alırız yani Big-O gösterimi n^2 dir

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

[2,6,16,18,22,27] dizisine bakıldığında 18 sayısı ortada olduğu için Average Case kapsamına girer
