---
title: About EasyLaTeX
linkTitle: About
menu: {main: {weight: 10}}
---

{{% blocks/cover title="EasyLaTex/EasyLaTex Pro" image_anchor="bottom" height="auto" %}}
A Free Powerful Mathematical Formula Recognition Tool
{.mt-5}
{.-text-yellow}

{{% /blocks/cover %}}

{{% blocks/section %}}

EasyLaTeX is a powerful mathematical formula recognition tool that helps you quickly convert handwritten or printed mathematical formulas into LaTeX code and provides preview image functionality. It can eliminate or reduce your workload of writing complex LaTeX code, aiming to provide convenience through this application.

EasyLaTeX is completely free, requires no user registration, and can be used without limitations.

## Main Features List

- Quick recognition of handwritten and printed mathematical formulas
- Support for taking photos and selecting formula images from the photo albums of mobile devices.
- Real-time preview of generated image with recognized LaTeX codes. 
- Support for most mathematical symbols and expressions
- Support for viewing historical recognition records
- Support for multiple languages
- Support for preview the generated images with various fonts


## About the Backend Model

The backend mathematical formula recognition model used by EasyLaTeX was fine-tuned based on an open-source model, and we are continuously optimizing the model parameters to improve its inference performance (such as accuracy, response time, etc.). However, the inference tasks of the model are still executed on our servers' CPUs, and since you probably know that CPU's computing power is far lower than GPU's, so you may get relatively slow responses for formula OCR tasks with EasyLaTeX. Currently the EasyLaTeX's timeout setting for the formula image OCR is 90 seconds, but per our testing result, most formula OCR tasks can be completed within 15 seconds.  


## Differences between EasyLaTeX and EasyLaTeX Pro

The main differences between EasyLaTeX and EasyLaTeX Pro lie in the backend models' parameter size and the running hardware for inference tasks. EasyLaTeX executes inference tasks on CPU, while EasyLaTeX Pro uses GPU, so EasyLaTeX Pro has faster response, hence a relatively better user experience. Additionally, the size of the EasyLaTeX Pro's model is about 40% larger than the size of EasyLaTeX's model, resulting in slightly higher accuracy than EasyLaTeX.  

In terms of functionalities, EasyLaTeX and EasyLaTeX Pro are completely identical.  

## Technical Support

If you have any issue in using the App, please send an email to: yunpeng_deng@sina.com

{{% /blocks/section %}}
