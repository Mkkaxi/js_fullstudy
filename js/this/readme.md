- this所处的词法作用域在哪里生效了，this作用域就指向哪里

- 在严格模式下，全局对象无法进行默认绑定，所以导致this只能绑定在undefined上

# 隐式绑定
当函数引用有上下文对象时，隐式绑定的规则就会把函数调用中的this绑定到这个上下文对象

# 隐式丢失
隐式绑定的函数会丢失绑定对象，它会应用默认绑定默认
函数在哪生效(执行)，该函数的this对象就指向其生效的作用域

# 显示绑定
call apply bind
如果call和apply的第一个参数写的是null，那么this指向window对象