dwz
=====

yii users who want use dwz  [dwz](j-ui.com) ui ,modify the old [yii-dwz extension](http://www.yiiframework.com/extension/dwzinterface)

user组件的配置：
----
```[php]
 'user' => array(
        // 'class' => 'RWebUser',
        // enable cookie-based authentication
        'allowAutoLogin' => true,
        // for dwz :
        'loginRequiredAjaxResponse'=> '{"statusCode":"301", "message":"会话超时了","forwardUrl":"site/login", "callbackType":"forward"}
       ',//'{"statusCode":"301", "message":"会话超时"}',
        'loginUrl'=>array('/account/account/login'),
    ),
```
