^ أي واحد من هذه هو الصنف class وأي واحد هو الكائن object ؟

```
class Person():
    def __init__(self, name, age):
        self.name = name
        self.age = age
        
yaser = Person('Yaser Alnajjar', 23)
mohammed = Person('Mohammed Alhakem', 23)
```

** Person هو class, أما yaser و mohammed هما الـ objects

* Person هو object, أما yaser و mohammed هما الـ classes

* كلهم classes

* كلهم objects

$ حاول مرة أخرى أو راجع الدرس السابق

-

^ ماهي قيمة yaser.name ؟

```
class Person():
    def __init__(self, name, age):
        self.name = name
        self.age = age
        
yaser = Person('Yaser Alnajjar', 23)
mohammed = Person('Mohammed Alhakem', 23)
```

* yaser

** Yaser Alnajjar

* Mohammed Alhakem

* mohammed

$ حاول مرة أخرى أو راجع الدرس السابق

-

^ كم يمكننا عمل objects من الـ Person class ?

```
class Person():
    def __init__(self, name, age):
        self.name = name
        self.age = age
```

** كم ما نريد

* 2

* 100

* كل الإجابات خاطئة

$ حاول مرة أخرى أو راجع الدرس السابق

-

^ هل هذا الكود سليم

```
class Person():
    def __init__(self, name, age):
        self.name = name
        self.age = age
        
p = Person()
```

* نعم, يمكننا إنشاء Person بدون تمرير أي متغيرات

** لا, يجب إنشاء ارسال المتغيرات name و age

$ حاول مرة أخرى أو راجع الدرس السابق