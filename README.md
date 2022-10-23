# patika_dev_insertion_sort_Project_1

bu [Patika.dev](https://www.patika.dev/tr) proje 1 insertion sort projesidir.

[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

-Insertion sortta ilk en sol eleman ile başlıyor bu eleman 22 ve sağdaki elemanlar inceleniyor.

-22'den küçük ve sağdaki tüm elemanların en küçüğü 2 olduğu için 2 ile 22 yer değiştiriyor.

-daha sonra bir sonraki yere geçiliyor 27 sayısından ve diğer sayılardan daha küçük olan 6 ile yer değiştiriyor.

-daha sonra 16 sayısına geçiliyor lakin ondan daha küçük elemman olmadığı için sabit kalıyor diğer sayıya 22'ye geçiliyor.

-22'den daha küçük 18 olduğu için 18 ve 22 yer değiştiriyor.

-bu değişimden sonra 22 rakamının sağındaki rakam inceleniyor ve ondan küçük olmadığı için program tamamlanmış oluyor.


2-Big-O gösterimini yazınız.

Big-O gösterimi O(n^2).


3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

18 sayısı en sonda olmadığı(worst case) veya olması gereken yerde olmadığı (best case) için average case'dir.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6] 2 ile 7 yer değiştirdi.

[2,3,5,8,7,9,4,15,6] 3'den daha küçük eleman yok sabit kaldı.

[2,3,4,8,7,9,5,15,6] 4 ile 5 yer değiştirdi.

[2,3,4,5,7,9,8,15,6] 5 ile 8 yer değiştirdi.
