# KorNLU Datasets

This is the dataset repository for our paper [_KorNLI and KorSTS: New Benchmark Datasets for Korean Natural Language Understanding_](https://arxiv.org/abs/2004.03289).

We introduce KorNLI and KorSTS, which are NLI and STS datasets in Korean.

## KorNLI

### Dataset Overview

| KorNLI                     | Total   | Train      | Dev.  | Test  |
| -------------------------- | ------- | ---------- | ----- | ----- |
| Source                     | -       | SNLI, MNLI | XNLI  | XNLI  |
| Translated by              | -       | Machine    | Human | Human |
| \# Examples                | 950,354 | 942,854    | 2,490 | 5,010 |
| Avg. \# words (premise)    | 13.6    | 13.6       | 13.0  | 13.1  |
| Avg. \# words (hypothesis) | 7.1     | 7.2        | 6.8   | 6.8   |


### Examples

| Example                                                      | English Translation                                          | Label         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------- |
| P: 저는, 그냥 알아내려고 거기 있었어요.<br />H: 이해하려고 노력하고 있었어요. | I was just there just trying to figure it out.<br />I was trying to understand. | Entailment    |
| P: 저는, 그냥 알아내려고 거기 있었어요.<br />H: 나는 처음부터 그것을 잘 이해했다. | I was just there just trying to figure it out.<br />I understood it well from the beginning. | Contradiction |
| P: 저는, 그냥 알아내려고 거기 있었어요.<br />H: 나는 돈이 어디로 갔는지 이해하려고 했어요. | I was just there just trying to figure it out.<br />I was trying to understand where the money went. | Neutral       |


## KorSTS

### Dataset Overview

| KorSTS        | Total | Train   | Dev.  | Test  |
| ------------- | ----- | ------- | ----- | ----- |
| Source        | -     | STS-B   | STS-B | STS-B |
| Translated by | -     | Machine | Human | Human |
| \# Examples   | 8,628 | 5,749   | 1,500 | 1,379 |
| Avg. \# words | 7.7   | 7.5     | 8.7   | 7.6   |


### Examples

| Example                                                      | English Translation                                      | Label |
| ------------------------------------------------------------ | -------------------------------------------------------- | ----- |
| 한 남자가 음식을 먹고 있다.<br />한 남자가 뭔가를 먹고 있다. | A man is eating food.<br />A man is eating something.    | 4.2   |
| 한 비행기가 착륙하고 있다.<br />애니메이션화된 비행기 하나가 착륙하고 있다. | A plane is landing.<br />A animated airplane is landing. | 2.8   |
| 한 여성이 고기를 요리하고 있다.<br />한 남자가 말하고 있다. | A woman is cooking meat.<br />A man is speaking.      | 0.0   |


## License

[Creative Commons Attribution-ShareAlike license (CC BY-SA 4.0)](http://creativecommons.org/licenses/by-sa/4.0/)

## References

If you use KorNLI or KorSTS for research, please cite our paper:
```bibtex
@article{ham2020kornli,
  title={KorNLI and KorSTS: New Benchmark Datasets for Korean Natural Language Understanding},
  author={Ham, Jiyeon and Choe, Yo Joong and Park, Kyubyong and Choi, Ilji and Soh, Hyungjoon},
  journal={arXiv preprint arXiv:2004.03289},
  year={2020}
}
```
