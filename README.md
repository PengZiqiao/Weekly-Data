# Weekly-Data
网尚周报与华润周报的数据部分

## Requirements
  *[Flask](https://github.com/pallets/flask)
  *[Flask-bootstrap](https://github.com/mbr/flask-bootstrap)
  *[openpyxl](http://bitbucket.org/ericgazoni/openpyxl)

## 使用步骤
### 1.创建一个Excel文件
文件名与文件位置为models.py里的常量FILE，默认是E:/weekly/static/供销价.xlsx。
### 2.创建4张sheet
分别为'商业', '办公', '住宅', '别墅',可以通过修改models.py里的常量SHEET_LIST来变更。
### 3.获取数据
路径：GIS-商品房市场-当周供销情况。
板块：不含溧水高淳。
功能：别选商业、办公、别墅，住宅的口径是住宅+别墅。
