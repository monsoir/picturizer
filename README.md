# 图片转字符画 Picturizer

将图片转换为字符画

## 运行

1. 创建并激活虚拟环境，使用的是 Python 3.6.2 开发

    ```
    virtualenv --no-site-packages env
    source env/bin/activate
    ```

1. 安装

    ```sh
    pip install picturizer
    ```

1. 使用

    ```sh
    picturize -i ~/Downloads/a_picture.jpg -o ~/Downloads/result.txt -s 1.0
    ```

## 帮助

```sh
picturize -h
```

```
usage: picturize [-h] -i [source_path] [-o [store_path]] [-s [a_scale]]

optional arguments:
  -h, --help            show this help message and exit
  -i [source_path], --input [source_path]
                        input file
  -o [store_path], --output [store_path]
                        output file
  -s [a_scale], --scale [a_scale]
                        scale of the picture, should be 0 < scale <= 1
```

## References

- [用Python把图片变成字符画](https://www.jianshu.com/p/991cb07b3ad3)
- [从RGB色转为灰度色算法](http://blog.csdn.net/xdrt81y/article/details/8289963)


