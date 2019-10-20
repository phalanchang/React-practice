# React 準備いろいろ

## Remote Repository の Clone

create a new repo を GitHub のほうでしたので、ローカルに持って来たい。

1. GitKraken の左上の File > Clone Repo を選択
2. GitHub の Clone or Download から html の URL を取得する
3. Gitkraken に戻ってきて、URL に入力

## ssh の話

RSA 鍵生成 > GitHub に登録

- Rocal GitKraken
1. GitKraken の 右上のアカウントの隣にある 三　マークをクリック
2. Preference > Authentication > Generate new Private / Public Key の Generate をクリック
3. SSH Public Key のクリップボードへコピーするアイコンをクリック
- Remote GitHub
4. GitHub の右上のアカウントのアイコンから Settings を選択
5. SSH and GPG keys を選択
6. New SSH keyをクリック
7. GitKraken でコピーした Public Key をペーストして登録