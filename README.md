# Prototypes of Temporally Activated Patterns

<img align="right" src="http://sailab.kaist.ac.kr/research-ptap/>

Deep neural networks have demonstrated competitive performance in classification tasks for sequential data. However, it remains difficult to understand which temporal patterns the internal channels of deep neural networks capture for decision-making in sequential data. To address this issue, we propose a new framework with which to visualize temporal representations learned in deep neural networks without hand-crafted segmentation labels. Given input data, our framework extracts highly activated temporal regions that contribute to activating internal nodes and characterizes such regions by prototype selection method based on Maximum Mean Discrepancy. Representative temporal patterns referred to here as Prototypes of Temporally Activated Patterns (PTAPs) provide core examples of sub-sequences in the sequential data for interpretability. We also analyze the role of each channel by Valeu-LRP plots using representative prototypes and the distribution of the input attribution. Input attribution plots give visual information to recognize the shapes focused on by the channel for decision-making.

                    
## Dataset 
We use time series datasets of [UCR repository](https://www.cs.ucr.edu/~eamonn/time_series_data/) ; Uwave (UWaveGestureLibraryAll), FordA and Starlight (StarlightCurves). And Smartphone Dataset for Human Activity Recognition (HAR) is a smartphone sensor dataset that records a person performing eight different activities. In this paper, we mainly use Uwave dataset, but other datasets show similar results.
                
                        
## Requirement
Our code is able to run on Colab. If you want to run in your local, you need; Keres >= 2.2.1, CPU Memore > 1TB                        
                        
                        
## details                        
http://sailab.kaist.ac.kr/wp-content/uploads/2021/06/PTAP_figure_main-1024x351.png
                        
                        
## Reference Code 
https://github.com/BeenKim/MMD-critic                        


## License
[Apache License 2.0](https://github.com/OpenXAIProject/tutorials/blob/master/LICENSE "Apache")


<br /> 
<br />

# XAI Project 

**These works were supported by Institute for Information & Communications Technology Promotion (IITP) grant funded by the Korea government (MSIT) (No.2017-0-01779, A machine learning and statistical inference framework for explainable artificial intelligence)**

+ Project Name : A machine learning and statistical inference framework for explainable artificial intelligence(의사결정 이유를 설명할 수 있는 인간 수준의 학습·추론 프레임워크 개발)

+ Managed by Ministry of Science and ICT/XAIC <img align="right" src="http://xai.unist.ac.kr/static/img/logos/XAIC_logo.png" width=300px>

+ Participated Affiliation : UNIST, Korea Univ., Yonsei Univ., KAIST, AItrics  

+ Web Site : <http://openXai.org>
