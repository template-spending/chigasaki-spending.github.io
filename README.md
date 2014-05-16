# 俺のゼニはどこ行った for テンプレート

こちらは地方自治体法で定められている区分（いわゆる款・項）を用いてWhere does my money go?（WDMMG）を立ち上げるためのテンプレートサイトです。
http://template.spending.jp/ で稼働しています。

### 目指すところ
・款・項ベースのWDMMGを立ち上げ易くする
多くの自治体で款・項を用いていますが、ベースとなる本家横浜版の分類が独自なので修正する箇所が多いですよね？
まずは修正量が最小で済むようなテンプレートを作ることを目指します。

・機能追加を取り込みやすくする
各地でWDMMGをより良くするために機能追加されてたりします。
その中には複数年度表示機能など、どの自治体バージョンでも使用したい機能があります。
でも本家横浜のサイトも実際に動いているのでpull requestとかしにくいと思います。
このテンプレートサイトを用いることで素敵な機能を個別にマージしなくていいようにしたいです。

### 開発について
とりあえず私が気になっていることをissue立てて地道にやっていこうかと思います、、、が！

pull request大歓迎！
チームに加わっていただける方も大歓迎！
こんな機能が欲しいとうのご意見ご要望も大歓迎！

です。よろしくお願いします。

Team for AnyWhere 
七島　偉之（Hideyuki Nanashima）, @jollyjoester


###以下、fork元の横浜バージョンに関する記載になります。
Where Does My Money Go? β版（2012年7月1日稼働）は、横浜市民が横浜市に納めている市税を対象として構築したものです。自分の年間総収入をスライドで設定し、単身世帯か扶養一人世帯かを選択すると、給与所得者であるという前提で、横浜市に納めている市税年総額と10分野毎に一日当たり支払っている市税額が表示されます。所得控除額は、単身世帯の場合33万円、扶養一人世帯の場合66万円、市税負担額は課税対象額の6％と設定しています。また、10分野への税金の配分比率は、横浜市の一般会計全体における10分野への予算配分比率(24年1月1日現在)を使っています。

現在このβ版は、横浜市税だけを対象としたものですが、今後、利用者の皆さんや日本政府や全国の自治体の皆さんのご意見、ご要望を踏まえて、特別会計や公営企業会計も含めたり、市債発行額・償還額を含めたり、神奈川県税や国税を含めたりなど、ニーズに応じて、どんどん成長させて行きたいと考えております。是非、皆様からの忌憚のないご意見、ご要望、ご指摘をお願いいたします。

なお、このサイトは、公共データのオープン化によって、地域社会を変え、日本社会を変え、世界にも影響を与え、貢献して行こうという思いを持って集まった以下のメンバーによって構築、運営されています。


Core Team: (@は Twitter Account)

伊藤　大貴(Hirotaka Itou), @hirochan (Adviser)
川島　宏一(Hiroichi Kawashima), @hiroichi_k (Coordinator)
佐藤　宏之(Hiroyuki Sato), @sa2hi (Linked Open Data化)
関　治之(Hal Seki:@hal_sk), Hack For Japan (Developer)
高木　祐介(Takagi Yuusuke:@nyatakasan), (Developer)
高野　光弘(TAKANO Mitsuhiro), @takano32 (Developer)
竹内　久知(Takeuchi Hisatomo:@3Dfalcon), 機能型3Dアルバム (Designer)
田島　逸郎(Itsuro Tajima), @niryuu (Developer)
玉木　光(Tamaki Hikaru), Pearlpuppy.com (Designer)
西林　孝(Takashi Nishibayashi), @hagino3000 (Developer)
藤村　良弘(Fujimura Yoshihiro), Facebook:Fujimura Yoshihiro (Policy Analyst)


このソースコードは、Open Definition(http://opendefinition.org/) の定義に沿っていれば、どなたでも利用、改変、及び再配布が可能です。
http://qiita.com/items/38c186efbd272ef59121
に、このソースコードを Fork して独自のサイトを作る為のドキュメントがありますので、是非ご自由にお使いください。
あなたのサイトを作成したら、是非御連絡や Pull Request をいただければと思います。
