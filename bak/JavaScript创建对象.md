### Object构造函数式
``` js

```

### 对象字面量式
``` js

```

### 工厂模式
``` js
/**
 * 函数 createPerson()能够根据接受的参数来构建一个包含所有必要信息的 Person 对象。
 * 可以无数次地调用这个函数，而每次它都会返回一个包含三个属性一个方法的对象。
 * 工厂模式虽然解决了创建\多个相似对象的问题，但却没有解决对象识别的问题（即怎样知道一个对象的类型）。
 * 主要好处就是可以消除对象间的耦合，通过使用工程方法而不是new关键字。将所有实例化的代码集中在一个位置防止代码重复。
 * 工厂模式解决了重复实例化的问题 ，但还有一个问题,那就是识别问题，因为根本无法 搞清楚他们到底是哪个对象的实例。
 */
function createPerson(name, age, job) {
    var o = new Object();
    o.name = name;
    o.age = age;
    o.job = job;
    o.sayName = function() {
    　　alert(this.name);
    }
    return o;
}
var person = createPerson('Grey', 27, 'Doctor');
```

### 安全工厂模式
``` js

```

### 构造函数模式
``` js
function Person(name, age, job) {
    this.name = name;
    this.age = age;
    this.job = job;
    this.sayName = function() {
        alert(this.name);
    }
}
var person1 = new Person('Nicholas', 29, 'Software Engineer'); 
var person2 = new Person('Grey', 27, 'Doctor');
```

### 原型模式
``` js
function Person() {

}

Person.prototype.name = 'Nicholas';
Person.prototype.age = 29;
Person.prototype.job = 'Software Engineer';
Person.prototype.sayName = function(){
    alert(this.name);
}

var person1 = new Person();
person1.sayName(); // "Nicholas"
var person2 = new Person(); 
person2.sayName(); // "Nicholas" 
alert(person1.sayName == person2.sayName); //true
```

### 混合构造函数和原型模式
``` js

```

### 动态原型模式
``` js

```

### 寄生构造函数模式
``` js

```

### 稳妥构造函数模式
``` js

```
