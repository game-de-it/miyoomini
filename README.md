# miyoomini(PLUS)で動作するQuickNESコア
QuickNESコアはステレオパンニング(Stereo Panning)機能を利用すると、ファミコンの音楽や効果音がステレオ化されます  
特に悪魔城伝説ではとても素晴らしいBGMに変化します  
なおonionUIから直接QuickNESを起動できないため、Retroarch単体起動してからコアをロードしてください

## 導入手順
---
1. [ここからQuickNESコア](https://github.com/game-de-it/miyoomini/blob/main/quicknes_libretro.so)をダウンロードしてください
2. SDカード内のRetroarch/.retroarch/coresフォルダにquicknes_libretro.soファイルをコピーします
3. SDカードをmiyoominiにセットして起動します  
4. Apps→Retroarchを起動します
5. Load Contentからnesファイルを指定します
6. 3つのnesエミュレータが表示されたらQuickNESを実行します
7. SELECT+ファンクションボタンを推してRetroarchのメニューを開きます
8. QUICK MENUでCoreOptions→Aspect Ratioを4:3にして、Audio ModeからStereo Panningを選択します
9. Bボタンを何回か押してMAIN MENUを開き、Configurarion Fileを開き、Save Current Configurationを実行します  
(これで次回QuickNESを起動した時に自動的に4:3とStereo Panningが有効になっています)
10. Retroarchメニューを終了するにはセレクト＋ファンクションボタンを押してください


以上
