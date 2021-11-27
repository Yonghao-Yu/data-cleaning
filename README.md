# 安装依赖
```shell
pip install -r requirements.txt
```

# 代码运行方式

运行初级数据筛选：
```shell
python img_filter/img_primary_filter.py
```   
   
运行高级数据筛选：
```shell
python img_filter/img_advanced_filter.py
```   


# 注意事项

1. 图片的路径不要有中文，否则用 opencv-python 读图片的类型是 NoneType