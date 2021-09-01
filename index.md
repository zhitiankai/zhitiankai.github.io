---
layout: default
---
**Paper1**:This is the unofficial demo page for the paper [One-shot Voice Conversion by Separating Speaker and Content Representations with Instance Normalization](https://arxiv.org/abs/1904.05742)
## Abstract
Recently, voice conversion (VC) without parallel data has been successfully adapted to multi-target scenario in which a single model is trained to convert the input voice to many different speakers. 
However, such model suffers from the limitation that it can only convert the voice to the speakers in the training data, which narrows down the applicable scenario of VC. 
In this paper, we proposed a novel one-shot VC approach which is able to perform VC by only an example utterance from source and target speaker respectively, and the source and target speaker do not even need to be seen during training. 
This is achieved by disentangling speaker and content representations with instance normalization (IN).
Objective and subjective evaluation shows that our model is able to generate the voice similar to target speaker.
In addition to the performance measurement, we also demonstrate that this model is able to learn meaningful speaker representations without any supervision. 
- - -
### *Male to male(p237->p292)*
- - -
#### *Source*
<audio src="p237_001.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p237_p292_M_M/p237_018_p292_155_tar.wav" controls preload></audio>
#### *Converted*
<audio src="p237_1_p292.wav" controls preload></audio>
- - -
### *Female to male(p262->p256)*
- - -
| **Source**   | **Target**  |**Converted** |
|  ----  | ----  |----  |
| <audio src="res/demo/p262_p256_F_M/p262_027_p256_150_src.wav" controls preload></audio>  | <audio src="res/demo/p262_p256_F_M/p262_027_p256_150_tar.wav" controls preload></audio> | <audio src="res/demo/p262_p256_F_M/p262_027_p256_150_con.wav" controls preload></audio>|

#### *Source*
<audio src="res/demo/p262_p256_F_M/p262_027_p256_150_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p262_p256_F_M/p262_027_p256_150_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p262_p256_F_M/p262_027_p256_150_con.wav" controls preload></audio>
- - -
### *Female to female(p276->p294)*
- - -
#### *Source*
<audio src="res/demo/p276_p294_F_F/p276_064_p294_069_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p276_p294_F_F/p276_064_p294_069_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p276_p294_F_F/p276_064_p294_069_con.wav" controls preload></audio>
- - -
### *Male to female(p278->p310)*
- - -
#### *Source*
<audio src="res/demo/p278_p310_M_F/p278_047_p310_324_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p278_p310_M_F/p278_047_p310_324_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p278_p310_M_F/p278_047_p310_324_con.wav" controls preload></audio>
- - -
