# Qanday qilib kompyuter fanini mustaqil o'rganish mumkin?

_Ushbu usul ingliz tilidan [Mansur Isakov](https://github.com/MansurIsakov) tomonidan tarjima qilingan. Original [Oz Nova](https://twitter.com/oznova_) va [Myles Byrne](https://twitter.com/quackingduck) tomonidan yaratilgan va https://teachyourselfcs.com/ havolasi orqali mavjud.\_

Agar siz o'zingiz dasturlashni o'rgangan bo'lsangiz yoki yaqinda bootcampdan o'tgan bo'lsangiz, keyingi qadamingiz kasbni o'rganish va kompyuter fanini o'rganishdir. Hozirgi kunda kompyuter fanlari bo'yicha eng yaxshi universitetlar darajasida ta'lim olish mumkin, bunga yillar va boylik sarflamasdan💸.

Bizda aql bovar qilmaydigan miqdordagi turli xil manbalardan foydalanish imkoniyati mavjud, ammo ba'zilari boshqalarga qaraganda yaxshiroqdir. Sizga "200+ bepul onlayn kurslar" ruhidagi boshqa ro'yxat kerak emas. Sizga kerak bo'lgan hamma narsa ikkita savolga javob beradi:

- **Qanday fanlarni** o'rganishim kerak va nima uchun?
- Ushbu fanlarni o'rganish uchun eng yaxshi **kitob yoki video ma'ruza kursi** nima?

Ushbu qo'llanma sizga ushbu savollarga javob topishga yordam beradi.

## Qisqacha aytganda:

Ushbu to'qqizta mavzuni ular ko'rsatilgan tartibda ko'rib chiqing. Tavsiya etilgan kitob yoki video ma'ruzalar kursidan foydalaning, yaxshisi ikkalasi ham. Ularning har birini o'rganish uchun 100-200 soat vaqt ajrating va martaba o'sishi bilan kerakli vaqtga qayting 🚀 .

| Mavzu                                                                 | Nima uchun o'rganish kerak?                                                                                                                               | Eng yaxshi kitob                                        | Eng yaxshi videolar               |
| --------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | --------------------------------- |
| **[Dasturlash](#dasturlash)**                                         | Rekursiya darajasidagi biror narsani "to'liq tushunmaydigan" odam bo'lmaslik uchun.                                                                       | _Structure and Interpretation of Computer Programs_     | Brian Harvey’s Berkeley CS 61A    |
| **[Kompyuter arxitekturasi](#kompyuter-arxitekturasi)**               | Kompyuter qanday ishlashini bilmasangiz, kod bilan nima qilish va qilmaslik haqidagi tushunchangiz yuzaki bo'ladi.                                        | _Computer Organization and Design_                      | Berkeley CS 61C                   |
| **[Algoritmlar va ma'lumotlar tuzilmalari](#algoritmlar-tuzilmalar)** | Agar siz stack, navbat, yog'och, grafikalar kabi asosiy ma'lumotlar tuzilmalaridan qanday foydalanishni bilmasangiz, qiyin muammolarni hal qila olmaysiz. | _The Algorithm Design Manual_                           | Steven Skiena’s lectures          |
| **[CS uchun matematika](#matematika-cs-uchun)**                       | CS asosan amaliy matematikaning tarmoqlaridan biridir. Shuning uchun matematikani bilish sizga katta ustunlik beradi.                                     | _Mathematics for Computer Science_                      | Tom Leighton’s MIT 6.042J         |
| **[Operatsion tizimlar](#operatsion-tizimlar)**                       | Siz yozgan kodning aksariyati OS tomonidan bajariladi. Shuning uchun, siz OS va kodning o'zaro ta'sirini bilishingiz kerak.                               | _Operating Systems: Three Easy Pieces_                  | Berkeley CS 162                   |
| **[Kompyuter tarmoqlari](#kompyuter-tarmoqlari)**                     | Internet hamma joyda: uning potentsialidan 100% foydalanish uchun qanday ishlashini bilib oling.                                                          | _Computer Networking: A Top-Down Approach_              | Stanford CS 144                   |
| **[Ma'lumotlar bazalari](#ma'lumotlar-bazalari)**                     | Ma'lumotlar ko'pgina dasturlarning asosidir, ammo faqat tanlanganlar ma'lumotlar bazasi tizimlari aslida qanday ishlashini tushunishadi.                  | _Readings in Database Systems_                          | Joe Hellerstein’s Berkeley CS 186 |
| **[Tillar va kompilyatorlar](#tillar-va-kompilyatorlar)**             | Agar tillar va kompilyatorlar qanday ishlashini tushunsangiz, yaxshiroq kod yozishingiz va yangi tillarni yanada samarali o'rganishingiz mumkin.          | _Compilers: Principles, Techniques and Tools_           | Alex Aiken’s course on Lagunita   |
| **[Taqsimlangan tizimlar](#taqsimlangan-tizimlar)**                   | Bugungi kunda _ko'pgina_ tizimlar taqsimlangan tizimlardir.                                                                                               | _Distributed Systems, 3rd Edition by Maarten van Steen_ | MIT 6.824                         |

## Bu hali ham ko'pdek tuyuladimi?

Agar ushbu to'qqiz mavzuni bir necha yil davomida mustaqil ravishda o'rganish g'oyasi umuman yoqimsiz bo'lib tuyulsa, biz ikkita kitobga e'tibor qaratishni taklif qilamiz: _Kompyuter tizimlari: dasturchi qarashi_ va _Yuqori yuklangan ilovalar_ (_Designing Data-Intensive Applications_). Bizning tajribamizga ko'ra, bu ikkita kitob, ayniqsa, tarmoq ilovalari bilan ishlaydigan va mustaqil ravishda yoki bootcampda dasturlashni o'rganganlar uchun vaqtingizni sarflash uchun juda mos keladi. Ular, shuningdek, yuqoridagi boshqa mavzular va manbalarni yaxshiroq tushunish uchun boshlang'ich nuqta bo'lib xizmat qilishi mumkin.

## Nima uchun kompyuter fanini o'rganish kerak?

<img align="left" width="500" src="https://teachyourselfcs.com/bilotta-tweet.png">

> Dunyoda har kuni 20 milliardga yaqin SMS-xabarlar yuboriladi. WhatsApp har kuni 42 milliard yukga duch keladi, shtatda 57 dasturchi bor. [pic.twitter.com/zZrtSIzhlR](https://t.co/zZrtSIzhlR)
>
> — Benedikt Evans (@BenedictEvans) [2 февраля 2016](https://twitter.com/BenedictEvans/status/694342874729545729)

Dasturchilar ikki turga bo'linadi: mavzu sohasining nozik tomonlarini tushunadigan va murakkab innovatsion ishlarni qila oladiganlar va bir nechta yuqori darajadagi ramkalar va tulalar bilan tanish bo'lganlar va shunchaki maxsus bilimlarni talab qilmaydigan ishlarni bajaradiganlar.

Ularning barchasi o'zlarini dasturchi deb atashadi va dastlabki bosqichlarda taxminan bir xil maosh olishadi. Ammo vaqt o'tishi bilan birinchi tur yanada murakkab, to'liq va yuqori maoshli ishlarga o'tadi. Masalan, ular menejmentga kirishadi va kompaniya ichida katta ta'sirga ega bo'lishadi, ochiq manbali loyihalarni amalga oshiradilar, timlidlarga aylanadilar yoki kodni salqin yozadilar.

Birinchi turdagi dasturchilar kompyuter fanlari bo'yicha chuqur bilimga ega-ular buni universitetda o'qish yoki uzluksiz o'z-o'zini tarbiyalash, uyqusiz tunlarni kitoblar bilan o'tkazish orqali olganmi, muhim emas. Dasturchilarning ikkinchi turi, odatda, ular asoslangan nazariyani emas, balki o'ziga xos vositalar va texnologiyalarni o'rganadigan yuzaki bilimlarga ega. Ular shunchaki yangi va yangi ko'nikmalarni rivojlantirmoqdalar, chunki u yoki bu texnologiya to'satdan ko'proq talab qilinadigan va ommabop bo'lib qoladi.

Hozirgi vaqtda ko'proq odamlar IT sohasiga kirib bormoqda, shu bilan birga kompyuter fanlari dasturlari bitiruvchilari soni deyarli bir xil bo'lib qolmoqda. Shunday qilib, sanoatda ikkinchi turdagi odamlar tobora ko'payib bormoqda, bu esa ularga yaxshi va qiziqarli ish topishni qiyinlashtirmoqda. Nihoyat o'zingizni birinchi turga kiritishingiz uchun bilimingizni oshirishni xohlaysizmi yoki shunchaki ish beruvchilar uchun ko'proq talabga ega bo'lishni va o'zingizni yanada ishonchli his qilishni xohlaysizmi, muhim emas, kompyuter fanlarini o'rganish sizga kerak bo'lgan narsadir.

Kompyuter fanlari bo'yicha bakalavr dasturlarining aksariyati dasturlashga "kirish" bilan boshlanadi. Ushbu kurslarning eng yaxshisi nafaqat yangi boshlanuvchilar uchun, balki muhim nazariy tushunchalarni o'rganish bosqichini o'tkazib yuborib, avval kodlashni o'rganganlar uchun ham muhimdir.

Bunday materialni o'rganish uchun odatda klassik kitob tavsiya etiladi _Kompyuter dasturlarining tuzilishi va talqini_ (_Structure and Interpretation of Computer Programs_) va MIT tomonidan shu nomdagi ma'ruzalar kursi. Va [kitob](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html), va [kurs](https://ocw.mit.edu/courses/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video_galleries/video-lectures/)
internetda mutlaqo bepul (ingliz tilida) mavjud. Biz bu ma'ruzalarni juda yaxshi ko'ramiz, lekin ularning o'rniga [Brayan Xarvi ma'ruza kursini](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter) olishni taklif qilamiz - Berkli universitetining 61a kursining yozuvi. Bizning fikrimizcha, ulardagi ma'lumotlar batafsilroq tahlil qilinadi va yangi boshlanuvchilar uchun ularni idrok etish osonroq bo'ladi.

Biz kitobning kamida uchta bobidan o'tishni tavsiya etamiz _Kompyuter dasturlarining tuzilishi va talqini_ va ular uchun mashqlarni bajaring. Bunga qo'shimcha ravishda, siz [exercism](http://exercism.io/) da vazifalarni hal qilishingiz mumkin.

Ushbu qo'llanma birinchi marta 2016-da nashr etilganligi sababli, bizdan tez-tez jon Deneroning 61a kursining yangi versiyasini va ularga mos keladigan _[Composing Programs](https://composingprograms.com/)_ kitobini tavsiya etamizmi, deb so'rashadi, unda asosiy dasturlash tili Python hisoblanadi. Bizning fikrimizcha, Denero kursi ham juda yomon emas va ba'zi talabalar bundan ham ko'proq zavqlanishadi. Ammo biz hali ham kitobdan boshlashni maslahat beramiz _Kompyuter dasturlarining tuzilishi va talqini_ va Brayan Xarvi kursi. Biz ushbu manbalar noyob ekanligiga ishonamiz va ular kompyuterlar va dasturlash haqidagi fikringizni tubdan o'zgartirishi mumkin. Albatta, ular hamma uchun mos emas. Kimdir kitobni yoqtirmaydi, ko'pchilik birinchi sahifalardan tashqariga chiqmaydi. Ammo bu kitob katta salohiyatga ega va uni o'qishga arziydi.

Agar _Kompyuter dasturlarining tuzilishi va talqini_ hali ham yoqmasa, _Composing Programs_ - ni sinab ko'ring. Agar siz yana bu narsa emasligini his qilsangiz, harakat qilib ko'ring _[How to Design Programs](http://www.htdp.org/)_. Agar ularning barchasi juda murakkab bo'lib tuyulsa, ularni bir muddat chetga surib, boshqa mavzularga o'tishga harakat qiling va bir-ikki yil ichida ularga qaytib boring.

Ushbu qo'llanma dasturlash haqida hech narsa bilmaydiganlar uchun yaratilmaganligini aniqlashtirmoqchimiz. Bu ko'proq kompyuter fanlarida rasmiy ma'lumotga ega bo'lmagan va nazariy asosga ega bo'lmagan tajribali dasturchilarga qaratilgan. Biz har doim intilish uchun joy borligini eslatish uchun qo'llanmamizga dasturlash bo'limini kiritdik. Ehtimol, bu kitoblar sizning bilimingizdagi bo'shliqlarni to'ldirishga yordam beradi. Agar siz ilgari hech qachon dasturlashtirmagan bo'lsangiz, lekin chindan ham o'rganishni xohlasangiz, avval [bu](https://www.reddit.com/r/learnprogramming/wiki/faq#wiki_getting_started) kabi qo'llanmani sinab ko'rishingiz kerak.

## Mavzular bo'yicha ko'rsatmalar

### Dasturlash

<img align="left" width="200" src="https://teachyourselfcs.com/sicp.jpg">

Kompyuter fanlari bo'yicha bakalavr dasturlarining aksariyati dasturlashga "kirish" bilan boshlanadi. Ushbu kurslarning eng yaxshisi nafaqat yangi boshlanuvchilar uchun, balki muhim nazariy tushunchalarni o'rganish bosqichini o'tkazib yuborib, avval kodlashni o'rganganlar uchun ham muhimdir.

Bunday materialni o'rganish uchun odatda klassik kitob tavsiya etiladi _Kompyuter dasturlarining tuzilishi va talqini_ (_Structure and Interpretation of Computer Programs_) va MIT tomonidan shu nomdagi ma'ruzalar kursi. Va [kitob](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html), va [kurs](https://ocw.mit.edu/courses/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video_galleries/video-lectures/)
internetda mutlaqo bepul (ingliz tilida) mavjud. Biz bu ma'ruzalarni juda yaxshi ko'ramiz, lekin ularning o'rniga [Brayan Xarvi ma'ruza kursini](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter) olishni taklif qilamiz Berkli universitetining 61a kursining yozuvi. Bizning fikrimizcha, ulardagi ma'lumotlar batafsilroq tahlil qilinadi va yangi boshlanuvchilar uchun ularni idrok etish osonroq bo'ladi.

Biz kitobning kamida uchta bobidan o'tishni tavsiya etamiz _Kompyuter dasturlarining tuzilishi va talqini_ va ular uchun mashqlarni bajaring. Bunga qo'shimcha ravishda, siz [exercism](http://exercism.io/) da vazifalarni hal qilishingiz mumkin.

Ushbu qo'llanma birinchi marta 2016-da nashr etilganligi sababli, bizdan tez-tez jon Deneroning 61a kursining yangi versiyasini va ularga mos keladigan _[Composing Programs](https://composingprograms.com/)_ kitobini tavsiya etamizmi, deb so'rashadi, unda asosiy dasturlash tili Python hisoblanadi. Bizning fikrimizcha, Denero kursi ham juda yomon emas va ba'zi talabalar bundan ham ko'proq zavqlanishadi. Ammo biz hali ham kitobdan boshlashni maslahat beramiz _Kompyuter dasturlarining tuzilishi va talqini_ va Brayan Xarvi kursi. Biz ushbu manbalar noyob ekanligiga ishonamiz va ular kompyuterlar va dasturlash haqidagi fikringizni tubdan o'zgartirishi mumkin. Albatta, ular hamma uchun mos emas. Kimdir kitobni yoqtirmaydi, ko'pchilik birinchi sahifalardan tashqariga chiqmaydi. Ammo bu kitob katta salohiyatga ega va uni o'qishga arziydi.

Agar _Kompyuter dasturlarining tuzilishi va talqini_ hali ham yoqmasa, _Composing Programs_ - ni sinab ko'ring. Agar siz yana bu narsa emasligini his qilsangiz, _[How to Design Programs](http://www.htdp.org/)_ harakat qilib ko'ring. agar ularning barchasi juda murakkab bo'lib tuyulsa, ularni bir muddat chetga surib, boshqa mavzularga o'tishga harakat qiling va bir-ikki yil ichida ularga qaytib boring.

Ushbu qo'llanma dasturlash haqida hech narsa bilmaydiganlar uchun yaratilmaganligini aniqlashtirmoqchimiz. Bu ko'proq kompyuter fanlarida rasmiy ma'lumotga ega bo'lmagan va nazariy asosga ega bo'lmagan tajribali dasturchilarga qaratilgan. Biz har doim intilish uchun joy borligini eslatish uchun qo'llanmamizga dasturlash bo'limini kiritdik. Ehtimol, bu kitoblar sizning bilimingizdagi bo'shliqlarni to'ldirishga yordam beradi. Agar siz ilgari hech qachon dasturlashtirmagan bo'lsangiz, lekin chindan ham o'rganishni xohlasangiz, avval [bu](https://www.reddit.com/r/learnprogramming/wiki/faq#wiki_getting_started) kabi qo'llanmani sinab ko'rishingiz kerak.

### Kompyuter arxitekturasi

<img align="left" width="200" src="https://teachyourselfcs.com/csapp.jpg">

> "Hardware" - bu platforma.
>
> — Mayk Actopn, Engine Director в Insomniac Games ([uning CppCon nutqini tomosha qiling](https://www.youtube.com/watch?v=rX0ItVEVjHc))

Kompyuter arxitekturasi (kompyuter tizimlari, kompyuterni tashkil qilish) juda muhim mavzu. Arxitektura bilimlari sizga chuqur qarashga va dasturiy ta'minot orqasida nima borligini bilib olishga imkon beradi. Biz CS-da rasmiy ma'lumotga ega bo'lmagan ko'plab dasturchilar ushbu mavzudan qunt bilan qochishlarini payqadik.

Yangi boshlanuvchilar uchun tavsiya qilishimiz mumkin bo'lgan manbalar _Kompyuter tizimlari: arxitektura va dasturlash. Dasturchining ko'rinishi_ (_[Computer Systems: A Programmer's Perspective](http://csapp.cs.cmu.edu/3e/home.html)_) va [kurs](http://csapp.cs.cmu.edu/3e/courses.html) kompyuter arxitekturasi bo'yicha, ushbu kitobga asoslanib, 1-6-boblarning ko'p qismini qamrab oladi.

Ushbu kitob mavzuni o'rganishga amaliy yondashuvi tufayli yaxshi. Kompyuter arxitekturasida ushbu kitob qamrab olmaydigan juda ko'p nozikliklar mavjud-hamma narsani qoplash mumkin emas. Ammo u yanada samarali kod yozishni boshlash va yaxshiroq dasturiy ta'minot yaratish uchun zarur bilimlarni beradi.

Materialni sekinroq sur'atda o'rganishni afzal ko'rgan, shuningdek, apparat va dasturiy ta'minotga teng darajada qiziqadiganlar uchun biz kitobni tavsiya qilamiz _Hisoblash tizimlarining Elementlari_ (_The Elements of Computing Systems_). U "Nand2Tetris"nomi bilan ham tanilgan. Ushbu kitob kompyuter qanday ishlashi haqida to'liq ma'lumot beradi. Har bir bob HDL - da eng oddiy mantiqni yozishdan tortib CPU va assembler bilan ishlashgacha bo'lgan katta tizimning bir qismini-Tetris o'yinini loyihalashga qaratilgan.

Sizga kitobning dastlabki olti bobini o'qib, loyihani bajarishingizni maslahat beramiz. Bu sizga "demir" ning o'zaro ta'sirini va kompyuterning arxitekturasi dasturiy ta'minotga qanday ta'sir qilishini tushunishga yordam beradi.

Kitobning birinchi yarmi va barcha loyihalar [Nand2Tetris](http://www.nand2tetris.org/) saytida bepul mavjud. Shuningdek, ushbu kitobda [Coursera](https://www.coursera.org/learn/build-a-computer).

Kitobni tushunish juda oson, garchi u ham apparat, ham dasturiy ta'minotni qamrab oladi. Bu uni o'qib bo'lgandan keyin to'liqlik hissi beradi. Afsuski, kitob bir nechta juda muhim tushunchalarni qamrab olmaydi-xotira ierarxiyasi va hisoblash quvuri.

Agar siz Nand2Tetris bilan yaxshi tanish bo'lsangiz, _Kompyuter tizimlari: arxitektura va dasturlash kitobiga qaytishni tavsiya qilamiz. Dasturchi qarash_ yoki allaqachon klassik kitobni o'qishga harakat qiling _Kompyuter arxitekturasi va kompyuter tizimlarini loyihalash_ Patterson va Hennesi (_[Computer Organization and Design](https://smile.amazon.com/Computer-Organization-Design-Fifth-Architecture/dp/0124077269)_). Ushbu kitobning ba'zi boblarini o'tkazib yuborish mumkin, bu juda batafsil; biz [CS61C course](http://inst.eecs.berkeley.edu/~cs61c/sp15/) Berkli universiteti tomonidan muayyan mavzularni o'rganish uchun. Ma'ruza yozuvlari va laboratoriya yozuvlari internetda mavjud va ma'ruzalarning eski versiyalarini [arxiv](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_) da topish mumkin.

### Algoritmlar va ma'lumotlar tuzilmalari

<img align="left" width="200" src="https://teachyourselfcs.com/skiena.jpg">

<img align="left" width="200" src="https://m.media-amazon.com/images/I/41w52FCezEL.jpg">

> Men tavsiya qiladigan yagona usul - yozishdan oldin o'ylab ko'ring.
>
> — Richard Xemming

Algoritmlar va ma'lumotlar tuzilmalarini bilish kompyuter fanlari sohasidagi ta'limdagi muvaffaqiyatning kalitidir, degan fikr bor. Bu, shuningdek, muammolarni hal qilish ko'nikmalarimizni o'rgatish uchun yaxshi vosita bo'lib, boshqa sohalarni o'rganishda katta yordam beradi.

Algoritm kitoblari - yuzlablar. Bizning sevimlimiz - _Algoritmlar. Ishlab chiqish uchun qo'llanma_ Stephen Skiena (_[The Algorithm Design Manual](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/)_. Murakkab muammolarni hal qilish - uning jazbiyati, shuning uchun u o'z talabalarni va o'qituvchilarini ham tortib olib ketishiga muvaffaq bo'ladi. Biz _Algoritmlar. Qurish va tahlil_ Korman va _Algoritmlar. Ishlab chiqish uchun qo'llanma_ Sedjvikning juda ko'p dalili va nazariy qismatlarni o'z ichiga oladi, shuning uchun amaliy algoritm va ma'lumotlar tuzilmalarini o'rganishni maqsad qilganlar uchun ancha qo'llanmaydi deb o'ylaymiz.

Video ma'ruzalarni afzal ko'rganlar uchun Stiven Skienada [YouTube-da joylashtirilgan ma'ruza kursi](https://www.youtube.com/watch?v=A2bFN3MyNDA&list=PLOtl7M3yp-DX32N0fVIyvn7ipWKNGmwpp) ham mavjud. Shuningdek, bizga [Coursera-da](https://www.coursera.org/specializations/algorithms) mavjud bo'lgan va [bu yerda](http://timroughgarden.org/videos.html) Tim Rafgarden kursi juda yoqadi. Shunday qilib, juda ko'p materiallar mavjud, siz faqat birini tanlashingiz kerak, bu sizga ko'proq mos keladi. Aslida, hozirda biz bu erda ko'rsatmagan juda ko'p manbalar mavjud. Agar biron bir foydali narsani topsangiz, unda to'xtashni tavsiya etamiz, bu shaxsiy imtiyozlar masalasidir!

Mashq qilish uchun biz [Leetcode](https://leetcode.com/) maslahat beramiz. Mumkin bo'lgan echimlar misollari va qaysi biri yaxshiroq ekanligi haqida munozaralar bilan ahamiyatsiz muammolar mavjud. Leetcode-dagi muammolarni hal qilish, shuningdek, Google kabi yirik kompaniyalar bilan suhbatga tayyorgarlik ko'rishda katta yordam beradi, chunki ular shunga o'xshash narsalarni so'rashni juda yaxshi ko'radilar. Algoritmlar va ma'lumotlar tuzilmalaridan samarali foydalanishni o'rganish uchun 100 ga yaqin tasodifiy vazifalarni hal qilishni tavsiya etamiz.

Va nihoyat, biz _[How to Solve It](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/)_ qo'llanmasini tavsiya qilamiz; bu CS amaliyoti va matematikaga mos keladigan ajoyib qo'llanma.

### CS uchun matematika

> Odamlar matematikaning qanchalik sodda ekanligini ko'rmaydilar, chunki ular hayot qanchalik murakkabligini anglamaydilar.
>
> — Jon fon Neyman

Bir ma'noda, kompyuter fanlari amaliy matematikaning bir qismidir. Ko'pgina dasturchilar buni e'tiborsiz qoldirishga harakat qilishadi, lekin biz uni o'z dasturimizga qo'shishni talab qilamiz. Bu buni qilmaganlarga nisbatan shubhasiz ustunlik beradi.

Kompyuter fanlari uchun matematikaning eng tegishli sohasi diskret matematikadir. "Diskret" - "uzluksiz" ning antonimi va diskret matematika, asosan, deb nomlangan intizomga kirmagan qiziqarli amaliy mavzular to'plamidir matematik tahlil. Ushbu mavzularning to'liq spektrini qamrab olishga urinmang-bu intizom juda ko'p kichik bo'limlarga ega. Keyinchalik aniq maqsad mantiqni, kombinatorikani va ehtimollikni, to'plamlar nazariyasini, grafikalar nazariyasini kuchaytirish va kriptografiyada keng qo'llaniladigan raqamlar nazariyasini biroz o'rganishdir. O'rganishga arziydigan matematikaning yana bir sohasi-bu chiziqli algebra. Bu kompyuter grafikasi va mashinani o'rganish usullari bilan ishlash uchun juda muhimdir.

Diskret matematikani o'rganishni [Laslo Lovasning ma'ruza matnlari](http://www.cs.elte.hu/~lovasz/dmbook.ps) dan boshlashni maslahat beramiz. Professor Lovasning ma'ruzalarini tushunish juda oson va intuitiv, shuning uchun ular hududni o'rganish uchun juda mos keladi.

Keyinchalik rivojlangan o'quvchilar uchun biz kitobni maslahat beramiz _Kompyuter fanlari uchun matematika_ (_[Mathematics for Computer Science](https://courses.csail.mit.edu/6.042/spring17/mcs.pdf)_) - MIT kursining shu nomli ma'ruzalari alohida kitobga to'plangan. [Video ma'ruzalar](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/) kurslar ham bepul mavjud va biz ularni diskret matematikani o'rganish uchun tavsiya qilamiz.

Chiziqli algebrani o'rganishni [Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) video seriyasidan boshlashni maslahat beramiz, keyin [Gilbert Strangning kitobi](https://www.amazon.com/Introduction-Linear-Algebra-Gilbert-Strang/dp/0980232775/) ga o'ting va [MIT-dan video ma'ruzalar](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/).

### Operatsion tizimlar

<img align="left" width="200" src="https://teachyourselfcs.com/ostep.jpeg">

Operatsion tizimlar bo'yicha ikkita klassik kitob - _[Operating System Concepts](https://www.amazon.com/dp/1118063333/) _ va _Zamonaviy operatsion tizimlar_ Tanenbaum (_[Modern Operating Systems](https://www.amazon.com/dp/013359162X/)_). Ushbu ikkala kitob ham chalkashligi va haddan tashqari murakkabligi uchun tanqid qilinadi, ular o'rtacha talaba uchun juda mos emas.

Yaxshi alternativ - _Operating Systems: Three Easy Pieces_, u [bepul mavjud](http://pages.cs.wisc.edu/~remzi/OSTEP/) ingliz tilida. Bizga, ayniqsa, kitobning tuzilishi va uni o'qish qulayligi yoqadi. Ushbu kitobdagi mashqlar, albatta, ularga vaqt ajratishga arziydi.

Ushbu kitobdan so'ng, "Arxitektura {OS nomi}" kabi darsliklardan foydalanib, alohida OS qurilmasini o'rganishni maslahat beramiz. Masalan, _[Lion's Commentary on Unix](https://www.amazon.com/Lions-Commentary-Unix-John/dp/1573980137/)_, _[The Design and Implementation of The FreeBSD Operating System](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972/)_, _[Mac OS X Internals](https://www.amazon.com/Mac-OS-Internals-Systems-Approach/dp/0321278542/)_. Linuxni o'rganish uchun biz Robert Lavning ajoyib kitobiga e'tibor berishni taklif qilamiz [Linux Kernel Development](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468).

Olingan bilimlarni mustahkamlashning ajoyib usuli - bu kichik yadro kodini o'qish va u erda o'zingizning xususiyatlaringizni qo'shish. Masalan, siz OS bilan tajriba o'tkazishingiz mumkin [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html), ANSI C-da Unix v6 modeli bo'yicha yozilgan va x86-da ishlaydi. Ushbu OS MIT kurslaridan biri uchun qo'llab-quvvatlanadi. _operating Systems: Three Easy Pieces_ kitobida [xv6 uchun laboratoriya](http://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf), bu erda siz potentsial loyihalar uchun ko'plab foydali g'oyalarni ko'rib chiqishingiz mumkin.

### Kompyuter tarmoqlari

<img align="left" width="200" src="https://teachyourselfcs.com/top-down.jpg">

> Biz kelajakni billur sharda ko'ra olmaymiz. Kelajak interneti uning jamiyati qiladigan narsa bo'ladi.
>
> — Bob Kan

Kompyuter tarmoqlari CS-ning eng muhim sohalaridan biridir, chunki dasturiy ta'minotni ishlab chiqishning aksariyati veb-saytga va shunga mos ravishda mijoz-server arxitekturasiga ta'sir qiladi. Kompyuter tarmoqlarini mustaqil ravishda o'rgangan talabalarimiz nihoyat ularni yillar davomida o'rab turgan atamalar, tushunchalar va protokollarni tushunishga muvaffaq bo'lganliklarini tan olishdi.

Ushbu mavzu bo'yicha bizning sevimli kitobimiz _[Computer Networking: A Top-Down Approach](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)_. Kitobda yaxshi loyihalar va mashqlar mavjud va ayniqsa biz [bular](http://www-net.cs.umass.edu/wireshark-labs/)ni tavsiya qilamiz internetda mavjud bo'lgan laboratoriya.

Video ma'ruzalardan o'rganishni afzal ko'rganlar uchun biz Stenford kursini sinab ko'rishni maslahat beramiz [_Introduction to Computer Networking_](https://www.youtube.com/playlist?list=PLvFG2xYBrYAQCyz4Wx3NPoYJOFjvU7g2Z), ilgari Stenfordning rasmiy ochiq kursi sifatida mavjud bo'lgan, ammo hozirda Afsuski, uni faqat YouTube-da norasmiy pleylist sifatida topish mumkin.

### Ma'lumotlar bazalari

<img align="left" width="200" src="https://teachyourselfcs.com/redbook.jpg">

<img align="left" width="200" src="https://teachyourselfcs.com/data-reality.jpg">

Ma'lumotlar bazalari o'z-o'zini o'rganish uchun eng qiyin va vaqtni talab qiladigan mavzulardan biridir. Bu soha nisbatan yangi-1970-yillardan keyin paydo bo'ldi. Shunday qilib, kompaniyalar uchun ma'lumotlar bazasi materiallari erkin foydalanish uchun foydali emas. Bundan tashqari, ushbu mavzu bo'yicha yaxshi darsliklar yozishi mumkin bo'lgan ko'plab potentsial mualliflar katta kompaniyalarda ishlashni afzal ko'rishgan yoki umuman o'z kompaniyalarini tashkil etishgan.

Shunday qilib, biz ushbu sohani mustaqil ravishda o'rganishni istaganlarga darsliklardan qochishni va Djo Xellerstaynning ma'lumotlar bazasi kursini yozishni boshlashni maslahat beramiz [Berkli universiteti CS 186](https://www.youtube.com/user/CS186Berkeley/videos) va keyin ushbu mavzu bo'yicha maqolalarni o'rganishga o'ting.

Ushbu sohada yangi boshlanuvchilar uchun eslatib o'tish kerak bo'lgan maqolalardan biri "[Architecture of a Database System](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf)". Bu yaxshi, chunki u relyatsion ma'lumotlar bazasini boshqarish tizimlari qanday ishlashi haqida umumiy tushunchalarni beradi. Bu keyingi mashg'ulotlar uchun ajoyib asos bo'lib xizmat qiladi.

_Readings in Database Systems_, ko'proq ["Qizil kitob"](http://www.redbook.io/) nomi bilan tanilgan - Piter Baylis, Jo Xellersteyn va Maykl Stounbraker tomonidan to'plangan va tahrirlangan maqolalar to'plami. CS 186 kursini yaxshi o'rganganlar uchun qizil kitob keyingi qadamdir.

Agar siz hali ham ushbu sohani o'rganish uchun darslikdan foydalanishni afzal ko'rsangiz, biz ko'rib chiqishni taklif qilamiz _[Database Management Systems](https://smile.amazon.com/Database-Management-Systems-Raghu-Ramakrishnan/dp/0072465638/)_. Agar siz yanada rivojlangan darajaga o'tishni istasangiz, jim Greyning klassik kitobiga e'tibor berishingiz kerak _[Transaction Processing: Concepts and Techniques](https://www.amazon.com/Transaction-Processing-Concepts-Techniques-Management/dp/1558601902)_.

Shuni ham ta'kidlashni istardimki, ma'lumotlarni modellashtirish ma'lumotlar bazalari bilan ishlashning ko'pincha e'tibordan chetda qoladigan va uni o'rganishga etarlicha e'tibor bermaydigan jihati. Biz ushbu mavzu bo'yicha o'qishni taklif qiladigan kitob _[Data and Reality: A Timeless Perspective on Perceiving and Management Information in Our Imprecise World](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215)_.

### Tillar va kompilyatorlar

<img align="left" width="200" src="https://teachyourselfcs.com/dragon.jpg">

> Formulali dasturchi bo'lmang. Foydalanuvchilar va boshqa dasturchilar uchun mahsulotlar yarating. To'qimachilik va metallurgiya sanoatini eslang: mashinalar yaratish yoki boshqarishni xohlaysizmi?
>
> — Kompilyator kursining boshlanishi Bodik irqi

Ko'pgina dasturchilar dasturlash tillarini o'rganadilar, CS bilan shug'ullanadiganlarning aksariyati tillar qanday ishlashini va ular nimaga asoslanganligini o'rganadilar. Bu ularga dasturlashda ham katta ustunlik beradi! Ularning bilimlari ko'chma; ular yangi til qanday ishlashini aniq tillarni o'rganganlarga qaraganda tezroq va chuqurroq tushunishlari mumkin.

Yangi boshlanuvchilar uchun sizga Bob Nistromni _[Crafting Interpreters](https://craftinginterpreters.com/contents.html)_ ni o'qishni maslahat beramiz. Matn yaxshi o'ralgan, o'qish juda qiziqarli va maqsadi ular foydalanadigan tillar va vositalar qanday ishlashini yaxshiroq tushunadiganlar uchun mos keladi. Sizga butun matnni ishlab chiqishingizni va u erda joylashgan vazifalarni ("challenges") echishga harakat qilishingizni maslahat beramiz.

Odatda Kompilyatorlarni o'rganish uchun _Kompilyatorlar kitobi tavsiya etiladi: prinsiplar, texnologiyalar va vositalar_ (_[Compilers: Principles, Techniques & Tools](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)_), u "ajdaho bilan kitob"nomi bilan ham tanilgan. Afsuski, bu o'z-o'zini o'rganish uchun juda mos emas. Bu o'qituvchilar uchun kurslar uchun bir necha semestrlik mavzularni tanlash uchun juda yaxshi.

Agar siz hali ham "ajdaho bilan kitob" dan foydalanishga qaror qilsangiz, unda undan ma'lum mavzularni tanlash yaxshidir. Agar ustozingiz yoki o'qituvchingiz sizga yordam bersa yaxshi bo'ladi. Biz tavsiya qilamizushbu kitobdan ko'proq video ma'ruzalarga qo'shimcha sifatida foydalaning. Masalan, [Aleks Aikenning edX-dagi ma'ruzalariga](https://www.edx.org/course/compilers).

### Taqsimlangan tizimlar

<img align="left" width="200" src="https://teachyourselfcs.com/ddia.jpg">

So'nggi yillarda kompyuterlar soni juda ko'paydi. Agar ilgari korxonalar tobora kuchayib borayotgan protsessorlarni sotib olishgan bo'lsa, endi hatto eng kichik dasturlar ham odatda bir nechta mashinalarda ishlaydi, ya'ni taqsimlangan. Tarqatilgan tizimlar-bu qanday tashkil etilishi mumkinligi haqidagi fan.

O'z-o'zini o'rganish uchun biz Martin Kleppmanning _[Designing Data-Intensive Applications](https://smile.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable-ebook/dp/B06XPJML5D/)_ tavsiya etamiz. Ushbu kitob ushbu sohadagi klassik darsliklardan farq qiladi: uni o'qish oson va olingan bilimlarni amalda qo'llashni istaganlar uchun yaratilgan. Shu bilan birga, kitob juda chuqur fundamental bilimlarni beradi.

Klassikani afzal ko'rganlar uchun biz maslahat beramiz _Tarmoqli tizimlar. Tanenbaum tamoyillari va paradigmalari_ ([Distributed Systems, 3rd Edition](https://www.distributed-systems.net/index.php/books/ds3/)\*). u ingliz tilida bepul onlayn mavjud.

Video ma'ruzalarni afzal ko'rganlar uchun ajoyib kurs - [MIT-dan 6.824-kurs](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB), Robert Moris tomonidan o'qilgan. Qo'shimcha materiallar [bu erda](https://pdos.csail.mit.edu/6.824/schedule.html) mavjud.

Tarqatilgan tizimlarni o'rganish uchun darslik yoki boshqa manbalardan foydalanishingiz muhim emas, maqolalarni o'qish ham majburiydir. Maqolalarning yaxshi ro'yxatini [bu erda](http://dsrg.pdos.csail.mit.edu/papers/) topish mumkin. Shuningdek, biz sizga [Papers we Love](http://paperswelove.org/) resursiga tashrif buyurishingizni maslahat beramiz.

## Savol-Javob

### Ushbu qo'llanmaning maqsadli auditoriyasi qanday?

Ushbu qo'llanma siz uchun, agar siz o'zingiz kodlashni o'rgangan bo'lsangiz, siz bootkamp bitiruvchisiz yoki o'rta maktabda o'qiyotgan bo'lsangiz va dasturlashni yaxshi ko'rsangiz. Shuningdek, qo'llanma dasturlashni o'rganayotgan talabalar uchun qo'shimcha material sifatida mos keladi. Qaysi bosqichda o'rganishni boshlash yaxshiroq-tanlov sizniki. Ammo biz nazariyani o'rganishdan oldin dasturlash bo'yicha tajribaga ega bo'lish yaxshiroq deb o'ylaymiz. Masalan, biz talabalar ma'lumotlar bazasi nazariyasini o'rganishga tayyor ekanliklarini payqadik, agar ular ilgari amalda duch kelgan bo'lsa. Va allaqachon web bilan bog'liq loyihada ishlagan talabalar kompyuter tarmoqlarini o'rganishga ko'proq intilishadi.

### AI / grafika / boshqa-ba'zi mavzular haqida nima deyish mumkin?

Biz bilishi kerak bo'lgan mavzular ro'yxatini tuzishga harakat qildik _Har bir dasturchi amaliyotchisi_, u qaysi mutaxassislik yoki sohada bo'lishidan qat'i nazar. Bizning tajribamizga ko'ra, bu erda to'plangan mavzularni o'rganish, kompyuter fanlari bo'yicha rasmiy ma'lumotga ega bo'lmagan holda ushbu sohaga kelgan dasturchilarning ko'pchiligiga katta foyda keltiradi. Ushbu mavzularni o'rganib chiqib, siz allaqachon aniqroq sohalarni o'rganib, yo'lingizni davom ettirish uchun poydevor qurasiz. Bundan tashqari, ularni o'rganib chiqqandan so'ng, mustaqil ravishda darsliklar va maqolalarni tanlash, boshqa mavzularni o'rganish osonroq bo'ladi. Biroq, biz "elektrchilar"sifatida tavsiya qilmoqchi bo'lgan bir nechta foydali manbalar:

- Sun'iy intellektni o'rganish uchun: video va loyihalar (Pacman projects) [Ai kirish kursi](http://ai.berkeley.edu/) Berkli universiteti. Darslik sifatida siz _san'iy intellektni olishingiz mumkin: Rassel va Novigning zamonaviy yondashuvi_ (_Artificial Intelligence: A Modern Approach_) olishingiz mumkin.
- Mashinani o'rganish uchun: [Endryu Ng kursi Coursera](https://www.coursera.org/learn/machine-learning?utm_source=gg&utm_medium=sem&utm_content=07-StanfordML-ROW&campaignid=2070742271&adgroupid=75329549926&device=c&keyword=how%20to%20apply%20machine%20learning&matchtype=b&network=g&devicemodel=&adpostion=&creativeid=369041663210&hide_mobile_promo&gclid=Cj0KCQjwyJn5BRDrARIsADZ9ykGtN4ncKEOckGaTNXz8h53J2twaqUPFci8e5wP3qiB_qJ9jsrMV-Q8aAifeEALw_wcB). Chuqurroq o'rganish kabi yanada murakkab va shov-shuvli mavzularga o'tishdan oldin barcha asoslarni yaxshi tushunganingizga ishonch hosil qiling.
- Kompyuter grafikasi uchun: kursdan o'ting [CS 184 Berkli](http://inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html) va darslik sifatida foydalaning [Computer Graphics: Principles and Practice](https://www.amazon.com/Computer-Graphics-Principles-Practice-3rd/dp/0321399528).

### Kurslarni o'tkazish tartibi qanchalik muhim?

Umuman olganda, ushbu fanlarning barchasi ma'lum darajada bir-biriga mos keladi va bir-biriga murojaat qiladi. Masalan, diskret matematika va algoritmlarni olaylik: matematikani o'rganish algoritmlarni tahlil qilish va yaxshiroq tushunishga yordam beradi, algoritmlarni o'rganish esa matematikani tushunishga turtki beradi. Ideal holda, karerangizda har bir mavzuga bir necha marta qaytganingiz ma'qul.

Shunday qilib, bizning qo'llanmamizda taklif qilingan tartib sizga yordam berishi kerak _Bir narsani boshlash_... agar siz ushbu mavzularni boshqa tartibda o'rganish siz uchun samaraliroq bo'ladi deb hisoblasangiz, buni qilishga harakat qiling. Operatsion tizimlar va ma'lumotlar bazalarini o'rganishdan oldin kompyuter arxitekturasi bilan tanishishingiz, tarqatilgan tizimlarni boshlashdan oldin kompyuter tarmoqlari va operatsion tizimlarini bilishingiz muhim deb o'ylaymiz.

### Ushbu qo'llanma Open Source Society va freeCodeCamp dasturidan nimasi bilan farq qiladi?

Ushbu qo'llanma 2016 yilda yaratilgan. O'sha paytda [Open Source Society](https://github.com/open-source-society/computer-science) qo'llanma juda ko'p fanlarni o'z ichiga olgan, o'rganish uchun taklif qilingan ba'zi resurslar kam edi, bundan tashqari, unda o'rganish uchun taklif qilingan jihatlar va kurslarni tanlash asoslanmagan. Biz o'z qo'llanmamizda faqat ixtisoslashuvidan qat'i nazar, har bir dasturchi bilishi kerak bo'lgan resurslarni to'plashga harakat qildik. Bundan tashqari, biz tanlovimizni asoslashga va bu erda keltirilgan manbalarning har biri nima uchun kerakligini tushunishga harakat qildik. Vaqt o'tishi bilan Open Source Society qo'llanmasi yaxshilandi, ammo biz hali ham qo'llanmamiz yanada tushunarli va yaxlit dasturni taklif qilishiga ishonamiz.

FreeCodeCamp - ning asosiy yo'nalishi kompyuter fanlari emas, balki dasturlashdir. Nima uchun kompyuter fanlarini aniq o'rganishingiz kerakligi haqidagi tushuntirishni [yuqorida](dasturlash) topish mumkin. Ammo, agar siz dasturlashda yangi bo'lsangiz, avval freeCodeCamp-dan o'tishni maslahat beramiz va bir-ikki yil ichida bizning qo'llanmamizga qaytamiz.

### X tili haqida nima deyish mumkin?

Muayyan dasturlash tilini o'rganish va kompyuter fanlari sohasini o'rganish butunlay boshqacha narsadir. Tilni o'rganish ancha oson va bu bilim unchalik ahamiyatli emas. Agar siz allaqachon bir nechta tillarni bilsangiz, bizning qo'llanmamizga amal qilishni maslahat beramiz va yangi tillarni ushbu mavzularni o'rganib chiqqandan keyin yoki undan keyin bilib oling. Agar siz dasturlashni yaxshi bilsangiz (masalan, kompyuter dasturlarining tuzilishi va talqinini yaxshi bilsangiz) va ayniqsa, agar siz allaqachon kompilyatorlarni o'rgangan bo'lsangiz, yangi til asoslarini o'rganish bir necha kundan ko'proq vaqtni talab qilmaydi. Va kutubxonalar, asboblar, ecosystemalarni yo'lda o'zlashtirish mumkin.

### Hamma gapiradigan X texnologiyasi haqida nima deyish mumkin?

Mavjud texnologiyalarning hech biri muhim emas, shuning uchun uni asos sifatida o'rganish kerak. Boshqa tomondan, siz yangi narsalarni o'rganishga undaganingiz juda yaxshi. Ammo hiyla-nayrang birinchi navbatda texnologiya asoslangan tushunchalarni yaxshi tushunishdir. Bu uning qanday ishlashini yaxshiroq tushunishga imkon beradi.

### Nima uchun kitobni tavsiya qilasiz _Kompyuter dasturlarining tuzilishi va talqini_, tushunish qiyin bo'lsa ham?

Uni o'qishga harakat qilib koring. Ko'pchilik bu kitobdan miyalar eriydi, deyishadi-siz bunday xususiyatni tez-tez eshitmaysiz. Agar siz kirmasangiz, har doim boshqa narsani sinab ko'rishingiz va keyinroq unga qaytishingiz mumkin.

### Nega "ajdaho kitobini" tavsiya qilasiz?

Ushbu kitob kompilyatorlar haqida hamma narsani o'z ichiga oladi, bu kitob qolganlardan ko'ra yaxshiroq maydonni qamrab oladi. Bu ko'pincha yomon rapga ega, chunki hozirgi zamonda unchalik dolzarb bo'lmagan ba'zi mavzularga juda ko'p e'tibor qaratilmoqda. Bunday misollardan biri tahlil qilishdir. Biroq, hech kim bu kitobni boshidan oxirigacha o'qish kerakligini aytmagan. Uning asosiy maqsadi o'qituvchiga uning asosida kursni shakllantirish uchun etarli material berishdir. Shunday qilib, o'z-o'zini o'rganadiganlar kitobdagi materialni juda tanlab o'rganishlari mumkin. Bundan ham yaxshiroq - jamoat mulki bo'lgan kurslarni asos qilib oling. Ularda material tanlovi allaqachon tajribali o'qituvchi tomonidan qilingan.

### Qanday qilib bir tonna pul sarflamasdan kitoblar va darsliklarga kirish mumkin?

Biz taklif qilgan ko'plab kitoblar ingliz tilida bepul onlayn mavjud. Bunday saxiylik uchun mualliflarga rahmat! Agar kitob bepul bo'lmasa, ikkinchi qo'l nusxalarini sotib olishni maslahat beramiz. Odatda kitoblar bir necha marta qayta nashr etiladi va eski versiyalari ham yaxshi ishlaydi. Yangi versiyaning avvalgilariga qaraganda 10 baravar yaxshiroq bo'lish ehtimoli juda past, garchi u odatda ancha qimmatga tushsa ham.

### Ushbu qo'llanmani kim yaratgan?

Ushbu qo'llanmaning birinchi versiyasi [Oz Nova](https://twitter.com/oznova_) tomonidan yaratilgan va [Myles Byrne](https://twitter.com/quackingduck), 2020 yilda u oz tomonidan yangilandi. Qo'llanma San - Frantsiskodagi kichik oflayn guruhlarda va internetda mingdan ortiq Bootcamp bitiruvchilari va rasmiy ma'lumotga ega bo'lmagan dasturchilar uchun kompyuter fanlarini o'qitish tajribamizga asoslanadi. Biz barcha talabalarimizga fidbek uchun minnatdorchilik bildiramiz.

Ishonchimiz komilki, etarli vaqt va xohish bilan siz biz yozgan hamma narsani o'zingiz o'rganishingiz mumkin. Ammo agar siz o'qituvchi sizni boshqaradigan intensiv, tuzilgan dasturni afzal ko'rsangiz, bizning [CS intensiv](https://bradfieldcs.com/csi/) sinab ko'ring. Biz sizga magistraturaga borishingizni [tavsiya qilmaymiz](https://ozwrites.com/masters/).

Ushbu qo'llanmaning yangilanishlari va kompyuter texnologiyalari sohasidagi yangiliklar va manbalarni kuzatib borish uchun [teachyourselfcs](https://teachyourselfcs.com/) sahifasidagi mailing sheet-ga obuna bo'ling.
