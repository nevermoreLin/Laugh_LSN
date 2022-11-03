# Laugh_LSN
This repository contains corresponding data of our paper "Laugh Betrays You? Learning Robust Speaker Representation From Speech Containing Non-Verbal Fragments".

<a href="https://arxiv.org/abs/2210.16028">Paper arxiv </a>  |

# 0. Introduction
In this paper, we introduce our research on learning speaker embedding from speech containing laughter components. Laughter clips are extracted from Voxceleb and CnCeleb and then feed into laughter detection binary classifier. Finally, we leverage these clips to construct evaluation trials under two scenerios: Speech-Laughter(SL) and Laughter-Laughter. The figure is shown below.


![image](https://github.com/nevermoreLin/Laugh_LSN/blob/main/fig/pipeline.jpg?raw=true)
 
Thus this repository contains two kinds of data: laughter clips and evaluation trials.

# 1.Laughter clips 
All of our clips could be downloaded on :
<a href="https://drive.google.com/drive/folders/1kh72qXWssDhkmlAhrboms-teR2RJHOoo?usp=sharing">Google Drive </a>

 The general overview is shown below: ![image](https://github.com/nevermoreLin/Laugh_LSN/blob/main/fig/clips_info.jpg?raw=true)

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