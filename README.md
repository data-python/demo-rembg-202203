# README

- 处理本地图片

```
rembg i test.jpg test.output.jpg
```

- 处理在线图片 @todo

```
curl -s https://image.xugaoxiang.com/imgs/2020/12/bf5f5553a596319b.jpg | rembg i > output.jpg
```

# 常见问题 @faq

- PIL.UnidentifiedImageError: cannot identify image file @todo
    - https://blog.csdn.net/cotyyang/article/details/108976567