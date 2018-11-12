# National Taiwan University Master Thesis - **xelatex**

* 國立臺灣大學碩士論文(台大碩論)
* origin version from: https://github.com/ychiaoli18/thesis.git
* This is NTU master thesis for xelatex/xeCJK version 
* Also fixed one typo in College name : replace "Enginnering" with "Engineering"

## Usage

* First, you need to install xelatex.
* Then, download ZIP in this page, or type:
* `git clone https://github.com/c62066206/thesis.git`
* `cd thesis`
* `make`
* Make sure there are no error messages.
* You can see the output file in `dist/`
* Now, you can start to write your thesis


# What you will write

## thesis.tex

* 論文封面/Cover of you thesis: around line 100
* 大章節名稱/Chapter name: around line 200

## thesis\_frontpages.tex

* 誌謝/Acknowledgement: around line 10
* 摘要/Abstract: after acknowledge

## thesis\_bib.bib

* 參考文獻/Reference

## chapters/

* 每一章節內容/Contents in each chapter

## images/

* 所有論文中的圖片/Images in your thesis

# Others

## Font
* ming font (ver 1.300) from: https://github.com/ButTaiwan/genryu-font
* You can also use kai and ming in your system directly.
* Or you can find any kai and ming that you like.

## TODO

* There are still some bugs like inconsistent indent distance. How weird ...

## Murmur by me

* The origin version (pdflatex) cannot show my name. I feel really sad ;(
* If there are any bugs (format or whatever), feel free to tell me: r05942066@ntu.edu.tw
