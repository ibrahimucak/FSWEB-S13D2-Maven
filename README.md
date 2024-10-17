# Java Algorithmic Thinking :)


### Hedeflerimiz:

### Palindrom Sayıyı Bulma

* Palindrom sayılar, kendisi ve tersen okunusu birbirine aynı olan sayılar demektir.
* 121 sayısının tersten okunusu da 121 olduğu için sayı plaindrom dur. Ya da 1001 sayısı da örnek verilebilir.
* ```isPalindrome``` isimli bir metod yazınız. ```int``` bir parametre almalı.
* Metodun dönüş değeri ```boolean``` olmalı.

isPalindrome(-1221); => true dönmeli
isPalindrome(707); => true dönmeli
isPalindrome(11212); => false dönmeli

### Mükemmel Sayıları Bulma

* Mükemmel Sayı, kendisi hariç tüm bölenlerinin toplamı kendisine eşit olan sayıya denir.
* Örneğin 6; 1, 2, 3 e bölünebilir. Bu değerlerin toplamı aynı zamanda 6 ya eşittir.
* ```isPerfectNumber``` isimli tek parametre alan bir metod yazmak istiyoruz.
* Parametresi 0'dan küçükse metod false döner.

isPerfectNumber(6); => true dönmeli (1+2+3=6)

isPerfectNumber(28); => true dönmeli (1+2+4+7+14=28)

isPerfectNumber(5); => false dönmeli (kendisi dışındaki tek böleni 1)

isPerfectNumber(-1); => false dönmeli(parametre 0'dan küçük olamaz)


### Sayıları Kelimelere Dök

* ```numberToWords``` isimli bir metod yazmalıyız ve içerisine bir tane ```int``` parametre almalı.
* metodumuz sayının numaralarına bakmalı ve string olarak her bir rakama karşılık gelen değerlerini yazdırmalı.
* Sayının değeri 0'dan küçükse "Invalid Value" değeri dönmeli.

numberToWords(123); => "One Two Three" dönmeli.

numberToWords(1010); => "One Zero One Zero" dönmeli.

numberToWords(-12); => "Invalid Value" dönmeli


