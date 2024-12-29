# simple-game-with-dice
This is a simple dice game where the user chooses one of the 6 dice faces and rolls three dice. If the three dice rolled match the number the user chose, their money is tripled, and if two dice match, it is doubled and one of them gets their money back.


# Explanation in English:

1. Function roll_dice:

Rolls three dice and returns their values as a list.
Uses the random.randint function to generate random numbers between 1 and 6 for each die.

2. Function play_game:

Manages the main game loop.
Displays the player's current budget and allows them to choose whether to continue playing.
Validates user input for selecting a number (1-6) and the amount to bet.
Calls the tas function to process the dice roll and update the budget.
Ends the game if the budget becomes zero or the player chooses to quit.

3. Function tas:

Handles the dice roll and calculates winnings or losses based on the player's choice and the dice results.
Matches are checked to determine if the player wins back their bet (1 match), doubles their bet (2 matches), or triples their bet (3 matches).
Updates the budget accordingly and provides feedback to the player.

4. Main Program Execution (__main__):

Greets the player and asks them to input an initial budget.
Ensures the budget is a positive number before starting the game.
If the budget is invalid, an appropriate error message is displayed.


# Türkçe Açıklamalar:

1. roll_dice Fonksiyonu:

Üç zar atar ve değerlerini bir liste olarak döndürür.
random.randint fonksiyonunu kullanarak her zar için 1 ile 6 arasında rastgele sayılar üretir.

2. play_game Fonksiyonu:

Ana oyun döngüsünü yönetir.
Oyuncunun mevcut bütçesini gösterir ve oyuna devam edip etmeyeceğini sorar.
Oyuncunun 1-6 arasında bir sayı seçmesini ve bahis miktarını girmesini doğrular.
Zar atışı yapmak ve bütçeyi güncellemek için tas fonksiyonunu çağırır.
Bütçe sıfıra ulaşırsa veya oyuncu çıkmak isterse oyunu sonlandırır.

3. tas Fonksiyonu:

Zar atışını işler ve oyuncunun seçimi ve zar sonuçlarına göre kazanç veya kayıpları hesaplar.
Eşleşmeler kontrol edilerek oyuncunun bahsini geri alması (1 eşleşme), iki kat kazanması (2 eşleşme) veya üç kat kazanması (3 eşleşme) belirlenir.
Bütçe buna göre güncellenir ve oyuncuya geri bildirim sağlanır.

4. Ana Program Çalışması (__main__):

Oyuncuyu selamlar ve başlangıç bütçesini girmesini ister.
Bütçenin pozitif bir sayı olmasını sağlar ve doğrular.
Eğer bütçe geçersizse uygun bir hata mesajı görüntüler.

# توضیحات کد به زبان فارسی:

1.تابع roll_dice:

سه تاس می‌اندازد و مقادیر آنها را به صورت یک لیست بازمی‌گرداند.
از تابع random.randint برای تولید اعداد تصادفی بین 1 تا 6 برای هر تاس استفاده می‌شود.

2. تابع play_game:

حلقه اصلی بازی را مدیریت می‌کند.
بودجه فعلی بازیکن را نمایش می‌دهد و از او می‌پرسد که آیا می‌خواهد بازی را ادامه دهد یا خیر.
ورودی بازیکن را برای انتخاب یک عدد بین 1 تا 6 و مقدار شرط بررسی می‌کند.
برای پردازش پرتاب تاس و به‌روزرسانی بودجه، تابع tas را فراخوانی می‌کند.
اگر بودجه بازیکن تمام شود یا بازیکن تصمیم به خروج بگیرد، بازی پایان می‌یابد.

3. تابع tas:

پرتاب تاس را مدیریت کرده و بر اساس انتخاب بازیکن و نتایج تاس‌ها، برد یا باخت را محاسبه می‌کند.
تعداد تطابق‌ها بررسی می‌شود:
یک تطابق: بازیکن مبلغ شرط خود را پس می‌گیرد.
دو تطابق: بازیکن دو برابر شرط خود را می‌برد.
سه تطابق: بازیکن سه برابر شرط خود را می‌برد.
بودجه بازیکن بر اساس برد یا باخت به‌روزرسانی می‌شود و پیام مناسب نمایش داده می‌شود.

4. اجرای برنامه اصلی (__main__):

بازیکن را خوش‌آمد می‌گوید و از او می‌خواهد بودجه اولیه خود را وارد کند.
مطمئن می‌شود که بودجه یک عدد مثبت است.
اگر بودجه نامعتبر باشد، پیام خطای مناسب نمایش داده می‌شود.
