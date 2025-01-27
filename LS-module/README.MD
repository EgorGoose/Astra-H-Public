#### О модуле   
- Ммодуль подключен только в LS шину.  
- Имеет несколько постоянных режимов, переключаемых вручную, и несколько автоматических функций.  
- Полезная информация выводится в основном на одометр в режиме ECN.
- Питание от засыпающей шины - для экономии энергии и обеспечения функции открывания стекол после открытия с брелка. 

#### Ручные режимы   
переключаются левой бобышкой вниз, отключение бобышкой вверх.
При переключении раздается звуковой сигнал в количестве, равном номеру режима. После последнего режима возврат в ноль.

##### Ручные режимы сейчас следующие:  

1. **Температура ОЖ + напряжение АБ**  
Режим включается по умолчанию в положении *IGN ON*.  
Выводится одновременно в виде *ХХХУУУ*, где  
*ХХХ* — температура,  
*УУУ* — напряжение*10  
при поднятом ручнике показания также выводятся на стрелки:  
Температура на спидометр (отрицательные значения преобразются в больше двухсот, типа -10 == 210 км/ч);  
напряжение — на обороты двигателя (12 вольт == 2000 об/мин, 14,4 == 4400 и т.д.)  

2. **Скорость + ассистент**  
Вывод формата *АХУЙЙЙ*, где  
*А* — отображение режима:  
  *0 — обычный,  
   1 — автостоп  
   2 — экстренное замедление,  
   3 — и то и другое*
*Х* — рекомендованная передача (может отличаться от текущей на +/-1).  
*У* — текущая передача,  
*ЙЙЙ* — скорость,  

3. **Скорость + ассистент + Спорт**    
***Активация штатного спортивного режима (<u>не требует кнопки спорт и приборной панели!</u>)***  
остальное см. Выше (Скорость + ассистент).

4. **Скорость + ассистент + Спорт + отключение ESP**    
***Отключение системы стабилизации ESP (<u>не требует кнопки спорт и приборной панели!</u>)***  
остальное см. Выше (Скорость + ассистент + Спорт).

5. **Открытые двери**  
Вывод формата *1QWERT*, Где  
*Q* — передняя левая дверь, значения 0 или F,  
*W* — задняя левая дверь, значения 0 или b,  
*E* — задняя дверь (багажник), значения 0 или A,  
*R* — задняя правая дверь, значения 0 или b,  
*T* — передняя правая дверь, значения 0 или F,  
*Например, 1Fb000 — открыты обе левые,  
100A00 — багажник, мать его!  
10000F — "Дорогая, хлопни дверью"*  

#### Постоянные режимы:  
1. **Задний ход.** При движении задним ходом верхний стоп подмигивает для лучшего обращения внимания пешеходов.  
2. **Автостоп** (горит третий стоп):  
   — при скорости менее 7 км/ч,  
   — при замедлении на холостых оборотах. Хотел сделать на замедление при ненажатой педали газа, но вышло так.  
   Гаснет при ускорении.  
   Из практики получается, что в 99% эта опция работает при замедлении в пробках/ на светофорах, как только выжал сцепление, и стоп загорается до касания тормоза. Еще 1% — это тошнение на 1-2 передачах, когда обороты падают ниже 1000.*  
3. **Экстренное замедление.** Обнаружено резкое замедление (0,64 g (9 км/ч за 0,4 с) и сильнее), включение задних поворотников на одну секунду.
#### Прочие режимы:    
1. **Пальцы вверх!** — при нажатии обеих бобышек вверх — **"спасибо"** путём моргания задними поворотниками 2 раза.  
2. При левой бобышке вверх+дальний свет на себя включаем **стробы** и хулиганим (два раза левым дальним, два раза правым…). Выход бобышкой вниз или вверх (подержать для надежности)  
3. **Открытые двери** — авто. Автоматическая индикация открытых дверей при, собственно, открытых дверях. Можно квитировать с выходом в предыдущий режим путем нажатия левой бобышки вниз. Квитирование стирается при закрытии всех дверей.
4. **Открытие окон** наполовину при повторном нажатии открывания на брелке. На последующее, соответственно, дооткроет полностью.
5. **Закрытие стекол** при постановке на охрану (включается верхний стоп).

#### Планируемые:   

1. **Анти-Жопа** — при нажатии обеих бобышек вниз  
 — замысловатое моргание всеми возможными огнями сзади, со стробом верхним тормозом.
 
#### Видео: 
1.  https://youtu.be/2XbBU5F6U5I  
2.  https://youtu.be/qPtYszo1Msc
