
# Technical Design Document

Gra zwana będzie Further Away The Edge !!!
Gra: zręcznościowa 
Tematyka: Fantastical Parkour
Glówne założenia Gry: 
- Przejście 1 pokazowego levela parkoura
- Możliwość przejścia gry w łatwy sposób lub w trudny lepiej oceniany sposób poprzez zebranie "monet czy czegoś"

Występowanie Mechanik jak:
- ruchome platformy
- znikające podłoga
- występowanie power upa w postaci wysokiego jumpa
- występowanie obrotowych przeszkód
- występowanie monety do zebrania


# WYKONANIE

Na początku ułożyłem level design w sposób taki, żeby był challenging. Gdy juz rozmieściłem wszystkie figury, to następnie zaczołem w blue printach nadać ruszające sie platformy, poprzez nadanie im roznych lokacji oraz duration, czyli jak szybo się będa przemieszczać, 
Następnie dodałem monetę, która w blueprinie zostaje zniszczona kiedy gracz dotknie jej box collision.
W podobny sposób dodałęm znikającą podłogę, ktora znika po funkcji delay, zeby gracz miał czas na wyskoczenie.
Następnie dodałem power upa w postaci, super jumpa. Kiedy gracz zetknie się z colisią power upa, to dostaje ulepszony skok, aby przejść poziom na określony czas.
Ostatecznie dodałem obrotowe sfery, na samym końcu nadając im ruch obrotowy Z velocity.
