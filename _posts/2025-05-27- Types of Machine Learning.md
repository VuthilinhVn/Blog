---
layout: post
title: "Phân loại hệ thống học máy (P1)"
subtitle: "Types of Machine Learning (P1)"
date: 2025-05-27 12:59:00 +0800
background: '/img/banner.jpg'
---

Có nhiều loại hệ thống học máy khác nhau, nhưng cơ bản thì người ta sẽ phân loại theo tác dụng của chúng. Thông thường thì có:
- Nó được train dưới sự giám sát của con người hay không? (Học có giám sát - supervised, học không giám sát - unsupervised, học bán  giám sát - semisupervised và học tăng cường - Reinforcement learning)
- Nó đc train từng bước hay không? ( học theo lô - batch learning và học học online - online learning)
- Nó hoạt động bằng cách nhớ dữ liệu hay rút ra quy luật(học dựa trên ví dụ - instance based hay học theo model - model based)
Trong phần này, chúng ta cùng tìm hiểu nhóm đầu tiên dựa theo sự giám sát của con người hay không nhé! 
1. **Supervised/Unpsupervised Learning**
	**a. Supervised learning - Học có giám sát**
		Trong học có giám sát, dữ liệu huấn luyện (*training data*) sẽ đc đưa vào mô hình (*fit*) với nhãn (*labels*) đầy đủ. 
		![Supervised learning](/img/bai-1-images/Pasted image 20250527120501.png)
		Một vài bài toán cho dạng này là bài toán phân loại (*classification*) và bài toán dự đoán (*predictors*). 
		Các thuật toán phổ biến thuộc loại học có giám sát là:
		- *KNN*
		*- Linear Regression*
		*- Logistic Regression*
		*- SVM*
		*- Decision Trees and Random Forests*
		*- Neural networks*
	**b. Unsupervised Learning - Học không giám sát**
		Trong học khồn giám sát, giống như bạn đoán mò vậy, dữ liệu huấn luyện (training data) sẽ không có nhãn (labels), và hệ thống phải học mà k có giáo viên. 
		![Unsupervised learning](/img/bai-1-images/Pasted image 20250527121009.png)
		Một số thuật toán thuộc loại học không giám sát là:
		- Nhóm thuật toán phân cụm (*Clusters*): K-Means, Hierarchical cluster analysis(HCA), Expectation Maximization
		- Nhóm thuật toán giảm chiều và trực quan hóa (*Visualization and dimensionality reduction*): PCA, Kernel PCA, LLE, t-SNE
		- Nhóm học mối liên hệ *(association rule learning)*: Apriori, Eclat
	**c. Semisupervised learning - Học bán giám sát**
		Một số bài toán khi chúng ta có số ít dữ liệu có nhãn và phần nhiều dữ liệu không gán nhãn, thì những thuật toán giải quyết bài toán dạng này được gọi là học bán giám sát.
		![Semisupervised learning](/img/bai-1-images/Pasted image 20250527120501.png)
		Nhu hình trên, một số điểm có nhãn(tam giác, vuông) và phần nhiều điểm khác k có nhãn(chấm tròn) vậy thì làm sao ta dự đoán đc điểm x thuộc class nào ? Với bài toán này chúng ta sẽ sử dụng các thuật toán bán giám sát. 
		Một số thuật toán bán giám sát thường gặp là sự kết hợp của học k giám sát và học có giám sat, ví dụ: Deep belief networks(DBNs) ...
	**d. Reinforcement learning - Học tăng cường**
		Học tăng cường là một thuật toán khác hoàn toàn. Trong hệ thống này, có thuật ngữ *"agent"*, nó sẽ quan sát môi trường, chọn và thực hiện hành động, sau mỗi hành đồng nó sẽ có *rewards*(thường) nếu làm tốt, ngược lại nó sẽ nhận *panalties*(phạt) nếu làm không tốt. Nó phải học từ chính nó theo 1 *policy*(chiến lược) tốt nhất để ít bị phạt nhất.
		![Reinforcement learning](/img/bai-1-images/Pasted image 20250527122131.png)
Vậy là chúng ta đã tìm hiểu sơ lược cơ bản về nhóm Học máy đầu tiên, các bạn hãy trả lời các câu hỏi bên dưới để củng cổ thêm kiến thức nhé. Chúc các bạn học tốt!
- *question1 : What is a labeled training set?*
- *question2: Can you name five types of machine learning you know?* 
- *question 3: What are the two most common supervised tasks?*
- *question 4: What type of machine learning algorithm would you use to allow a robot to walk in various unknown terrain?*
- *question 5: what type of algorithm would you us to segment your customers in to multiple groups?* 
