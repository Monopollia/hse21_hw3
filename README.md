# hse21_hw3

*Ссылка на GoogleColab:* https://colab.research.google.com/drive/1IUWG0rQL1z1a5yw0DftU-BkoL5JiDZZJ#scrollTo=qMpPGqa8Shzv

## 1
### Общая табличка
ID | тип |	количество ридов |	Aligned reads (%) |	Aligned 1 time (%) |	Reads on genes (%)
-|-|-|-|-|-
SRR3414629 |	перепрогр |	21 106 089 |	20 510 113 (97.18 %) |	18 375 888 (87.06 %) |	16 049 609 (76.04 %)
SRR3414630 |	перепрогр |	15 244 711 |	14 832 680 (97.30 %) |	13 186 139 (86.50 %) |	11 465 324 (75.21 %)
SRR3414631 |	перепрогр |	24 244 069 |	23 547 686 (97.13 %) |	20 928 945 (86.33 %) | 18 408 851 (75.93 %)
SRR3414635 | контроль	| 20 956 475	| 20 395 865 (97.32 %) |	18 428 317 (87.94 %) |	16 275 997 (77.67 %)
SRR3414636 | контроль |	20 307 147 |	19 757 059 (97.29 %) |	17 825 380 (87.78 %) |	15 757 580 (77.60 %)
SRR3414637 | контроль	| 20 385 570	| 19 847 291 (97.36 %) |	17 844 858 (87.54 %) |	15 736 978 (77.20 %)

### Статистика из MultiQC (файлы в папке 'graphics')
![image](https://user-images.githubusercontent.com/61352475/144046743-55676671-81f8-4fcd-aa83-42916f8749bf.png)
![image](https://user-images.githubusercontent.com/61352475/144046813-7077ce7a-c9c0-412b-8621-b85c2f7720f7.png)
![image](https://user-images.githubusercontent.com/61352475/144046851-129a4840-2088-4efd-ac7c-64c66f28a72d.png)
![image](https://user-images.githubusercontent.com/61352475/144046899-dec51594-7330-44a9-ab18-99820312d853.png)
![image](https://user-images.githubusercontent.com/61352475/144046926-e12bdfa3-40d6-4ffb-84d7-ee98ff7365cd.png)
![image](https://user-images.githubusercontent.com/61352475/144046970-23f8ca4b-a752-469b-8274-77add5143f7f.png)
![image](https://user-images.githubusercontent.com/61352475/144046998-bae3a956-1086-4ce4-8671-4686cd914a54.png)
![image](https://user-images.githubusercontent.com/61352475/144047040-7fd337af-eab4-41c8-b578-313ecd8d759e.png)

### Далее делаем Hisat(см. соответствующую папку)

### Считаем кол-во уникально-картированных чтений
![image](https://user-images.githubusercontent.com/61352475/144047115-d2143cc2-4cf2-4a74-81c3-83367584dea7.png)

### Делаем htseq и смотрим на статистику
![image](https://user-images.githubusercontent.com/61352475/144047355-8f241337-a02d-457d-8b70-ffb1ec113117.png)
![image](https://user-images.githubusercontent.com/61352475/144047454-f962e751-d0a6-4138-af31-cd30254c27c2.png)

### И считаем общее кол-во чтений, которые попали на гены
![image](https://user-images.githubusercontent.com/61352475/144047612-8e344206-a824-4c81-a4cc-2c410d2621a5.png)
### ALL.COUNTS
![image](https://user-images.githubusercontent.com/61352475/144048497-e498a51b-b21d-478e-b1a0-f149cdaceb60.png)

## 2
*Ссылка на GoogleColab (R-пакет):* https://colab.research.google.com/drive/1Qj-DNyRTP_jfIe61D9ILNScZb0D2iZQk#scrollTo=hRIInUCNch3G

### HeatMap
![image](https://user-images.githubusercontent.com/61352475/144047698-41e32d78-e9a4-4a75-ada0-f45f4649d707.png)
### plotMA
![image](https://user-images.githubusercontent.com/61352475/144047761-6adda614-0733-4f64-83d7-d790fbec0700.png)
### HeatMap2
![image](https://user-images.githubusercontent.com/61352475/144048015-06eb1f0c-b699-4d4f-aa97-e494636684b5.png)

###  "Normalized counts" для 3х образцов
![image](https://user-images.githubusercontent.com/61352475/144048066-82a432ec-1ee0-4c24-a1c9-fb00319906fd.png)
![image](https://user-images.githubusercontent.com/61352475/144048104-42256778-b491-4c74-a0f6-90bd2a3b38d6.png)
![image](https://user-images.githubusercontent.com/61352475/144048143-d6cb6d5c-b9ac-49ac-8171-565942df0a78.png)
