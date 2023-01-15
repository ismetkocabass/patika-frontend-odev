## SELECTION SORT PROJECT


## Selection Sort
- [22,27,16,2,18,6] 

- [2,27,16,22,18,6]--> En küçük sayıyı buluyoruz ve en başa yazıyoruz. (n tane eleman)


- [2,6,16,22,18,27]--> (n-1) eleman içinden tekrar en küçük sayıyı bulup ikinci sıraya yazıyoruz.


- [2,6,16,22,18,27]--> (n-2) eleman içinden tekrar en küçük sayıyı buluyoruz zaten üçüncü sırada.Dokunmuyoruz.


- [2,6,16,18,22,27]--> Bu şekilde giderek bitiriyoruz. Küçükten büyüğe sıralamış olduk. 



## Big-O gösterimi

Selection Sort için;

İlk adımda (n) eleman, ikinci adımda (n-1) eleman, üçüncü adımda (n-2) eleman ile işlem yaparak 1 eleman kalana kadar devam ediyoruz.

Formül--> n+(n-1)+(n-2)+...+1= n(n+1)/2 

n^2+n /2 elde ettik. n^2 yi alıyoruz.  
Sonuç--> O(n^2)


## Time Complexity

[2,6,16,18,22,27] 

Dizi sıralandıktan sonra 18 sayısı ortada olduğu için avarage case kapsamına girer.

---

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı;

 - [**2**,3,5,8,7,9,4,15,6]--> En küçük sayı ve en baştakini yer değiştir.

 - [2,**3**,5,8,7,9,4,15,6]--> 3 doğru yerde.Dokunma.

 - [2,3,**4**,8,7,9,**5**,15,6]--> 4 ve 5 yer değişir.

 - [2,3,4,**5**,7,9,**8**,15,6]--> 5 ve 8 yer değişir.







