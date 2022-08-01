# Merge-Sort-Projesi
Merge Sort Projesi- Aysun Akbal

www.patika.dev

Proje 2

[16,21,11,8,12,22] -> Merge Sort

s1: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

c1: Merge Sort'ta diziyi bir anda sıralamak yerine parçalara ayırıyoruz. Önce diziyi ikiye bölelim:

2) [16,21,11] ve [8,12,22] olmak üzere iki dizi elde ediyoruz. Bu dizileri ikiye bölelim

3) [16,21] - [11] ve [8,12] - [22] dizilerini elde ettik..

4) Tek parça kalana kadar bölmeye devam ediyoruz: [16]-[21]-[11]-[8]-[12]-[22]

5) Birer parça halindeki verileri küçükten büyüğe doğru gruplayalım.

[16,21]-[11]-[8,12]-[22] => [11,16,21] - [8,12,22]

6) Son olarak,iki grubu da birleştirelim. [8,11,12,16,21,22]


s2: Big-O gösterimini yazınız.

C2: O(nLogn) 'dir.


www.patika.dev
