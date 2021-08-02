# Typora

* <font size="4">**نحوه نصب:**</font>

  Typora را میتوان از مسیر زیر نصب نمود:

  بسته به سیستم عامل میتوان فایل exe برنامه را از سایت آن به صورت رایگان دانلود کرد و سپس با اجرای آن برنامه را نصب نمود.

* <font size="4">**نحوه نصب پوسته :**</font>

  برای نصب پوسته فارسی فایل آن را به پسوند *.CSS* از سایتهایی مانند *GitHub* دانلود نموده و سپس در مسیر زیر فایل را قرار میدهیم. پوسته از طریق آیکون **Themes** در دسترس خواهد بود:

  > <div dir="ltr" style="float: left">
  >     File>>Preferences>>Appearance>>Theme Folder
  > </div>

* <font size="4">**نحوه خروجی گرفتن از Typora :**</font>

  برای گرفتن خروجی از Typora مسیر زیر را دنبال میکنیم و سپس فرمت مورد نظر را انتخاب مینماییم:

  > <div dir="ltr" style="float: left;background-color: light;">
  >     File>>Export
  > </div>



# Markdown

* <font size="4">**Markdown چیست:**</font>

  <p style="text-align: justify;">Markdown در سال 2004 با این ایده که بتواند خواندن و نوشتن یک متن تحت وب را برای همه آسان کند و قابل تبدیل به خانواده HTML هم باشد به وجود آمد. از Markdown به عنوان یک استاندارد متن نویسی یاد می‌شود و بزرگترین مزیت این استاندارد استفاده از حروف ساده و کوتاه برای اهداف نگارشی (از جمله پررنگ کردن متن و .... ) می‌باشد. به عنوان مثال برای پررنگ کردن متن با استفاده از Markdown، کافی است کلمه را بین دو ستاره (*) قرار دهیم.</p>

  <p style="text-align: justify;">Markdown از دو بخش تشکیل شده است: بخش اول ویرایشگر متنی که نوشته را گرفته و استانداردسازی می‌کند و بخش دوم تبدیل‌کننده‌ای به زبان پرل (PERL) است که نتیجه را به HTML تبدیل می‌کند.</p>

  <p style="text-align: justify;">سایت هایی مانند GitHub ، Bitbucket ، Reddit ، Diaspora ، Stack Exchange ، OpenStreetMap و SourceForge از انواع Markdown برای نگارش آسان و سریع کاربران استفاده می‌کنند.</p>

  * **مزایا:**
    1. از Markdown میتوان برای خیلی از موارد استفاده نمود از جمله: وبسایت، ایمیل، پیامک، انواع فرمتها، کتاب و ...
    2. پرتابل هست و فایل آن با هر اپلیکیشینی قابل خواندن است.
    3. وابسته به پلتفرمی نیست.
    4. اگر اپلیکیشینی که اکنون در حال استفاده از آن هستیم متوقف شود و دیگر کار نکند، فایل Markdown رو میتوانیم با اپلیکیشن دیگری بدون مشکل باز کرده و کار را ادامه دهیم.
    5. استفاده گسترده ای از آن میشود و رایج است. مانند وبسایتهای *Reddit*  و *GitHub* که Markdown را ساپورت می کنند.
    6. یادگیری آسانی دارد.

  * **معایب Markdown در نوشتن برخی موارد و یا ویرایش خودکار متن و ... است که شاید بتواند آن را با استفاده از برخی شخصی سازیها و یا استفاده از برخی ویرایشگرها برطرف نمود.**

* **نحوه کار با Markdown:**

  برای کار با Markdown با از syntax آن استفاده نمود. و همچنین میتواند از ویژگیهای فرمتهای مختلف مثل CSS و Html نیز استفاده کرد. مثلا با قرار دادن متن داخل ** ** متن ما **bold** میشود و یا با قرار دادن متن داخل * * متن ما *italic* میگردد.



# Git

* **چیستی و چرایی git:**

  <p style="text-align: justify;">گیت یک نوع سیستم کنترل ورژن (VCS) است که با آن میتوان تغییران اعمال شده در فایل ها را ساده تر پیگیری کرد و به اشتراک گذاشت. گیت برای هماهنگ کردن وظایف میانِ اشخاصِ مختلفی که، روی یک پروژه کار می‌کنند، مفید است. هم‌چنین می‌توان با ذخیره‌ی “Checkpoint” پیشرفتِ پروژه را در طی زمان بررسی کرد. </p>

* **نحوه ساخت repository:**

  <p style="text-align: justify;">  برای ساخت یک repository  ابتدا داخل سایت Host، گیت هاب یک اکانت میسازیم و در سایت از مسیر زیر اقدام به ساخت یک repo جدید مینماییم: </p>

  > <div dir="ltr" style="float: left;background-color: light;">
  >     GitHub>>Profile>>Repositories>>New(public)
  > </div>

  سپس پس از نصب گیت در سیستم خود، به مسیر فایل مورد نظرمان رفته و با دستور *.git init*  و config  به مسیر repository جدید مان وصل میشویم و اکنون میتوانیم کار با repository را شروع کنیم.

  

* **دستورات ابتدایی git:**

  <div dir="ltr" style="float: left;background-color: light;"><b>Create a new create a new repository on the command line: </b></div>
  
  <div dir="ltr" style="float: left;background-color: light;">
      git init
  </div>

<div dir="ltr" style="float: left;background-color: light;">
 	git add README.md
</div>

<div dir="ltr" style="float: left;background-color: light;">
 git commit -m "first commit"
</div>

<div dir="ltr" style="float: left;background-color: light;">
 git branch -M main
</div>

<div dir="ltr" style="float: left;background-color: light;">
 git remote add origin https://github.com/MohammadMahdiKarimKhani1998/test1.git
</div>

<div dir="ltr" style="float: left;background-color: light;">
 git push -u origin main
</div>

<div dir="ltr" style="float: left;background-color: light;">
 git config --global user.name "Your User Name"
</div>

<div dir="ltr" style="float: left;background-color: light;">
 git config --global user.email "Your Email"
</div>





# Typora

* <font size="4">**نحوه نصب:**</font>

  Typora را میتوان از مسیر زیر نصب نمود:

  بسته به سیستم عامل میتوان فایل exe برنامه را از سایت آن به صورت رایگان دانلود کرد و سپس با اجرای آن برنامه را نصب نمود.

* <font size="4">**نحوه نصب پوسته :**</font>

  برای نصب پوسته فارسی فایل آن را به پسوند *.CSS* از سایت هایی مانند *GitHub* دانلود نموده و سپس در مسیر زیر فایل را قرار میدهیم. پوسته از طریق ایکون **Themes** در دسترس خواهد بود:

  > <div dir="ltr" style="float: left">
  >  File>>Preferences>>Appearance>>Theme Folder
  > </div>

* <font size="4">**نحوه خروجی گرفتن از Typora :**</font>

  برای گرفتن خروجی از Typora مسیر زیر را دنبال میکنیم و سپس فرمت مورد نظر را انتخاب مینماییم:

  > <div dir="ltr" style="float: left;background-color: light;">
  >  File>>Export
  > </div>



# Markdown

* <font size="4">**Markdown چیست:**</font>

  <p style="text-align: justify;">Markdown در سال 2004 با این ایده که بتواند خواندن و نوشتن یک متن تحت وب را برای همه آسان کند و قابل تبدیل به خانواده HTML هم باشد به وجود آمد. از Markdown به عنوان یک استاندارد متن نویسی یاد می‌شود و بزرگترین مزیت این استاندارد استفاده از حروف ساده و کوتاه برای اهداف نگارشی (از جمله پررنگ کردن متن و .... ) می‌باشد. به عنوان مثال برای پررنگ کردن متن با استفاده از Markdown، کافی است کلمه را بین دو ستاره (*) قرار دهیم.</p>

  <p style="text-align: justify;">Markdown از دو بخش تشکیل شده است: بخش اول ویرایشگر متنی که نوشته را گرفته و استانداردسازی می‌کند و بخش دوم تبدیل‌کننده‌ای به زبان پرل (PERL) است که نتیجه را به HTML تبدیل می‌کند.</p>

  <p style="text-align: justify;">سایت هایی مانند GitHub ، Bitbucket ، Reddit ، Diaspora ، Stack Exchange ، OpenStreetMap و SourceForge از انواع Markdown برای نگارش آسان و سریع کاربران استفاده می‌کنند.</p>

  * **مزایا:**
    1. از Markdown میتوان برای خیلی از موارد استفاده نمود از جمله: وبسایت، ایمیل، پیامک، انواع فرمتها، کتاب و ...
    2. پرتابل هست و فایل آن با هر اپلیکیشینی قابل خواندن است.
    3. وابسته به پلتفرمی نیست.
    4. اگر اپلیکیشینی که اکنون در حال استفاده از آن هستیم متوقف شود و دیگر کار نکند، فایل Markdown رو میتوانیم با اپلیکیشن دیگری بدون مشکل باز کرده و کار را ادامه دهیم.
    5. استفاده گسترده ای از آن میشود و رایج است. مانند وبسایتهای *Reddit*  و *GitHub* که Markdown را ساپورت می کنند.
    6. یادگیری آسانی دارد.

  * **معایب Markdown در نوشتن برخی موارد و یا ویرایش خودکار متن و ... است که شاید بتواند آن را با استفاده از برخی شخصی سازیها و یا استفاده از برخی ویرایشگرها برطرف نمود.**

* **نحوه کار با Markdown:**

  برای کار با Markdown با از syntax آن استفاده نمود. و همچنین میتواند از ویژگیهای فرمتهای مختلف مثل CSS و Html نیز استفاده کرد. مثلا با قرار دادن متن داخل ** ** متن ما **bold** میشود و یا با قرار دادن متن داخل * * متن ما *italic* میگردد.



# Git

* **چیستی و چرایی git:**

  <p style="text-align: justify;">گیت یک نوع سیستم کنترل ورژن (VCS) است که با آن میتوان تغییران اعمال شده در فایل ها را ساده تر پیگیری کرد و به اشتراک گذاشت. گیت برای هماهنگ کردن وظایف میانِ اشخاصِ مختلفی که، روی یک پروژه کار می‌کنند، مفید است. هم‌چنین می‌توان با ذخیره‌ی “Checkpoint” پیشرفتِ پروژه را در طی زمان بررسی کرد. </p>

* **نحوه ساخت repository:**

  <p style="text-align: justify;">  برای ساخت یک repository  ابتدا داخل سایت Host، گیت هاب یک اکانت میسازیم و در سایت از مسیر زیر اقدام به ساخت یک repo جدید مینماییم: </p>

  > <div dir="ltr" style="float: left;background-color: light;">
  >  GitHub>>Profile>>Repositories>>New(public)
  > </div>

  سپس پس از نصب گیت در سیستم خود، به مسیر فایل مورد نظرمان رفته و با دستور *.git init*  و config  به مسیر repository جدید مان وصل میشویم و اکنون میتوانیم کار با repository را شروع کنیم.

  

* **دستورات ابتدایی git:**

  <div dir="ltr" style="float: left;background-color: light;"><b>Create a new create a new repository on the command line: </b></div>

  <div dir="ltr" style="float: left;background-color: light;">
      git init
  </div>

<div dir="ltr" style="float: left;background-color: light;">
 	git add README.md
</div>

<div dir="ltr" style="float: left;background-color: light;">
 git commit -m "first commit"
</div>

<div dir="ltr" style="float: left;background-color: light;">
 git branch -M main
</div>

<div dir="ltr" style="float: left;background-color: light;">
 git remote add origin https://github.com/MohammadMahdiKarimKhani1998/test1.git
</div>

<div dir="ltr" style="float: left;background-color: light;">
 git push -u origin main
</div>

<div dir="ltr" style="float: left;background-color: light;">
 git config --global user.name "Your User Name"
</div>

<div dir="ltr" style="float: left;background-color: light;">
 git config --global user.email "Your Email"
</div>





<div dir="ltr" style="float: left;background-color: light;"><b>Change url:</b></div>

<div dir="ltr" style="float: left;background-color: light;">
    git remove -v
</div>

<div dir="ltr" style="float: left;background-color: light;">
    git remote set-url origin YOUR NEW URL
</div>
