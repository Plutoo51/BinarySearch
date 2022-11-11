# BinarySearch
BinarySearch 
[Patika.dev](https://www.patika.dev/tr)

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

İlk olarak 7 den başlayalım. 5 eklendiğinde daha küçük olduğu için 7nin soluna eklenir

5-7

1 eklendiğinde daha küçük oludğu için 5 ve 7 nin soluna eklenir

1-5-7

8 eklendiğinde 7 den büyük olduğu için 7 nin sağına eklenir

1-5-7-8

3 eklendiğinde 5 ve 7 den küçük 1 den büyük olduğu için 1 in sağına eklenir

1-3-5-7-8

6 eklendiğinde 7 den küçük ve 5 ten büyük olduğu için 5 in sağına eklenir

1-3-5-6-7-8

0 eklendiğinde 7,5,6,1 den küçük olduğu için 1 in soluna eklenir

0-1-3-5-6-7-8

9 eklendiğinde 8 den büyük olduğu için sağa eklenir

0-1-3-5-6-7-8-9

4 eklendiğinde 3 ten büyük 5 ten küçük olduğu için 3 ün sağına eklenir

0-1-3-4-5-6-7-8-9

2 eklendiğinde 0 ve 1 den büyük 3,4,5,6,7 den küçük olduğu için 1 in sağına eklenir

0-1-2-3-4-5-6-7-8-9
