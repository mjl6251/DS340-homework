### Reverse Dictionary

## What Is a Reverse Dictionary?
The reverse dictionary is a model that takes the description of the semantics of the target word as input, and outputs the target word and other words that match the description.

## How To Use Our System
Run diff.py in terminal or python to enter the definition of words. It will give the possible words you are trying to find in rank. You can keep enter word definitions until you stop the program.

### Core Model

The core model is based on our proposed **Multi-channel Reverse Dictionary Model** [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/5365/5221)] [[code](https://github.com/thunlp/MultiRD)], as illustrate in the following figure.

<div align=center>
<img src="resources/MRD_model.png" alt="model" width = "500" />
</div>


### Pre-trained Models and Data

You can [download](https://cloud.tsinghua.edu.cn/d/811dcb428ed24480bc60/) and decompress the pre-trained models and data to `BASE_PATH/website_RD/` to reimplement the system.


## Cite

If the code or data help you, please cite the following two papers.

```
@inproceedings{qi2020wantwords,
  title={WantWords: An Open-source Online Reverse Dictionary System},
  author={Qi, Fanchao and Zhang, Lei and Yang, Yanhui and Liu, Zhiyuan and Sun, Maosong},
  booktitle={Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing: System Demonstrations},
  pages={175--181},
  year={2020}
}

@inproceedings{zhang2020multi,
  title={Multi-channel reverse dictionary model},
  author={Zhang, Lei and Qi, Fanchao and Liu, Zhiyuan and Wang, Yasheng and Liu, Qun and Sun, Maosong},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  pages={312--319},
  year={2020}
}
```



