## 面向对象版拳皇控制人物

### 1. 创建游戏对象
### 2. 使用原型创建技技能法
        1. 向后  
            改变图像  
            设置定时器每13ms left值减少5px  
        2.向前  
            同向后  
        3. 向下  
            改变图片地址  
### 3. 不放技能时
        1. 取消定时器  
        2. 改变图片为站立  
### 4. 放技能 active
        if(this.skill[keyCode]){  
            this.skill[keyCode].call(this);  
        }  
### 5. 实例化对象
        1. 键盘按下调用active()方法,松开时调用stop()方法