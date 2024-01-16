## Lesson 5

1. ## Scopes

#### "Scoope" (oʻzlashtirish) funksiyasi JavaScript tilidagi bir konseptdir, bu funksiya oʻzlashtirilgan (local) oʻzgaruvchilarni, funksiya ichidagi oʻzgaruvchi va funksiyalarga oʻzlashtirishga yoʻl qoʻyadi. Bu funksiya JavaScriptning qisqa bir yozuvlash vaqtida boʻyida oʻzgaruvchilar va funksiyalar orasida koʻzlangan oʻzlashtirilgan joylar yaratishga imkon beradi.



2. ### for function
#### JavaScript tilidagi for tsikli bu biror amallarni bir nechta marta takrorlash uchun ishlatiladi. Quyidagi sintaksisni o'rganamiz:

```
for (boshlang'ich holat; shart; yangilanuvchi ifoda) {
    // Amalni bajarish
}
```
##### Bu yerni:

- boshlang'ich holat: Tsikl boshlanishida bajariladigan amallar.
- shart: Tsiklni qandayda to'xtatishni aniqlaydigan shart.
- yangilanuvchi ifoda: Har bir tsikl o'tganda bajariladigan ifoda.

### Masalan, 1 dan 5 gacha sonlarni ekranga chiqarish uchun quyidagi tsiklni ishlatamiz:

```
for (let i = 1; i <= 5; i++) {
    console.log(i);
}
```

Bu tsikl i ni 1 dan 5 gacha o'zgaruvchi bilan boshladi, har safar i ni ekranga chiqaradi, va i ni har safar bir oshiradi (i++). Tsikl i 5 dan katta yoki teng bo'lgan bo'lsa to'xtaydi (i <= 5 shart bilan).


3. ### while function

#### while — shart bajarilguncha ishlaydi. Agar shart bajarilmasa, sikl to'xtaydi va keyingi qadamdan davom etadi.

##### massalan:
```
let x = 1;

while (x <= 5) {
    console.log(x);
    x++;
}
```

#### Bu dasturni ishga tushirganda, 1 dan 5 gacha bo'lgan sonlarni chiqaringizni ko'rasiz. while sikli sharti (x <= 5) bajariladiganligicha davom etadi. Sikl ichida console.log(x) bilan x qiymatini ekranga chiqariladi va x++ orqali x o'zgaruvchisi birga oshiriladi, shuningdek har bir sikldan so'ng shart tekshiriladi. Shart bajarilmasa, sikl to'xtaydi.