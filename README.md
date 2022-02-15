# Job-Prediction-Data-Mining-Analysis-and-ML
Analysis Report has been attached which contains:
1. **Information of the Dataset**<br/>
&nbsp;&nbsp;a. type/Count and Non Null information about the dataset<br/>
&nbsp;&nbsp;b. unique values in each Non Numeric column<br/>
&nbsp;&nbsp;c. HeatMap<br/>

2. **Data Preprocessing and Analysis**<br/>
&nbsp;&nbsp;a. Handling if any missing values<br/>
&nbsp;&nbsp;b. Checking if the percentage values lie between 0 to 100<br/>
&nbsp;&nbsp;c. Label Encoding the Categorical/Non-Numeric Values<br/>
&nbsp;&nbsp;d. Feature Scaling the Numeric Values<br/>

3. **Combining the Output Labels**<br/>
&nbsp;&nbsp;a. Manually Combining the labels<br/>
&nbsp;&nbsp;b. Combining Features using Cosine Similarity between labels<br/>

4. **Feature Selection**<br/>

5. **Model Evaluation/Experiments and Analysis**<br/>
&nbsp;&nbsp;a. ANN Model on both types of Output Clubbing Techniques and Varying Test
Sizes<br/>
&nbsp;&nbsp;&nbsp;&nbsp;i. Output Columns Clustering Technique 1 - Manually with Varying Test Size [0.1,0.2,0.3,0.4,0.5]<br/>
&nbsp;&nbsp;&nbsp;&nbsp;ii. Output Columns Clustering Technique 2 - Cosine Similarity with Varying Test Size [0.1,0.2,0.3,0.4,0.5]<br/>
&nbsp;&nbsp;b. ANN Model on both types of Output Clubbing Techniques and Varying
Hidden Layers and Neurons<br/>
&nbsp;&nbsp;&nbsp;&nbsp;i. Output Columns Clustering Technique 1 - Manually with varying
neurons and layers of the hidden layer:
hidden_layers=[(50),(50,50),(25,25),(50,25),(50,50,50),(50,50,25),(50,25,2
5),(50,50,25,25),(50,50,50,25),(50,50,50,50)]<br/>
&nbsp;&nbsp;c. ANN Model on Feature Selection Data on both thee techniques:<br/>
