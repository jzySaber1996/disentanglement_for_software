# Software-related Chat Disentanglement
This repository contains dataset and DLD metrics analysis. 
The 

## SOTA models
The state-of-art models and datasets are available as follow:

- [BiLSTM](https://github.com/layneins/e2e-dialo-disentanglement): Implemented by Liu et al.
- [FF](https://github.com/jkkummerfeld/irc-disentanglement/zipball/master): Implemented by Kummerfeld et al.
- [BERT](https://github.com/layneins/e2e-dialo-disentanglement): Implemented by Liu et al.
- [E2E](https://github.com/layneins/e2e-dialo-disentanglement): Implemented by Liu et al.
- [PtrNet](https://github.com/vode/onlinePtrNet_disentanglement): Implemented by Yu et al.

## Datasets

## Metrics
The source code of traditional metric is available in [utils.py](./utils.py), including NMI, ARI and Shen-F.

The F1 and DLD require the reformation of predicted data. Since the preprocessing data of intermediate steps are private for other works, we propose the 1st version of reformat code [reformat_e2d_source_data.py](reformat_e2d_source_data.py).

If you need the complete data of annotation and preprocessing, please contact us via [ziyou2019@iscas.ac.cn](mailto:ziyou2019@iscas.ac.cn)
## Diagrams
All diagrams of article are available in [diagrams](./diagrams) directory.