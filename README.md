# PitagoraserRe
2015年にUnrealEngine4を使用してチーム制作した、RTS系ゲームです。<br>
全てUnrealEngine4のBlueprintを使用して制作されています<br>
<br>
# 遊び方<br>
迫ってくる黒い妖精から部屋の中央のテーブルにあるケーキを守るRTSです。3つ全て食べられてしまうとゲームオーバーです。<br>
プレイヤーはドミノを配置して倒すことで妖精を撃退できます。ドミノは魔法陣上から並べていって、並べ終わったら魔法陣を起動することで、倒し始めることが出来ます<br>
魔法陣は部屋に3箇所あり、それぞれにワープできます。画面左上に表示された魔法陣へワープします。任意に切り替えて、効率よくドミノを並べていきましょう<br>
部屋にあるオブジェクトのいくつかはドミノを当てることで様々な動作を起こします。これを利用して妖精を倒すことも出来るので、活用してみてください。<br>
<br>
製作当時にチームメンバーに制作してもらったPVです。<br>
https://youtu.be/weatrnUde38<br>
<br>
# 操作方法<br>
ゲームパッドを使用します。<br>
左スティックで移動、回転<br>
Xboxコントローラ基準で、Bボタンでドミノ配置、Aボタンで緑の魔法陣起動、Xボタンで青の魔法陣起動、Yボタンで黄色の魔法陣起動<br>
Lトリガーでワープ先魔法陣の切り替え、Rトリガーで魔法陣へワープ<br>
# 担当箇所<br>
<br>
自分が担当<br>
レベルブループリントの内、コメントが水色の部分<br>
Domino全般<br>
Player全般<br>
Cola_Blueprint<br>
houki_Blueprint<br>
Books_Blueprint<br>
Skate_Blueprint<br>
pitaGameState<br>
<br>
全てBlueprintなので、拡張子を省いています<br>
チームの別のプログラマが担当<br>
レベルブループリントの内、コメントが緑の部分<br>
MainUI<br>
ResultUI<br>
TitleUI<br>
TutorialUI<br>
AI_Enemy<br>
<br>
<br>
以下に、画面遷移図と一部のクラス図を掲載します。<br>
![default](https://cloud.githubusercontent.com/assets/19707051/23805961/40689f3e-0603-11e7-94b0-94f56e696bcf.PNG)<br>
CharacterClass部分は、PlayerのBlueprintに該当します。<br>
![default](https://cloud.githubusercontent.com/assets/19707051/23805952/3cc3877c-0603-11e7-94c6-8561e4cc79d2.PNG)<br>
<br>
![default](https://cloud.githubusercontent.com/assets/19707051/23805962/423277ea-0603-11e7-8b7c-f30d73a54bd7.PNG)<br>