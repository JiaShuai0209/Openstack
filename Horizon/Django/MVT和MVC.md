## MVC设计模式  
Model-View-Controller 模型-视图-控制器  
* M： 数据处理，Model，主要封装对数据库层的访问，对数据库中的数据进行增、删、改、查操作。
* V： 界面显示，view，负责显示model层的数据。
* C： 逻辑处理，Controller，用于接收请求，处理业务逻辑，与Model和View交互，返回结果。

![MVC](https://github.com/JiaShuai0209/Openstack/blob/master/Horizon/Django/Picture/MVC.png)

## Django MVT 模式
Model-View-Template 
*M： Model, 与MVC中的M相同，负责对数据的处理
*V： View, 与MVC中的C类似，负责处理用户请求，调用M和T，响应请求
*T： Template, 模板 与MVC中的V类似，负责如何显示数据（产生html界面）
