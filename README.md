Task #1: Programuotojams

Sukurti klausimyno puslapį.

Laravel framework, MySQL duomenų bazė, frontend technologija nesvarbi. Bent minimalistinis dizainas (bootstrap/foundation etc.). Vartotojas gali pasirinkti vieną iš dviejų ar daugiau testų. Testas turi susidaryti iš bent 10 klausimų susijusių su programavimu:

klausimai rodomi atsitiktine tvarka, bet nesikartoja
kiekvienas klausimas turi tam tikrą taškų skaičių
taškai sumuojasi
rodoma tik po 1 klausimą vienu metu, atsakius, rodomas kitas klausimas
atnaujinus (refresh/navigation) langą ar gryžus į tinklapį turi prisiminti paskutini sprendžiamą klausimą, taškų sumą, etc..
galimybė pradėti testą iš naujo
baigus testą leidžia išsaugoti rezultatą, įvesti vardą
baigus testą gaunama nuoroda per kurią galima peržiūrėti atsakytus klausimus
Rezultatų lentelė. Nėra vartotojo paskyros, viskas "anonimiška". Administravimas nebūtinas



#running the app first time:
1. apt update
2. docker-compose up

#building the app:
1. ./vendor/bin/sail build
2. docker-compose up

#running the app
1. docker-compose up

#stopping the app
1. CTRL + C