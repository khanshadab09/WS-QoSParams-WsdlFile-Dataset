# Integrated Dataset README (Version 1.0)

**Last updated:** 2025/12/11

---

## 📘 ABOUT THE DATASET

The Integrated Dataset incorporates QoS parameters along with OWL-S Semantic Web Service descriptions presented in dual formats — Natural Language and SWRL/KIF.

The research utilized **QWS (Dataset-1)** and **WS-DREAM (Dataset-2)**, selected for their comprehensive QoS metadata and verified WSDL URIs.

The dataset integrates:
- QoS metrics  
- Semantic service descriptions in **OWL-S**
- Two semantic formats: **NL OWL** and **SWRL/KIF (SWRL OWL)**

Semantic descriptions were successfully generated for:
- **169 services** from QWS (Dataset-1)
- **286 services** from WS-DREAM (Dataset-2)

Each service is represented in both semantic formats, resulting in:
- **910 OWL-S semantic files**

---

## 📊 Semantic File Summary

```
+-----------------------+------------------+------------------------+-------------+
| Dataset               | NL Format (OWL-S)| SWRL/KIF Format (OWL-S)| Total Files |
+-----------------------+------------------+------------------------+-------------+
| QWS (Dataset-1)       | 169              | 169                    | 338         |
+-----------------------+------------------+------------------------+-------------+
| WS-DREAM (Dataset-2)  | 286              | 286                    | 572         |
+-----------------------+------------------+------------------------+-------------+
| Total Semantic Files  | 455              | 455                    | 910         |
+-----------------------+------------------+------------------------+-------------+
```

- **Dataset download link:**  
    https://github.com/khanshadab09/WS-QoSParams-WsdlFile-Dataset.git
- **View the dataset details link:**
    https://khanshadab09.github.io/WS-QoSParams-WsdlFile-Dataset/
---

## 📂 List of Contents

### **WS_Integrated_Dataset/**
```
└── Integrated_Dataset.xlsm
```

A macro-enabled Excel workbook containing:
- Two sheets: **QWS (Dataset-1)** and **WS-DREAM (Dataset-2)**
- QoS details preserved as provided
- Final columns containing hyperlinks to OWL-S semantic description files
- Both Natural Language and SWRL/KIF semantic descriptions

---

### **WS_Semantic_Description_Files/**
```
└── QWS Ver 2
    ├── NL OWL
    └── SWRL OWL
└── WS-DREAM Dataset1
    ├── NL OWL
    └── SWRL OWL
```

The **NL OWL** and **SWRL OWL** directories store the semantic description files of the web services in Natural Language and SWRL/KIF formats, respectively.

---

## 📚 References

### **QWS (Dataset-1):**
Please cite the following when using this dataset:

- Al-Masri, E., & Mahmoud, Q. H. *Investigating web services on the world wide web.* WWW ’08, pp. 795–804.
- Al-Masri, E., & Mahmoud, Q. H. *QoS-based Discovery and Ranking of Web Services.* ICCCN 2007, pp. 529–534.
- Al-Masri, E., & Mahmoud, Q. H. *Discovering the best web service.* WWW 2007, pp. 1257–1258.

### **WS-DREAM (Dataset-2):**
- Zheng, Z., Zhang, Y., & Lyu, M. R. *Investigating QoS of Real-World Web Services.* IEEE TSC, 2014.
- Zheng, Z., Zhang, Y., & Lyu, M. R. *Distributed QoS Evaluation for Real-World Web Services.* ICWS 2010, pp. 83–90.

---

**If you use this dataset in published research, please cite the above papers.**  
Thank you!
