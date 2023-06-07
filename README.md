- 「ファインチューニングLLMクラブ」という名称はかっこ悪いため、以後は「FTLLMクラブ」と略記することにする。

# プログラムの実行環境について
当レポジトリのプログラムは.ipynbファイルに記述されています。勉強会ではkaggleのカーネル上で実行する予定ですが、ローカルで実行する場合は以下の手順をふんでください。なおGPUがないとつらいことも多いです。

```shell
cd FTLLM_CLUB
python -m venv .env

source .env/Scripts/activate  # bash系のシェル
.env/Scripts/activate.bat     # windows系のシェル

pip -r requirements.txt
```

# コンテンツ
- [LLM(大規模言語モデル)の基本設計](./documents/gpt2.ipynb)
- [GPT系アテンション層の実装](./documents/attention.ipynb)
- [自然言語処理をディープラーニングと強化学習のフレームワークで理解する](./documents/nlp_with_dl_rl.ipynb)
- [RLHFとPPO](./documents/ppo.ipynb)
- [LangChainのchainとmemory](./documents/langchain.ipynb)

