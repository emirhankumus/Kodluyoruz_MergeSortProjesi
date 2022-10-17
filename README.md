## Kodluyoruz Merge Sort Projesi

Proje 2
[16,21,11,8,12,22] -> Merge Sort

1-) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

a-) [16,21,11] ve [8,12,22] olarak ikiye ayırırdık ve üçlü iki grubumuz oluştu.

b-) [16]   [21,11] ve [8]   [12,22] tekrardan ikiye böldük ve 4 grubumuz oluştu.

c-) [16]   [21]   [11] ve [8]   [12]   [22] tek hale gelecek şekilde 6 farklı grup oluştu.

d-) [16]   [11,21] ve [8]  [12,22]  olacak şekilde tekrar sıralama yaparak ikili gruplar haline getirilir.

e-) [11,16,21] ve [8,12,22] olacak şekilde tekrar sıralama yaparak üçlü gruplar haline getirilir.

f-) [8,11,12,16,21,22] olacak şekilde tekrar sıralama yapılır ve tüm gruplar birleştirilir.Son halini aldı.

2-)Big-O gösterimini yazınız.

Big-O(n*(logn)) = Big-O(6*(log6))