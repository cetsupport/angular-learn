# angular-learn
Understand Angular


关键点：

使用yarn link来调试angular

1. tsconfig.json中需要修改：

    "preserveSymlinks": true,

这个主要是让tsc工作不报错

2. angular.json中需要修改：
projects->architect->build->configurations->development->
              "preserveSymlinks": true,

这部分主要是让ng build不报错

好文章：https://juejin.cn/post/7049304777791897631
