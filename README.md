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
3.	Според друга формула: V(G) = P + 1 V(G) = 7 + 1 = 8 -Каде што P е бројот на предикатни јазли, кои во CFG се B2, C, D, G, H, J, M.
Multiple Condition
If(hr<0 || hr>24)
![s11](https://user-images.githubusercontent.com/80771458/120223225-90076a80-c241-11eb-977c-d638622a366a.png)

If(min<0 || min>59)
![s22](https://user-images.githubusercontent.com/80771458/120223305-b200ed00-c241-11eb-8eb1-1ee4ddf874c9.png)

If(sec>=0 && sec<=59)
![ss3](https://user-images.githubusercontent.com/80771458/120223403-d52b9c80-c241-11eb-8078-e0dfcc221a62.png)

If(hr==24 && min==0 &&sec==0)
![ss4](https://user-images.githubusercontent.com/80771458/120223563-0c9a4900-c242-11eb-86af-bef1c2476be7.png)


