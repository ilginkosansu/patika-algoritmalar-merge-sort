# Merge Sort 
Elimizdeki dizin --> [16, 21, 11, 8, 12, 22] --> devamlı ikiye bölerek elimizde kalan elemanları sıralarız

1. adım -> [16, 21,11, 8, 12, 22]
2. adım -> [16, 21, 11] ve [8, 12, 22]
3. adım ->[16, 21] , [11 ] ve [8, 12] , [22 ]
4. adım -> [11, 16, 21] ve [8, 12 ,22 ]
5. adım -> [8 , 11, 12,  16, 21, 22]

-------------
## Big-O Notation
Big-O = O(logn)  --> elimizdeki elemanları sürekli ikiye bölüm o şekilde karşılaştırma yaptığımız için performans açısından daha verimlidir, sıralama için harcanılan vakit neredeyse yarısı kadardır.