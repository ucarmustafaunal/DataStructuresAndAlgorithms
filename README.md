# Proje 1: Sıralama Algoritmaları Analizi

## Insertion Sort İle Sıralama

Verilen dizi: [22, 27, 16, 2, 18, 6]

### Aşamalar

1. [**22**, 27, 16, 2, 18, 6]
2. [22, **27**, 16, 2, 18, 6]
3. [**16**, 22, 27, 2, 18, 6]
4. [2, **16**, 22, 27, 18, 6]
5. [2, 16, **18**, 22, 27, 6]
6. [2, 6, **16**, 18, 22, 27]

### Big-O Gösterimi

Insertion Sort algoritmasının ortalama ve en kötü durum karmaşıklığı O(n^2)'dir.

### Aranılan Sayının Durumu

Dizi sıralandıktan sonra 18 sayısı, "Average case" kapsamına girer.

- Average case: Aradığımız sayının ortada olması
- Worst case: Aradığımız sayının sonda olması
- Best case: Aradığımız sayının dizinin en başında olması

## Selection Sort İle İlk 4 Adım

Verilen dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

1. [**7**, 3, 5, 8, 2, 9, 4, 15, 6]
2. [**2**, 3, 5, 8, 7, 9, 4, 15, 6]
3. [2, **3**, 5, 8, 7, 9, 4, 15, 6]
4. [2, 3, **4**, 8, 7, 9, 5, 15, 6]

# Proje 2: Merge Sort Analizi

## Verilen Dizi ve Merge Sort Aşamaları

Verilen dizi: [16, 21, 11, 8, 12, 22]

1. **Divide**:
   - [16, 21, 11]
   - [8, 12, 22]

2. **Conquer**:
   - Sol yarı dizi: [11, 16, 21]
   - Sağ yarı dizi: [8, 12, 22]

3. **Merge**:
   - Birleştirilmiş dizi: [8, 11, 12, 16, 21, 22]

## Big-O Gösterimi

Merge Sort algoritmasının karmaşıklığı O(n log n)'dir.

# Proje 3: Binary Search Tree Aşamaları

## Verilen Dizi ve BST Aşamaları

Verilen dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

BST yapısına dönüştürme aşamaları:

1. Kök (root) 7 olarak atanır.
2. 5, 7'nin sol çocuğu olarak atanır.
3. 1, 5'in sol çocuğu olarak atanır.
4. 8, 7'nin sağ çocuğu olarak atanır.
5. 3, 5'in sağ çocuğu olarak atanır.
6. 6, 3'ün sağ çocuğu olarak atanır.
7. 0, 1'in sol çocuğu olarak atanır.
8. 9, 8'in sağ çocuğu olarak atanır.
9. 4, 3'ün sağ çocuğu olarak atanır.
10. 2, 1'in sağ çocuğu olarak atanır.