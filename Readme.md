# Multilayer Multivariate Forecasting Network (MMRP)

Welcome to the repository for **"Multilayer Multivariate Forecasting Network for Precise Resource Utilization Prediction in Edge Data Centers"**, published in the journal **Future Generation Computer Systems**.

## 📄 Paper Information

**Title:** Multilayer Multivariate Forecasting Network for Precise Resource Utilization Prediction in Edge Data Centers  
**Journal:** Future Generation Computer Systems  
**DOI:** [10.1016/j.future.2024.107692](https://doi.org/10.1016/j.future.2024.107692)  
**Link:** [ScienceDirect Article](https://www.sciencedirect.com/science/article/pii/S0167739X24006563)

### Abstract
Efficient resource management and accurate prediction of cloud workloads are vital in modern cloud computing environments, where dynamic and volatile workloads present significant challenges. Traditional forecasting models often fail to fully capture the intricate temporal dependencies and non-linear patterns inherent in cloud data, leading to inefficiencies in resource utilization. To overcome these limitations, this research introduces the MultiLayer Multivariate Resource Predictor (MMRP), a novel deep learning architecture that seamlessly integrates a Multi-Head Attention Transformer model with Convolutional Neural Networks and Bidirectional Long Short-Term Memory units. The proposed model is designed to excel in capturing long-range dependencies and complex patterns, thereby significantly enhancing the accuracy of workload predictions. Extensive, rigorous experimentation using real-world Alibaba and Google cluster traces reveals that the proposed model consistently outperforms existing state-of-the-art models and related cloud resource utilization prediction in both univariate and multivariate time series forecasting tasks. The model demonstrates a remarkable improvement in prediction performance, with an average R squared increase of 5.76% and a Mean Absolute Percentage Error reduction of 84.9% compared to the best-performing baseline models. Furthermore, our model achieves a significant reduction in Root Mean Square Error by approximately 35.34% and decreases Mean Absolute Error by about 39.49% on average. Its scalability and adaptability across various cloud environments underscore the proposed model’s potential to optimize resource allocation, paving the way for more efficient and reliable cloud-based systems.

**Keywords:** Workload prediction, Cloud data center, Time series, Transformer, Attention mechanism, Convolution, Forecasting.

---

## 🛠️ Setup Instructions

To set up the environment required to reproduce or work on this project:

```bash
conda env create -f MMRPenv.yml
```

---

## 📊 Datasets

The datasets used in this work can be found at the following locations:

- [Alibaba Cluster Traces](https://github.com/alibaba/clusterdata)  
- [Google Cluster Traces](https://github.com/google/cluster-data)

---

## ✉️ Contact and Code Access

The code for this work will be made available upon request. Feel free to reach out to me via my LinkedIn profile:

[Shivani Tripathi on LinkedIn](https://www.linkedin.com/in/shivanitripathi1225)

---

## 📜 Citation

If you found this work helpful, please cite the following:

```bibtex
@article{MMRP2025,
    author = {Shivani Tripathi, Priyadarshni, Rajiv Misra, T.N. Singh},
    title = {Multilayer multivariate forecasting network for precise resource utilization prediction in edge data centers},
    journal = {Future Generation Computer Systems},
    year = {2025},
    pages = {107692},
    issn = {0167-739X},
    doi = {10.1016/j.future.2024.107692},
    url = {https://www.sciencedirect.com/science/article/pii/S0167739X24006563}
}
```

