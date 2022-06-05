# [Patika.dev](https://app.patika.dev/) Veri Yapıları ve Algoritmalar Eğitimi

## Merge Sort Projesi

### [16,21,11,8,12,22] -> Merge Sort
1-) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

- Önce dizinimizi, tek elemanlı diziler elde edinceye kadar ikiye bölüyoruz.
 |- |- |- |- |- |- |- |- |- |- |- |- |
 |  |  |  |16|21|11|8 |12|22|  |  |  |
 |  |  |  |  |  |  |  |  |  |  |  |  |
 |  |  |16|21|11|  |  |8 |12|22|  |  |
 |  |  |  |  |  |  |  |  |  |  |  |  |
 |  |16|21|  |11|  |  |8 |  |12|22|  |
 |  |  |  |  |  |  |  |  |  |  |  |  |
 |16|  |21|  |11|  |  |8 |  |12|  |22|

- Sonra sıralı bir dizi elde edinceye kadar tek elemanlı dizilerimizi ikili şekilde birleştiriyoruz
 |- |- |- |- |- |- |- |- |- |- |- |- |
 |16|  |21|  |11|  |  |8 |  |12|  |22|
 |  |  |  |  |  |  |  |  |  |  |  |  |
 |  |16|21|  |11|  |  |8 |  |12|22|  |
 |  |  |  |  |  |  |  |  |  |  |  |  |
 |  |  |11|16|21|  |  |8 |12|22|  |  |
 |  |  |  |  |  |  |  |  |  |  |  |  |
 |  |  |  |8 |11|12|16|21|22|  |  |  |

 2-) Big-O Gösterimini Yazınız
 - O(n^2)

---

_Patika.dev profilim:_ [https://app.patika.dev/uygardgn](https://app.patika.dev/uygardgn)