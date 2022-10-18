# <center> NSV-TTS: Non-speech vocalization modeling and transfer in Emotional Text-to-speech</center>

<center> Author name</center>  


<center>Netease Games AI Lab, Guangzhou, China</center>  

## Abstract
This paper addresses the problem of non-speech verbal (NSV) modeling and transfer in emotional TTS. The goal is to transfer NSV to the target speaker, whose training data contains no NSV samples. We utilize unsupervised learning to extract unsupervised linguistic units for NSV labeling. Besides that, we propose token mixing and random masking to mitigate the training-inference mismatch problem. We evaluate the proposed method on various NSV types and emotion classes. The experimental results reveal that using ULUs as the input representation does not affect the emotional TTS performance. Furthermore, the proposed method provides a decent performance in the NSV transfer task. Lastly, we conduct ablation studies to investigate the proposed method further. 
Paper link: [arXiv](Not Available so far ...)  


## Zero-shot NSV Transfer Demo


### Cough

| **Anger** | **Disgust** | **Doubt** | **Fear** | **Sad** | **Surprise** |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <audio src="wavs/cough/anger/0.wav" controls preload></audio> | <audio src="wavs/cough/disgust/0.wav" controls preload></audio> | <audio src="wavs/cough/fear/0.wav" controls preload></audio> | <audio src="wavs/cough/sad/0.wav" controls preload></audio> | <audio src="wavs/cough/surprise/0.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="wavs/cough/anger/1.wav" controls preload></audio> | <audio src="wavs/cough/disgust/1.wav" controls preload></audio> | <audio src="wavs/cough/fear/1.wav" controls preload></audio> | <audio src="wavs/cough/sad/1.wav" controls preload></audio> | <audio src="wavs/cough/surprise/1.wav" controls preload></audio> |
| --- | --- | --- |

### Cry

| **Fear** | **Sad** | 
| :--- | :--- |
| <audio src="wavs/cry/fear/0.wav" controls preload></audio> | <audio src="wavs/cry/fear/0.wav" controls preload></audio> |
| --- | --- |
| <audio src="wavs/cry/fear/1.wav" controls preload></audio> | <audio src="wavs/cry/fear/1.wav" controls preload></audio> |
| --- | --- |


### Fright

| **Fear** |
| :--- |
| <audio src="wavs/fright/fear/0.wav" controls preload></audio> |
| --- |
| <audio src="wavs/fright/fear/1.wav" controls preload></audio> |
| --- |


### laughter

| **Happy** |
| :--- |
| <audio src="wavs/laughter/happy/0.wav" controls preload></audio> |
| --- |
| <audio src="wavs/laughter/happy/1.wav" controls preload></audio> |
| --- |

### Struggle

| **Fear** | **Surprise** |
| :--- | :--- |
| <audio src="wavs/struggle/fear/0.wav" controls preload></audio> | <audio src="wavs/struggle/surprise/0.wav" controls preload></audio> |
| --- | --- |
| <audio src="wavs/struggle/fear/1.wav" controls preload></audio> | <audio src="wavs/struggle/surprise/1.wav" controls preload></audio> |
| --- | --- |


