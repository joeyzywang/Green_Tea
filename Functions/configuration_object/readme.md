配置对象模式(configuration object pattern) 是一种提供更整洁的API的方法

尤其在传递大量的参数并不是很方便。一个更好的办法是仅使用一个参数对象来替代所有参数，让我们将该参数对象称为conf，也就是配置的意思。

配置对角的优点在于：
不需要记住众多的参数以及其顺序
可以安全忽略可选参数
更加易于阅读和维护
更加易于添加和删除参数

而配置对象的不利之处在于：
需要记住参数名称
属性名称无法被压缩