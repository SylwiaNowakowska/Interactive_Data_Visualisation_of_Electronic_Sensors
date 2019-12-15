# INTERACTIVE DATA VISUALIZATION OF ELECTRONIC NOSE (Python: Bokeh library)

Dataset consists of signals recorded by R. Huerta *et al*., [1] via electronic nose consisting of 8 MOX gas sensors and a temperature and a humidity sensor. 
The electronic nose was placed in a home environment and was exposed to two different stimuli: banana and wine. Thr background activity was also recorded. [1, 2] 

The interactive visualization in Bokeh allows for comparison of signals resulting from different stimuli as well as for visualization of these signals decorellated from temperature and humidity. 

This project consist of:
1. Two jupyter notebooks: 
    - Data preparation 
    - Interactive visualization in Bokeh
2. Original data files: 
    - Dataset_Split10min.npy
    - Dataset_Split10min_hashtable.npy
    - HT_Sensor_metadata.dat
3. Modified data files (code in notebooks):
    - dataset_pd.pkl
    - dataset_pd_decorr.pkl
    - metadata_sub.pkl
    
References:
1. R. Huerta *et al*., Chemom. Intell. Lab. Syst. 157, 169-176 (2016).
2. UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Gas+sensors+for+home+activity+monitoring 

![Alt Text](https://github.com/SylwiaNowakowska/INTERACTIVE-DATA-VISUALIZATION-OF-ELECTRONIC-NOSE/blob/master/Gas%20Sensors%20-%20Interactive%20visualization.gif)
