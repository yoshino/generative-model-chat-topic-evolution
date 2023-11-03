# Generative Model Chat Topic Evolution
[生成モデルに基づき雑談するエージェントの会話トピック選好性に関する文化進化](https://www.jstage.jst.go.jp/article/pjsai/JSAI2023/0/JSAI2023_4H3OS6b04/_article/-char/ja/)の実装(非公式)です。

<img width="608" alt="スクリーンショット 2023-11-03 12 02 08" src="https://github.com/yoshino/generative-model-chat-topic-evolution/assets/17586662/1be01e80-c951-450f-b1ff-1f6700e7c926">

[2023年度 人工知能学会全国大会 (第37回)](https://confit.atlas.jp/guide/event/jsai2023/subject/4H3-OS-6b-04/detail?lang=ja)より
> 近年生成モデルを用いたコミュニケーション創発過程への接近が注目されている。本研究は会話する人々が創る集団形成の理解のため、生成モデルに基づき雑談するエージェントの文化形質進化モデルを構築した。社会的な親密度を近さで表現した2次元空間上に個体が存在し、会話トピックの選好性を表す単語であり不変の遺伝形質（個性）と他者から受け取る複数の文化形質を持つ。それらを基に文章生成AI（GPT-2）で文を生成・発話し、近傍個体との発話中の単語共有度が閾値より大きい（小さい）場合に接近（離反）する。さらにごく近くの個体の発話からトピック単語を受け取る文化形質伝達が生じる。極性辞書におけるポジティブあるいはネガティブな単語を個性として持つ個体が各半数存在し文化形質伝達がない場合、複数の小個体群とそれに接近離反を繰り返す個体が生じ、前者はポジ、後者はネガ個体である傾向があった。これは、トピックの極性で発話の安定性や一般性が異なることを示唆する。文化形質伝達を導入した場合、この傾向が弱まり集団全体で交流する中で、極性に関係なく多くの個体に共有される主要な文化形質が生まれる等の傾向が観察された。

This Repository:
- model: [ELYZA-japanese-Llama-2-7b-fast-instruct](https://huggingface.co/elyza/ELYZA-japanese-Llama-2-7b-fast-instruct)
- execution environment: local mac(M2) 

