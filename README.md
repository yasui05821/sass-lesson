# Sass入門ハンズオン

## はじめに

### 1\.このリポジトリをダウンロードして、sass-lessonのフォルダの中に移動します

```
$ git clone https://github.com/lec-cafe/sass-lesson
$ cd ./pug-lesson
```

`$ git clone`コマンドが難しい場合はZipでのダウンロードが可能です。  
　  
　

### 2\. npmをインストールします

```
$ npm install
```
  
  　
   
※ gulpを初めて使う方は以下のコマンドも入力してください


```
$ npm install gulp -g
```
エラー出たら、`$ sudo npm install gulp -g`このコマンドを実行してください。
（その時にパスワードを聞かれるので、自分のパソコンのパスワードを入力してください) 
　  
　



## コマンドについて

1\.scssファイルをコンパイルする。

```
$ gulp build
```


2\.sassの中にある全てのscssファイルを監視して、自動でコンパイルします。

```
$ gulp
```
