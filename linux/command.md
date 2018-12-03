# 命令

## cd

切换目录

> cd [dirName]

### 实例

```bash
cd / # 切换到根目录
cd ~ # 切换到用户主目录
cd .. # 切换到父级目录
```

## ls

列出当前目录下的文件及目录

> ls [-alrtAFR][name...]

### 参数

- -a 显示所有文件及目录 (以"."开头的  视为隐藏文件不会列出)
- -A 同 -a ，但不列出 "." (当前目录) 及 ".." (父目录)
- -l 列出详情
- -F 在列出的文件名称后加一符号；例如可执行档则加 "\*", 目录则加 "/"
- -R 列出所有子目录
- -r 倒序
- -t 按修改时间排序
- -S 按文件大小排序

### 实例

列出当前目录下所有名称以 s 开头的文件，按创建时间倒序 :

```bash
ls -ltr s*
```

## mkdir

用来创建目录

> mkdir [-p] dirName

### 参数

- -p 或 --parents 创建路径

### 实例

```bash
mkdir -p demo/test1
```