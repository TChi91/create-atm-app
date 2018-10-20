## ما رأيك في هذا الكود؟

```
def withdraw(balance, request):
    # allowed papers: 100, 50, 10, 5, and cents
    
    if request > balance:
        print("Can't give you all this money !!")
        return balance
    
    elif request < 0:
        print("More than zero plz!")
        return balance
    
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
              
        return balance - request
    
balance = 500

balance = withdraw(balance, 275)

print(balance)
```

## أعتقد بأنك لاحظت المشكلة :wink:

المشكلة في الكود السابق هو أن الدالة تقوم بعمل return في عدة أماكن.

```
    if request > balance:
        print("Can't give you all this money !!")
        return balance
    
    elif request < 0:
        print("More than zero plz!")
        return balance
```

 مع أنه بالإمكان جعلها في نهاية الدالة فقط!
 
```
            elif request < 5:
              print("give " + str(request))
              request = 0
              
    return balance - request
```

حاول قدر الإمكان عمل return **واحدة في الدالة (في نهايتها)** لأن هذا سيساعدك كثيراً على تتبع الدالة أثناء اصلاح المشاكل.

تعرف تقنية استعمال return واحدة فقط بـ one return statement per function.