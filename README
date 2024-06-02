# MS2SL: Multimodal Spoken Data-Driven Continuous Sign Language Production
While current sign language translation technology has made significant strides, there is still no viable solution for generating sign sequences directly from spoken content, e.g., text or speech. 
In this paper, we propose a unified framework for continuous sign language production toease communication between sign and non-sign language users. The framework can capably convert multimodal 
spoken data (speech or text) into continuous sign keypoint sequences. In particular, a sequence diffusion model is crafted to step-by-step generate sign predictions, employing text or speech audio 
embeddings extracted by pretrained models like CLIP and HuBert. Moreover, by formulating a joint embedding space for text, audio, and sign, we bind data from the three modalities and leverage the 
semantic consistency across modalities to provide informative feedback signals for the training of diffusion model. This embedding-consistency learning strategy minimizes the reliance on triplet 
sign language data and ensures continuous model refinement, even with a missing audio modality. Experiments on How2Sign and PHOENIX14T datasets demonstrate that our model achieves competitive 
performance in producing signs from both speech and text data.

# How2Sign
## Text-to-Sign
**Text:** Let me demonstrate you this on my back because it's a lot easier.

<img src="samples/G3GcPpidwxk_9-5-rgb_front/G3GcPpidwxk_9-5-rgb_front.webp" width="1000" height="170" alt="WebP Image">
	
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**Text:** Right now, winter ties are probably the more popular way to go.

<img src="samples/G3GcPpidwxk_17-5-rgb_front/G3GcPpidwxk_17-5-rgb_front.webp" width="1000" height="170" alt="WebP Image">

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Text:** I have got some leather mittens here.

<img src="samples/-g0iPSnQt6w_14-1-rgb_front/-g0iPSnQt6w_14-1-rgb_front.webp" width="1000" height="170" alt="WebP Image">

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Text:** I have got some leather mittens here.

<img src="samples/fzOH00UZg84_2-8-rgb_front/fzOH00UZg84_2-8-rgb_front.webp" width="1000" height="170" alt="WebP Image">
	

## Audio-to-Sign

**Text:** And I'm actually going to lock my wrists when I pike.
<audio src="./samples/-g0iPSnQt6w_12-1-rgb_front/-g0iPSnQt6w_12-1-rgb_front.mp3" controls style="width: 300px;" type="audio/mpeg"></audio>

<img src="samples/-g0iPSnQt6w_12-1-rgb_front/-g0iPSnQt6w_12-1-rgb_front.webp" width="1000" height="170" alt="WebP Image">


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Text:** The rudder is the vertical stabilizer.
<audio src="./samples/-fZc293MpJk_6-1-rgb_front/-fZc293MpJk_6-1-rgb_front.mp3" controls style="width: 300px;" type="audio/mpeg"></audio>

<img src="samples/-fZc293MpJk_6-1-rgb_front/-fZc293MpJk_6-1-rgb_front.webp" width="1000" height="170" alt="WebP Image">

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Text:** There's the orange portal that we came out of and that's this test chamber.
<audio src="./samples/-g45vqccdzI_10-1-rgb_front/-g45vqccdzI_10-1-rgb_front.mp3" controls style="width: 300px;" type="audio/mpeg"></audio>

<img src="samples/-g45vqccdzI_10-1-rgb_front/-g45vqccdzI_10-1-rgb_front.webp" width="1000" height="170" alt="WebP Image">

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Text:** So, we've got to find a way to get to the exit.
<audio src="./samples/-g45vqccdzI_4-1-rgb_front/-g45vqccdzI_4-1-rgb_front.mp3" controls style="width: 300px;" type="audio/mpeg"></audio>

<img src="samples/-g45vqccdzI_4-1-rgb_front/-g45vqccdzI_4-1-rgb_front.webp" width="1000" height="170" alt="WebP Image">

