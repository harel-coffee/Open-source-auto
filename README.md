Source Code of 《Multi-modal data fusion for supervised learning-based identification of USP7 inhibitors: a systematic comparison》

---

### 1. Overall architecure

![Figure 1.jpg](https://s2.loli.net/2022/07/12/Q6lrSmyGkBAagXM.jpg)


### 2. Requirements:

- Python >= 3.6

- numpy

- pandas

- scikit_learn

- pytorch

- tqdm

  

### 3. Document Structure:

> │  LICENSE </br>
> │  README.md </br>
> │  requirements.txt&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Recommended Environment </br>
> ├─data&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# The origin dataset</br>
> ├─results&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Stored the results of the experiment 1-15</br>
> │       &nbsp;&nbsp;&nbsp;&nbsp;└─&nbsp;ML_results&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;#  experiment 1-7</br>
> │&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DL_results.xlsx&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;#  experiment 8-15</br>
> └─src&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Stored the main codes</br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├─DL-1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   #  The source code for experiment 14 corresponding to PartB in the figure. </br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;#  Experiment 8-13 only needs to change the inputs.</br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├─DL-2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   #  The source code of Experiment 15 corresponding to PartC in the figure.</br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└─ML&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     #  The source code of experiments 1-7 corresponding to PartA in the figure.</br>

 

### 4. Contact:

Hovi Tang: hovi@shu.edu.cn