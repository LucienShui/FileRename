# FileRename

会替换和这个脚本同一目录下所有文件名里能够匹配到的字符串（包括脚本本身）。

# 说明

使用前请修改`config.py`中的内容：

```python
banList  # 程序执行的过程中如果遇到在此列表中的文件名或文件夹名则跳过
recursive  # 是否要递归修改以当前目录为根的所有文件夹，值为`False`的话则只修改当前目录下的文件
old  # 欲修改的文件名
new  # 修改后的文件名
```

确认`config.py`无误后，将程序和配置文件放至待修改的目录中，执行`python3 rename.py`即可。
