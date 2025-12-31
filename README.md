## **Detection of DDOS attacks by comparing classical machine learning method and deep learning methods**

![AI](images/robotic.jpg "NumPy Cheat Sheet")

## Dataset
The dataset used in this project is derived from the CICIDS 2017 dataset.
It consists of real network traffic captured in PCAP format and converted
into CSV files using CICFlowMeter. The dataset contains both benign traffic
and DDoS attack traffic with multiple flow-based features.

### Neural Networks and Algorithms 🤹‍♀️
* [📺 Desicion Trees](https://www.youtube.com/watch?v=jVh5NA9ERDA)
* [📺 Recurrent Neural Network](https://www.youtube.com/watch?v=y7qrilE-Zlc)
* [📺 LSTM](https://www.youtube.com/watch?v=BSpXCRTOLJA)
* [📺 Bidirectional LSTM](https://www.youtube.com/watch?v=bTXGpATdKRY)
* [📺 Support Vector Machine (SVM) ](https://www.youtube.com/watch?v=bTXGpATdKRY)

![Image](images/bwd_packet_length.jpg "image")

**Desicion Tree Classifier:**
![Predicted](images/predicted_attacks.jpg "predicted attacks")
## *Results of Networks and Algorithms* 🔮

| Framework | Information | 
| :--- | :--- |
| Bidirectional LSTM | 99.7 % 
| SVM | 97.12 %|
| Desicion Trees |99.95 % 

## 📁 How to Run
1. Place dataset CSV files in a `dataset/` folder
2. Open and run:
   - `Detection of DDOS Attack.ipynb`
   - `Desicion Trees.ipynb`
   - `Training_RNN_DDOS_Attack.ipynb`

## 🛠️ Dependencies
Install with:pip install pandas numpy scikit-learn tensorflow matplotlib seaborn
## 📌 Notes
- Dataset is large and not included; please download from the official source.
