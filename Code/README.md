This is the PyTorch implementation of the paper:

## Mixing It Up: Inducing Empathy and Politeness using Multiple Behaviour-aware Generators for Conversational Systems

## Requirements
pip install -r requirements.txt
```

## Experiment

### Training and Testing ###

python main.py --model experts  --label_smoothing --noam --emb_dim 300 --hidden_dim 300 --hop 1 --heads 2 --topk 5 --cuda --pretrain_emb --softmax --basic_learner --schedule 10000 --save_path save/

