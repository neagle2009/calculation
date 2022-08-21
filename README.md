#用法:
```
usage: cal.py [-h] [-l Level] [-c Count] [-t Type] [-r int]

加减法算式生成

options:
  -h, --help            show this help message and exit
  -l Level, --level Level
                        难度控制 1: 常规(退位进位都有); 2: 困难模式, 仅退位,进位
  -c Count, --count Count
                        生成算式数目
  -t Type, --type Type  生成类型, 1: 加法; 2: 减法; 3: 加减混合;
  -r int, --range int   生成算式范围1: 一位数(TODO); 2: 两位数; 3: 三位数;
```

###1. 
format check
```
python3 -m pip install flake8 pylint

flake8 FILE
```

fix format, [format setting](https://pypi.org/project/yapf/#id1)
```
pip install yapf

# if support python2.7 
pip install futures

yapf -i FILE
```
###2. support docx
```
pip install python-docx

# docx段落设置
https://baijiahao.baidu.com/s?id=1663325988716544457
```
