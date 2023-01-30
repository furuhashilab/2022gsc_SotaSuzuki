# 2022gsc_SotaSuzuki
2022年度古橋ゼミ論用レポジトリ

# 全国ラーメン二郎店舗および神奈川県内二郎系ラーメン店舗位置情報オープン化の継続

全国のラーメン二郎店舗のメタデータ更新及び、新規ラーメン二郎店舗の追加と神奈川県内二郎系ラーメン店舗位置情報データ、メタデータの更新が目的。

2022年度 ゼミ論文

青山学院大学 地球社会共生学部 地球社会共生学科

鈴木颯汰/SOTA SUZUKI

学生番号 1A119090

指導教員 古橋大地 教授

© Furuhashi Laboratory/Sota Suzuki, CC BY 4.0

## Abstract

本研究は2018年度地球社会共生学部卒業生である渡邊結南氏の卒業論文「日本全国ラーメン二郎店舗位置情報オープン化の実践」に着想を得て、神奈川県内の「二郎系ラーメン」店舗及び、全国ラーメン二郎店舗の地理空間情報を、OpenStreetMap（以下OSM） データベース内に登録し、だれもが自由に二郎系ラーメンのデータにアクセスし、二次利用が可能な状態を構築することが目的である。

## Introduction

本来、中国由来の麺文化である「拉麺（らーめん）」は、日本に伝播する過程の中で独自の進化を遂げ、日本の「ラーメン」という食文化を確立し、2021年現在、代表的な日本の文化の象徴として、広く親しまれている。その中で、1968年に創業した東京都港区三田を拠点としている「ラーメン二郎」というラーメンブランドが存在する。こってりとした味付けと、満腹感を重視したコストパフォーマスの良いラーメンを提供する店舗だ。ラーメン二郎は、三田での創業以降、独特の味つけと提供方法で、日本のラーメンの中で、「二郎系」という１つのジャンルを確立した。2022年現在、ラーメン二郎は日本に41店舗存在し、暖簾分けシステムというシステムの中で、日本各地に店舗を広げている。これらの二郎系ラーメン愛好家は「ジロリアン」と呼ばれ、各地の二郎系店舗を食べ歩き、その情報共有ウェブサイトも数多く存在する。 一方で、2021年の段階ではラーメン店舗マップとして二郎系ラーメンの位置情報が日本全国網羅され、二次利用可能なオープンデータ化がされている例は見当たらないことから、二郎系ラーメンのアプリやマップを作る上で、そのデータをオープンに公開・共有することは車輪の再発明と呼ばれる現地調査重複の無駄を省き、ジロリアンらの活動を支える基礎資料となる。併せて、それらのデータを共有するために必要なプラットフォームには何を選択すべきか検討を行い、OSMデータベース内への格納が現実的であると判断し、現地調査によって得られた日本全国のラーメン二郎店舗情報のマッピングを渡辺氏が、その研究のデータ更新やタギングルールの統一を依田氏が行ったことで、OSMのオープンな地理空間情報プラットフォームを用いて、日本全国のラーメン二郎店舗データ、およびそのメタデータを整理、網羅することによって、誰もが自由にラーメン二郎店舗データにアクセスし、再利用することが可能な状況が構築構築された。今年度は昨年度のゼミ論研究に引き続き、神奈川県内の二郎系ラーメン店舗と全国ラーメン二郎店舗の位置情報データ及びメタデータを整理、更新を行う。

## Method

現在営業している全国のラーメン二郎店舗は４２店舗。また、神奈川県内の二郎系ラーメン店舗は７１店舗確認できている。（2023年1月時点）
情報源は昨年度に引き続き、現地調査を行うことができた店舗にのみsource=surveyを記入した。ほかは更新が行われている公式Twitterなどを参照したほか、DMなどで連絡し、実際に情報の聞き込みを行った。
また、本年は対象店舗の数が昨年度よりも多いことから、Facebookグループの[ラーメン二郎を愛する会](https://www.facebook.com/groups/389660794496077)において対象店舗の投稿がないか逐一確認を行った。そしてこれらの情報をもとに以下のタギングルールに則り書き込みを行った。

- 店舗データが未入力の店舗を入力

- 全店舗の住所を入力

- 全店舗のOpening_hoursを入力

- 全店舗のopening_hours:covid19を入力

- amenity=fastfoodに統一

- cuisine=ramen;jiroに統一

- delivery=yes/no

- takeout=yes/no

- drive_through=no

- outdoor_seating=no

- branch=支店の場合入力

- source=survey（筆者が現地調査を行うことができた店舗のみ）

![editor](https://user-images.githubusercontent.com/72395572/152496616-469b0406-8f4a-44c3-afe2-9afc9c07443a.png)

## Result

現在営業をしている全国のラーメン二郎店舗と神奈川県内の二郎系ラーメンの店舗データをOSM上で編集、追加を行い公開する。
2022年度の店舗増減は以下の通りになった。

- ラーメン二郎
ラーメン二郎は一橋学園店が新たにオープンし、合計４１店舗となった。

- 県内二郎系ラーメン
横浜市：新規９店舗、閉店１店舗 → 合計８店舗増
川崎市：新規２店舗、閉店２店舗 → 合計増減なし
その他：新規１３店舗、閉店１店舗 → 合計１２店舗増
総合して新規２４店舗、閉店４店舗で合計２０店舗の増加となった。

情報源は現地調査を行うことができた店舗にのみsource=surveyを記入した。ほかは更新が行われている公式Twitterなどを参照したほか、DMなどで連絡し、実際に情報の聞き込みを行った。

## Discussion

主な論点は以下の3点である。

1. 二郎系ラーメンに適したcuisineタグのvalueの検討を行った結果、渡邊氏のリファレンスによればcuisine=ramen;jiroは「ラーメン二郎」のみを指すタグではなく、あくまで「二郎系」を指すものであったことから、cuisine=ramen;jiroという組み合わせのタグセットを選択した。また、二郎系の定義を定めることで、ただ二郎系を提供している店舗を二郎系ラーメン店ではなく、二郎系ラーメンをメインで提供している店に絞った。

2. また、 新型コロナウイルスの脅威が未だ収まらない現在、コロナ前の営業時間や時短営業時の営業時間とは異なる、新たな営業時間で営業している店舗が散見された。この営業時間は新型コロナウイルスを考慮しての営業時間であることには変わりはないと判断し、Opening_hours:covid19の欄に記入することにした。そのため、通常の営業時間をOpening_hoursに、時短の営業時間や新たな営業時間をOpening_hours:covid19にそれぞれ誤りのないよう注意を払い入力した。

3. 二郎系ラーメンのお店はラーメン二郎とは異なり、お持ち帰りやUberEatsなどのデリバリーのサービスを実施している店舗が存在することから、その情報の収集を漏らさないようにし、delivery、takeawayのタグにその有無を記入した。

## Conclution

本研究を通じて、筆者が現地調査と聞き込み行った全国のラーメン二郎店舗と神奈川県内の二郎系ラーメン１１２店舗分の地理空間情報とメタデータをOSMデータベース内に登録し、既存のデータの見直しを行った。また、渡邊氏のリファレンスにのっとり新たな「二郎系ラーメン」の店舗のメタデータをOSM上で編集、追加し、公開することができた。しかしながら、本年は新型コロナウイルスの流行前と時短営業の時間とも違う新たな営業時間で営業を行なっている店舗がいくつかあり、OSMに記載する際にどれが今の営業時間なのかが分かりずら苦なっているのが課題であると感じた。またお持ち帰りのサービスを始める店舗が多く出てくることが予想され、その情報をどのように素早く反映するか、また現地調査を実施することのできていない店舗が多く残ったことや、コロナ期間前の営業時間についてデータを得られなかったことも課題として残っており、今後徐々に入力していく必要があると考えている。

## 先行研究
https://furuhashilab.github.io/www4yunawatanabe/

https://github.com/furuhashilab/2020gsc_shunsuke-yoda

https://github.com/furuhashilab/2021gsc_SotaSuzuki

## レポート

- 参考文献リスト



- 発表スライド

https://docs.google.com/presentation/d/1xGH_nZsShMgH3FwRLgbSYamyQxdcpfSOcF4ObUmiAn4/edit?usp=sharing

- Medium



- グラレコ



## 謝辞

本研究を進めるにあたり、青山学院大学地球社会共生学部教授の古橋大地氏をはじめ、先行研究を行った渡邊結南氏、依田峻輔氏、現地調査に協力していただいた柴山息吹氏にこの場をお借りして深く感謝申し上げます。










