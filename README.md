# MigMix1M4Fig
フォント「MigMix-1M」のregularをベースに、矢印記号も等幅フォントを目指して修正しました。目的は図解を文字で表現したかったからです。  
Based on the font 'migmix1m', the arrow symbols have also been modified aiming for monospaced fonts. The purpose is to express the graphics with letters.  

## 欲しいフォント条件
- 英数字、仮名と漢字と記号が全て等幅フォント
- 罫線が鎖線にならず連続
- 半角英数：全角文字＝1:2
- 全角文字の縦横比＝1:1
- 記号文字も全角等幅
- 文字サイズ均一
- なるべくライセンスが軽い（改変可・商業・再配布可）

## 利用したもの
- メモ帳(notepad.exe)
- FontForge
- Font「MigMix1M 」のデータ
- Visual studio code
- 秀丸エディタ
- AutoCAD

## 作成するフォントの内容
項目|内容
:-: |:-: 
元フォント|MigMix-1M
基準文字|罫線素片
全角文字サイズ|1000×1000
文字太さ|46
文字隙間|0
半角と全角の等幅比|1（英+数）:2（仮名+漢字+記号）

# 変更したフォント
文字|unicode番号<br>「&#x〇〇〇〇；」
:-: |:-:  
→  |2192 
←  |2190 
↑  |2191 
↓  |2193 
↔  |2194 
↕  |2195 
↰  |21B0 
↱  |21B1 
↲  |21B2 
↳  |21B3 
⇄  |21C4 
⇅  |21C5 
⇆  |21C6 
⇤  |21E4 
⇥  |21E5 
⍅  |2345 
⍆  |2346 
⍏  |234F 
⍖  |2356 
─  |2500 
│  |2502 
╭　|256D  
╮　|256E  
╯　|256F  
╰　|2570  
╱　|2571  
╲　|2572  
╳　|2573  
◉　|25C9
○  |25CB
●  |25CF
■  |25A0 
◇  |25C7 
◢  |25E2 
◣  |25E3 
◤  |25E4 
◥  |25E5 
◸　|25F8  
◹　|25F9  
◺　|25FA 
◿　|25FF 
⤒  |2912 
⤓  |2913 
⭰  |2B70 
⭱  |2B71 
⭲  |2B72 
⭳  |2B73 

# Sample
## UML
### 入力元文字 Input letter
```
╭────╮
│クラス図│
╰────╯
┌─────────┐
│神戸住民　　　　　│
├─────────┤
│名前　　　　　　　│
│住所　　　　　　　│
│電話番号　　　　　│
│年齢　　　　　　　│
├─────────┤
│通勤する（）　　　│
│買い物に行く（）　│
└─┬───────┘
　　│0..*
　　│
　　│
　　◇1
┌─────────┐
│会社　　　　　　　│
├─────────┤
│会社名　　　　　　│
│住所　　　　　　　│
│電話番号　　　　　│
├─────────┤
│所属する（）　　　│
│脱退する（）　　　│
└─────────┘
```

### 出力結果　Output
![UML](https://github.com/kobe2018/migmix1m4Fig/blob/master/Fig_sample/uml.png "UML図")
