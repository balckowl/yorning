# yorning

## 作成物概要
条件文を書くとYesまたはNoで返すYesNo関数、YESまたはNOで返す関数が使えるpythonライブラリを作りました。

## 作成動機
* pipでインストールできるライブラリを作りたかった。
* 競技プログラミングで使えるライブラリを作成したかった。

## 使用技術
* Python

## インストール方法
```
pip install yorning
```

## 使用方法
```python
import yorning

a = 5
yorning.YesNo(a>1)
#Yes
yorning.YesNo(a<1)
#No

yorning.YESNO(a>1)
#YES
yorning.YESNO(a<1)
#NO
```
