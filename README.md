# 虹膜识别小组

环境配置：
安装python3
导入如下python  包
Cython	0.29.13	
Keras	2.3.0	
Keras-Applications	1.0.8	
Keras-Preprocessing	1.1.0	
Markdown	3.1.1	
Pillow	6.1.0	
PyYAML	5.1.2	
Werkzeug	0.15.6	
absl-py	0.8.0	
astor	0.8.0	
cycler	0.10.0	
gast	0.3.2	
google-pasta	0.1.7	
grpcio	1.23.0	
h5py	2.10.0	
joblib	0.13.2	
kiwisolver	1.1.0	
matplotlib	3.1.1	
mobilenet-v3	0.1.4	
numpy	1.17.2	
opencv-python	4.1.1.26	
pip	19.2.3	
prefetch-generator	1.0.1	
protobuf	3.9.1	
pycocotools	2.0	
pyparsing	2.4.2	
python-dateutil	2.8.0	
scikit-learn	0.21.3	
scipy	1.3.1	
setuptools	40.8.0	
sinaweibopy3	1.3	


将数据集output.json放入data文件夹中
json格式如下

    {
        "annotations": {
            "bbox": [
                "503",
                "47",
                "276",
                "270"
            ],
            "category_id": 1
        },
        "ringID": "1320145"
    },
    {
        "annotations": {
            "category_id": 1,
            "bbox": [
                "494",
                "46",
                "281",
                "267"
            ]
        },
        "ringID": "1004721"
    },
    
    bbox表示图片中虹膜的位置的四个点坐标
    图片格式为800大小
    ringID为图片的文件名，以jpg结束
    
    
    
    
    运行：
    
    点击train文件夹中的train.py的main函数即可运行获得训练模型
