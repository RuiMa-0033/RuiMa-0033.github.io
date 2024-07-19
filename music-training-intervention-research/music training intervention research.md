# **Spontaneous activity in the basal ganglia during the activation state on aging in a music training intervention**

 

## **Introduction**

​    After the exploring the hierarchy of the brain network, I continued the research about the data during high/low reward music stimulations among four groups (old controls, musicians; young controls, musicians). This time I deeply focused on the basal ganglia, a deep region of the brain which involved in emotional regulation and reward systems, to discovery some evidence, distinct with normal aging, that the basal ganglia also participant in the connection system between prefrontal cortex and the brain regions consist with primary sensory cortex.

 

## **Result** 

### Statics ALFF  

ALFF was quantified at each voxel for four groups by Brainnetome Atlas, which displayed a non-uniform spatial distribution across the brain in various music stimulations. Participants regardless of controls and musicians who listened to the favorite music showed less different ROIs than dislike music between older groups and younger groups. In the meanwhile, musicians showed less different ROIs between older groups and younger groups than controls no matter what kind of musical stimulation.

During the musician’s group, we found that when musicians listened to the favorite music, there were no significant difference in brain’s regions especially in primary perception cortex such as visual, auditory as well as somatosensory. The trends also occurred in ventral caudate during high reward music, however, when musicians listened to the music they dislike, the region also show significant difference between old and young. In the meanwhile, the musicians showed significant age difference in prefrontal cortex which is responsible for high cognitive functions.

During the controls, ALFF figures showed great age difference not only in the regions of primary sensory cortex, but also in the ventral caudate, associate high relative with emotional regulation and reward systems, both in two types of music. However, when they listen to the music, there was no difference in the region of prefrontal between old and young.

​                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          

Figure 1. Two sample t-test brain maps during older controls and younger controls(left) as well as older musicians and younger musicians(right) of statics ALFF values, the bar charts indicate the significant difference in the region of auditory, visual as well as ventral caudate.

### Statics ALFF prediction model

After performing the predictive model analyses, we found that statics ALFF value during high reward music task could predict the music training age during musicians (r = 0.66, p<0.001). 



Figure 2. statics ALFF predicts the music training age among musicians’ group. The result of ALFF as features to predict music training age is shown on the line chart (r = 0.6636, p<0.001). Filled circles were included in this correlation analysis indicate the individuals’ original and predict data. Solid line and dashed line with shadow represented the best-fitted line and 95% confidence interval of the Person’s correlation analysis, respectively. ALFF, amplitude of low-frequency fluctuation. 

### Functional connectivity result

During the functional connectivity result, controls showed significant difference between younger controls and older controls when they listened to the favorite music, especially between frontal lobe to the other regions, which indicated that compare to the old groups, the young controls show more robust connections between these regions. However, during musicians, we didn’t find the significant difference in the functional connection during old and young.



Figure 3. Functional connectivity significant difference results between younger controls and older controls (FDR correction, p<0.05).

 

## **Result**

​    We found that the value of ALFF in high award music could predict musicians’ music training years. Compared to musicians, control older adults had significantly lower ALFF values in the ventral caudate cortex than younger adults. In the meanwhile, connection between precentral gyrus and other region, especially in basal ganglia and sensory cortex were significant difference between younger controls and older controls. Older musicians outperformed older controls and showed comparable performance to younger musicians. However, musicians' spontaneous activity in the prefrontal lobes decreased with age, whereas no differences were shown in the control group.

 

 

 

 

## **Methods**

### Statics Alff calculation

To determine group-level temporal variability of ALFF, the fast Fourier transform was used as the average of the power spectrum’s square root in the 0.01–0.08 Hz frequency bandwidth. First, we used DynamicBC to calculate the statics ALFF for each subject in both types of music. Then One-way ANOVA analysis was performed to investigate the group differences of temporal variability of ALFF among four distinct groups (FDR correction, p<0.05).

 

### Music training age prediction

We predicted the music training age for each participant in musicians using a general linear model (GLM) in order to investigate the relationship between statics ALFF during music reward task and expertise in music measured by music training age. First, we used statics ALFF value in musicians as features. We applied a leave-one-out cross-validation (LOOCV) to establish the reliable model. In each LOOCV, we considered one subject as the test data, the other was used as train data to build the prediction model. After that the left-behind subjects were used to examine the training model. Finally, we used the Pearson’s correlation between predict data and original data to determine whether static ALFF could predict the musicians’ training age. If the statical significance level of p<0.05, we then considered that the statics ALFF could predict music training age among musicians’ group.



Figure4. Schematic diagram of the music training age ALFF-based predictive model.

### Functional connectivity calculation

To investigate the functional connectivity (FC) between region of interest (ROI), The Pearson correlation coefficient (Fisher-z transformed) was used as two different regions’ connectivity. DynamicBC was used to perform FC among four groups during music award task, after functional connectivity matrix were established, two sample t-test was used to compare the results between young controls and older controls as well as between younger musicians and older musicians (FDR correction, p<0.05). 

 