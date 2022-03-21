# Alphabet_Soup_applications
machine learning to predict Alphabet Soup funding applications

This worksheet uses deep learning in order to correctly identify applicants that will work correctly with Alphabet soup funding.  

This worksheet uses the following libraries:
    import pandas as pd
    from pathlib import Path
    import tensorflow as tf
    from tensorflow.keras.layers import Dense
    from tensorflow.keras.models import Sequential
    from sklearn.model_selection import train_test_split
    from sklearn.preprocessing import StandardScaler,OneHotEncoder

The following worksheet takes applicant data, then uses OneHotEncoder in order to convert the data from categorical data into numberical data. 
Next the worksheet uses standardscaler and creates three nueral networks models in order to show the accuarcy of how well each model worked.
Each model is saved in the second resources section under alphabet soup H5.

