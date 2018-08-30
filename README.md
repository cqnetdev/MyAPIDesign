# 我的API构思
1、API应该具有鉴权、接口传入传出参数记录、异常处理及通用数据结构返回功能。   
2、定义AuthorizeFilter实现鉴权功能。   
3、定义HTTPActionFilter实现接口调用前后的参数记录。   
4、定义ExceptionFilter实现全局异常捕获。   
5、定义一个Result类用于数据结构定义，确保所有的Action执行完毕后的返回类型都是Result。   
