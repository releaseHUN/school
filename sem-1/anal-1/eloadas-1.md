kovetelmeny:
	1. zh: oct 28. 8:00-10:00
	1. pot: nov 15. 18:00-20:00
	2. zh: nov 22. 18:00-20:00
	2. pot: nov 29. 18:00-20:00
	min. 40%

jelolesek:
	termeszetes szamok: N
		{0, 1, 2...}
	egesz szamok: Z
		{0 +- 1 +- 2...}
	racionalis szamok: Q
		{p / q | ahol p egesz szam &&  q termeszetes szam}
	valos szamok: R
	komplex szamok: C

|     | +; x | -     | /     | lim   | sqrt  |
| --- | ---- | ----- | ----- | ----- | ----- |
| N   | true | false | false | false | false |
| Z   | true | true  | false | false | false |
| Q   | true | true  | true  | false | false |
| R   | true | true  | true  | true  | false | 
| C   | true | true  | true  | true  | true  |

sqrt(-1) ! R

i^2 = -1

az i az egy kitalalt egyseg
def:
	a komplex szamok halmaza az x + iy
	pl: 2 + 3i

permanencia elv:
	ugy terjesztjuk ki a muveleteket egy szukebb halmazrol egy bovebb halmazra hogy a legtobb muveleti szabaj ervenyben maradjon
	pl: sqrt(-2) = (sqrt(2) x i)^2 = sqrt(2)^2 x i^2 = -2

muveletek:
	algebrai alak:
		z = x + iy | x = valos, y = valos
		Re(Z) = x | C -> R
		Im(Z) = y | C -> R
		
		z hossza = abs(z) = sqrt(Re(z)^2 + Lm(z)^2)
		
		z szoge = tg() = y / x | ctg() = x / y

szorzas:
	tagonkent tortenik pl: Z x Z = (x + iy)(x + iy)

konyugalas:
	x tengelyen valo tukrozes
	C alapveto szimmetriaja

osszeadas, kivonas:
	lenyegeben vektorok osszeadasa
	z1 = x1 + iy1
	z2 = x2 = iy2
	z1 + z2 = (x1 + iy1) + (x2 + iy2) = (x1 + x2) + i(y1 = y2)

szorzas:
	pl: (2 + 3i)(5 - 7i) = 2 x 5 + 2(-7i) + (3i)5 + 3i(-7i) = 31 + i
	z1 x z2 = (x1 + iy1)(x2 + iy2) = (x1 x x2 - y1 x y2) + i(x1 x y2 + x2 x y1)

trigonometrikus alak:
	hosszal es argumentummal(szogevel) van megadva
	szorozni trigonometrikus alakban: hosszokat szorozzuk, argumentumokat ossze adjuk