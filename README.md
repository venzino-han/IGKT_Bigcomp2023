# Inductive Graph-based Knowledge Tracing 
[Bigcomp2023](https://ieeexplore.ieee.org/abstract/document/10066831)

```
@inproceedings{han2023inductive,
  title={Inductive Graph-based Knowledge Tracing},
  author={Han, Donghee and Kim, Daehee and Han, Keejun and Yi, Mun Yong},
  booktitle={2023 IEEE International Conference on Big Data and Smart Computing (BigComp)},
  pages={92--99},
  year={2023},
  organization={IEEE}
}
```

# Datasets 
- EdNet dataset from : https://github.com/riiid/ednet
- ASSIST2017 dataset from : https://sites.google.com/view/assistmentsdatamining
- Pre-processed dataset in `data` directory. (only ASSIST2017 dataset in this repository)
<br />

# Docker Container
- Docker container use cgmc project directory as volume 
- File change will be apply directly to file in docker container

# Train 
1. `make up` : build docker image and start docker container
2. check `train_config/train_list.ymal` file (default: assist2017 with igmc, igkt, igkt_ts and igkt_gat)
3. `python3 src/train.py` : start train in docker container

<br />
