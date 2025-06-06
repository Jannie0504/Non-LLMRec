# Non-LLMRec: A Lightweight Recommendation Framework Inspired by LLM Analysis

## Examples to run the codes

The command to evaluate the backbone models and RLMRec is as follows.

- **Backbone**
  '''bach
  python encoder/train_encoder.py --model {model_name} --dataset {dataset} --cuda 0

- **RLMRec**
  '''bash
  python encoder/train_encoder.py --model {model_name} --dataset {dataset} --cuda 0

- **Non-LLMRec**
  '''bash
  python encoder/train_encoder.py --model {model_name} --dataset {dataset} --emb bert4rec_knn --cuda 0

Supported models/datasets:
**model_name: gccf, lightgcn, sgl, simgcl, autocf**
**dataset: amazon, yelp**

# 제안 모델은 코드/모델/proposed.py에 구현되어 있다.

# 제안 모델을 run하려면,
# python run.py를 실행하면 된다. 
