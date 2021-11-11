# recommendation_session_based_ultradeep
A large-scale datasets for session-based recommendation  and sequential recommendation

Video-6M: https://drive.google.com/file/d/1wd3xzF9VnZ6r35nMb3-H4E31vWK87vjW/view?usp=sharing

This datasets includes around 6 million users and their sequential watching behaviors. It can be used for session-based recommendation  or sequential recommendation. You can use
Transformer or NextItNet to model user behaviors and may find that Video-6M is very good for validating expressiveness of deep recommendation models. In general, you can use over 100 layers for pursuring optimal accuracy.

```
@article{wang2020stackrec,
  title={StackRec: Efficient Training of Very Deep Sequential Recommender Models by Iterative Stacking},
  author={Wang, Jiachun and Yuan, Fajie and Chen, Jian and Wu, Qingyao and Li, Chengmin and Yang, Min and Sun, Yang and Zhang, Guoxiao},
  journal={Proceedings of the 44th International ACM SIGIR conference on Research and Development in Information Retrieval},
  year={2021}
}

@inproceedings{chen2021user,
  title={A User-Adaptive Layer Selection Framework for Very Deep Sequential Recommender Models},
  author={Chen, Lei and Yuan, Fajie and Yang, Jiaxi and Ao, Xiang and Li, Chengming and Yang, Min},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={35},
  number={5},
  pages={3984--3991},
  year={2021}
}

@article{yuan2019simple,
	title={A simple convolutional generative network for next item recommendation},
	author={Yuan, Fajie and Karatzoglou, Alexandros and Arapakis, Ioannis and Jose, Joemon M and He, Xiangnan},
	journal={Proceedings of the Twelfth ACM International Conference on Web Search and Data Mining},
	year={2019}
}
```
