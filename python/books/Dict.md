
# 字典資料型態的運算
```
dict1 = {"A":"內向穩重", "B":"外向樂觀", "O":"堅強自信", "AB":"聰明自然"}

name = input("輸入要查詢的血型:")

blood = dict1.get(name)

if blood == None:  
    print("沒有「" + name + "」血型！")
else:  
    print(name + " 血型的個性為：" + str(dict1[name]))
```

```
dict1 = {"林小明":85, "曾山水":93, "鄭美麗":67}
name = input("輸入學生姓名：")
if name in dict1:  
    print(name + "的成績為 " + str(dict1[name]))
else:  
    score = input("輸入學生分數：")
    dict1[name] = score
    print("字典內容：" + str(dict1))
```



```
dict1={"金牌":26, "銀牌":34, "銅牌":30}

item1 = list(dict1.items())

for name, num in item1:
    print("得到的 %s 數目為 %d 面" % (name, num))
```

```
dict1={"金牌":26, "銀牌":34, "銅牌":30}

item1 = list(dict1.items())

for name, num in item1:
    print("得到的 %s 數目為 %d 面" % (name, num+100))
```


```
dict1={"金牌":26, "銀牌":34, "銅牌":30}
listkey = list(dict1.keys())
listkey
```

```
dict1={"金牌":26, "銀牌":34, "銅牌":30}
listvalue = list(dict1.values())
listvalue
```

```
dict1={"金牌":26, "銀牌":34, "銅牌":30}
listkey = list(dict1.keys())
listvalue = list(dict1.values())
for i in range(len(listkey)):
    print("得到的 %s 數目為 %d 面" % (listkey[i], listvalue[i]))
```

# 物件導向程式設計:類別(class)與物件()

```
class Animal():      #定義類別  
    def __init__(self, name,age):
        self.name = name  #定義屬性 
        self.age = age
        print("正在產生物件")
        print(self.name + str(self.age) + "歲，很會唱歌!")
    def sing(self):       #定義方法        
        print(self.name + str(self.age) + "歲，很會唱歌!")  
    def grow(self,year):  #定義方法        
        self.age += year     
        
bird = Animal("鸚鵡",1) #以 Animal 類別，建立一個名叫鸚鵡、1歲大的 bird物件
bird.grow(11)     #長大1歲
bird.sing()      #鸚鵡2歲，很會唱歌!
```

```
class Animal():      #定義類別  
    def __init__(self, name,age):
        self.name = name  #定義屬性 
        self.age = age
        print("正在產生物件")
        print(self.name + str(self.age) + "歲，很會唱歌!")
    def sing(self):       #定義方法        
        print(self.name + str(self.age) + "歲，很會唱歌!")  
    def grow(self,year):  #定義方法        
        self.age += year     
        
bird = Animal("鸚鵡",1) #以 Animal 類別，建立一個名叫鸚鵡、1歲大的 bird物件
bird.grow(11)     #長大1歲
bird.sing()      #鸚鵡2歲，很會唱歌!

dog = Animal("狗狗",111) 
dog.grow(11)     
dog.sing() 

```
