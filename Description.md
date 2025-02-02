# **TOPSIS-Based Evaluation of Pre-Trained Models for Text Sentence Similarity**

## **Objective**  
The goal of this analysis is to apply the **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** method to determine the best pre-trained model for **text sentence similarity**. This is achieved by evaluating multiple models based on various performance criteria.

## **Candidate Models**  
The following sentence similarity models are considered:  
- **BERT**  
- **RoBERTa**  
- **SBERT (Sentence-BERT)**  
- **Universal Sentence Encoder**  
- **DistilBERT**  

## **Evaluation Criteria**  
Each model is assessed based on five key criteria, where some require maximization (+) and others minimization (-):  
1. **Cosine Similarity (+)** – Measures sentence similarity accuracy. Higher is better.  
2. **Inference Speed (-)** – Measures the time taken for sentence similarity computation. Lower is better.  
3. **Model Size (-)** – Indicates the storage space required for the model. Lower is better.  
4. **Memory Usage (-)** – Represents RAM consumption during inference. Lower is better.  
5. **Dataset Performance (+)** – Evaluates accuracy on benchmark datasets. Higher is better.  

## **Methodology**  
1. **Decision Matrix Construction** – Performance values for each model are compiled into a matrix.  
2. **Normalization** – The decision matrix is normalized to ensure fair comparison across different metrics.  
3. **Weight Assignment** – Weights are assigned to reflect the relative importance of each criterion.  
4. **Computation of Ideal & Negative-Ideal Solutions** – The best and worst possible values for each metric are determined.  
5. **Distance Calculation** – The Euclidean distance of each model from the ideal and negative-ideal solutions is computed.  
6. **TOPSIS Score Computation** – A score is assigned to each model based on its proximity to the ideal solution.  
7. **Ranking** – Models are ranked based on their TOPSIS scores.  

## **Results**  
A table is generated displaying the **TOPSIS scores** and rankings of all models. Additionally, a **bar chart visualization** is included to illustrate the comparative performance of the models. The results are also saved as a **CSV file** for easy upload to GitHub.

## **Conclusion**  
The model with the **highest TOPSIS score** is identified as the best choice for text sentence similarity tasks. This structured approach ensures a balanced and data-driven model selection process.  

---

### 📌 **How to Use**  
1. Clone the repository.  
2. Run the Python script to compute TOPSIS scores.  
3. View the results in CSV format or visualize the rankings using the generated bar chart.  

Would you like any modifications or additional details? 🚀

