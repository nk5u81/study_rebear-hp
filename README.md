# study_rebear-hp
中村勉強用

☆ルール
覚えたこと/作業内容を記載しておく
更新日とセットで記載していく

＜目標＞
期日：8月2日（金）
ゴール：rebear HPを作成

最終的にnotionに記載をして、誰でもHPを作成できるようにする
・作成方法
・開発環境を整える方法

=========
7月19日(金)
1. githubで新しくrepositoryを作成する
    1. new をタップ
    2. 出てくるコードをコピー
    3. ターミナルを立ち上げてgithubと連結したクローンファイルを作成
        ・cd desktop
        ・git clone コピーしたリンク
    4. デスクトップにファイルが作成されているかを確認
    5. ファイルが作成されていたら完了
2. node.jsのインストール
　・https://retval.jp/blog/m1-mac-nodenv/

3. １番で作成したファイルをvs.cordで開く
    1. 新しいファイルを作成
    2. ターミナルを開き npx serve をすることで、ローカルと紐づける

4. nodeのバージョンをvs.cord上で管理する
    1. 「.node-version」というファイルを作成
    2. versionを入力
        新規nodeの場合は、nodenv install xx.xx.x でインストール

5. 変更点をgitに反映
    1. git add .
    2. git commit -m 'xxx'
    3. git push -u origin head 