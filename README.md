# はっちゃんの自由帳

人生経験や備忘録~~やくだらない雑談~~などを気が向いたらおいていく場所です。

連絡先：[Twitter(現X)](https://x.com/obukun_quality?s=20)

Page URL:<https://hatchan-desire.github.io>

***

## Collaboratorsへ

招待された方はリポジトリ内にファイルを追加することができる。

### ブログの書き方

#### 1-1. ブランチを作成する（絶対！）

  Codeのタブの画面左上に`Branches`という項目があるのでそれをクリック。画面が移動したら右上の`New branch`を選択する。
  
![image](https://github.com/Hatchan-Desire/Hatchan-Desire.github.io/assets/75426954/c783b6c1-81e3-451c-a841-b117ee30feca)
![image](https://github.com/Hatchan-Desire/Hatchan-Desire.github.io/assets/75426954/08220cf1-d0c4-42e1-851c-f793fb3b7ba0)

　ブランチの名前を設定して`Create new branch`を選択。Sourceは`main`でよい

  ブランチ名にあなたの名前が含まれていると管理が楽で助かります。
  
#### 1-2. 作業ブランチの移動

　先ほど作ったブランチを選択する。
 
![image](https://github.com/Hatchan-Desire/Hatchan-Desire.github.io/assets/75426954/d6293c3e-b8df-46ea-a0d5-7d515fb38267)

  これによってmainとは"別の世界線"で作業をすることができる。Mergeするまで本番環境に影響しないので自由にいじれる。やったね！

#### 2-1. docsにファイルを格納する

　リポジトリ内にある`docs`フォルダに移動。
 
![image](https://github.com/Hatchan-Desire/Hatchan-Desire.github.io/assets/75426954/ab81b4da-9a30-4b09-be59-c218e502303a)

　`Add file`をクリックして`Create new file`を選択する。
 
![image](https://github.com/Hatchan-Desire/Hatchan-Desire.github.io/assets/75426954/cea4e382-c25b-4d8a-b491-880865c43859)

　わかりやすいファイル名を決める。このとき拡張子は`.md`とすること。HTML・CSSが書ける人はそれでもよい
 
![image](https://github.com/Hatchan-Desire/Hatchan-Desire.github.io/assets/75426954/2b0487bc-2520-4753-a6cd-103aeeca2d34)

#### 2-2. コミットする

　ある程度内容が書けたら、`Commit changes...`をクリックして変更を保存する（このときファイル内には1文字以上入力されている必要があるので注意、空ファイルはダメ）。
適当にコミットメッセージを書いてコミットする。

#### 2-3. Pull requestを作成する

　コミットが完了したら、mainへの実装を申請する（＝プルリクエスト）。
 
![image](https://github.com/Hatchan-Desire/Hatchan-Desire.github.io/assets/75426954/faa99823-0704-4e82-b556-0191cf068016)

　`Contribute`→`Open pull request`→`Create pull request`の順にクリックしてリクエストを作成する。

***

#### 3-1. ドキュメントを編集しよう

　自分で書いたドキュメントを後から編集することができる。自分のブランチに移動して、編集したいファイルを開いて鉛筆アイコンをクリックし編集モードに入る。

![image](https://github.com/Hatchan-Desire/Hatchan-Desire.github.io/assets/75426954/ec470b17-c7e0-475b-b274-eee413be8e49)

　編集が終わったら、新規作成時と同様にコミット・プルリクエストを行う。

#### 3-3. ドキュメントに画像を貼る

　URLを使ってMarkdownファイル内に画像を埋め込むことができる。クリップボードから画像をペーストすると、自動的にリンクを当ててくれる。

記述例：
```
![代替テキスト](https://...)
```

結果：

![代替テキスト](https://media.discordapp.net/attachments/694104681147793468/1211192830496735232/IMG_0965.jpg?ex=65ed4e39&is=65dad939&hm=c13f20219a6b1d2bfb9fd64c194bac7cf290828b96fe2f2a3457abfe4548916d&=&format=webp&width=450&height=600)
