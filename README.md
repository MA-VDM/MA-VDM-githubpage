<h1 align="center"> Video Examples </h1>

Finetuning on AnimateDiff+UCF101.

&nbsp;

<h2 align="left"> Examples with motion alignment </h2>

we show examples with Instantaneous Consistency (IC) motion alignment and Long-term Consistency (LC) motion alignment. 
During inference, we control the strength of the motion alignment by the lora scaling $\alpha$.

### $\alpha_{IC} = 0.01$, $\alpha_{LC} = 0.01$


<h3 align="center"> <img src="./ic0.01_lc0.01_grid_downsampled.gif" alt="alpha_ic_0.01_alpha_lc_0.01"> </h3>


&nbsp;

### $\alpha_{IC} = 0.3$, $\alpha_{LC} = 0.01$

With a stronger IC motion alignment, the subject/background consistency is better, less temporal flickering, and larger motion smoothness.
<h3 align="center"> <img src="./ic0.3_lc0.01_grid_downsampled.gif" alt="alpha_ic_0.3_alpha_lc_0.01"> </h3>


&nbsp;

### $\alpha_{IC} = 0.01$, $\alpha_{LC} = 0.6$

With a stronger LC motion alignment, the motion dynamic degree is higher.
<h3 align="center"> <img src="./ic0.01_lc0.6_grid_downsampled.gif" alt="alpha_ic_0.01_alpha_lc_0.6"> </h3>


&nbsp;

### $\alpha_{IC} = 0.3$, $\alpha_{LC} = 0.3$

Apply stronger IC and LC simultaneously, the motion is better, but aesthetic_quality and imaging_quality degrade. Joint training of two motion alignments may solve this issue.
<h3 align="center"> <img src="./ic0.3_lc0.3_grid_downsampled.gif" alt="alpha_ic_0.3_alpha_lc_0.3"> </h3>


&nbsp;
