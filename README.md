■サービス概要
ARを用いたメッセージアプリ。
カメラと座標機能を用いて、スマホなどのカメラで撮影した地点についてのユーザーからのメッセージをARで視覚的に残して、いわゆる口コミや感想などをカメラ越しに共有できるSNS的なツールのサービス

■ このサービスへの思い・作りたい理由
発想のきっかけになったのは自身が中学生のころから楽しませていただいた、とあるゲームのシリーズにおけるオンライン機能の一つです。
そのゲームにおいてはユーザー間のコミュニケーションツールの一つとして「ゆるく繋がる」というのをテーマに定型文の組み合わせでフィールドの様々な場所にメッセージを残せる仕様となっていましたが、これが実世界においても有用なコミュニケーションツールとなりうるのではと思い至り、開発してみようと考えました。

■ ユーザー層について
SNSでの発信が当たり前となっている10代～40代ぐらいのスマホで日常的にご飯や景色を撮影されるユーザーであれば楽しんでもらえるのではと考えています。

■サービスの利用イメージ
概要にもあるように口コミや感想などを実在の建物や道路などの景色に対してカメラ越しに見えるようなイメージです。
例えば、料理屋の店先に対して「〇〇というメニューが安くておいしい！」とか「店員さんの対応が素晴らしい」といった口コミ、観光地の絶景ポイントに対して「夕焼けがエモい！」みたいな感想、もしくはなんてことのない場所で「ここで猫が集会してるの見た」とか発見や報告のようなメッセージを視覚的に見れるようなイメージ。
カメラ越しにユーザーと同じ場所に来た人々の様々な反応が得られ、更にメッセージに対してのコメント機能などもあればコミュニケーションが広がるのではと考えています。

■ ユーザーの獲得について
メッセージを残した場所の撮影機能とXなどのSNSとの共有機能なども盛り込んで拡散していけるように開発できたらと考えているので、そこが導線としてユーザー獲得に繋がると想定しています。

  #想定したユーザー層に対してそれぞれどのようにサービスを届けるのか現状考えていることがあれば教えてください。

■ サービスの差別化ポイント・推しポイント
撮影場所に直接の伝言のようにメッセージを残せる想定なので利用イメージの感想や発見などの形でのサービスが他の類似アプリとの差別化であり、推しポイントといえると考えています。

  #似たようなサービスが存在する場合、そのサービスとの明確な差別化ポイントとその差別化ポイントのどこが優れているのか教えてください。  
  #独自性の強いサービスの場合、このサービスの推しとなるポイントを教えてください。

■ 機能候補
ログイン機能
撮影機能
AR投射機能
座標観測機能と撮影機能の連携
掲示板（SNS）的な機能
既存SNSアプリとの共有機能

  #現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないのでMVPリリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。

■ 機能の実装方針予定
AR関連
・AR.js
javaScriptで動作する、HTMLとJavaScriptだけでAR体験を実現できるから簡単に始められる

・AR.ToolKit
世界初のAR技術として開発したAR開発ツール。オープンソース化されていて無料で使用できる

  #一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもので良いので教えて下さい。