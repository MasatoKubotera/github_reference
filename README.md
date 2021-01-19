# github_reference
---
## コマンド

---
## Markdown記法・HTML記法

- ### 見出し(大きい太文字)

  ```
  # 見出し1
  ## 見出し2
  ### 見出し3
  ```
  # 見出し1
  ## 見出し2
  ### 見出し3

  ```
  <h1>見出し1</h1>
  <h2>見出し2</h2>
  <h3>見出し3</h3>
  ```
  <h1>見出し1</h1>
  <h2>見出し2</h2>
  <h3>見出し3</h3>

- ### 引用

  ```
  >テキスト
  ```
  >テキスト

- ### 太文字

  ```
  **テキスト**
  ```
  **テキスト**
  ```
  <strong>テキスト</strong>
  ```
  <strong>テキスト</strong>

- ### 打消し線

  ```
  ~~テキスト~~
  ```
  ~~テキスト~~

- ### コード(単行)

  ```
  `テキスト`
  ```
  `テキスト`

- ### コード(単行・複数行)
  ~~~
  ```
  テキスト
  テキスト
  ```
  ~~~
  ```
  テキスト
  テキスト
  ```
  ~~~
  ```.c
  int 変数名;
  ```
  ~~~
  ```.c
  int 変数名;
  ```

  ```
  <code>テキスト</code>
  ```
  <code>テキスト</code>

- ### 箇条書き

  ```
  - テキスト
    - テキスト
  ```
  - テキスト
    - テキスト

  ```
  1.  テキスト
  2.  テキスト
  ```
  1.  テキスト
  2.  テキスト

- ### 水平線

  ```
  ***
  または
  ---
  ```
  ***
  ---

- ### リンク

  ```
  [テキスト](URL)
  ```
  [テキスト](https://github.com/MasatoKubotera)

  ```
  <a href="URL">テキスト</a>
  ```
  <a href="https://github.com/MasatoKubotera">テキスト</a>

- ### 画像

  ```
  ![テキスト](画像URLまたはパス)
  ```
  ![テキスト](https://avatars2.githubusercontent.com/u/53966390?s=460&u=6c1b0733a0b28f09b410179d4482c407606f732d&v=4)

  ```
  <img src="画像URLまたはパス">
  ```
  <img src="https://avatars2.githubusercontent.com/u/53966390?s=460&u=6c1b0733a0b28f09b410179d4482c407606f732d&v=4">

  ```
  <img src="画像URLまたはパス" width="100px">
  ```
  <img src="https://avatars2.githubusercontent.com/u/53966390?s=460&u=6c1b0733a0b28f09b410179d4482c407606f732d&v=4" width="100px">

  - #### リンクと画像の組み合わせ

    ```
    [![テキスト](画像URLまたはパス)](URL)
    ```
    [![テキスト](https://avatars2.githubusercontent.com/u/53966390?s=460&u=6c1b0733a0b28f09b410179d4482c407606f732d&v=4)](https://github.com/MasatoKubotera)

    ```
    <a href="URL"><img src="画像URL" width="100px"></a>
    ```
    <a href="https://github.com/MasatoKubotera"><img src="https://avatars2.githubusercontent.com/u/53966390?s=460&u=6c1b0733a0b28f09b410179d4482c407606f732d&v=4" width="100px"></a>

  - #### 画像URL取得方法

    1.  issueを開く
      <img src="https://user-images.githubusercontent.com/53966390/105071086-7aca4480-5ac7-11eb-85d6-ad73489c3daf.png" width="100px">

    2.  画像を貼り付けまたはドラッグ
      <img src="https://user-images.githubusercontent.com/53966390/105071078-79991780-5ac7-11eb-914d-4cb16851b47a.png" width="100px">

    3.  "https:○○"の画像URLが取得できる．取得した画像URLはisuueを閉じても有効．

- ### 表

  ```
  |タイトル1|タイトル2|
  |---|---|
  |値1|値2|
  ```
  |タイトル1|タイトル2|
  |---|---|
  |値1|値2|

  ```
  |タイトル1|タイトル2|タイトル3|
  |:---|:---:|---:|
  |左寄せ|中央寄せ|右寄せ|
  ```
  |タイトル1|タイトル2|タイトル3|
  |:---|:---:|---:|
  |左寄せ|中央寄せ|右寄せ|

- ### コメントアウト(単行・複数行)

  ```
  <!--
    コメントアウトする内容
  -->
  ```

- ### 折りたたみ
  - #### 閉じた折りたたみ

    ```
    <details>
      <summary>表示テキスト</summary>
        テキスト
    </details>
    ```
    <details>
      <summary>表示テキスト</summary>
        テキスト
    </details>

  - #### 開いた折りたたみ

    ```
    <details　open>
      <summary>表示テキスト</summary>
        テキスト
    </details>
    ```
    <details open>
      <summary>表示テキスト</summary>
        テキスト
    </details>

- ### インデント

  ```
  <dl>
    <dt>テキスト</dt>
    <dd>テキスト</dd>
  </dl>
  ```
  <dl>
    <dt>テキスト</dt>
    <dd>テキスト</dd>
  </dl>

- ### 改行
  ```
  1行空白の行を挿入
  <br>タグ
  ```

---
## Works cited
- [Markdown記法 サンプル集](https://qiita.com/tbpgr/items/989c6badefff69377da7)
- [Markdown記法一覧](https://qiita.com/oreo/items/82183bfbaac69971917f)
- [Markdown記法でコメントアウトする](https://qiita.com/yu0819ki/items/e1e1d20cedc68706ba23)
- [【Markdown】改行するための書き方について徹底解説！](https://www.sejuku.net/blog/77336)
- [【GitHub】README.md に画像を表示させる簡単な方法](https://qiita.com/ROY_M/items/2c4feb5de05535441bc8)