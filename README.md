
Kredit Tasdiqlashni Bashoratlash loyihasi
Bu loyiha mijozlarning ma'lumotlarini tahlil qilib, kredit olish imkoniyatini bashoratlash uchun SVM (Support Vector Machine) modelidan foydalanadi.

Maqsad
Ushbu loyiha mijozlar haqidagi ma'lumotlar asosida kredit holatini (tasdiqlangan yoki rad etilgan) bashorat qilishni maqsad qiladi.

Kutubxonalarni o'rnatish
Loyiha uchun kerakli kutubxonalarni o'rnating:

bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn
Qadamlar
Ma'lumotlarni yuklash va tozalash:

NaN (bo'sh) qiymatlarni olib tashlash.
Kategoriyali qiymatlarni raqamli qiymatlarga almashtirish.
'Loan_Status' ustunini 0 va 1 ga almashtirish.
Ma'lumotlarni vizualizatsiya qilish:

Mijozlarning ta'lim darajasi va oilaviy holati asosida kreditning tasdiqlanishi va rad etilishi.
Model yaratish:

Ma'lumotlarni o'rgatish va test qilish uchun ajratish.
Support Vector Machine (SVM) modeli yordamida o'qitish.
Aniqlikni baholash:

O'qitish va test ma'lumotlari bo'yicha modelning aniqligini hisoblash.
Natijalar
O'qitish aniqligi: Model o'qitish ma'lumotlari asosida 78-80% aniqlik ko'rsatadi.
Test aniqligi: Test ma'lumotlari asosida 76-79% aniqlik.
Foydalanish
Loyihani ishga tushirish uchun ma'lumotlarni yuklab olib, kodni ishlating.
