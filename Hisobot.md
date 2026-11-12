# Hisobot: Parazitologiya mavzulari bo'yicha testlar

- **Manba:** `Мавзу.zip` (149 ta mavzu, `001.docx` … `149.docx`).
- **Rol:** Test tuzuvchi, Parazitologiya bo'yicha shifokor.
- **Shablon:** `shablon.xlsx` (Question | A | B | C | D | E | Correct | Comment).
- **Natija:** `Testlar/001.xlsx` … `Testlar/149.xlsx`.
- **Savollar manbasi (JSON):** `src/Мавзу/_build/questions/` (30 ta partiya fayli).

## 1. Fayllar va savollar soni

| Ko'rsatkich | Qiymat |
|---|---|
| Test fayllari | 149 |
| Jami savollar | 1611 |
| Savollar soni bir faylda | 10–11 |
| QA xatolari (qat'iy rejim) | 0 |
| Qayta o'qib tekshirish (jszip) | 0 muammo: soni 10–11, ketma-ket 3 ta bir xil harf yo'q, har izohda «iqtibos» bor, kirill aralashmasi yo'q |

## 2. To'g'ri javob harflari taqsimoti

| A | B | C | D | E |
|---|---|---|---|---|
| 324 (20,1%) | 314 (19,5%) | 330 (20,5%) | 318 (19,7%) | 325 (20,2%) |

## 3. To'g'ri javob 10% dan uzun bo'lgan savollar

Jami **87 ta savol (5,4%)**. Ularning hech biri 30% chegaradan oshmaydi. Qavs ichida to'g'ri javob eng uzun noto'g'ri javobdan necha foiz uzunligi berilgan.

- 004: S8 (24%)
- 021–030: 021 S4; 022 S10; 023 S1, S8; 024 S3; 026 S3, S4, S8; 029 S1; 030 S1, S2, S8, S9, S10 (11–16%)
- 041–050: 041 S1; 042 S1, S3, S5; 043 S6, S8; 044 S3, S5, S6; 046 S5, S8, S9; 048 S7, S8, S9; 049 S3 (22%); 050 S2, S5, S6, S11 (21%)
- 072 S9, 073 S9, 077 S7, 080 S5 (har biri 11%)
- **111–120 (eng ko'p, 37 ta):**
  - 111: S4, S8, S9 (30%)
  - 113: S1, S2, S5 (30%), S8 (28%), S10
  - 114: S1, S3, S6
  - 115: S2, S4, S7
  - 116: S1, S5, S6, S7, S8
  - 117: S1, S9
  - 118: S3, S6, S7, S8
  - 119: S1 (28%), S4
  - 120: S1, S2 (29%), S3, S4, S7, S10 (29%), S11
- 121–130: 121 S5, S8; 122 S5, S7; 124 S4; 125 S5; 127 S10, S11; 128 S3, S5; 129 S4, S5; 130 S8, S10

> Tavsiya: 111–120 partiyasida to'g'ri javob uzunligi bo'yicha "ishora" sezilishi mumkin. Bu savollarni qo'lda ko'rib chiqish yoki noto'g'ri javoblarni uzaytirish maqsadga muvofiq.

## 4. Mavzu matnlaridagi farqlar va ziddiyatlar

1. **001:** qonunlar va Rossiya hujjatlariga oid bandlar matnning o'zida tasdiqlanmagan deb belgilangan.
2. **003, 007, 009:** Bilgarts kashfiyoti 003 da "XIX asr", 007 va 009 da aniq 1851-yil. Bu ziddiyat emas, aniqlik darajasidagi farq. Ismlar imlosi ham har xil: Tyson/Tayson, Looss/Lus.
3. **004 va 006:** 004 ankilostomidozni geogelmintlar qatoriga qo'shadi. 006 dagi 121-son 4-ilova ro'yxatida esa geogelmintozlar faqat askaridoz va trixosefalyoz.
4. **009:** akademik "Jaloliddin Azimov" deb yozilgan, adabiyotda "Azimov D.A.". Fedchenko "A.P." va "A.T. Fredchenko" deb ikki xil yozilgan.
5. **010:** xo'jayinlar avval "uch asosiy tur" deyiladi, xulosada esa to'rttasi sanaladi. Parazitizm simbiozning turi deyiladi, mutualizm va kommensalizm esa undan alohida ajratiladi.
6. **011:** superinvaziya "parazit ko'paymaydigan gelmintozlarda tipik" deyiladi. Misol sifatida esa gimenolepidoz va strongiloidoz keltiriladi, ularda parazit ko'payadi.
7. **011 va 012:** 011 invaziya va infeksiyani farqlaydi. 012 esa "aralash infeksiya, ya'ni aralash invaziya" deb ularni tenglashtiradi.
8. **013 va 016:** 013 bezgak bevosita yuqmaydi deydi. Shu matnning o'zida va 016 da qon quyish, shprits va onadan homilaga yuqish keltirilgan.
9. **014:** JSST bo'yicha 5 tur, milliy matnda 4 tur. "P. vivax eng keng tarqalgan" degan gap Afrikada P. falciparum ustunligi haqidagi gapga zid.
10. **014 va 018:** davolanmagan tropik bezgakda o'lim 014 da "24 soat ichida", 018 da "bir necha kun ichida".
11. **017, 018, 020:** eritrotsitlar yoshini tanlash bo'yicha bayonlar har xil.
12. **022 va 023:** kuzatuv muddati 022 da 3 yil, 023 da 1 yil (uch kunlik bezgakda 3 yil). Ikkala matnda ham "muddatni milliy hujjat belgilaydi" degan gap bor.
13. **025:** "2017-yildan beri 14 mamlakat sertifikatlangan" deyiladi, ammo Qirg'iziston 2016-yilda sertifikatlangan deb yozilgan.
14. **027:** harorat chegaralari "tasdiqlanmagan" deyiladi, keyin aniq qiymatlar beriladi: P. vivax 16 °C, P. falciparum 18 °C.
15. **028 va 030:** preparatlar soni bo'yicha farq bor: kamida 2 ta yoki 3 tadan. Tomchilar soni va diametri ham farq qiladi: JSST bo'yicha 3 ta tomchi, ~1 sm; milliy tartibda 2 ta tomchi, ~5 mm.
16. **030:** qon olinadigan barmoq JSST bo'yicha uchinchi barmoq, milliy tartibda 3- yoki 4-barmoq. Chaqaloqlarda tovon olinishi taqiqlanadi va ruxsat etiladi deb ikki xil yozilgan. Fen bilan quritish ham bir joyda ruxsat etiladi, boshqa joyda taqiqlanadi.
17. **031 va 032:** fiksatsiya bir joyda metanol, boshqa joyda 96° spirt (10 daqiqa) yoki Nikiforov aralashmasi (20 daqiqa). Tezkor bo'yash usuli qancha preparatga mo'ljallangani ham farq qiladi: 1–15 ta yoki 20 tadan ko'p.
18. **035:** bezgak holatlarining epidemiologik toifalari uch xil ro'yxatda beriladi: CDC, 121-son buyruq va milliy qo'llanma.
19. **036:** o'choq toifalari soni xalqaro tasnifda 3 ta, 121-son buyruqda 4 ta, milliy qo'llanmada 6 ta.
20. **039 va 040:** sporogoniya ta'riflari har xil. "Eng samarali chora" deb uch xil chora ko'rsatilgan.
21. **041:** to'qima shizogoniyasi asosiy qismda "bir necha kun", milliy qismda 6 haftagacha yoki 3 haftagacha.
22. **044:** tugatilgan o'choq "ro'yxatdan chiqarilmaydi" deyiladi. 121-son buyruqda esa 3 yillik sog'lomlashtirish muddati bor.
23. **045:** leyshmanioz viloyatlari adabiyotda 3 ta. 121-son buyruqda 7 viloyat va Qoraqalpog'iston.
24. **046 va 049:** chivinchalar turlari soni bir joyda 9 ta, boshqa joyda 12 ta. Visseral leyshmanioz tashuvchisi bir joyda P. alexandri, boshqa joyda Ph. longiductus yoki Ph. angustus.
25. **047 va 056:** O'zbekistonda rezervuar va tur "tasdiqlanmagan" deyiladi. Shu matnlarning 121-son qismida esa L. infantum va itlar aniq ko'rsatilgan.
26. **048:** inkubatsiya "oylar bilan" va "2–8 oy, ba'zan 1,5 yil" deb ikki xil berilgan. Mavsumiylik ham farq qiladi: 048 da xarakterli emas, 046 va 050 da mavsumiy.
27. **051 va 058:** teri leyshmaniozi yarasi 051 da "og'riqsiz", 058 da "kam og'riydi".
28. **057 va 059:** davolanmagan visseral leyshmaniozda o'lim JSST bo'yicha ">95%", 121-son bo'yicha "98–99%". Tashxis algoritmlari ham farq qiladi.
29. **061:** itlarni yo'q qilish umumiy qismda samarasiz deyiladi. 121-son buyruq esa kasal itlarni yo'qotishni belgilaydi.
30. **063:** kuzatuv muddati avval berilmaydi, keyin aniq sanalar keltiriladi: 1, 3, 6, 9 va 12-oylar.
31. **064:** dorilar ro'yxati umumiy qism va milliy bayonnomada mos emas. Dozalar "bayonnomada keltirilgan" deyiladi, lekin keltirilmagan.
32. **065:** visseral leyshmanioz viloyatlari 121-son buyruqning asosiy qismi va 2-ilovasida har xil.
33. **068–070:** kanali qaytalama terlama qo'zg'atuvchilari umumiy qismda B. persica va B. latyschewii. 121-son qismida Sogdiana va Latishev–Sofiyev spiroxetalari. Hududlar ham farq qiladi: cho'l yoki tog' oldi (400–1500 m).
34. **071:** inkubatsiya bir joyda "o'rtacha 7 kun, 4–18 kun", boshqa joyda "6–8 kun, 3–20 kun".
35. **072 va 073:** spiroxetalar xurujlar orasida 121-son bo'yicha aniqlanadi, umumiy qismda aniqlanmaydi. Ko'riladigan maydonlar soni ham har xil.
36. **074 va 075:** 121-son bo'yicha "yagona chora" kanalarga qarshi kurash. Umumiy qismda esa uch yo'nalish bor, jumladan deratizatsiya.
37. **078 va 080:** takroriy tekshiruv "ketma-ket 3 kun" yoki "2–3 kun oralatib" deb ikki xil. Gimenolepidozda 5–7 kun oralatib.
38. **083 va 087:** trixotsefalyozda intensiv o'choq chegarasi 083 da ≥30%, 087 da 10–15%. Bu faktdan savol tuzilmadi.
39. **084:** tuxumning yetilishi "taxminan 3 hafta" va "bir necha hafta" deb ikki xil. Chuvalchangning umri "bir yildan ortiq" va "taxminan bir yil" deb ikki xil.
40. **090:** askaridoz yuqish mavsumi 121-son bo'yicha yoz-kuz, boshqa bo'limda bahor-yoz. Bu faktdan savol tuzilmadi.
41. **094 va 099:** kuzatuv muddatlari avval "bir necha oy" deyiladi, 121-son bo'yicha 2, 4 va 6-oylar.
42. **095 va 097:** xavfli go'sht turlari bir joyda "tuzlangan yoki dudlangan", boshqa joyda "quritilgan yoki tuzlangan".
43. **102:** alveokokk nomi ikki xil: E. multilocularis va Alveococcus multilocularis.
44. **104:** diagnostik punksiya bir joyda "aspiratsiyadan keyin tekshiriladi" deyiladi, boshqa joyda "odatda qilinmaydi".
45. **106 va 108:** "eng samarali chora" uchun turli choralar ko'rsatilgan.
46. **109 va 110:** nomlanish ikki xil: difillobotriaz va difillobotrioz.
47. **114 va 115:** fassiolaning invazion bosqichi metaserkariya yoki adoleskariy deb ataladi. U bir joyda o'simlikka yopishgan, boshqa joyda suvda erkin suzadi.
48. **116:** inkubatsiya "bir necha hafta" deyiladi. Tuxumlar esa 2,5–3 oydan keyin topiladi.
49. **119:** opistorxoz mollyuskasi Bithynia yoki Codiella. Qo'zg'atuvchi O. viverrini va O. felineus yoki faqat O. felineus.
50. **119 va 120:** tuzlangan yoki dudlangan baliq bir joyda xavfli, boshqa joyda (uzoq muddat ishlov berilsa) xavfsiz.
51. **123:** toksokaroz qo'zg'atuvchisi T. canis va T. cati. 121-son bo'yicha faqat T. canis.
52. **126:** toksokaroz yuqish mavsumi bahor-yoz yoki yoz-kuz. Bu faktdan savol tuzilmadi.
53. **128:** protozoozlar tarqalishi "tekshirilmagan" deyiladi. 121-son bo'yicha esa lyamblioz 15–20%, balantidiaz 4–5%.
54. **129:** lyamblioz sistasi o'lchami 8–12 mkm yoki 10–14 × 6–10 mkm.
55. **131:** lyamblioz kistasining xlorga chidamliligi ikki xil berilgan: chidamli, yoki 1 mg/l da 72 soatda halok bo'ladi. Mavsumi ham ikki xil: yoz-kuz yoki aprel-may va yoz.
56. **133 va 136:** zararsiz amyobalar topilganda bir joyda davolash talab qilinmaydi deyiladi. 121-son bo'yicha esa tashuvchilar davolanadi.
57. **138:** toksoplazmoz bo'yicha bir sharhda aholining ~1/3 qismi zararlangan deyiladi, boshqasida "60 mln dan ortiq".
58. **139, 143, 144:** SanQvaN 0112-26 ro'yxatga olingan sana "2026-yil 21-iyul" deb yozilgan. Sana tekshirilishi kerak.
59. **140 va 142:** usul nomlari ikki xil: Beyermann va Berman. 142 xulosasidagi "formalin-efir" usul asosiy qismda "sirka-efir" deb nomlanadi.
60. **146 va 147:** "intensiv" atamasi uch xil ma'noda ishlatilgan: epg, aholiga nisbatan ko'rsatkich va o'choq toifasi. 147 dagi sonli misol "o'ylab topilgan" deb belgilangan.
61. **148:** muzlatish "eng muhim chora" deyiladi, shu matnda "hamma parazitga ishonchli emas" ham deyiladi.

Imlo xatolari:
- 008 "bilanzararlanish"
- 023 xulosasida uzilib qolgan "P."
- 053 "O'zbekistonRespublikasida"
- 081 "Gimenalipedoz"
- 086 va 137 "tashhisi"
- 091 va 099 "epidemiologic"
- 098 "veterinary"
- 116 va 119 "chuvalang"
- 140 "Gelmintozlarnin glaboratoriya"

## 5. Matnda "tasdiqlanmagan" yoki "tekshirilmagan" deb belgilangan faktlar

Bu faktlarning birortasi to'g'ri javob sifatida ishlatilmagan. Deyarli barcha mavzularda adabiyotlar ro'yxatidagi ayrim manbalar "qisman tasdiqlanmagan" deb belgilangan. Quyida matn ichidagi asosiy belgilangan faktlar keltirilgan.

- **001:** O'RQ-393 qonuni (2015); "Fuqarolar sog'lig'ini saqlash to'g'risida"gi qonun; Rossiya hujjatlari (MU 3.2.1756-03, MUK 4.2.3145-13) va ularning qo'llanishi.
- **002, 003:** belgilangan fakt yo'q.
- **004, 005, 007, 008:** faqat adabiyotlardagi qisman belgilar.
- **006:** tasnifning Skryabinga tegishliligi.
- **009:** ayrim tarixiy tafsilotlar; Kyuxenmeyster ishlari.
- **010:** paratenik xo'jayin; parazitizm evolyutsiyasi.
- **011:** davriy davolash va qayta zararlanish; aholida parazitlarning notekis taqsimlanishi.
- **012:** strongiloidozda giperinvaziya.
- **013:** kanali qaytalama terlama tashuvchilari; profilaktika.
- **014:** Afrikada P. vivax ga moyillikning pastligi.
- **015:** P. cynomolgi, P. simium va P. brasilianum odamda uchrashi; o'rmonlar kesilishining ta'siri.
- **016:** sayohatchilarda bezgakning kechishi; mavsum chegaralari.
- **017:** inkubatsiya muddatlari; davolash sxemalari.
- **018:** og'ir shakllar tafsilotlari: buyrak, o'pka shishi, gipoglikemiya.
- **019:** dispanser muddatlari.
- **020:** eritrotsitlar yoshini tanlash; serebral bezgak oqibatlari; to'rt kunlik bezgakda buyrak zararlanishi; parazitemiya chegarasi.
- **021, 022, 030:** belgilangan fakt yo'q.
- **023:** gametotsitlarning saqlanish muddati; HRP2/HRP3 mutantlari.
- **024:** strategiyaning maqsad foizlari.
- **025:** mintaqa natijalari.
- **026:** P. malariae, P. ovale va P. knowlesi import ekanligi; turlarning rasmiy ro'yxati.
- **027:** bahor muddatlari va harorat chegaralari.
- **028:** natijani talqin qilish tartibi.
- **029:** SOP larning to'liq ro'yxati.
- **032:** preparatlarni saqlash muddati.
- **033:** sifat nazorati bo'g'inlari; tashqi baholash; maqsad qiymatlari.
- **034:** oxirgi mahalliy holat yili va viloyatlari.
- **035:** sertifikatlashning milliy mezonlari.
- **036:** muddatlar; xavf toifalari; hujjat shakllari.
- **037:** import statistikasi; kuzatuv muddati.
- **038:** mahalliy holat atamalari.
- **039:** suvdagi bosqichlar muddati; An. stephensi.
- **040:** gametogenez; sporogoniya harorati va kunlari.
- **041:** P. falciparum siklining sinxron emasligi.
- **043:** o'choq chegarasi masofalari; hujjat shakllari.
- **044:** monitoring chastotasi; o'choqni tugatish muddati.
- **045:** zoonoz va antroponoz bo'linishi; holatlar soni.
- **046:** rezervuar tur nomlari; mavsumiylik oylari.
- **047:** O'zbekiston uchun qo'zg'atuvchi tur va manba.
- **048:** antroponoz shaklning klinikasi.
- **049:** P. sergenti yashash joyi.
- **050:** L. major rezervuar turlari; odamning yuqishni kuchaytiruvchi roli.
- **051:** kultura va PZR imkoniyati; Montenegro testi.
- **052:** chivincha lichinkalari; immunitet.
- **053:** kimyoviy usullar; huquqiy asos.
- **054:** mahalliy dasturlar.
- **055:** davolash va qayta faollashuv.
- **056:** rezervuar hayvon; PKDL bemorlari manba sifatida.
- **057:** inkubatsiya muddatlari; PKDL.
- **058:** klinik variantlar.
- **059:** aspirat olish; tashxis algoritmi.
- **060:** hayvonlarga qarshi choralar; samaradorlik mezonlari.
- **061:** rezervuarlarni nazorat qilish hajmi.
- **062:** leyshmanioz bo'yicha milliy SOP va tashqi baholash.
- **063:** PKDL; kuzatuv muddatlari.
- **064:** dori ro'yxati; bemorni yo'naltirish tartibi.
- **065:** endemik viloyatlar ro'yxati va holatlar soni.
- **066:** materiallar tafsiloti.
- **067:** ko'payish joylari; jurnal shakli.
- **068:** O'zbekistondagi tur.
- **069:** hududlar.
- **070:** mahalliy manbalar va kana turlari.
- **071:** isitma davomiyligi; asoratlar; milliy protokollar.
- **072:** ho'l tomchi usuli; serologiya va PZR.
- **073:** ko'riladigan maydonlar soni; sifat nazorati.
- **074:** kuzatuv muddati; vositalar ro'yxati.
- **075:** deratizatsiya va dezakarizatsiya vositalari; xavfli guruhlar.
- **076:** tuxum yetilish muddatlari; tarqalish ko'rsatkichlari.
- **077:** ostritsa va ichak belgilari orasidagi bog'liqlik.
- **078:** tasma va surtma usullarining sezgirligi.
- **079:** dezinfeksiya vositalari; kuzatuv muddati.
- **080:** Rodentolepis nomi; bilvosita hayot sikli; xavf omillari.
- **081:** inkubatsiya; asab belgilari; dorilar va dozalar.
- **082:** kuzatuv tartibi; maktab dasturi.
- **083:** dorilarning milliy ro'yxatda borligi; ivermektin.
- **084:** chuvalchang va tuxumning yashash muddatlari; cho'chqa askaridasi.
- **085:** A vitamini uchun raqobat; asoratlar.
- **086:** najas tekshiruvi usullari; serologiya.
- **087:** o'lchamlar (3–5 sm); harorat va muddatlar.
- **088:** prolaps chastotasi; temir preparatlari.
- **089:** boyitish usullari; tuxum o'lchami (50–55 mkm).
- **090:** saqlanish muddatlari; chang va hasharotlar orqali yuqish.
- **091:** xavf guruhlari; aholidan tanlanma.
- **092:** WHA54.19 bayoni; mas'uliyat taqsimoti.
- **093:** tarqalish ko'rsatkichlari.
- **094:** muddatlar; bachadon shoxlari soni.
- **095:** xavfsiz harorat va muddatlar.
- **096:** takroriy tekshiruv muddatlari.
- **097:** muzlatish rejimi; neyrotsistitserkoz.
- **098:** zararsizlantirish rejimlari; hujjat shakllari.
- **099:** muddatlar; hamkorlik tartibi.
- **100:** milliy tartib; zararlanganlar soni.
- **101:** muzlatish rejimi; hayvonlarni emlash.
- **102:** turlarning tarqalishi; genotiplar.
- **103:** O'zbekistonda alveokokkoz.
- **104:** KT/MRT imkoniyati; kistalar tasnifi.
- **105:** xavf omillarining ulushi; mavsumiylik.
- **106:** emlash; dastur bosqichlari.
- **107:** qayd etish tartibi; it najasini tekshirish usullari.
- **108:** huquqiy asos; skrining qamrovi.
- **109:** O'zbekiston bo'yicha tarqalish.
- **110:** fiksator turi; molekulyar usullar; dispanser muddatlari.
- **111:** baliqlarning zararlanganligi; muzlatish rejimlari.
- **112:** zararsizlantirish rejimlari; dispanser kuzatuvi.
- **113:** muzlatish va pishirish qiymatlari.
- **114:** O'zbekistonda ustun tur; o'lchamlar.
- **115:** suv sifatini baholash; mavsumiylik.
- **116:** epidemiologik tekshiruv tartibi.
- **117:** Kato–Katz intensivlik sinflari.
- **118:** xlorlash standartlari; ommaviy davolash.
- **119:** opistorxozning tarqalishi.
- **120:** baliq turlari; pishirish va muzlatish rejimlari.
- **121:** fiksator; serologiya va PZR imkoniyati.
- **122:** pishirish va muzlatish rejimlari.
- **123:** xom jigar orqali yuqish; seroprevalentlik.
- **124:** O'zbekistonda toksokaroz holati.
- **125:** biopsiya va molekulyar usullar.
- **126:** mavsumiy o'zgarishlar.
- **127:** veterinar va tibbiyot xizmatlari hamkorligi.
- **128:** protozoozlar ko'rsatkichlari; balantidiaz.
- **129:** lyamblioz ko'rsatkichlari; genotiplar.
- **130:** bolalar jamoalarida skrining.
- **131:** milliy ma'lumotlar; mavsumiylik.
- **132:** suv me'yorlari; kontaktlarni tekshirish.
- **133:** O'zbekistonda amyobiaz.
- **134:** tashuvchilar soni; o'g'it orqali yuqish.
- **135:** faqat adabiyotdagi belgi.
- **136:** tashuvchilarni tekshirish tartibi.
- **137:** fiksator; immunologik usullar.
- **138:** harorat tavsiyalari; homiladorlar skriningi.
- **139:** madaniy odatlar.
- **140:** McMaster usuli; Beyermann usuli; eozinofiliya.
- **141:** eozinofiliya; tekshiruv me'yorlari; nazorat muddatlari.
- **142:** JSST afzal ko'rgan usul; Mini-FLOTAC; tanlanma hajmi.
- **143:** ob'ektlar ro'yxati; me'yor qiymatlari.
- **144:** suv tekshirish me'yorlari; oqova suvlar.
- **145:** tasnif mezonlari va chegaralar; iqlim bo'yicha zonalash.
- **146:** formulalar; ko'paytirish koeffitsienti.
- **147:** o'rtacha intensivlik; standartlashtirish.
- **148:** T. solium va trixinelloz bo'yicha O'zbekiston ma'lumotlari; pishirish harorati.
- **149:** anizakioz; issiqlik va muzlatish rejimlari (55 °C, −20 °C, −35 °C); tuzlash.

## 6. Mutaxassis tekshiruvi uchun eslatmalar

- QA skripti faqat matn mosligini tekshiradi. Tibbiy mazmun (dozalar, me'yorlar, muddatlar) mutaxassis tomonidan tekshirilishi kerak.
- Bir nechta partiyada (031–040, 041–050, 071–080, 121–130) ayrim **noto'g'ri javoblardagi raqamlar matnda yo'q**. Ular faqat chalg'ituvchi variant sifatida qo'yilgan, masalan:
  - 074: "3–5 kun"
  - 079: "yiliga 2/3/4/6 marta"
  - 129: "C va D assemblajlari"
  - 033 S7: "taxminan 10 foizi"
- Bu variantlarni ko'rib chiqish tavsiya etiladi.
- 011 S5 variantida "manbadan" so'zi bor. U taqiqlangan "manbada" shakli emas, lekin xohlasangiz almashtirish mumkin.
- Bitta faylni (masalan `Testlar/001.xlsx`) Excel'da ochib ko'rish tavsiya etiladi.
