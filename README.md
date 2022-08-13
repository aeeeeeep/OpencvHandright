# OpencvHandright
___A software for auto simulating Chinese handwriting___

## Vision
Reveal the nature of Chinese handwriting and use it to implement beautiful, simple and easy-to-use interfaces.

## Finish

## TODO

* 使用霍夫变换获取直线线长，位置，计算出 `font size`，`word spacing`，`line spacing`
* 检测纸张的边缘，结合线长，计算出 `left margin`，`right margin`，`top margin`，`bottom margin`
* 检测背景图片白平衡，设置 `font color`
* 通过多条直线的畸变与变换，进行图片标定，得到三维旋转矩阵，将生成的文字图片与背景图片在相机坐标系上对应起来 (论文：https://aeeeeeep.github.io/papers/icpr2020_nakano.pdf)
* 调用 AI 文章生成器 SDK，自动生成文章内容
