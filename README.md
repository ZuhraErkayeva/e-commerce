# Post API

Bu loyiha **Django** va **Django REST Framework (DRF)** yordamida yaratilgan bo‘lib, foydalanuvchilar faqat `title` (sarlavha) va `description` (ta'rif) maydonlariga ega postlarni yaratishi mumkin.  


## Xususiyatlar:
- Faqatgina `title` va `description` maydonlarini qabul qiladi.
- RESTful API standartlariga mos keladi.
- JSON formatda ma'lumotlarni qaytaradi.


## Texnologiyalar:
- **Python**: 3.8+  
- **Django**: 4.x  
- **Django REST Framework**: 3.x  


## O‘rnatish va Loyihani Ishga Tushirish:

1. **Virtual muhitni yarating va ishga tushiring:**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Windows uchun: .venv\Scripts\activate
   ```

2. **Bog‘liqliklarni o‘rnating:**
   Django va DRF’ni o‘rnating:
   ```bash
   pip install django djangorestframework
   ```

3. **Loyihaning migratsiyalarini ishga tushiring:**
   ```bash
   python manage.py migrate
   ```

4. **Lokal serverni ishga tushiring:**
   ```bash
   python manage.py runserver
   ```
