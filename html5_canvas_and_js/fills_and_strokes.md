# 填充和描边
`context.fillStyle` `context.strokeStyle`

`context.lineWidth` `context.lineCap` `context.lineJoin`

---

1. 使用 `<canvas>` 画布进行绘图与使用 PS 或 AI 绘图理念接近；

2. 填充：用指定的样式（**颜色**、**渐变** (见15.2.8) 或 **图像**）填充图形；

3. 描边：在图形的边缘画线；

4. 填充和描边样式指定两属性：`fillStyle` `strokeStyle`；

5. 两个属性接受的值：默认为 `#000`
    * 颜色字符串
    * 渐变对象（见 15.2.8）
    * 模式对象（见 15.2.9）

6. 描边除了 `strokeStyle` 属性外还有其他三个属性
    * `lineWidth`：num
    * `lineCap`：butt, round or square
    * `lineJoin`：round, level or miter

7. 然后所有涉及描边和填充的操作都将使用这两个样式，直至重新设置这两个值。
