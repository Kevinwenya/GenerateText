# GenerateText
文本生成--从原理到实现
# char-rnn-cn
基于char-rnn和tensorflow生成歌词
# 运行环境
python3 + tensorflow1.0
# 训练
## 训练RNN模型，训练歌词模型
python3 gen_lyrics.py 0
# 预测（生成歌词）
python3 gen_lyrics.py 1
## 训练RNN模型，训练生成诗歌
python3 train_rnn.py
## 预测生成古诗词
python3 test_rnn_model.py

