# Git

* **چیستی و چرایی git:**

  <p style="text-align: justify;">گیت یک نوع سیستم کنترل ورژن (VCS) است که با آن میتوان تغییران اعمال شده در فایل ها را ساده تر پیگیری کرد و به اشتراک گذاشت. گیت برای هماهنگ کردن وظایف میانِ اشخاصِ مختلفی که، روی یک پروژه کار می‌کنند، مفید است. هم‌چنین می‌توان با ذخیره‌ی “Checkpoint” پیشرفتِ پروژه را در طی زمان بررسی کرد. </p>

* **نحوه ساخت repository:**

  <p style="text-align: justify;">  برای ساخت یک repository  ابتدا داخل سایت Host، گیت هاب یک اکانت میسازیم و در سایت از مسیر زیر اقدام به ساخت یک repository جدید مینماییم: </p>

  > <div dir="ltr" style="float: left;background-color: light;color: darkgreen;">
  > GitHub >> Profile >> Repositories >> New(public)
  > </div>
  >
  > آدرس سایت GitHub:
  >
  > [https://github.com/]

  سپس پس از نصب گیت در سیستم خود، به مسیر فایل مورد نظرمان رفته و با دستور *.git init*  و config  به مسیر repository جدید مان وصل میشویم و اکنون میتوانیم کار با repository را شروع کنیم. (در ادامه به طور مفصل تری توضیح داده شده است.)

  

* **دستورات ابتدایی git:**

  

  <div dir="ltr" style="float: left;background-color: light;"><b>Create a new create a new repository on the command line: </b></div>

  ```jsx
  git init
  ```

  * این دستور برای ساخت یک repository جدید در محل فایل پروژه استفاده میشود. حال شما میتوانید با ادامه مراحل زیر فایل خود را به repository درون گیت هابتون انتقال دهید.

  ```jsx
  git config --global user.name "Your User Name"
  git config --global user.email "Your Email"
  ```

  ```jsx
  git remote add origin "Your repository directory(url)"
  ```

  * git remote add  یک remote  به نام origin(این نام رایج است و میتوان تغییر داد) و با url  مشخص میسازد.

  ```jsx
  git add "Your items"
  ```

  * با این دستور تغییرات فایل شما به مسیر کاری شما اضافه میگردد. اگر به جای **"Your items"** ، '.' قرار دهید کل تغییرات اعمال میگردد. مانند:

  ```jsx
  git add .
  ```

  

  ``` jsx
  git commit -m "Your comment"
  ```

  * پس از دستور add از این دستور که یکی از عملگرهای هسته گیت هست استفاده میکنیم تا تصویری از تغییرات اعمالی در خط زمانی کاری پروژه گرفته شود  و اماده انتقال و اعنال تغییرات گردد.

  ```jsx
  git push origin master
  ```

  * از این دستور برای انتقال نهایی تغییرات به repository شما استفاده شود.






<div dir="ltr" style="float: left;background-color: light;"><b>Change url:</b></div>

```jsx
git remove -v
git remote set-url origin "Your New Url"
```

