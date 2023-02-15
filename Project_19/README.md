# Graduation project - Prediction of steel temperature on steel manufacturing

Steel manufacturing company requested to develop the system for the prediction of steel temperature for the optimization of electricity costs. Based on the provided data from company it's required to conduct an analysis and train a models for the prediction of the steel temperature.

**Project goal:** train a model for the prediction of the steel temperature for optimization of electricity cost during production..

The tasks to be completed for goal achievement:
1) To connect to database and load the initial data;
2) Overview the data and conduct the exploratory data analysis;
3) To prepare the data, select the target and features;
4) Train the models;
5) Select the best model and test it.

Provided data includes seven datasets:
- steel.data_arc data on electrodes usage,
- steel.data_bulk - data on bulk materials (volume),
- steel.data_bulk_time - data on bulk materials (time),
- steel.data_gas - data on gas usage (quantity),
- steel.data_temp - results of temperature measurement,
- steel.data_wire - data on wired materials (volume),
- steel.data_wire_time - data on wired materials (time).

## Data description

Dataset steel.data_arc
    - key - batch number,
    - BeginHeat - start heating time,
    - EndHeat - finish heating time,
    - ActivePower - value of active power,
    - ReactivePower value of reactive power.

Dataset steel.data_bulk
    - key - batch number,
    - Bulk1 ... Bulk15 - quantity of inserted material.

Dataset steel.data_bulk_time
    - key - batch number,
    - Bulk1 ... Bulk15 - time of inserted material.

Dataset steel.data_gas
    - key - batch number,
    - gas - quantity of inserted gas.

Dataset steel.data_temp
    - key - batch number,
    - MesaureTime - measurement time,
    - Temperature - temperature value.

Dataset steel.data_wire
    - key - batch number,
    - Wire1 ... wire15 -  quantity of inserted wired material.
Dataset steel.data_wire_time
    - key - batch number,
    - Wire1 ... Wire15 - time of inserted wired material.

All datasets has columns "key" with batch number. 
Datasets could have several rows with same key: the recurrence is related to the number of iteration.