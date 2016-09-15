<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [一部のマルチバイト文字の問題に対応したdoctoc](#一部のマルチバイト文字の問題に対応したdoctoc)
  - [セットアップ](#セットアップ)
  - [使い方](#使い方)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


# 一部のマルチバイト文字の問題に対応したdoctoc

[doctoc](https://github.com/thlorenz/doctoc)はmarkdownのTOC（目次）を生成するスクリプト。  
全角コロンや全角カッコの問題に対応してある。  


## セットアップ

```
git clone --depth 1 https://github.com/aoyama-val/doctoc.git
cd doctoc
npm install
```


## 使い方

`README.md`の中に

```
<!-- START doctoc -->
<!-- END doctoc -->
```

と書いておいて

```
node /path/to/doctoc/doctoc.js README.md
```
