# wecpy-tip
微信小程序坑


1:wepy中使用组件共享状态     
2:props会合并到data     
3:模板中不能调用任何方法,模板字符串也不行     
4:使用this.属性名 = 属性值 进行状态修改     
5:在异步函数中更新数据的时，必须手动调用$apply方法，才会触发脏数据检查流程的运行       
6:子组件随父组件更新，用 属性名后点sync 可以动态传值，但需要在父组件状态更新后调用$apply      

