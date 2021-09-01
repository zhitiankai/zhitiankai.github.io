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
<audio src="p292_001.wav" controls preload></audio>
#### *Converted*
<audio src="p237_1_p292.wav" controls preload></audio>
- - -
### *Female to male(p262->p256)*
- - -
#### *Source*
<audio src="p262_001.wav" controls preload></audio>
#### *Target*
<audio src="p256_001.wav" controls preload></audio>
#### *Converted*
<audio src="p262_1_p256.wav" controls preload></audio>
- - -
### *Female to female(p276->p294)*
- - -
#### *Source*
<audio src="p276_002.wav" controls preload></audio>
#### *Target*
<audio src="p294_002.wav" controls preload></audio>
#### *Converted*
<audio src="p276_2_p294.wav" controls preload></audio>
- - -
### *Male to female(p278->p310)*
- - -
#### *Source*
<audio src="p278_002.wav" controls preload></audio>
#### *Target*
<audio src="p310_002.wav" controls preload></audio>
#### *Converted*
<audio src="p278_2_p310.wav" controls preload></audio>
- - -
### *THS dataset(spk1->spk2)*
- - -
#### *Source*
<audio src="spk1_81.wav" controls preload></audio>
#### *Target*
<audio src="spk2_81.wav" controls preload></audio>
#### *Converted*
<audio src="spk1_81_spk2.wav" controls preload></audio>
- - -
**Paper2**:This is the unofficial demo page for the paper [A One-shot Voice Conversion using Activation Guidance and Adaptive Instance Normalization](https://arxiv.org/abs/2011.00316)
## Abstract
Recently, voice conversion (VC) has been widely studied.Many VC systems use disentangle-based learning techniques to separate the speaker and the linguistic content information
from a speech signal. Subsequently, they convert the voice by changing the speaker information to that of the target speaker.
To prevent the speaker information from leaking into the content embeddings, previous works either reduce the dimension or quantize the content embedding as a strong information
bottleneck. These mechanisms somehow hurt the synthesis quality. In this work, we propose AGAIN-VC, an innovative VC system using Activation Guidance and Adaptive Instance
Normalization. AGAIN-VC is an auto-encoder-based model,comprising of a single encoder and a decoder. With a proper activation as an information bottleneck on content embeddings, the trade-off between the synthesis quality and the speaker similarity of the converted speech is improved drastically. This one-shot VC system obtains the best performance
regardless of the subjective or objective evaluations.
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
