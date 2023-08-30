# brain_activity_decoding-NMA_CN_2023

Functional magnetic resonance imaging (fMRI) is a technique used to measure brain activity by detecting changes in blood flow.
Previous research has shown that different brain regions are activated during different cognitive tasks. For example, the frontal lobe is involved in math problem-solving, while the temporal lobe is involved in language processing. However, these studies have just focused on brain activity during one task.
 In this study, we aimed to identify the most important regions in the brain for detecting whether a person is reading a story or solving a math problem using language data in the Human Connectome Project (HCP) dataset.  
We hypothesized that some regions of the brain would show different activity patterns while reading a story compared to solving a math problem. 
Our second hypothesis is that if a model can decode the type of task that a participant did, it can also decode some features of our dataset for example the difficulty of the math problem.
We built a convolutional neural network (CNN) model to predict which task the participant was doing based on the language data in the HCP dataset, within the given time frame. We then used permutation feature importance to identify which regions were most important for predicting the tasks.
Our model analyzed the neural activity patterns in the brain during the tasks and identified several important networks, including the Posterior-Mu, Cingulo-Opercular, and Frontopariet networks. These networks were found to be significantly more important for predicting the type of the given stimuli compared to other regions in the brain.

Our findings contribute to a better understanding of the neural mechanisms underlying language processing during different cognitive tasks and highlight the importance of specific brain networks in this process. 
The limitations of our study include the limited sample size and the potential for bias in the HCP dataset.
Future research could expand on our findings, using larger and more diverse datasets to confirm our results and identify additional networks involved in language processing during cognitive tasks.  They can also extract more features from the model.
In conclusion, our study demonstrates the potential of using permutation feature importance to identify key brain networks involved in language processing during different cognitive tasks.

### Members of the Team: 
- Amirali Soltanmohammadi
- Milad Dehnoei
- Roza Hamidi
- Zahra Rahimi
- Mahya Nafissi

