# wasurenaide-audio-analyzer

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/beachcode111/wasurenaide-audio-analyzer/blob/main/Qwen2_Audio_wasurenaide_analyzer.ipynb)

[**iPhoneからColabで開く**](https://colab.research.google.com/github/beachcode111/wasurenaide-audio-analyzer/blob/main/Qwen2_Audio_wasurenaide_analyzer.ipynb)

Qwen2-Audioを使い、MP3/WAVを25秒ごとに分析して、曲全体の評価と修正案を日本語で表示するノートブックです。

## 使い方

1. 上の「Open in Colab」をタップしてGoogleアカウントで開きます。
2. Colabの「ランタイム」→「ランタイムのタイプを変更」で **T4 GPU** を選びます。
3. 上から順にセルを実行します。初回はライブラリとモデルの読み込みに時間がかかります。
4. 最後のセルに表示されるGradioのURLを開き、MP3/WAVを選んで「音源を分析」を押します。

このColabリンクはノートブックの固定リンクです。分析画面のURLはColabを起動するたびに変わります。GPUの提供状況はGoogle Colabの利用状況によります。
