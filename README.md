# Veri Yapıları ve Algoritmalar
## Selection Sort Projesi-1

[22,27,16,2,18,6] -> Insertion Sort 

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

### Detaylı Açıklama
- ilk aşamada  ilk sayıdan başladık  ve sırayla ikili gruplar halinde sayılarımızı karşılaştırıyoruz, 22 ve 27 sayılarının sıralaması doğru daha sonra 27 ile 16 sayısını karşılaştırdık ve 16 27'den daha küçük bu yüzden sola geçti ama bitmedi 16 22'den de küçük tekrar sola geçti ve bu konumdaki halini aldık şuan 27'e kadar olan kısmı sıraladık [16,22,27,2,18,6].
- [16,22,27,2,18,6] bu sıralamadan devam ediyoruz, 27 sayısına kadar sıralamıştık bu yüzden 27 ve bir sonraki sayı olan 2'yi karşılaştırıyoruz. 2 sayısı karşılaştırılarak sırayla en başa geliyo çünkü karşılaştırıldığı diğer sayıların hepsinden küçük.
- [2,16,22,27,18,6] sıralama bu şekilde devam ediyoruz, bu sefer 27 ile bir sonraki sayı olan 18'i karşılaştırıyoruz. 18 27'den küçük olduğu için bir sola geçiyor,sonra tekrar karşılaştırdık 18 22'den de küçük tekrar sola geçiyor.
- [2,16,18,22,27,6] sıralamamız bu şekilde sonra rakamımız 6 ile 27'i karşılaştırıyoruz, 6 sayısı 27'den daha küçük bu yüzden sola geçiyor, 6 sayısı 22'den de daha küçük tekrar sola geçti, 6 sayısını 18 ve 16 ilede karşılaştırdık bu sayılardanda küçük olduğun için tekrar sola geçiyor ve sıralamayı bu şekilde tamamlamış oluyoruz.[2,6,16,18,22,27]
-------

## Big-O gösterimini yazınız.
Big O:O(n^2)

---
## Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

- Average case: Aradığımız sayının ortada olması
- Worst case: Aradığımız sayının sonda olması
- Best case: Aradığımız sayının dizinin en başında olması.

Cevap: [2,6,16,18,22,27]  Dizisi sıralandığında 18 sayısı ortada bulunduğu için beklenen durum oluyor bu da Average Case'e girer.

---
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Mantığı dizideki en küçük elemanı bulup en başa atar, diğer baştaki elemanıda en küçük elemanın yerine yazar, daha sonra tekrar ikinci en küçüğü bulup 2.sıraya atar 1'e bakmaz çünkü en küçüğü bir önceki adımda bulmuştu.Buna göre ilk dört adımı yazalım.

- [2,3,5,8,7,9,4,15,6]
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6]
- [2,3,4,5,6,9,8,15,7]

[www.patika.dev](https://www.patika.dev/tr)