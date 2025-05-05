---
title: 关于 EasyLaTeX
linkTitle: 关于
menu: {main: {weight: 10}}
---

{{% blocks/cover title="EasyLaTex/EasyLaTex Pro" image_anchor="bottom" height="auto" %}}
一个免费强大的数学公式识别工具
{.mt-5}

{{% /blocks/cover %}}

{{% blocks/section %}}


EasyLaTeX是一款强大的数学公式识别工具，它能够帮助您快速将手写或打印的数学公式转换为LaTeX代码并提供预览图片功能，它可以免去或减轻您编写复杂的Latex代码的工作量，希望通过本应用为您提供方便。  

EasyLaTeX完全免费，不需要用户注册，可以直接无限制使用。  

## 主要功能清单

- 快速识别手写和打印的数学公式
- 支持拍照和从相册选择数学公式图片
- 实时预览生成的LaTeX代码
- 支持绝大多数数学符号和表达式
- 支持查看历史识别记录
- 支持多语言环境
- 支持选择多种字体生成的预览图片
** **

## 关于后端模型

EasyLaTeX应用的后端服务所使用的数学公式识别模型是在某开源的模型上fine-tune产出，并且会持续优化模型参数以提高模型的推理性能（如准确率、相应速度等)。 但EasyLaTeX的后端模型的推理任务仍然由服务器的CPU执行，由于CPU计算能力要远远低于GPU的计算能力，所以数学公式图像识别可能不会有快速的响应结果。目前EasyLaTeX针对图像识别的响应超时时间为90秒，但通过我们的测试，一般情况下大多数数据公式的识别任务会在15秒以下完成。
** **

## EasyLaTeX 和 EasyLaTeX Pro 的区别

EasyLaTeX和EasyLaTeX Pro的主要区别在于后端的模型参数大小和运行推理任务的硬件。EasyLaTeX是由CPU执行推理任务，而EasyLaTeX Pro是由GPU执行，所以EasyLaTeX Pro会有更快的响应速度，进而带来相对较好的用户体验，此外EasyLaTeX Pro的模型参数规模比EasyLaTeX的模型大40%左右，准确率略高于EasyLaTeX。  

功能上EasyLaTeX和EasyLaTeX Pro完全相同。
** **

## 技术支持

如果您在使用过程中遇到任何问题，请发送邮件至：yunpeng_deng@sina.com

{{% /blocks/section %}}
