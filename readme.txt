### 4# 修改参数
   在[configs.json]中修改网络类型，lable标签（如raccoon），和其他参数 注意存放图片(train_img)和存放注释(train_ann)的文件夹名称
   ![examlpe](https://github.com/TonyZ1Min/yolo-for-k210/blob/master/cfg.png)
   
-*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- -*- 

 
### 5# 如果只有自己的样本图片(任意尺寸都可以)，还没有VOC格式的xml注释文件，可使用根目录下的[labelImg.exe]进行注释：

    先将图片放在train_img文件夹
    
    Open Dir--->选择存放图片的文件夹(train_img) 
    
    Change Save Dir--->选择存放注释文件夹(train_ann)
    
    Create RectBox--->框选要标注的物体并输入lable，和上文configs中的相同（如raccoon）
    
    Save后点下一个(Next Image)
    会自动生成标注的目标位置的xml文件保存在注释文件夹中
   