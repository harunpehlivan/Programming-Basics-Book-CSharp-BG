#### Проверяване за 0

Нека си създадем и инициализираме нужните за логиката и изчисленията променливи. В едната ще пазим **резултата от изчисленията**, а другата ще използваме за **крайния изход** на програмата.

![](/assets/chapter-4-2-images/03.Operations-02.jpg)

Прочитайки внимателно условието разбираме, че има случаи, в които не трябва да правим **никакви** изчисления, а просто да изведем резултат.

Следователно първо може да проверим дали второто число е **`0`** (нула), както и дали операцията е **деление** или **модулно деление**, след което да инициализираме резултата.

![](/assets/chapter-4-2-images/03.Operations-03.jpg)

Нека сложим резултата като стойност при инициализацията на **`output`** параметъра. По този начин може да направим само **една проверка** - дали е необходимо да **преизчислим** и **заменим** този резултат. 

Спрямо това кой подход изберем, следващата ни проверка ще бъде или обикновен **`else`** или единичен **`if`**. В тялото на тази проверка, с допълнителни проверки за начина на изчисление на резултата спрямо подадения оператор, можем да разделим логиката спрямо **структурата** на очаквания **резултат**. 