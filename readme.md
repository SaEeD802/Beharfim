# Chat Project

این یک پروژه چت آنلاین است که با استفاده از Django و Django Rest Framework پیاده‌سازی شده است.

## راه‌اندازی پروژه

برای اجرای این پروژه، مراحل زیر را دنبال کنید:

1. **دانلود پروژه:**
    ```bash
    git clone https://github.com/SaEeD802/Beharfim.git
    cd Beharfim
    ```

2. **ایجاد محیط مجازی:**
    ```bash
    python -m venv venv
    ```

3. **فعال‌سازی محیط مجازی:**
    - در ویندوز:
        ```bash
        venv\Scripts\activate
        ```
    - در لینوکس/مک:
        ```bash
        source venv/bin/activate
        ```

4. **نصب کتابخانه‌ها:**
    ```bash
    pip install -r requirements.txt
    ```

5. **ایجاد جداول در پایگاه داده:**
    ```bash
    py manage.py makemigrations
    py manage.py migrate
    ```

6. **اجرای سرور:**
    ```bash
    py manage.py runserver
    ```

حالا پروژه شما آماده به کار است! می‌توانید به [localhost:8000](http://localhost:8000) بروید و از آن استفاده کنید.

**نکته:**
- ممکن است بخواهید تنظیمات پایگاه داده و دیگر تنظیمات را در فایل `settings.py` تغییر دهید.
- برای خروج از محیط مجازی، دستور `deactivate` را اجرا کنید.

موفق باشید!
