# Kodluyoruz İlk Repo
Bu repo [Kodluyoruz](https://www.kodluyoruz.org/) Front-End Eğitiminde oluşturduğumuz ilk repo. İçerisinde bir adet README dosyası, bir adet de index.html barındırıyor.

![](https://github.com/SerpilTY/kodluyoruzilkrepo/blob/main/odluyoruz.jpg)

# Installation

Öncelikle projeyi clonelayın.

```
git clone https://github.com/SerpilTY/kodluyoruzilkrepo
```

# Usage

Projeyi cloneladıktan sonra Visual Studio Code programında açınız.

Linux için:

```
cd kodluyoruzilkrepo
code . 

```


# Contributing

Pull requestler kabul edilir. Büyük değişiklikler için, lütfen önce neyi değiştirmek istediğinizi tartışmak için bir konu açınız.

# License

[MIT](www.mit.edu)

<hr>

# Proje 1
# Inserion Sort

## 1.[22,27,16,2,18,6] dizisini insertion sorta göre aşamalarını yazınız.
1. [2|,27,16,22,18,6]
2. [2,6|,16,22,18,27]
3. [2,6,16|,22,18,27]
4. [2,6,16,18|,22,27]
5. [2,6,16,18,22,27]

## 2.Big-O gösterimi O(n^2)

## 3.Time Complexity:

Avarage Case:Aradığımız sayının dizinin ortasında veya ortalarında olması.
Worst Case:Aradığımız sayının sonda olması veya büyükten küçüğe sıralanmış olması.
                [27,22,18,16,6,2]
Best Case:Aradığımız sayının dizinin en başında olması.
                [2,6,16,18,22,27]

Dizi Sıralandıktan sonra avarage case sınıfına girer çünkü 18 sayısı ortalardadır.
                [2,6,16,|18|,22,27]             
                                     
## 4. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. [2|,3,5,8,7,9,4,15,6]
2. [2,3|,5,8,7,9,4,15,6]
3. [2,3,4|,8,7,9,5,15,6]
4. [2,3,4,5|,7,9,8,15,6]

[Patika.dev](https://www.patika.dev/tr)

<hr>
# Proje 2
# Merge Sort
[16,21,11,8,12,22] 
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

## 1. Aşamalar: 

	    [16,21,11,8,12,22]
      [16,21,11]	   [8,12,22]	     
  [16,21]    [11]       [8,12]    [22]
  [11,16,21]         [8,12,22]	       
      [8,11,12,16,21,22]
		

## 2. Big O Gösterimi: 
O(nlogn)
