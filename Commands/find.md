# دستور find

دستور `find` برای جستجوی فایل‌ها و دایرکتوری‌ها بر اساس شرایط مختلف استفاده می‌شود.

---

## مثال‌ها:

- پیدا کردن فایل با نام مشخص در دایرکتوری جاری و زیرشاخه‌ها:
```bash
find . -name "filename.txt"

Find anyfile with Extention *.log

find /var/log -type f -name "*.log"
