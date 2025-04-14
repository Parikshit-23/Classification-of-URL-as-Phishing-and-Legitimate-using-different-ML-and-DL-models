# Classification-of-URL-as-Phishing-and-Legitimate-using-different-ML-and-DL-models

## 📌 Project Overview

This project aims to build a robust classification model that can effectively distinguish between legitimate and phishing URLs using various Machine Learning (ML) and Deep Learning (DL) techniques. By leveraging the structural and behavioral features of URLs, we aim to identify phishing attempts before they pose a threat to users.

---

## 📂 Dataset

- **Total Samples**: 20,000 URLs  
  - 10,000 Legitimate URLs  
  - 10,000 Phishing URLs
- **Type**: Binary Classification  
- **Label**: `1` for phishing, `0` for legitimate

---

## 🧠 Features Used

| Feature           | Description                                           |
|-------------------|-------------------------------------------------------|
| `haveIP`          | Presence of IP address in the URL                     |
| `have_@`          | Presence of '@' symbol in the URL                     |
| `URL_length`      | Length of the URL                                     |
| `URL_depth`       | Depth of the URL (number of subdirectories)           |
| `Redirection`     | Use of '//' in the URL indicating possible redirection|
| `https_domain`    | Use of HTTPS in domain                                |
| `Tiny_URL`        | Usage of URL shortening services                      |
| `Prefix/suffix`   | Use of '-' in domain name                             |
| `DNS_record`      | Availability of DNS record                            |
| `Web_traffic`     | Ranking information of website                        |
| `domain_age`      | Age of the domain                                     |
| `iFrame`          | Presence of iframe tags in the page                   |
| `mouse_over`      | Use of mouse-over events to hide links                |
| `right_click`     | Right-click functionality disabled                    |
| `web_forward`     | Number of web forwards                                |

---

## 🛠️ Models Used

### 🧪 Machine Learning Models
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost Classifier

### 🤖 Deep Learning Models
- Multi-layer Perceptron (MLP)
- Autoencoder Neural Network

---

## 📊 Evaluation Metrics

- **Accuracy**
- **Precision**

Each model was evaluated based on the above metrics to compare their performance in phishing URL detection.

---

## 📈 Power BI Dashboard (Optional Component)

An interactive Power BI dashboard was developed to visualize:

- Distribution of legitimate vs. phishing URLs
- Feature importance across models
- Model performance comparison
- Prediction interface (optional: input URL and get classification)

*(Screenshots or .pbix file can be added here if included)*

---

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Classification-of-URL-as-Phishing-and-Legitimate-using-different-ML-and-DL-models.git
cd Classification-of-URL-as-Phishing-and-Legitimate-using-different-ML-and-DL-models
