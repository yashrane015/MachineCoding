数据遍历

1. 遍历每个文件夹中的子文件
2. 如果是文件夹，则回到步骤1
3. 如果是文件，则取.py结尾的文件
4. 读文件，按照"\n\n\n"分割，遍历每部分
5. 如果包含"def"和“class”，则取出
6. 如果不在100 - 500则移除