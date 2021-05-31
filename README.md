# SI_Lab2_193210
Втора лабараториска вежба по 
Софтверско инженерство

Ивана Талеска, 193210

Control Flow Graph
![si_lab2](https://user-images.githubusercontent.com/80771458/120222222-e5427c80-c23f-11eb-9b2b-4967d65656a8.png)

Цикломатска комплексност
Цикломатската комплексност на графот е 8. Тоа се забележува на три начини:
1.	Според бројот на региони, кој е еднаков на 8
2.	Според формулата: V(G) = E – N + 2 V(G) = 26 – 20 + 2 = 8 -Каде што Е е бројот на врски, а N е бројот на јазли во графот
3.	Според друга формула: V(G) = P + 1 V(G) = 7 + 1 = 8 -Каде што P е бројот на предикатни јазли, кои во CFG се b2, c, d, g, h, j, m.

Multiple Condition

If(hr<0 || hr>24)

![s1](https://user-images.githubusercontent.com/80771458/120225248-2db06900-c245-11eb-9b78-d446faa928b5.png)

If(min<0 || min>59)

![s2](https://user-images.githubusercontent.com/80771458/120225251-2e48ff80-c245-11eb-96d0-9ef2fe80709c.png)


If(sec>=0 && sec<=59)

![s3](https://user-images.githubusercontent.com/80771458/120225252-2ee19600-c245-11eb-925d-767ce7c3bca1.png)


If(hr==24 && min==0 &&sec==0)

![s4](https://user-images.githubusercontent.com/80771458/120225253-2ee19600-c245-11eb-9829-0eb491bc71fc.png)









