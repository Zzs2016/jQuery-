# jQuery-
对事件委托delegate的实际使用；
因jQuery入口函数的执行在DOM元素执行完毕后就完成，因此登陆弹出框不会被监听到；
使用$("body").delegate("span","click",function(){ });将新弹出的DOM事件监听委托给body完成。
