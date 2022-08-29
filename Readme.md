 # روش اجرای پروژه روی لوکال 

- ابتدا پایتون را از لینک زیر دانلود کنید
```bash
https://www.python.org/
```
    
- در مراحل نصب پایتون تیک path  را بزنید. 

- پس از نصب پایتون با استفاده از دستور زیر پروژه را کلون کنید:
```bash
git clonehttps://github.com/KhjMeister/Django_virtual_class_Api.git
```

- پس از اتمام کلون دستور زیر را وارد کنید:
```bash
pip install pipenv
```
- سپس با کد زیر وارد پوشه Backend  شوید و دستور بعدی :
```bash
cd Backend
```
- سپس کدهای زیر را برای نصب ماژول های مورد نیاز بزنید:

- ابتدا :
```bash
pipenv shell
```
- سپس:
```bash
pipenv install
```
- پس از اتمام نصب ماژول ها با کد زیر وارد پوشه Config  شوید:
```bash
cd Config
```
- با کد زیر لوکال هاست را اجرا کنید: 
```bash
py manage.py runserver
```




