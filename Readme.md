 # روش اجرای پروژه روی لوکال 

- ابتدا پایتون را از لینک زیر دانلود کنید
    https://www.python.org/
- در مراحل نصب ایتون تیک path  را بزنید

- پس از نصب پایتون با استفاده از دستور زیر پروژه را کلون کنید:
    git clonehttps://github.com/KhjMeister/Django_virtual_class_Api.git

- پس از اتمام کلون دستور زیر را وارد کنید:
    pip install pipenv

- سپس با کد زیر وارد پوشه Backend  شوید و دستور بعدی :

    cd Backend
- سپس کدهای زیر را برای نصب ماژول های مورد نیاز بزنید:

- ابتدا :
    pipenv shell
- سپس:
    pipenv install
- پس از اتمام نصب ماژول ها با کد زیر وارد پوشه Config  شوید:
     
    cd Config
- با کد زیر لوکال هاست را اجرا کنید: 

    py manage.py runserver




