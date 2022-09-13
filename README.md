# Lern-Bericht
Luca J.W

## Einleitung

Ich musste ein Random Number Generator Programmieren (RNG) in C#.

## Was habe ich gelernt?
Ich habe gelernt wie man in eine Gewünschte Zahl höher oder kleiner als die Nummer vom RNG.

## Beschreibung
**Textliche Beschreibung**

Ich habe zuerst mit der Definitionen der Zwei Zahlen die man für dieser code braucht. Die erste Zahl muss als RNG definiert werden und danch den Bereich von 1 bis 100 definieren. Die zweite Zahl die Gewünschte Zahl wird als "int" 0 definiert weil sie später verändert wird. Aber bevor ich das grösser/kleiner schreibe musste ich ein "While" schreiben, weil es sind ja zwei möglichkeiten grösser oder kleiner. Danach schrieb ich den Satz "Geben Sie Bitte Ihre gewünschte Zahl ein". Dort habe ich die Gewünschte Zahl zu einen "Convert.ToInt32(Console.ReadLine());" gemacht. Weil man seine eigene Zahl eingeben will. Am Ende schrieb ich "If" für kleiner und "If else" für grösser. Bei kleiner stand (GewünschteZahl < rand_num) und Console.WriteLine(" Zahl zu klein");. Bei grösser ist es einfach das umgekehrte.

![Kleiner oder Grösser](https://user-images.githubusercontent.com/110892742/189851979-d67711f3-9b72-4a07-94b3-0233e18bca2b.png)

**Code**
```C#
Console.Write("Geben Sie Bitte Ihre gewünschte Zahl ein");
                    GewünschteZahl = Convert.ToInt32(Console.ReadLine());

                    if (GewünschteZahl < rand_num)
                    {
                        Console.WriteLine(" Zahl zu klein");

                    }
                    else if (GewünschteZahl > rand_num)
                    {
                        Console.WriteLine("Zahl zu gross");
                    }
                    else if (GewünschteZahl == rand_num)
                    {
                        Console.WriteLine("Sie haben gewonnen");
                    }
   ```   

## Verifikation

Der Text zeigt mir wie ich strukturiert programmiert habe, das Bild zeigt mir ob meine Arbeit die ich geleiste habe Funktioniert und der Code zeigt mir genau was ich progammiert habe.
# Reflektion zum Arbeitsprozess

Ich arbeitete besser in der Lektion in den wir Zuhause waren, weil ich nicht von meinen Kollegen abgelenkt oder abgelenkt habe.

Ich habe zu oft mit meinem Kollegen unterhalten, dies führte das ich nicht so schnell und gut gearbeitet habe.

**VBV**: Ich sollte weniger mit meinen Kollegen unterhalten, damit ich schneller und besser arbeite.
