# Seeker-Machine Status Monitoring

As a part of [Seeker Project](https://github.com/TheSeekerProject/Seeker-Main), we are releaseing (and will keep maintaining) a new dataset. This is one of few datasets publicly available on Machine status monitoring. As a part of deploying Seeker on real world, we tested Seeker on 4 different predictive maintenance datasets.

1. [Bearing Fault Dataset](https://engineering.case.edu/bearingdatacenter)
    + A popular public dataset for bearing fault detection
    + Analysis available in the paper
2. [TOOL WEAR DATASET OF NUAA_IDEAHOUSE](https://ieee-dataport.org/open-access/tool-wear-dataset-nuaaideahouse#)
    + Another publicly available dataset for tool wear prediction. It has it's own README files about the dataformat.
    + The data is noisy and the results using this dataset was not encouraging (for classification/ regression model development)
3. [A Griding Data Set](https://github.com/TheSeekerProject/Seeker-MachineStatus/tree/main/GridingDataSet)
    + Predicting the surface finish of a griding job from the statistical data using random forest
    + The code and implementation was taken from "[An Efficient Edge-Cloud Partitioning of Random Forests for Distributed Sensor Networks](https://ieeexplore.ieee.org/abstract/document/9931595)"
  4. [Machine Status Monitoring Dataset](https://github.com/TheSeekerProject/Seeker-MachineStatus/tree/main/MachineStatusDataSet)
      + Our own dataset developed from mounting sensors at two different positions on a [bridgeport machine](https://en.wikipedia.org/wiki/Bridgeport_(machine_tool_brand))
      + Desciption of the dataset and organization is given below.
