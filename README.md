# Path
**最新バージョンのダウンロード：[Path 1.0](https://github.com/RJ45K/path/releases/tag/v1.0)**
***
### About
Pathは、カレントディレクトリのパスをソースコードとする変な言語です。  
**python3の入ったWindowsでしか動きません。**
***
### Usage
ソースコードのフォルダにcdしてpath.exeを実行するだけです。  
  
3種類のコマンドライン引数が用意されています。  
\-help：ヘルプを表示します。  
\-wait：タイムアウト処理を無効にします（通常は3秒でタイムアウト）。  
\-gui ：guiで起動します。
***
### Grammar
基本的な文法はpython3のワンライナーと同じです。  
ただ、\/:*?"<>|をファイル名に入れることができないので、*を++に置き換えたり、:を;に置き換えたりしてください。
***
### Hello, world!
pythonのハローワールドの、
```
print('Hello, world!')
```
と同じ名前のディレクトリにcdしてpath.exeを実行します。
```
C:\> cd C:\print('Hello, world!')
C:\print('Hello, world!')> C:\path\to\file\path.exe

Hello, world!
```
***
### FizzBuzz
出力は一部省略しています。
```
C:\> cd C:\for i in range(100);\print(['FizzBuzz',i+1,i+1,'Fizz',i+1,'Buzz','Fizz',i+1,i+1,'Fizz','Buzz',i+1,'Fizz',i+1,i+1][(i+1)%15])
C:\for i in range(100);\print(['FizzBuzz',i+1,i+1,'Fizz',i+1,'Buzz','Fizz',i+1,i+1,'Fizz','Buzz',i+1,'Fizz',i+1,i+1][(i+1)%15])> C:\path\to\file\path.exe

1
2
Fizz
:
:
Buzz
```
