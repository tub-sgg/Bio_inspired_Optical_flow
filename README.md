# *Optical flow estimation using space-time separable filters*

This is the code used to produce filter part(Section 2.2 and Section 3.1) of the  results published in  
Tobias Brosch, Stephan Tschechne and Heiko Neumann(2015)On event-based optical flow detection.frontier in neuroscience
But generating these result needs pre-knowledge included in  
(Section 3 )Stephan Tschechne, Roman Sailer, and Heiko Neumann()Bio-Inspired Optic Flow from Event-Based Neuromorphic Sensor Input,
and (Section 3.1 )Stephan Tschechne,Tobias Brosch,Roman Sailer. On event-based motion detection and integration   
  
  
####The repository contains the following:  

>-Python code:  in the folder:src
> > 1.optical_flow.ipynb 
> > > a.definition of  spatial and temporal filters  
> > > b. visualization of filters above in 2d or 3d view   
>>>c.implementation of equation (Eq 23) in the first paper and visualization  
>>>d.using aggregation to calculate the velocity at each pixel for optical flow  based on separable filters and visualization(Eq.33 in first paper)  
>>>e. .npy files are the intermediate filter  
>
>>2.util.py
>>>some useful tools for loading data , the time consuming calculation, plotting tools and etc,this code
is provided by  https://github.com/cedric-scheerlinck/jupnote_event_demo  


>-Dataset:  
>>event data is located in the folder :slider_far.in this project, only the events.txt is used  

>-Figures:  
>> the generated figures are saved in the folder: output_figures  

>-Papers: 
>>the related papers are saved in the folder:related_papers.It contains all the three papers which has been used in the
this project


#### Dependencies of this code
numpy,  
matiplotlib,  
pandas,  
opencv,  
scipy

