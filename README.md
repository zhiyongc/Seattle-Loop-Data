# Seattle Inductive Loop Detector Dataset V.1 (2015)

> Dataset for *Traffic Forecasting*

> <img src="https://github.com/zhiyongc/Seattle-Loop-Data/blob/master/DataLoop.png" width="600" height="400"></img>
### Data Download Link: [Seattle Loop Dataset](https://drive.google.com/drive/folders/1XuK0fgI6lmSUzmToyDdHQy8CPunlm5yr?usp=sharing)
#### The data is collected by the inductive loop detectors deployed on freeways in Seattle area. The freeways contains I-5, I-405, I-90, and SR-520. The speed information at each milepost is averaged from multiple loop detectors. 
---
#### The data download link contains a list of files:
* `speed_matrix_2015`: Loop Speed Matrix, which is a pickled file that can be read by pandas or other python packages
* `Loop_Seattle_2015_A.npy`: Loop Adjacency Matrix, which is a numpy matrix
* `Loop_Seattle_2015_reachability_free_flow_Xmin.npy`: Loop Free-flow Reachability Matrix during X minites' drive
* `nodes_loop_mp_list.csv`: List of loop detectors' milepost, with the same order of that in the Loop Speed Matrix 
---
#### If you use this dataset in your work, please cite the following reference:
###### Reference:
* `Cui, Z., Ke, R., & Wang, Y. (2018). Deep Bidirectional and Unidirectional LSTM Recurrent Neural Network for Network-wide Traffic Speed Prediction. arXiv preprint arXiv:1801.02143.`
* `Cui, Z., Henrickson, K., Ke, R., & Wang, Y. (2018). High-Order Graph Convolutional Recurrent Neural Network: A Deep Learning Framework for Network-Scale Traffic Learning and Forecasting. arXiv preprint arXiv:1802.07007.`
###### Bitex:
```
@article{cui2018deep,
  title={Deep Bidirectional and Unidirectional LSTM Recurrent Neural Network for Network-wide Traffic Speed Prediction},
  author={Cui, Zhiyong and Ke, Ruimin and Wang, Yinhai},
  journal={arXiv preprint arXiv:1801.02143},
  year={2018}
} ,
@article{cui2018high,
  title={High-Order Graph Convolutional Recurrent Neural Network: A Deep Learning Framework for Network-Scale Traffic Learning and Forecasting},
  author={Cui, Zhiyong and Henrickson, Kristian and Ke, Ruimin and Wang, Yinhai},
  journal={arXiv preprint arXiv:1802.07007},
  year={2018}
}
```
#### Note: This dataset should only be used for research.
