# 刑法過去問帳

ロースクール既修者入試（刑法）の過去問を、**刑法の単元ごとに**引ける学習帳。

**https://law-kakomon.github.io/keiho-kakomon/**

- **単元から引く** — 総論（違法性阻却・責任・未遂・共犯・罪数）／個人的法益／社会的法益／国家的法益
- **条文から引く** — 検索欄に `240` と入れると、強盗致死傷が論じられた回が並ぶ
- **論点・判例で探す** — 「正当防衛」「承継的共同正犯」「最決平成20年5月20日」などで検索
- **問題と解説をその場で読む** — 同志社・立命館は PDF をページ内に表示。関学・慶應・中央はサーバー側の設定で埋め込めないため新しいタブで開く
- **解いた回に印をつける** — チェックはこの端末のブラウザにだけ残る

収録は同志社・立命館・関学・慶應・中央の5校、計 88 回（2005〜2027年度）。

**PDF は各大学の公式ページをそのまま開きます**（このリポジトリに複製は置いていません）。

## 使い方

```bash
open 開く.command
```

## 更新

```bash
python3 tools/fetch_sources.py
python3 tools/digest.py <新しいID>
# tools/classify.py に単元・論点を追記
python3 tools/build_data.py
```

くわしくは [CLAUDE.md](CLAUDE.md)。

## 出典

- [同志社大学法科大学院 過去の入試・履修免除試験問題](https://law-school.doshisha.ac.jp/entrance_ex/question/)
- [立命館大学法科大学院 過去の入試問題・講評](https://www.ritsumei.ac.jp/lawschool/admission/past.html/)
- [関西学院大学法科大学院 入試過去問題（解答例・出題の意図）](https://www.kwansei.ac.jp/lawschool/admissions/kakomon/)
- [慶應義塾大学法科大学院 過去の入試問題](https://www.ls.keio.ac.jp/nyushi/examination.html)
- [中央大学法科大学院 入学者選抜の過去問題等の情報公開](https://www.chuo-u.ac.jp/academics/pro_graduateschool/law/orientation/selection/past/)

## 姉妹サイト

- [民法過去問帳](https://law-kakomon.github.io/minpo-kakomon/)
- [民事訴訟法過去問帳](https://law-kakomon.github.io/minso-kakomon/)
- [会社法過去問帳](https://law-kakomon.github.io/kaisha-kakomon/)
- [行政法過去問帳](https://law-kakomon.github.io/gyosei-kakomon/)
