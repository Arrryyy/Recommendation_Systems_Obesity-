# Recommendation_Systems_Obesity

## Description

This dataset contains information related to predicting obesity based on various inputs. The dataset includes the following variables:

- **Gender**: Description of gender.
- **Age**: Description of age.
- **family_history_with_overweight**: Description of family history with overweight.
- **FAVC**: Description of FAVC (Frequency of consumption of high caloric food).
- **FCVC**: Description of FCVC (Frequency of consumption of vegetables).
- **NCP**: Description of NCP (Number of main meals).
- **CAEC**: Description of CAEC (Consumption of food between meals).
- **SMOKE**: Description of smoking habits.
- **CH2O**: Description of CH2O (Consumption of water daily).
- **SCC**: Description of SCC (Calories consumption monitoring).
- **FAF**: Description of FAF (Physical activity frequency).
- **TUE**: Description of TUE (Time using technology devices).
- **CALC**: Description of CALC (Caloric consumption monitoring).
- **Automobile**: Description of automobile usage.
- **Bike**: Description of bike usage.
- **Motorbike**: Description of motorbike usage.
- **Public_Transportation**: Description of public transportation usage.
- **Walking**: Description of walking habits.
- **NObeyesdad**: Description of the obesity class label.

Variables ignored in the recommendation system:

- **SCC**
- **FAF**
- **TUE**
- **CALC**
- **Automobile**
- **Bike**
- **Motorbike**
- **Public_Transportation**
- **Walking**

## Recommendation System Overview

This recommendation system aims to predict obesity based on a set of input features. The selected features are carefully chosen to capture relevant information about an individual's lifestyle, eating habits, and family history. The prediction model will be trained on a dataset containing historical data to learn patterns and relationships between the input variables and the target variable (NObeyesdad - obesity class label).

### Input Features

1. **Demographic Information:**
   - Gender
   - Age

2. **Lifestyle and Dietary Habits:**
   - Family history with overweight
   - Frequency of consumption of high caloric food (FAVC)
   - Frequency of consumption of vegetables (FCVC)
   - Number of main meals (NCP)
   - Consumption of food between meals (CAEC)
   - Smoking habits (SMOKE)
   - Consumption of water daily (CH2O)

### Output

- **NObeyesdad**: Obesity class label

## Usage

1. **Data Preprocessing:**
   - Handle missing values
   - Encode categorical variables
   - Normalize or scale numerical features

2. **Training the Model:**
   - Select a machine learning algorithm suitable for classification.
   - Split the dataset into training and testing sets.
   - Train the model using the training data.

3. **Evaluation:**
   - Evaluate the model's performance using the testing set.
   - Use appropriate metrics such as accuracy, precision, recall, and F1-score.

4. **Prediction:**
   - Utilize the trained model to predict obesity based on new input data.

## Dataset Citation

If you use this dataset or the recommendation system in your work, please cite the original source of the dataset to give credit to the creators.

## Contributors

This project has been solely undertaken in development by me. 

## License

MIT License

Copyright (c) 2024 Aryan Jain 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


