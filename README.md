# 介绍
本demo主要是扩展jquery的一些插件，主要是在工作中用 的form表单 表单验证validate  表格datagrid 封装的ajax 弹出框dialog
#安装
直接git clone 或者下载
#使用
##dialog的使用
var d1=dialog.dialog({  
        closeBar:true,  
        title:'提示',     
        content:"我是内容" ,        
        button:[        
            {   
                "buttonText":'',        
                "callback":function(){},        
                "clazz":""      
            },  
            {   
                "buttonText":'取消',      
                "callback":function(){},        
                "clazz":""      
            }   
        ]       
    }).show();
###set()方法：
    d1.set('更改的内容')
###show()方法:
    d1.show()
###clear()方法：
    d1.clear()
###hide()方法：
    d1.hide()
##_function 使用：
    _function.DX(12.33)  =>壹拾贰元叁角叁分
    _function.DateFormat(1289407948,'yyyy-MM-dd hh:mm:ss') =>  2010-11-11 00:52:28
    _function.priceFormat(10)   => 10.00
##form.js 的使用
###实例化一个jq对象
    var form=$('#form').form();
###获取表单的值
    var formData=form.getData()
###设置表单的值
    form.setData()
###提交表单
    form.submit()
###重置表单的值
    form.reset()
###清除表单的值
    form.clear()
##validate.js 的使用
###实例化
    var form=$('form1').validate()
###在表单里设置validate 自定义属性
    form.getError()
#说明
此demo主要是工作过程中用的，公用的
#感谢
感谢所有对插件有 贡献的人
