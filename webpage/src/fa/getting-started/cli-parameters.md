# پارامترهای رابط خط فرمان

شما می توانید از این پارامترها در رابط خط فرمان استفاده کنید:

| پارامتر                     | شرح                                                                                                                 |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| `--راهنمایی`                | صفحه راهنمایی را نشان می دهد                                                                                        |
| `--قابل حمل`                | برنامه را در حالت قابل حمل اجرا می کند                                                                              |
| `--پاک کردن تنظیمات `       | تنظیمات را پاک کرده و برنامه را اجرا می کند                                                                         |
| `--نسخه برداری از تنظیمات`  | روگرفتی از تنظیمات و سایر اطلاعات مربوط به برنامه و محیط را در مارک داون گیت هاب چاپ می کند و از برنامه خارج می شود |
| `--دوره <name>`       | برنامه را در یک زمینه متفاوت برای تنظیمات و پرونده های داخلی اجرا می کند                                            |
| `--پذیرفتن-نمونه های-متعدد` | به شروع نمونه های متعددی از QOwnNotes اجازه می دهد، حتی اگر در تنظیمات مجاز نباشند.                                 |

::: tip
اگر با نصب QOwnNotes به مشکل برخورد کردید، شاید بخواهید با استفاده از پارامتر `--دوره` برنامه را با تنظیمات جدید و بدون از دست دادن تنظیمات فعلی خود آغاز کنید.

```bash
QOwnNotes --تست دوره
```
:::

شما می توانید برنامه را به صورتی متفاوت با رابط خط فرمان در سیستم عامل های مختلف اجرا کنید:

| سیستم عامل         | فرمان                                                      |
| ------------------ | ---------------------------------------------------------- |
| لینوکس             | `QOwnNotes` (یا `qownnotes` اگر به صورت اسنپ نصب شده باشد) |
| سیستم عامل مکینتاش | `/Applications/QOwnNotes.app/Contents/MacOS/QOwnNotes`     |
| ویندوز             | `QOwnNotes.exe`                                            |
