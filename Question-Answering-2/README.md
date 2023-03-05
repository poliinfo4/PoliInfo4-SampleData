# PoliInfo4-Question-Answering-2-SampleData

## 目的
Question Answering 2 は、会議録の質問の要約が与えられたときに、会議録から質問に対応する答弁を見つけだし、要約した結果を返すことを目的としています。

PoliInfo-3 で実施した Question Answering と同様に、2001 年以降の東京都議会（定例会）を対象とします。

- 入力
    - 都議会だよりに含まれる、議員の質問の要約（JSON フォーマット）
    - 本会議の会議録に含まれる、議員・答弁者（説明員）の発言（JSON フォーマット）
- 出力
    - 各質問に対応する答弁（説明）の簡潔な要約（JSON フォーマット）

## 配布ファイル
- 学習用ファイル（サンプル）
    - `QuestionAnswering2_Sample.json`
        - Question Answering で使用する学習データのサンプル

- 会議録ファイル（サンプル）
    - `PoliInfo4_Utterances_Sample.json`
        - 本会議の会議録に含まれる、議員・答弁者（説明員）の発言のサンプル
