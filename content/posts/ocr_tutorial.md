---
title: "Guide for arabic OCR"
date: 2021-01-06T15:05:07+02:00
draft: false
categories: ["computational arabic"]

---

### Using Tesseract 'Optical Character Recognition' for Arabic prints.

> #### Install Tesseract
>
> - follow [instructions][tut] to install tools (for mac I use HomeBrew, and git clone tessract)
> - To check if installation is succesfull, type in terminal `tesseract man` for the manual. 
> - Download the OCR languages needed. In Terminal type `tesseract --list -langs` 
> - [Post-Installation Instructions][tut2]
> - download the language files needed and place them at `/usr/local/share/tessdata`
> - for arabic, download ara.traineddata file from tessdata_best, which is trained at google!
> - finally, follow the [Command Line Usage][tut3] samples. :)


[tut]:https://tesseract-ocr.github.io/tessdoc/Compiling.html
[tut2]:https://tesseract-ocr.github.io/tessdoc/Compiling-–-GitInstallation.html#post-install-instructions 
[tut3]:https://tesseract-ocr.github.io/tessdoc/Command-Line-Usage.html#simplest-invocation-to-ocr-an-image
