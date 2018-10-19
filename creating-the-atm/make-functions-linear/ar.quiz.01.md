^ أي واحدة من هذه الدوال لديها فقط ارجاع واحد one return statement per function ?

```
def func1(name):
	if name == 'yaser':
		return 'hello yaser'
	else
		return 'we dont know you!'
		
def func2(name):
	if name == 'yaser':
		result = 'hello yaser'
	else
		result = 'we dont know you!'
	
	return result
```

* func1

** func2

* كلاهما يستعملوا أكثر من return

* كلاهما لا يستعملوا أكثر من return

$ حاول مرة أخرى أو راجع الدرس السابق

-

^ هل لدى هذه الدالة إرجاع واحد فقط one return statement ?

```
def sum1(x):
    if x > 0:
        result = 0

        while(x > 0):
            result += x
            x -= 1

        return result
```

** صحيح

* خاطئ

$ حاول مرة أخرى أو راجع الدرس السابق

-

^ هل لدى هذه الدالة إرجاع واحد فقط one return statement ?

```
def sum2(x):
    if x < 0:
        return
    
    result = 0

    while(x > 0):
        result += x
        x -= 1

    return result
```

* صحيح

** خاطئ

$ حاول مرة أخرى أو راجع الدرس السابق