# Anemia-Screening-CNN
DeepVision : Non-Invasive Anemia Screening with CNNs

Anemia is a common but often over looked condition, specially in communities with limited access to medical testing. Blood tests is the standard method for diagnosing anemia which can be invasive, expensive, and difficult to access in remote areas. In this project, we explore an alternative solution: Using eye images and deep learning to screen for anemia. Since changes in eye pallor can be a sign of low hemoglobin levels, we trained two image classification models: a light weight custom CNN and a MobileNetV2-based transfer learning model to detect anemia from conjunctiva images. Both models were trained and evaluated on a pulicly available dataset. While MobileNetV2 achieved higher accuracy, our CNN model offered faster, more efficient performance. Together, these results show promise for building accessible, non-invasive screening tools that could run directly on every day machines and help identify anemia early, even in low-resource settings.

![image](https://github.com/user-attachments/assets/d8131db7-efa4-4f9f-bafb-8bdc15f5dcde)

Experimental Results: The custom CNN achieved strong performance, particularly on non-anemic cases, with an overall test accuracy of 91%. Precision and recall scores were competitive, though slightly lower for the anemic class. The loss and accuracy curves showed steady convergence with minimal overfitting.

![image](https://github.com/user-attachments/assets/83966e74-1281-464c-b2f9-8cb611d6d922)


**Dataset** - We used a publicly available dataset consisting of labeled eye images with corresponding hemoglobin levels. For this project, we framed it as a binary classification problem grouping images into two classes: non anemic and anemic. The dataset includes a diverse range of eye images, captured under varying lighting and imaging conditions, which makes it well - suited for building a model intended for real-world use.

 **Refer to the report and ipynb file for more details**
