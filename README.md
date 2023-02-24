
# Merge Sort

## [16, 21, 11, 8, 12, 22] dizisini Merge sort algoritmasına göre sıralayınız:
- Diziyi ortadan ikiye böl: [16, 21, 11] - [8, 12, 22]
- Dizileri ortadan ikiye böl: [16, 21] - [11] - [8, 12] - [22]
- Dizileri ortadan ikiye böl: [16] - [21] - [11] - [8] - [12] - [22]
- Dizileri birleştir: [16, 21] - [11] - [8, 12] - [22]
- Dizileri birleştir: [11, 16, 21] - [8, 12, 22]
- Dizileri birleştir: [8, 11, 12, 16, 21, 22]

## Merge sort algoritmasının Big-O gösterimini yazınız:
- O(n*logn)
