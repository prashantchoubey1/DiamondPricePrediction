# DiamondPricePrediction
Steps:
1. Create a project folder
2. Create a virtual env inside the folder using system terminal
3. Open vscode using code . in terminal
4. Create a setup.py file - Install all dependencies using a file 
5. Create requirements.py file - Parameterizing the setup.py
6. Create a folder structure -
    a. src - 
        components - data ingestion.py, data transformation.py, model trainer.py [stores the pickle file in artifacts]
        pipelines - training_pipeline.py and prediction_pipeline.py
        exception.py - handling exceptions, for defining custom exceptions
        logger.py - this files stores log files in a required format, will be used similar to logging library
        utils.py - common methods like loading object and save objects
    b. notebooks-
        used for EDA
    c. templates - stores html files 
    d. application.py - flask application - used to define function to get and post and mapped to html files