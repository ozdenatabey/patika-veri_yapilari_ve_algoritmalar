# Problem:
**[22,27,16,2,18,6]** dizisinin *Selection Sort* türüne göre aşamalarını yazınız.

Big-O gösterimini yapınız.

Time Complexity: Dizi sıralandıktan sonra **18** sayısı aşağıdaki case'lerden hangisinin kapsamına girer? 

1- *Average Case*: Aradığımız sayının ortada olması

2- *Worst Case*: Aradığımız sayının sonda olması

3- *Best Case*: Aradığımız sayının dizinin en başında olması

**[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
# Çözüm
Selection Sort türüne göre sıralama yapılırken öncelikle en küçük sayıyı listenin en başından başlayarak tek tek bütün elemanları gezerek bulmaya çalışırız. En küçük sayı bulunduktan sonra en baştaki sayı ile yer değiştirilir.
**<p> 1. [22,27,16,2,18,6] <p>**
**<p> 2. [2,27,16,22,18,6] <p>**
Daha sonra yukarıdaki işlemin aynısını ikinci en küçük sayı için tekrarlarız.
**<p> 3. [2,6,16,22,18,27] <p>**
Yukarıdaki aşamada görüldüğü üzere üçüncü en küçük sayı zaten olması gereken konumda bulunduğu için bir sonraki adıma geçildi.
**<p> 5. [2,6,16,22,18,27] <p>**
Ve bu şekilde işlemler en son sayı da yerine geçene kadar devam eder..
**<p> 6. [2,6,16,18,22,27] <p>**

> *Yukarıdaki sıralamanın Big-O gösterimi n.(n+1)/2'den O(n^2) dir.*

> *Dizi sıralandıktan sonra 18 sayısı "Average Case" kapsamına girer.*

**[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımı:

<ul>
<li>[2,3,5,8,7,9,4,15,6]</li>
<li>[2,3,5,8,7,9,4,15,6]</li>
<li>[2,3,4,8,7,9,5,15,6]</li>
<li>[2,3,4,5,7,9,8,15,6]</li>
</ul>