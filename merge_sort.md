# Problem
**[16,21,11,8,12,22]**

    Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    Big-O gösterimini yazınız.

# Çözüm
<ul>
<li>[16,21,11,8,12,22]</li>
<li>[16,21,11]-[8,12,22]</li>
<li>[16,21]-[11] [8,12]-[22]</li>
<li>[16]-[21] [11] [8]-[12] [22]</li>
<li>[16,21]-[11] [8,12]-[22]</li>
<li>[11,16,21]-[8,12,22]</li>
<li>[8,11,12,16,21,22]</li>
</ul>

> *Big-O gösterimi 2^x=n olduğundan O(nlong) şeklindedir.*