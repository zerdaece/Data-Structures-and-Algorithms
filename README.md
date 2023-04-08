# Data-Structures-and-Algorithms
Assigment1_patika.dev

Selection Sort

-- Insertion Sort -> [22,27,16,2,18,6]

n [22,27,16,2,18,6]
n-1 [2,27,16,22,18,6]
n-2 [2,6,16,22,18,27]
n-3 [2,6,16,22,18,27]
n-4 [2,6,16,18,22,27]
n-5 [2,6,16,18,22,27]
Her seferinde sağdan sola verileri dolaştı ve küçükle büyüğün yerini değiştirerek en sonunda bir sıralama oluşturdu.

^^^ Big-O gösterimi O(n^2) dir.
^^^ TimeComplexity Average case 'e giriyor . 18 verisi neredeyse ortada bulunuyor.

-- Selection Sort (ilk 4 adım) -> [7,3,5,8,2,9,4,15,6]

Adım 1 * [2,3,5,8,7,9,4,15,6]
Adım 2 * [2,3,5,8,7,9,4,15,6]
Adım 3 * [2,3,4,8,7,9,5,15,6]
Adım 4 * [2,3,4,5,7,9,8,15,6]
