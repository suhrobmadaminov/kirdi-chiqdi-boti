Telegram Guruh Boshqaruvi Boti

Umumiy ma'lumot

Bu Telegram bot bo'lib, aiogram freymvorki yordamida yaratilgan. U Telegram guruhlarida foydalanuvchilarning qo'shilish va chiqib ketish xabarlarini avtomatik ravishda o'chirish uchun mo'ljallangan. Shuningdek, bot /start va /help kabi asosiy komandalar orqali foydalanuvchilar bilan muloqot qiladi.

Xususiyatlar





Xabarlarni avtomatik o'chirish: Guruhga qo'shilish yoki chiqib ketish xabarlarini o'chiradi.



Komanda ishlovchilari:





/start: Foydalanuvchilarni kutib oladi va botni guruhga qo'shish hamda admin qilish bo'yicha ko'rsatmalar beradi.



/help: Bot komandalari va funksiyalari haqida batafsil ma'lumot beradi.



Guruh a'zolari o'zgarishi: Foydalanuvchilar guruhga qo'shilganda yoki chiqib ketganda log qaydi yuritadi.



Xatolarni boshqarish: Xabarlarni o'chirish yoki bot ishlashida yuzaga kelgan xatolarni log qilish uchun mustahkam tizim.



Asinxron ishlaydi: Pythonning asyncio moduli yordamida Telegram hodisalarini samarali boshqaradi.

Talablar





Python 3.7 yoki undan yuqori versiya



aiogram kutubxonasi (pip install aiogram)



Telegram Bot Tokeni (BotFather orqali olinadi)

O'rnatish





Repozitoriyani klonlang yoki bot skriptini yuklab oling.



Kerakli kutubxonalarni o'rnating:

pip install aiogram



Bot tokenini o'z tokeningiz bilan almashtiring:

bot = Bot(token='SIZNING_BOT_TOKENINGIZ')



Botni ishga tushiring:

python bot.py

Foydalanish





Botni Telegram guruhingizga qo'shing.



Botga xabarlarni o'chirish huquqi bilan admin maqomini bering.



Quyidagi komandalardan foydalaning:





/start: Xush kelibsiz xabarini va ko'rsatmalarni ko'rsatadi.



/help: Bot funksiyalari haqida batafsil ma'lumot beradi.



Bot avtomatik ravishda qo'shilish/chiqib ketish xabarlarini o'chiradi va tegishli faoliyatlarni log qiladi.

Kod tuzilishi





Botni ishga tushirish: Botni sozlash va aiogram orqali ishga tushirish.



Komanda ishlovchilari: /start va /help komandalari uchun maxsus funksiyalar.



Xabar ishlovchisi: Guruhga qo'shilish yoki chiqib ketish xabarlarini aniqlab, o'chiradi.



Guruh a'zolari ishlovchisi: Foydalanuvchilarning guruhdagi o'zgarishlarini (qo'shilish/chiqib ketish) log qiladi.



Asinxron boshqaruv: asyncio yordamida botni samarali ishlatish.

Log qaydlari





Bot guruhdagi har bir muhim harakatni (masalan, xabar o'chirish, foydalanuvchi qo'shilishi yoki chiqib ketishi) log fayliga yozadi.



Xatoliklar yuzaga kelsa, ular ham log qilinadi va foydalanuvchiga xabar berilmaydi.

Eslatma





Botni guruhda to'g'ri ishlashi uchun unga xabarlarni o'chirish huquqi berilishi shart.



Agar bot ishlamayotgan bo'lsa, token to'g'ri kiritilganligini va internet aloqasini tekshiring.

Litsenziya

Ushbu loyiha ochiq kodli bo'lib, foydalanuvchilar tomonidan o'zgartirilishi va qayta ishlatilishi mumkin. Litsenziya haqida qo'shimcha ma'lumot uchun loyiha fayllarini ko'rib chiqing.
