# Kodluyoruz-Veri-Yap-lar-ve-Algoritmalar

##İnsertion Sort Projesi
https://github.com/tahirpinarli

Proje 1
[22,27,16,2,18,6]  Insertion Sort
1.)	Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2.)	Big-O gösterimini yazınız
3.)	Time Complexity: Avarage case: Aradığımız sayının ortada olması,Worst case: aradığımız sayının sonda olması, Best case: aradığımız sayının dizinin en başında olması.
4.)	Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız 


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort’a göre ilk 4 adımını yazınız.

1.)
1.)	[22,27,16,2,18,6]  Önce ilk terime bakılır
2.)	[22,27,16,2,18,6]  Daha sonra ikinci terim ile ilk terim kıyaslanır.
3.)	[16,27,22,2,18,6]  Sonrasında üçüncü terime bakılır ve 3 terim birbirleri ile kıyaslanır.
4.)	[2,16,22,27,18,6]  Dördüncü terim seçilir ve diğer üç terim ile kıyaslanır.
5.)	[2,16,18,22,27,6]  Beşinci terim ve ilk dört terim kıyaslanır.
6.)	[2,6,16,22,27,18]  Altıncı terim ve diğer beş terim kıyaslanır ve sıralanır

Ve sonuç olarak 6 işlemde sıralama işlemi tamamlanır.

2.)
Big O Notion (n.(n+1))/2 sonucundan baskın eleman n^2 olduğu için O(n^2) olarak bulunur.

3.)
Worst case durumunda n elemanlı bir sistemi birden n ye kadar sıralamamız gerekir ve bu yüzden time complexity O(n^2)’dir.
Avarage case durumunda n elemanlı bir sistem için yine elemanları tek tek sıralamamız gerekeceği için time complexity O(n^2)’dir.

Best case durumunda elimizdeki veriler sıralı gelmiştir ve bu yüzden sadece n tane işlem yapmamız yeterlidir ve time complexity O(n)’dir.

4.)
Dizinin sıralanmış hali [2, 6, 16 , 18, 22, 27] şeklindedir. "18" sayısı ortalarda sayılabileceği için bu durum average case kapsamına girer.

[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız
0-) [7*, 3, 5, 8, 2, 9, 4, 15, 6]  İlk terim seçilir.
1-) [3, 7*, 5, 8, 2, 9, 4, 15, 6] İkinci terim seçilir, diğer terimle kıyaslanır ve terimler sıralanır. (3-7)
2-) [3, 5, 7*, 8, 2, 9, 4, 15, 6]  Üçüncü terim seçilir, diğer 2 terimle sırayla kıyaslanır ve terimler sıralanır. (3-5-7)
3-) [3, 5, 7, 8*, 2, 9, 4, 15, 6] Dördüncü terim seçilir, diğer 3 terimle sırayla kıyaslanır ve terimler sıralanır. "8" olması gereken indexte olduğu için sırası değiştirilmez. (3-5-7-8)
4-) [2, 3, 5, 7, 8*, 9, 4, 15, 6]  Beşinci terim seçilir, diğer 4 terimle sırayla kıyaslanır ve terimler sıralanır. (2-3-5-7-8)
İlk 4 adımın sonunda elde edeceğimiz veri seti şu şekilde olur: [2, 3, 5, 7, 8*, 9, 4, 15, 6].
