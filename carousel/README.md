## 纯css制作的轮播图效果

cssdemo.html为纯css制作的新闻轮播图,以下为jquery制作

### 1. 开始第一张显示其余隐藏
### 2. 定时器功能,图片循环播放
        1. 设置indexPage++,index等于ndexPage除以图片张数取余  
        2. 对应的ndexPage图片显示,其余隐藏  
        3. 对应的小圆点变色
### 3. 点击小圆点跳到对应的图
        1. 使index值等于点击小圆点的index值  
        2. 对应的ndex图片显示,其余隐藏  
        3. 对应的小圆点变色  
### 4. 左右按钮
        1. 点击左按钮indexPage减1  
        2. 对应的ndexPage图片显示,其余隐藏  
        3. 对应的小圆点变色
        4. 右按钮同理
### 5. 鼠标覆盖时关闭定时器,鼠标离开时开启定时器
