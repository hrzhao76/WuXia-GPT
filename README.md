# WuXia-GPT
My playground for WuXia(literally martial arts and chivalry) text generator based on [`NanoGPT`](https://github.com/karpathy/nanoGPT). 

## Tokenization

Two approaches were explored, the `char` mode and the `jieba` default. The example outputs are in [ouputs](./TianLong/outputs/) with names `samples.txt`. 

## Pretraining
``` bash
cd TianLong/
python train.py config/TianLong_jieba.py

```

## Generation
``` bash 
python sample.py --out_dir=outputs/TianLong-jieba/
```