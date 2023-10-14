---
description: 一触而就开发平台文档
---

# 开始使用

## 介绍

一触而就是stable Diffusion API需求的一站式解决方案！我们为您的网站和应用程序提供简单、经济高效、易于集成的API！

## 接口集合

text-to-image

image-to-image

controlnet

inpaint

instruct

upscale

face-fix

{% content-ref url="stable-diffusion-api-jie-kou.md" %}
[stable-diffusion-api-jie-kou.md](stable-diffusion-api-jie-kou.md)
{% endcontent-ref %}

## 价格

我们的API计费是基于使用量的 - 您只需支付您实际使用的部分。每个图像生成请求的计费是按1M像素步骤计算的 - 这是一个与根据输出大小和所需时间（步骤）创建图像所需的计算资源成对应的单位。

要计算像素步骤的数量，请将请求的图像宽度、高度与步骤数相乘。如果在生成过程中输出图像被放大（例如在/v1/enhancements/upscale中），则使用缩放后的分辨率进行计算。对于没有宽度和高度参数但需要源图像的资源，使用该图像的尺寸进行计算。对于不需要步骤参数的模型，默认值为1。

每个模型都有其自己的每1M像素步骤的价格。要获取新模型的最新价格，请在API仪表板中查看数值或使用/v1/models端点。

{% content-ref url="broken-reference" %}
[Broken link](broken-reference)
{% endcontent-ref %}
