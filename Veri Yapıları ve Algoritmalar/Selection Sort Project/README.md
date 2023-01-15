## Selection Sort Projesi ##


## Selection Sort

- [22,27,16,2,18,6] 

- [**2,27,16,22,18,6**]--> En küçük sayıyı buluyoruz ve en başa yazıyoruz.

- [2,**6,16,22,18,27**]--> (n-1) eleman içinden tekrar en küçük sayıyı bulup ikinci sıraya yazıyoruz.

- [2,6,**16,22,18,27**]--> (n-2) eleman içinden tekrar en küçük sayıyı buluyoruz zaten üçüncü sırada.

- [2,6,16,**18,22,27**]--> Küçükten büyüğe sıralamış olduk.


## Big-O 

İlk adımda (n) eleman, ikinci adımda (n-1) eleman, üçüncü adımda (n-2) eleman ile işlem yaparak 1 eleman kalana kadar devam ediyoruz.

Formül--> n+(n-1)+(n-2)+...+1= n(n+1)/2 

n^2+n /2 elde ettik. n^2 yi alıyoruz.  
Sonuç--> O(n^2)


## Time Complexity

[2,6,16,18,22,27] 

Dizi sıralandıktan sonra 18 sayısı ortada olduğu için avarage case kapsamına girer.

