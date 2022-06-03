Ирина Јовановска
183099
Софтверско инженерство
Лабораториска 2

![Граф](https://user-images.githubusercontent.com/102820280/171958368-23886879-ffb6-4d70-8db1-049cf8a76b87.png)
![Код](https://user-images.githubusercontent.com/102820280/171958381-5034637c-7bee-4e36-affe-5ed5df4d15dd.png)


- Почнуваме од иницијалниот јазол A кој може да продолжи во B или C D E 
(трите се запишани во едно бидејќи ако се изврши C тогаш секако ќе се извршат и D и Е ) 
- Доколку А отиде во B, се поврзува со крајниот јазол бидејќи фрла exception. 
- Потоа од CDE може да отиде во G или во F
- Ако отиде во F тогаш F оди во крајниот јазол(исто се фрла exception и се завшрува задачата)
- Доколку оди во G се креира листата, па продолжува во H1.
- H ни е for ciklus затоа го делиме на 3 дела. Првиот дел за иницијализација int i=0
- H1 е условот i < n
- H2 ќе биде за i++
- H1 продолжува во H2 по што се извршува I и тука имаме услов. Ако не е исполнет оди директно во T и се враќа во for-от со што се зголемува i за 1.
- Од H3 пак се враќа во H2 и се проверува условот. Ако е исполнет пак оди во I, ако не е оди директно во U. (Циклусот се извршува се додека H2 не стане False и не отиде во јазолот U.
- После I се извршуваат Ј и К. Па се прави одлука, ако е точен условот се извршува L, а ако не се оди во O па во Q.
- И кај L имаме услов, ако е исполнет oди во М а ако не тогаш се извршува N.
- Ako O e True oди во P, во спротивно во Q. Ako Q е точно оди во R, а во спротивно во S. И од тука се враќа во H3, го проверува условот т.е се извршува иницијализацијата па се проверува H2.
- Кога ќе заврши циклусот и H3 oди во U.

Цикломатска комплексност

Цикломатската комплексност на овој код е 9, истата ја добив преку формулата P+1, каде што P е бројот на предикатни јазли. Во случајoв P=8, па цикломатската комплексност изнесува 9
