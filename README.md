# 一部のマルチバイト文字の問題に対応したdoctoc

[doctoc](https://github.com/thlorenz/doctoc)はmarkdownのTOC（目次）を生成するスクリプト。  
全角コロンや全角カッコの問題に対応してある。  


## セットアップ

```
git clone https://github.com/aoyama-val/doctoc.git
cd doctoc
npm install
```


## 使い方

`README.md`の目次を生成するには（`README.md`が上書きされるので注意）:

```
node /path/to/doctoc/doctoc.js README.md
```
