# Laugh_LSN
This repository contains corresponding data of our paper "Laugh Betrays You? Learning Robust Speaker Representation From Speech Containing Non-Verbal Fragments".

<a href="https://arxiv.org/abs/2210.16028">Paper arxiv </a>  |

# 0. Introduction
In this paper, we introduce our research on learning speaker embedding from speech containing laughter components. Laughter candidates are extracted from Voxceleb and CnCeleb and then feed into laughter detection binary classifier to obtain laughter clips. Finally, we leverage these clips to construct evaluation trials under two scenerios: Speech-Laughter(SL) and Laughter-Laughter. The figure is shown below.


![image](https://github.com/nevermoreLin/Laugh_LSN/blob/main/fig/pipeline.jpg?raw=true)
 
Therefore, this repository contains two kinds of data: laughter clips and evaluation trials.

# 1. Laughter clips 
All of our clips could be downloaded on :
<a href="https://drive.google.com/drive/folders/1kh72qXWssDhkmlAhrboms-teR2RJHOoo?usp=sharing">Google Drive </a>

 The general overview is shown below:
 
  ![image](https://github.com/nevermoreLin/Laugh_LSN/blob/main/fig/clips.jpg?raw=true)

For convenience, we provide some sample clips for you to have an intuitive appreciation on these clips.

<ul>
  <li>
    <a href="https://laughter-1304631821.cos.ap-shanghai.myqcloud.com/vox-id00358-laugh_2.mp3">vox-id00358-laugh_2</a>&nbsp&nbsp
    <a href="https://laughter-1304631821.cos.ap-shanghai.myqcloud.com/vox-id00398-laugh_1.mp3">vox-id00398-laugh_1</a>&nbsp&nbsp
    <a href="https://laughter-1304631821.cos.ap-shanghai.myqcloud.com/vox-id00633-laugh_5.mp3">vox-id00633-laugh_5</a>
  </li>
  <li>
    <a href="https://laughter-1304631821.cos.ap-shanghai.myqcloud.com/ent-id10293-laugh_1.mp3">ent-id10293-laugh_1</a>&nbsp&nbsp
    <a href="https://laughter-1304631821.cos.ap-shanghai.myqcloud.com/ent-id10534-laugh_0.mp3">ent-id10534-laugh_0</a>&nbsp&nbsp
    <a href="https://laughter-1304631821.cos.ap-shanghai.myqcloud.com/ent-id10683-laugh_3.mp3">ent-id10683-laugh_3</a>
  </li>
  <li>
    <a href="https://laughter-1304631821.cos.ap-shanghai.myqcloud.com/int-id10249-laugh_3.mp3">int-id10249-laugh_3</a>&nbsp&nbsp
    <a href="https://laughter-1304631821.cos.ap-shanghai.myqcloud.com/int-id10696-laugh_1.mp3">int-id10696-laugh_1</a>&nbsp&nbsp
    <a href="https://laughter-1304631821.cos.ap-shanghai.myqcloud.com/int-id10915-laugh_0.mp3">int-id10915-laugh_0</a>
  </li>
</ul>
Besides, the meta information could be found in <a href="https://github.com/nevermoreLin/Laugh_LSN/tree/main/clips/record">record_folder</a>, the structure follows the rule below???

```
    clip_name         origin_utterance_name      start_time         end_time
vox-id00035-laugh_3 id00035-TaejKlg4LoA-00106 5.880853972317141 7.892362753506518
vox-id00035-laugh_4 id00035-TaejKlg4LoA-00106 4.8268708881470275 6.47793589929671
      ....                   ....                  ....                ....      
```

# 2. Evaluation Set 

The following table shows the brief information of our evaluation set on two scenerios: **Speech-Laughter(SL)** and **Laughter-Laughter(LL)**. The trials can be found in <a href="https://github.com/nevermoreLin/Laugh_LSN/tree/main/trails">trials</a>.

![image](https://github.com/nevermoreLin/Laugh_LSN/blob/main/fig/trials.jpg?raw=true)
 
# 3. Experimental Result 

We utilize a novel method called **Laughter-Splicing Network (LSN)**, which can significantly boost performance on our proposed evaluation set. Experimental result are presented below: 

![image](https://github.com/nevermoreLin/Laugh_LSN/blob/main/fig/result.jpg?raw=true)

The following figure is our LSN model backbone.

<div align="center">
  <img src="https://github.com/nevermoreLin/Laugh_LSN/blob/main/fig/LSN.jpeg?raw=true" width=60%  />
</div>