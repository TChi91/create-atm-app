## كود المهمة السابقة

```
# allowed papers: 100, 50, 10, 5, and cents

balance = 500
request = 275

if request > balance:
    print("Can't give you all this money !!")

elif request < 0:
    print("More than zero plz!")

else:
    while request > 0:

        if request >= 100:
            request -= 100
            print("give 100")

        elif request >= 50:
            request -= 50
            print("give 50")

        elif request >= 10:
            request -= 10
            print("give 10")

        elif request >= 5:
            request -= 5
            print("give 5")

        elif request < 5:
            print("give " + str(request))
            request = 0
```

### شكل الكود في حال استخدمنا الدوال


```
def withdraw(balance, request):
    # your function here

balance = 500

balance = withdraw(balance, 277)
balance = withdraw(balance, 30)
balance = withdraw(balance, 5)
balance = withdraw(balance, 500)
```

## ماهي المهمة المطلوبة؟

* قم بكتابة دالة withdraw, بناء على الكود السابق الموجود بالأعلى.
* الدالة أولاً ستقوم بطباعة الرصيد balance.
* بعدها ستقوم بنفس الخوارزمية في الكود السابق (سحب الأموال بالشكل الذي شرحنا في الورشة السابقة).
* تقوم الدالة بإرجاع الرصيد balance بعد خصمه من الطلب request.

## كيفية تجربة الأكواد ؟

قبل أن تشارك حلك, قم بالتأكد بأن الكود **يعمل أمامك** في PyCharm أو VSCode أو أي برنامج آخر.

## كيف تقوم بمشاركة الحلول ؟

بإمكانك مشاركة الحلول في مجتمع كورتابز على هذا الرابط:

<a href="https://forums.coretabs.net/t/مشاركة-حلول-تجنب-النسخ-واللصق-باسخدام-الدوال/1159" style="display: block; width: 200px; background-color: #5355e8; background-image:linear-gradient(to left, #2d43e7, #9042e8); color:#fff; padding: 10px; margin: 30px auto; border-radius:100px; text-decoration: none; font-size: 18px; text-align: center;">مشاركة الحل</a>