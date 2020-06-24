# Umut Tepe Algoritma Soruları
> **Soru** 1: Klavyeden rastgelen girilen 2 tane sayının karelerinin toplamını ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. SAYI OKU
- A2. SAYI2 OKU
- A3. TOPLAM = pow(SAYI,2) + pow(SAYI2,2)
- A4. TOPLAM YAZ
- A5. DUR

# 
> **Soru** 2: Klavyeden girilen 6 tane sayının toplamını ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. TOPLAM=0, I=0
- A2. SAYI OKU
- A3. TOPLAM += SAYI
- A4. I++
- A4. EGER(I < 6) MI? (E) A2. GIT
- A5. TOPLAM YAZ
- A6. DUR
 
# 
> **Soru** 3: 1 ile 100 arasındaki sayıları toplayan algoritmayı yapınız.
- A0. BASLA
- A1. I=1, TOPLAM =0
- A2. TOPLAM += I
- A3. I++
- A4. EGER(I <= 100) MI? (E) A2. GIT
- A5. TOPLAM YAZ
- A6. DUR
 
# 
> **Soru** 4: 1 ile 100 arasındaki 3 ve 5 ‘in katlarını ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. I=1
- A2. EGER(I%3 == 0 && I%5== 0) MI? (H) A5.GIT
- A4. I YAZ
- A5. I++
- A6. EGER(I< 100) MI? (E) A2. GIT
- A7. DUR
 
# 
> **Soru** 5: Klavyeden girilen bir sayının asal sayı olup olmadığını ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. I=2
- A2. SAYI OKU
- A3. EGER(I < SAYI) MI? (H) A7. GIT
- A4. EGER(SAYI%I == 0) MI? (E) A9. GIT
- A5. I++
- A6. A3. GIT
- A7. “Asal sayidir” YAZ
- A8.A11. GIT
- A9. “Asal sayi degildir” YAZ
- A10. DUR
 
# 
> **Soru** 6: Klavyeden girilen bir sayının tek mi çift mi olduğunu ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. SAYI OKU
- A2. EGER(SAYI%2 == 0) MI? (H) A5. GIT
- A3. “Cift sayidir” YAZ
- A4. A6. GIT
- A5. “Tek sayidir” YAZ
- A6. DUR

# 
> **Soru** 7: Girilen n tane sayının ortalamasını ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. I=0, TOPLAM=0
- A2. N OKU
- A3. SAYI OKU
- A4. TOPLAM += SAYI
- A5. I++
- A6. EGER(I < N) MI? (H) A3. GIT
- A7. ORT = TOPLAM/N
- A8. ORT YAZ
- A9. DUR

# 
> **Soru** 8: 1’den 1000’e kadar olan sayıların toplamını ve ortalamasını ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. I=2, TOPLAM=0
- A2. TOPLAM += I
- A3. I++
- A4. EGER(I == 1000) MI? (H) A2. GIT
- A5. ORT = TOPLAM/(I-1)
- A6. ORT, TOPLAM YAZ
- A7. DUR

# 
> **Soru** 9: Girilen vize ve final notuna göre öğrencinin kalıp kalmadığını ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. VIZE OKU
- A2. FINAL OKU
- A3. EGER(VIZE*0.4 + FINAL*0.6 >= 50) MI? (H) A6. GIT
- A4. “Ogrenci gecti” YAZ
- A5. A7. GIT
- A6. “Ogrenci kaldi” YAZ
- A7. DUR

# 
> **Soru** 10: Girilen bir sayının faktöriyelini ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. I=1,SONUC
- A2. SAYI OKU
- A3. SONUC *= I
- A4. I++
- A5. EGER(I<=SAYI) MI? (E) A3. GIT
- A6. SONUC YAZ
- A7. DUR

# 
> **Soru** 11: ax²+bx+c=0 verilen denklemin köklerini bulan algoritmayı yapınız.
- A0. BASLA
- A1. A OKU
- A2. B OKU
- A3. C OKU
- A4. DELTA = pow(B,2)-4*A*C
- A5. EGER(DELTA > 0) MI? (H) A10. GIT
- A6. X1 = (-B+sqrt(DELTA))/2*A
- A7. X2 = (-B-sqrt(DELTA))/2*A
- A8. X1, X2 YAZ
- A9. A14. GIT
- A10. EGER(DELTA == 0) MI? (H) A13. GIT
- A11. X1 = -B/2*A
- A12. X1 YAZ
- A13. “Reel kok yok” YAZ
- A14. DUR

# 
> **Soru** 12: Girilen sayının kaç basamak olduğunu ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. BASAMAK=0
- A2. SAYI OKU
- A3. SAYI /= 10
- A4. BASAMAK++
- A5. EGER(SAYI > 0) MI? (E) A3. GIT
- A6. BASAMAKYAZ
- A7. DUR

# 
> **Soru** 13: Girilen sayıya kadar olan 7 ve 3’ün katı olan sayıları ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. I=1
- A2. SAYI OKU
- A3. EGER(I%3 && I%7 == 0) MI? (H)
- A4. I YAZ
- A5. I++
- A6. EGER(I < SAYI) MI? A3. GIT
- A7. DUR

# 
> **Soru** 14: Girilen sayının mutlak değerini ekrana yazan programı yapınız.
- A0. BASLA
- A1. SAYI OKU
- A2. EGER(SAYI < 0) MI? (H) A4. GIT
- A3. SAYI *= -1
- A4. SAYI YAZ
- A5. DUR

# 
> **Soru** 15: n tane girilen sayı içerisinden pozitif, negatif sayıların ve 0 sayısının adedini ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. I=0, NEG=0,POZ=0,SIFIR=0
- A1. N OKU
- A2. SAYI OKU
- A3. EGER(SAYI > 0) MI? (H) A5. GIT
- A3. POZ++
- A4. A9. GIT
- A5. EGER(SAYI < 0) MI? (H) A8. GIT
- A6. NEG++
- A7. A9. GIT
- A8. SIFIR++
- A9. I++
- A10. EGER(I < N) MI? (E) A2. GIT
- A11. POZ,NEG,SIFIR YAZ
- A12. DUR

# 
> **Soru** 16: Rastgele girilen n tane sayı içerisinde tek sayıları 1 arttırıp karelerini alıp toplayan, çift sayıların kareköklerini alıp toplayan ve tek ve çift sayıların adetlerini ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. I=0, TTOP=0, CTOP=0, TADET=0, CADET=0
- A2. N OKU
- A3. SAYI OKU
- A4. EGER(SAYI%2 == 0) MI? (H) A7. GIT
- A4. CTOP += sqrt(SAYI)
- A5. CADET++
- A6. A9. GIT
- A7. TTOP += pow(SAYI+1,2)
- A8. TADET++
- A9. I++
- A10. EGER(I < SAYI) MI? (E) A3. GIT
- A11. TADET,TTOP,CADET,CTOP YAZ
- A12. DUR

# 
> **Soru** 17: Girilen kenar uzunluklarına göre üçgen oluşturup oluşturmadığını eğer oluşturuyorsa çevre ve alanını ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. A, B, C OKU
- A2. EGER (A+B>C && A+C>B && B+C>A) MI? (H) A15 . GIT
- A3. EGER (A=B && A=C) MI? (H) A6. GIT
- A4. “Eskenar ucgendir.” YAZ
- A5. A10. GIT
- A6. EGER(A!=B && A!=C && B!=C) MI? (H) A9. GIT
- A7. “Cesitkenar ucgendir.” YAZ
- A8. A10. GIT
- A9.”Ikizkenar ucgendir.” YAZ
- A10. CEVRE=A+B+C
- A11. S=CEVRE/2
- A12. ALAN=sqrt(S*(S-A)*(S-B)*(S-C))
- A13. CEVRE, ALAN YAZ
- A14. A16. GIT
- A15. “Ucgen olusamaz.” YAZ
- A16. DUR

# 
> **Soru** 18: Girilen sayının Tau sayı olup olmadığını yazan algoritmayı yapınız.
- A0. BASLA
- A1. I=1, BOLEN=0
- A2. SAYI OKU
- A3. EGER(SAYI%I == 0) MI? (H) A5. GIT
- A4. BOLEN++
- A5. I++
- A6. EGER(I <= SAYI) MI? (E) A3. GIT
- A7. EGER(SAYI%BOLEN== 0) MI?
- A8. “Tau sayisi” YAZ
- A9. A11. GIT
- A10. “Tau sayisi degil” YAZ
- A11. DUR

# 
> **Soru** 19: Girilen aralıklardaki heterometrik sayıları ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. ADEGER OKU
- A2. UDEGER OKU
- A3. HESAP = ADEGER * (ADEGER + 1)
- A4. HESAP YAZ
- A5. ADEGER++
- A6. EGER(ADEGER < UDEGER) MI? (H) A3. GIT
- A7. DUR

# 
> **Soru** 20: Girilen bir sayının palidrom sayı olup olmadığını ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. YENISAYI=0
- A2. SAYI OKU
- A3. EGER (SAYI>=10) MU? (H) A2. GIT
- A4. X=SAYI
- A5. KALAN=X % 10
- A6. YENISAYI=YENISAYI*10+KALAN
- A7. X = (X – KALAN)/10
- A8. EGER (X==0) MI? (H) A5. GIT
- A9. EGER (SAYI==YENISAYI) MI? (H) A12. GIT
- A10. “Palidrom sayisidir.” YAZ
- A11. A13. GIT
- A12. “Palidrom sayisi degildir.” YAZ
- A13. DUR

> **Örnek** 21: İki sayının toplamını hesaplayan ve sonucu ekrana yazan algoritmayı yapınız.
- A0 . BASLA
- A1 . SAYI1 OKU
- A2 . SAYI2 OKU
- A3 . TOPLAM= SAYI1+ SAYI2
- A4 . TOPLAM YAZ
- A5 . DUR

> **Örnek** 22: Kullanıcının girdiği iki sayının karelerinin toplamını hesaplayan ve sonucu ekrana yazan algoritmayı yapınız.
- A0 . BASLA
- A1 . SAYI1 OKU
- A2 . SAYI2 OKU
- A3 . SAYI_KARE1=SAYI1*SAYI1
- A4 . SAYI_KARE2=pow (SAYI2, 2)
- A5 .TOPLAM = SAYI_KARE1 + SAYI_KARE2
- A6 . TOPLAM YAZ
- A7 . DUR

> **Örnek** 23: Kullanıcının girdiği bir sayının kare, küpü ve karekökünü hesaplayan ve bunları ekranda görüntüleyen algoritmayı yapınız.
- A0 . BASLA
- A1 . SAYI OKU
- A2 . KARE=pow (SAYI, 2)
- A3. KUP=pow (SAYI, 3)
- A4 . KAREKOK=sqrt (SAYI)
- A5 . KARE, KUP, KAREKOK YAZ
- A6 . DUR

> **Örnek** 24: Klavyeden girilen rastgele 5 sayının toplamını bulan ve toplamı görüntüleyen algoritmayı yapınız.
- A0 . BASLA
- A1 . TOPLAM=0, SAYAC=0
- A2 . SAYI OKU
- A3 . TOPLAM = TOPLAM + SAYI
- A4 . SAYAC = SAYAC + 1
- A5 . EGER (SAYAC ==5) MI? (H), A2. GIT
- A6 . TOPLAM YAZ
- A7 . DUR

> **Örnek** 25: 1+2+3+…….+100 kadar olan sayıların toplamını bulan ve sonucu yazıcıya yazan algoritmayı yapınız.
- A0. BASLA
- A1. TOPLAM=1, SAYAC=1
- A2. SAYAC = SAYAC + 1
- A3. TOPLAM=TOPLAM + SAYAC
- A4. EGER (SAYAC ==100) MI? (H) A2. GIT
- A5. TOPLAM YAZ
- A6. DUR

> **Örnek** 26: 1’den 100’e kadar olan çift sayıların toplamını bulan ve bunları yazıcıya yazan algoritmayı yapınız.
- A0. BASLA
- A1. TOPLAM=2, SAYAC=2
- A2. SAYAC+=2
- A3. TOPLAM=TOPLAM + SAYAC
- A4. EGER (SAYAC ==100) MI? (H) A2. GIT
- A6. TOPLAM YAZ
- A7. DUR

> **Örnek** 27: 1’den 1000’e kadar olan çift ve tek sayılar toplamlarını ve çift ve tek sayıların adetlerin bulan ve bunları yazıcıya yazan algoritmayı yapınız.
- A0. BASLA
- A1. CTOP=0, CADET=0, TTOP=0, TADET=0, SAYAC=0
- A2. SAYAC=SAYAC+1
- A3. KNTRL=SAYAC%2
- A4. EGER (KNTRL==0) MI? (H) A8. GIT
- A5. CTOP=CTOP+SAYAC
- A6. CADET++
- A7. A10. GIT
- A8. TTOP+=SAYAC
- A9. TADET++
- A10. EGER (SAYAC<1000) MI? (E) A2. GIT
- A11. CTOP, CADET, TTOP, TADET YAZ
- A12. DUR

> **Örnek** 28: Girilen herhangi bir aralıktaki sayma sayılarının çift ve tek sayılar toplamlarını ve çift ve tek sayıların adetlerin bulan ve bunları yazıcıya yazan algoritmayı yapınız.
- A0. BASLA
- A1. CTOP=0, CADET=0, TTOP=0, TADET=0
- A2. ALTDEGER, USTDEGER OKU
- A3. EGER (ALTDEGER<USTDEGER) MU? (H) A2. GIT
- A4. KNTRL=ALTDEGER%2
- A5. EGER (KNTRL==0) MI? (H) A9. GIT
- A6. CTOP+=ALTDEGER
- A7. CADET++
- A8. A11. GIT
- A9. TTOP+=SALTDEGER
- A10. TADET++
- A11. ALTDEGER++
- A12. EGER (ALTDEGER<USTDEGER+1) MI? (E) A4. GIT
- A11. CTOP, CADET, TTOP, TADET YAZ
- A12. DUR

> **Örnek** 29: Klavyeden bilinmeyen miktarda okutulan pozitif ve negatif tam sayıların ayrı ayrı toplamlarını, pozitif ve negatif sayıların adetlerini bulan ve sıfır sayısı girildiğinde programı sonlandıran sonuçları ekrana yazan algoritmayı yapınız.
- A0. BASLA
- A1. PTOP=0, PADET=0, NTOP=0, NADET=0
- A2. SAYI OKU
- A3. EGER (SAYI==0) MI? (E) A11. GIT
- A4. EGER (SAYI>0) MI? (E) A8. GIT
- A5. NTOP=NTOP+SAYI
- A6. NADET ++
- A7. A2. GIT
- A8. PTOP+=SAYI
- A9. PADET ++
- A10. A2. GIT
- A11. PTOP, PADET, NTOP, NADET YAZ
- A12. DUR

> **Örnek** 30: 1’den 100’e kadar olan tek sayılar toplamı ve tek sayılar adedini hesaplayan ve sonucu ekrana yazan algoritmayı yapınız.
- A0 . BASLA
- A1 . TEKTOP = 1, SAYAC=3, TEKADET=2
- A2 . TEKTOP = TEKTOP + SAYAC
- A3 . EGER (SAYAC = 99) MU? (E) A6. GIT
- A4 . SAYAC= SAYAC + 2
- A5. TEKADET=TEKADET + 1
- A6. A2. GIT
- A6 . TEKTOP, TEKADET YAZ
- A7 . DUR

> **Örnek** 31: Klavyeden girilen bir tam sayının faktöriyelini hesaplayan ve ekranda görüntüleyen algoritmayı yapınız.
- A0. BASLA
- A1. FAKTOR=1
- A2. SAYI OKU
- A3. EGER (SAYI<0) MI? (H) A6. GIT
- A4. “Negatif tamsayinin faktoryeli hesaplanmaz.” YAZ
- A5. A13. GIT
- A6. EGER (SAYI==0) MI? (H) A9. GIT
- A7. “0!=” FAKTOR YAZ
- A8. A13. GIT
- A9. FAKTOR*=SAYI
- A10. SAYI – –
- A11. EGER (SAYI==0) MI? (H) A9. GIT
- A12. FAKTOR YAZ
- A13. DUR

> **Örnek** 32: 30’dan 90’a kadar çift sayıların ortalamasını hesaplayan ve sonucu ekrana yazan programın algoritmasını yapınız.
- A0. BASLA
- A1. TOP=32, ADET=1, SAYAC=32
- A2. SAYAC+=2
- A3. TOP+=SAYAC
- A4. ADET++
- A5. EGER (SAYAC<88) MI? (E) A2. GIT
- A6. ORT= TOP/ADET
- A7. ORT YAZ
- A8. DUR

> **Örnek** 33: Klavyeden girilen iki sayıdan en büyüğünü bulup ekranda gösteren algoritmayı yapınız.
- A0. BASLA
- A1. SAYI1 OKU
- A2. SAYI2 OKU
- A3. EGER (SAYI1>SAYI2) MI? (H) A6. GIT
- A4. SAYI1 “Buyuktur.” YAZ
- A5. A7. GIT
- A6. SAYI2 “Buyuktur.” YAZ
- A7. DUR

> **Örnek** 33: Klavyeden girilen üç sayıdan en büyüğünü bulan ve ekranda görüntüleyen algoritmayı yapınız.
- A0. BASLA
- A1. S1, S2, S3 OKU
- A2. EGER ((S1>S2) AND (S1>S3)) MI? (E) A6. GIT
- A3. EGER ((S2>S1) AND (S2>S3)) MI? (E) A8. GIT
- A4. S3 “Buyuktur.” YAZ
- A5. A9. GIT
- A6. S1 “Buyuktur.” YAZ
- A7. A9. GIT
- A8. S2 “Buyuktur.” YAZ
- A9. DUR

> **Örnek** 34: Klavyeden girilen N tane sayma sayısından en büyük ve en küçük sayıları bulan ve bu sayıları ekranda görüntüleyen algoritmayı yapınız.
- A0. BASLA
- A1. “Sayi adedini giriniz” YAZ
- A2. N OKU
- A3. EGER (N<1) MI? (E) A2. GIT
- A4. SAYI OKU
- A5. ENB=SAYI
- A6. ENK=SAYI
- A7. N – –
- A8. EGER (N= =0) MI? (E) A16. GIT
- A9. SAYI OKU
- A10. EGER (SAYI>ENB) MI? (H) A13. GIT
- A11. ENB=SAYI
- A12. A7. GIT
- A13. EGER (SAYI<ENK) MI? (H) A7. GIT
- A14. ENK=SAYI
- A15. A7. GIT
- A16. ENK, ENB YAZ
- A17. DUR

> **Örnek** 35: Bir sayının kendisi hariç pozitif tamsayı çarpanları (kalansız bölen sayıların) toplamı kendisine eşit olan sayıya mükemmel sayı denir. Klavyeden girilen bir sayının mükemmel sayı olup/olmadığını bulan ve sayı mükemmel sayı ise yazıcıya “mukemmel sayidir.” değilse “mukemmel sayi degildir.” ibaresini ekranda görüntüleyen algoritmayı yapınız.
- A0. BASLA
- A1. TOPLAM=0, SAYAC=1
- A2. SAYI OKU
- A3. EGER (SAYI==1) MI? (E) A12. GIT
- A4. KALAN=SAYI%SAYAC
- A5. EGER (KALAN==0) MI? (H) A7. GIT
- A6. TOPLAM=TOPLAM+SAYAC
-A7. SAYAC++
- A8. EGER (SAYAC<SAYI) MI? (E) A4. GIT
- A9. EGER (TOPLAM==SAYI) MI? (H) A12. GIT
- A10. SAYI “ mukemmel sayidir.” YAZ
- A11. A13. GIT
- A12. SAYI “ mukemmel sayi degildir.” YAZ
- A13. DUR

> **Örnek** 36: İki basamaklı iki doğal sayının birler basamağındaki rakamların toplamı 10 ve onlar basamağındaki rakamları aynı ise bu iki doğal sayıya bağdaşık sayı denir. Klavyeden girilen iki doğal sayının bağdaşık sayı olup/olmadığını bulan ve de bağdaşık sayı ise “Bagdasik sayilardir.” değilse “Bagdasik sayilar degil.” ibaresini ekrana yazan programın algoritmasını yapınız.
- A0. BASLA
- A1. X, Y OKU
- A2. EGER (X>=10 AND X<=99 AND Y>=10 AND Y<=99) MU? (H) A1. GIT
- A3. XBIRLER=X%10
- A4. YBIRLER=Y%10
- A5. EGER ((XBIRLER + YBIRLER)==10) MU? (H) A11. GIT
- A6. XONLAR=(X-XBIRLER)/10
- A7. YONLAR=(Y-YBIRLER)/10
- A8. EGER (XONLAR==YONLAR) MI? (H) A11. GIT
- A9. “Bagdasik sayidir.” YAZ
- A10. A12. GIT
- A11. “Bagdasik sayi degildir.” YAZ
- A12. DUR

> **Örnek** 37: Pozitif bir tamsayıyı kalansız bölen sayılar adedi o sayıyı kalansız bölebiliyorsa o tamsayıya Tau sayısı denir. (Örneğin 1, 2, 8, 12, 18, 24, 36, 40, 56, … Tau sayısı olan 18 sayısı, kalansız bölen sayıları 1, 2, 3, 6, 9 ve 18’dir. Kalansız bölen sayı adedi 6 olup ve 6 sayısıda 18’i kalansız bölebilmektedir). Klavyeden girilen bir sayının Tau sayı olup/olmadığını bulan ve de Tau sayısı ise “Tau sayisidir.” değilse “Tau sayisi degildir.” ibaresini yazıcıya yazan programın algoritmasını yapınız.
- A0. BASLA
- A1. SAYAC=0, TOPADET=0
- A2. SAYI OKU
- A3. SAYAC++
- A4. EGER ((SAYI%SAYAC)==0) MI? (H) A6. GIT
- A5. TOPADET++
- A6. EGER (SAYAC<SAYI) MI? (E) A3. GIT
- A7. EGER ((SAYI%TOPADET)==0) MI? (H) A10. GIT
- A8. “Tau sayidir.” YAZ
- A9. A11. GIT
- A10. “Tau sayisi degildir.” YAZ
- A11. DUR

> **Örnek** 38: x pozitif bir tamsayı olmak üzere x(x+1) ifadesinden elde edilen sayılara heterometrik sayıları denir. Örneğin 2=1.2, 6=2.3, 12=3.4, …. dir. Klavyeden girilen bir aralıktaki heterometrik sayıları hesaplayan ve ekrana yazan programın algoritmasını yapınız.
- A0. BASLA
- A1. SAYAC=0
- A2. ALTSAYI, USTSAYI OKU
- A3. EGER (ALTSAYI<USTSAYI) MI? (H) A2. GIT
- A4. SAYAC++
- A5. HESAP=pow(SAYAC, 2) + SAYAC
- A6. EGER (HESAP==ALTSAYI) MI? (E) A12. GIT
- A7. EGER (HESAP<ALTSAYI) MI? (E) A4. GIT
- A8. ALTSAYI++
- A9. EGER (ALTSAYI<USTSAYI) MI (H) A14. GIT
- A10. SAYAC=1
- A11. A5. GIT
- A12. ALTSAYI YAZ
- A13. A8. GIT
- A14. DUR

> **Örnek** 39: Baştan ve sondan yazılışları aynı olan sayılara palidrom sayıları denir. Örneğin 11, 22, 33, 44, …101, 111, 121, 131, …. 1001, 1111, … dir. Klavyeden girilen bir sayının palidrom sayı olup/olmadığını bulan ve de palidrom sayısı ise “Palidrom sayisidir.” değilse “Palidrom sayisi degildir.” ibaresini yazıcıya yazan programın algoritmasını yapınız.
- A0. BASLA
- A1. YENISAYI=0
- A2. SAYI OKU
- A3. EGER (SAYI>=10) MU? (H) A2. GIT
- A4. X=SAYI
- A5. KALAN=X % 10
- A6. YENISAYI=YENISAYI*10+KALAN
- A7. X = (X – KALAN)/10
- A8. EGER (X==0) MI? (H) A5. GIT
- A9. EGER (SAYI==YENISAYI) MI? (H) A12. GIT
- A10. “Palidrom sayisidir.” YAZ
- A11. A13. GIT
- A12. “Palidrom sayisi degildir.” YAZ
-A13. DUR

> **Örnek** 40: X ve Y bir tamsayı çifti olsun. X’nin kendisi hariç kalansız bölenlerinin toplamı Y’ye ve Y’nin kendisi hariç kalansız bölenlerinin toplamı X’e eşitse bu iki sayıya dost sayılar denir. Buna göre Klavyeden girilen iki tamsayının dost sayı olup/olmadığını bulan ve de dost sayı ise “Dost sayilar.” değilse “Dost sayi degiller.” ibaresini yazıcıya yazan programın algoritmasını yapınız.
- A0. BASLA
- A1. X, Y OKU
- A2. XTOP=0, YTOP=0
- A3. XSAYAC=X
- A4. XSAYAC – –
- A5. EGER (XSAYAC==0) MI? (E) A9. GIT
- A6. EGER (X % XSAYAC==0) MI? (H) A4. GIT
- A7. XTOP+=XSAYAC
- A8. A4. GIT
- A9. YSAYAC=Y
- A10. YSAYAC – –
- A11. EGER (YSAYAC==0) MI? (E) A15. GIT
- A12. EGER (Y % YSAYAC==0) MI? (H) A10. GIT
- A13. YTOP+=YSAYAC
- A14. A10. GIT
- A15. EGER (XTOP==Y AND X==YTOP) MU? (H) A18. GIT
- A16. “Dost sayilar.” YAZ
- A17. A19. GIT
- A18. “Dost sayi degiller.” YAZ
- A19. DUR

> **Örnek** 41: İki pozitif tam sayının bölme işlemini sadece çıkarma işlemi kullanarak bölüm ve kalanı hesaplayan ve bölüm ve kalanı görüntüleyen algoritmayı yapınız.
- A0. BASLA
- A1. BOLUM = 0
- A2. SAYI1, SAYI2 OKU
- A3. EGER (SAYI1=0 AND SAYI2=0) MI? (E) A11. GIT
- A4. EGER (SAYI1=0 AND SAYI2 !=0) MI? (E) A13. GIT
- A5. EGER (SAYI1!=0 AND SAYI2 = 0) MI? (E) A15. GIT
- A6. SAYI1=SAYI1-SAYI2
- A7. BOLUM=BOLUM+1
- A8. EGER (SAYI1>SAYI2) MI? (E) A6. GIT
- A9. BOLUM, SAYI1 (=FARK) YAZ
- A10. A16. GIT
- A11. “Belirsiz” YAZ
- A12. A16. GIT
- A13. “ Sifir” YAZ
- A14. A16. GIT
- A15. “Tanimsiz” YAZ
- A16. DUR

> **Örnek** 42: N elemanlı bir diziye rastgele pozitif tam sayılar girilmektedir. Bu tam sayıların aritmetik ortalamasını hesaplayan ve aritmetik ortalamayı ve de eleman sayısını yazıcıya yazan programın algoritmasını yapınız.
- A0. BASLA
- A1. I=0, TOPLAM=0
- A2. N OKU
- A3. EGER (N<=0) MI? (E) A2. GIT
- A4. DIZI[I] OKU
- A5. I++
- A6. EGER (I<N) MI? (E) A4. GIT
- A7. I=0
- A8. TOPLAM=TOPLAM+DIZI[I]
- A9. I++
- A10. EGER (I<N) MI? (E) A8. GIT
- A11. ORT=TOPLAM/N
- A12. N, ORT YAZ
- A13. DUR

> **Örnek** 43: N elemanlı bir diziye rastgele tam sayılar girilmektedir. Bu tam sayıların içinde tek ve çift pozitif sayıların aritmetik ortalamalarını hesaplayan ve aritmetik ortalamalarını ve de tek ve çift pozitif sayıların eleman sayılarını (adetlerini) ekrana yazan programın algoritmasını yapınız.
- A0. BASLA
- A1. I=0, TTOP=0, TADET=0, CTOP=0, CADET=0
- A2. N OKU
- A3. EGER (N<=0) MI? (E) A2.GIT
- A4. DIZI[I] OKU
- A5. I++
- A6. EGER (I<N) MI? (E) A4. GIT
- A7. I=0
- A8. EGER (DIZI[I]<=0) MI? (E) A15. GIT
- A9. EGER (pow(-1, DIZI[I])==1) MI? (H) A13. GIT
- A10. CTOP=CTOP+DIZI[I]
- A11. CADET++
- A12. A15. GIT
- A13. TTOP=TTOP+DIZI[I]
- A14. TADET++
- A15. I++
- A16. EGER (I<N) MI? (E) A8. GIT
- A17. CORT=CTOP/CADET
- A18. TORT=TTOP/TADET
- A19. CORT, TORT, CADET, TADET YAZ
- A20. DUR

> **Örnek** 44: N ve M elemanlı iki dizinin elemanlarına rastgele tam sayılar girilmektedir. Bu İki dizi elemanlarının toplamını üçüncü bir diziye aktaran ve de bu dizin elemanlarını ekrana yazan programın algoritmasını yapınız.
- A0. BASLA
- A1. I=0, J=0
- A2. N, M OKU
- A3. EGER (N>0 && M>0) MI? (H) A2. GIT
- A4. EGER (N==M) MI? (H) A20. GIT
- A5. DIZIA[I] OKU
- A6. I++
- A7. EGER (I<N) MI? (E) A5. GIT
- A8. DIZIB[J] OKU
- A9. J++
- A10. EGER (J<N) MI? (E) A10. GIT
- A11. I=0
- A12. DIZIC[I]=DIZIA[I] + DIZIB[I]
- A13. I++
- A14. EGER (I<N) MI? (E) A12. GIT
- A15. I=0
- A16. DIZIC[I] YAZ
- A17. I++
- A18. EGER (I<N) MI? (E) A16. GIT
- A19. A21. GIT
- A20. “Toplama islemi yapılamaz” YAZ
- A21. DUR

> **Örnek** 45: N elemanlı bir diziye rastgele tam sayılar girilmektedir. Bu dizinin içindeki en büyük ve en küçük sayıları ve dizi indislerini bulup ekrana yazan programın algoritmasını yapınız.
- A0. BASLA
- A1. I=0
- A2. N OKU
- A3. DIZI [I] OKU
- A4. I++
- A5. EGER (I<N) MI? (E) A3. GIT
- A6. ENB=DIZI[I-1]
- A7. ENBINDIS=I-1
- A8. ENK=DIZI[I-1]
- A9. ENKINDIS=I-1
- A10. I- –
- A11. EGER (DIZI[I]>ENB) MI? (H) A15. GIT
- A12. ENB=DIZI[I]
- A13. ENBINDIS=I
- A14. A18. GIT
- A15. EGER (DIZI[I]<ENK) MI? (H) A18. GIT
- A16. ENK=DIZI[I]
- A17. ENKINDIS=I
- A18. EGER (I==0) MI? (H) A10. GIT
- A19. ENB, ENK,ENBINDIS, ENKINDIS YAZ
- A20. DUR

> **Örnek** 46: Klavyeden girilen N elemanlı bir A dizisini küçükten büyüğe doğru kabarcık sıralama (bubble sort) yöntemini kullanarak rastgele tam sayıları sıralayan ve bunları sıralamadan önceki/sonraki durumu ekranda gösteren programın algoritmasını yapınız.
- A0. BASLA
- A1. I=0
- A2. N OKU
- A3. EGER (N<=0) MI? (E) A2. GIT
- A4. A[I] OKU
- A5. I++
- A6. EGER (I<N) MI? (E) A4. GIT
- A7. I=0
- A8. A[I] YAZ
- A9. I++
- A10. EGER (I<N) MI? (E) A8. GIT
- A11. I=0
- A12. J=0
- A13. EGER (A[J+1]<A[J]) MI? (H) A17. GIT
- A14. TEMP=A[J]
- A15. A[J]=A[J+1]
- A16. A[J+1]=TEMP
- A17. J++
- A18. EGER (J<N-1) MI? (E) A13. GIT
- A19. I++
- A20. EGER (I<N) MI? (E) A12. GIT
- A21. I=0
- A22. A[I] YAZ
- A23. I++
- A24. EGER (I<N) MI? (E) A22. GIT
- A25. DUR

> **Örnek** 47. Klavyeden girilen N elemanlı bir A dizisini küçükten büyüğe doğru araya ekleme sıralama (insertion sort) yöntemini kullanarak rastgele tamsayıları sıralayan ve bunları sıralamadan önceki/sonraki durumu ekranda gösteren programın algoritmasını yapınız.
- A0. BASLA
- A1. I=0
- A2. N OKU
- A3. EGER (N<=0) MI? (E) A2. GIT
- A4. A[I] OKU
- A5. I++
- A6. EGER (I<N) MI? (E) A4. GIT
- A7. I=0
- A8. A[I] YAZ
- A9. I++
- A10. EGER (I<N) MI? (E) A8. GIT
- A11. I=1
- A12. TEMP=A[I]
- A13. J=I-1
- A14. EGER (J>=0 && A[J]>TEMP) MU? (H) A19. GIT
- A15. A[J+1]=A[J]
- A16. J – –
- A17. A[J+1]=TEMP
- A18. A14. GIT
- A19. I++
- A20. EGER (I<N) MI? (E) A12. GIT
- A21. I=0
- A22. A[I] YAZ
- A23. I++
- A24. EGER (I<N) MI? (E) A22. GIT
- A25. DUR

> **Örnek** 49: 60 kişilik bir sınıfta Fizik dersinin vize sınavından alınan en yüksek, en düşük notu ve not ortalamasını bulan ve en yüksek, en düşük notu ve de vize not ortalamasını ekrana yazdıran programın algoritmasını yapınız.
- A0. BASLA
- A1. SAYAC=1
- A2. SAYAC “. VIZE NOTU GİRİNİZ: ” YAZ
- A3. VIZE OKU
- A4. EKN= VIZE
- A5. EBN= VIZE
- A6. TOP= VIZE
- A7. SAYAC++
- A8. SAYAC “. VIZE NOTU GİRİNİZ: ” YAZ
- A9. VIZE OKU
- A10. TOP=TOP+VIZE
- A11. EGER (VIZE<EKN) MI? (H) A14. GİT
- A12. EKN=VIZE
- A13. A16. GIT
- A14. EGER (VIZE > EBN )MI? (H) A16. GIT
- A15. EBN=VIZE
- A16. EGER (SAYAC <60 ) MI? (H) A7. GIT
- A17. ORT= TOP/60
- A18. EBN, EKN, ORT YAZ
- A19. DUR

> **Örnek** 50: Klavyeden bulunduğunuz yılı ve ürünün o günkü fiyatını giriniz. Her yıl enflasyon oranını % 15 kabul ederek önümüzdeki 18 yıl için; her bir yıl sonunda yılı, enflasyon farkını ve ayakkabının yeni fiyatını ekrana yazan programı algoritmasını yapınız.
- A0. BASLA
- A1. YIL OKU
- A2. FIYAT OKU
- A3. ARTIS = 0; SAYAC=1
- A4. “YIL ARTIS YENI FIYAT” YAZ
- A5. YIL, ARTIS, FIYAT YAZ
- A6. EGER (SAYAC <=18) MU? (H) A13. GIT
- A7. ARTIS * = 0.15
- A8. FIYAT += ARTIS
- A9. YIL+= 1
- A10. YIL, ARTIS, FIYAT YAZ
- A11. SAYAC++
- A12. A5. GIT
- A13. DUR