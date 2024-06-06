# M5Core2_Gallery🖼  
## これは何？  
M5Stack Core2 でjpg画像を表示させます  
![デモ動画](./assets/demo.mp4)  
複数の画像がある場合は、M5Core2のAボタン・Cボタンで遷移できます  

## 使い方
1. `git clone https://github.com/Sorutrt/M5Core2_Gallery.git` でリポジトリをクローンします
2. SDカード直下に `img` ディレクトリを配置し、`.jpg`拡張子の画像を入れます
3. `/src/main.cpp`をコンパイルし書き込みます
4. M5Core2上に読み込んだ画像の名前が2秒間表示されます
5. 画像が表示されます

## 上手くいかないとき
### ポートが合っていますか？
M5Core2が接続されているCOMポートを選んでください  

### 書き込みに失敗する
この問題のほとんどはUSBケーブルの交換やSerial Speedを下げることで解決します  

### ディレクトリ名やファイル名を確認してください
SDカード**直下**に`img` ディレクトリを作成してください  
また、`.jpeg`や`.png` は認識されません  


## 使用したもの  
[Loose Drawing🎨](https://loosedrawing.com)（デモ動画内の画像）  
### 開発環境
M5Core2, PlatFormIO, VSCode, Windows