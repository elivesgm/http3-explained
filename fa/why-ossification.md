# استخوان‌سازی (Ossification)

اینترنت شبکه‌ای از شبکه‌هاست. در طول مسیر تجهیزاتی در جاهای مختلف بر روی اینترنت راه اندازی شده‌اند تا از کارکرد درست این شبکه‌ای از شبکه‌ها اطمینان حاصل کنند. این دستگاه‌ها، دستگاه‌هایی که در شبکه توزیع شده‌اند، همان‌هایی هستند که ما اغلب به عنوان دستگاه‌های میانی از آنها یاد می‌کنیم. دستگاه‌هایی که در جایی بین دو پایانه قرار گرفته‌اند و بخش‌های اصلی انتقال داده‌های شبکه مرسوم را تشکیل می‌دهند.

این دستگاه‌ها در خدمت اهداف مشخصی هستند اما من فکر می‌کنم که می‌توان گفت بطور کلی به دلیل آنکه شخصی فکر می‌کند آنها باید در آنجا باشند تا همه چیز درست کار کند آنجا قرار گرفته‌اند.

دستگاه‌های میانی بسته‌های IP را بین شبکه‌ها مسیریابی می‌کنند، آن‌ها ترافیک مخرب را مسدود می‌کنند، ‌عمل NAT (برگردان نشانی شبکه) را انجام می‌دهند، کارایی را بهبود می‌بخشند، برخی تلاش می‌کنند تا ترافیک در حال عبور را مورد بررسی و جاسوسی قرار دهند، و بیشتر.

برای آنکه این دستگاه‌ها وظیفه‌ خود را انجام دهند ملزم هستند تا درباره‌ی شبکه و پروتکل‌هایی که توسط آن‌ها نظارت شده و یا تغییر یافته است آگاه باشند. آنها نرم افزار را به همین هدف اجرا می‌کنند. نرم افزاری که پیاپی بروزرسانی نمی‌شود.

گرچه این‌ها اجزای متصل کننده‌ای هستند که اینترنت را در کنار هم نگاه می‌دارند معمولاً با آخرین تکنولوژی همراه نیستند. میانه‌ی شبکه معمولاً به سرعتِ لبه‌ها، کارخواه‌ها و کارگزار‌های سراسر جهان حرکت نمی‌کند. 

پروتکل‌هایی که این دستگاه‌ها ممکن است بخواهند بررسی کنند و ببینند تا که چه چیز درست هست و چه چیز خیر، چنین مشکلاتی را دارند: این دستگاه‌ها مدت‌ها قبل هنگامی که این پروتکل‌ها امکانات آن زمان را داشتند کار گذاشته شده‌اند. معرفی امکانات جدید‌تر یا تغییر در عملکرد به گونه‌ای که قبل‌تر شناخته نشده است می‌تواند خطرِ بد و یا غیرمجاز تلقی شدن توسط چنین دستگاه‌هایی به همراه داشته باشد. چنین ترافیکی می‌تواند افت یا تأخیر داشته باشد تا درجه‌ای که کاربران به راستی دیگر نخواهند از آن امکانات استفاده کنند.

چنین مشکلی را "سختی پروتکل" و یا "استخوان‌سازی پروتکل" می‌نامند.

تغییرات در TCP نیز دچار سختی می‌شوند: برخی دستگاه‌ها مابین یک کارخواه و کارگزار موارد ناشناخته‌ی جدید TCP را تشخیص می‌دهند و از آنجا که آنها نمی‌دانند این موادر چیستند چنین اتصالاتی را مسدود می‌کنند. سیستم‌ها اگر مجاز به بررسی جزئیات پروتکل‌ باشند، نحوه برخورد همیشگی آنها را یاد می‌گیرند و به مرور تغییر آنها ناممکن می‌شود. 

تنها راهِ به‌راستی مؤثر برای "مقابله" با استخوان‌سازی، این است که ارتباطات به جهت جلوگیری از دیده شدن بیشتر محتوای در حال گذر پروتکل توسط دستگاه‌های میانی تا جای ممکن رمزگذاری شوند.
