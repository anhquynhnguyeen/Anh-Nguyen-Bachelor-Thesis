# ML-Based Fingerprinting Devices in OT Security

## Project description

The process of this project contains four main sections, each focusing on exploring a technique for handling class imbalance, along with that is three machine learning algorithms, and two smaller sections, which are data preprocessing and Case Study. The performance of these models is measured by four metrics, namely accuracy, precision, recall, and F1-score. By comparing and analyzing these results, the most efficient combination is identified as SMOTE and Random Forest, which will then be used for Case Study, which will involve applying this combination on an accurate real-world dataset to evaluate the practical application of these models. The final subsection of Case Study, the visualization of the Case Study is demonstrated for qualitative analysis purposes.

## Research question 
Comparing the Effectiveness of Machine Learning Algorithms for Predicting Device Types 

## Machine Learning Models

Random Forest

<div align="center">
  <img src="./doc/RF.png" alt="RF" width="600"/>
</div>

<br>

Naive Bayes

<div align="center">
  <img src="./doc/NB.png" alt="NB" width="600"/>
</div>

<br>
 
XGBoost

<div align="center">
  <img src="./doc/XGBoost.png" alt="XGBoost" width="600"/>
</div>

<br>

## Techniques for Handling Class Imbalance

Class Weighting

<div align="center">
  <img src="./doc/CW.png" alt="CW" width="600"/>
</div>

<br>

SMOTE (Synthetic Minority Over-sampling technique)

<div align="center">
  <img src="./doc/SMOTE.png" alt="SMOTE" width="600"/>
</div>

<br>
 
Random Oversampling

<div align="center">
  <img src="./doc/RO.png" alt="RO" width="600"/>
</div>

<br>

## Results Format

The results of the models in the .ipynb file are similar to the result of Case Study below, which consists of various metrics and accuracy:

<div align="center">
  <img src="./doc/CS.png" alt="CS" width="600"/>
</div>

<br>

## Experimental results

Main Summary of the results: 
1. The most efficient machine learning model was Random Forest, which consistently outperformed the other models, demonstrated its significant ability in handling class imbalance, and maintained high accuracy and other metrics in both datasets and across techniques. 
2. The worst performance consistently belonged to Naive Bayes. Despite the application of class weighting and random oversampling, this machine learning model still struggled to handle class imbalance, resulting in low accuracy and other metrics for all categories, with precision and recall values remaining below acceptable levels. 
3. SMOTE generally enhanced accuracy, precision, and recall, especially for minority classes. 
4. For highly imbalanced datasets, the combination of Random Forest and SMOTE stands as the most robust and efficient approach.
5. Case Study's results suggested that the model with Random Forest and SMOTE possesses high potential for real-world datasets and strongly indicate its practical use in real-life scenarios. 

## References

1. Apruzzese, G. et al. (2023) ‘The role of machine learning in Cybersecurity’, *Digital Threats: Research and Practice*, 4(1), pp. 1–38. doi:10.1145/3545574.
2. Auret, L. and Aldrich, C. (2012) ‘Interpretation of nonlinear relationships between process variables by use of random Forest’, *Minerals Engineering*, 35, pp. 27–42. doi:10.1016/j.mineng.2012.05.008.
3. Bakirarar, B. and Elhan, A.H. (2023) ‘Class weighting technique to deal with imbalanced class problem in Machine Learning: Methodological Research’, *Turkiye Klinikleri Journal of Biostatistics*, 15(1), pp. 19–29. doi:10.5336/biostatic.2022-93961.
4. Berardi, D. et al. (2023) ‘When operation technology meets information technology: Challenges and opportunities’, *Future Internet*, 15(3), p. 95. doi:10.3390/fi15030095.
5. Boukerche, A. and Coutinho, R.W. (2021) ‘Design guidelines for machine learning-based cybersecurity in internet of things’, *IEEE Network*, 35(1), pp. 393–399. doi:10.1109/mnet.011.2000396.
6. Breiman, L. (1996) ‘Bagging predictors’, *Machine Learning*, 24(2), pp. 123–140. doi:10.1007/bf00058655.
7. Breiman, L. (2001). Random Forest. *Machine learning*, 45, 5–32. [https://doi.org/10.1023/A](https://doi.org/10.1023/A): 1010933404324
8. Chawla, N.V. et al. (2002) ‘Smote: Synthetic minority over-sampling technique’, *Journal of Artificial Intelligence Research*, 16, pp. 321–357. doi:10.1613/jair.953.
9. Chen, T. and Guestrin, C. (2016) ‘XGBoost: A scalable tree boosting system’, *Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining*, pp. 785–794. doi:10.1145/2939672.2939785.
10. De Ville, B. (2013). Decision trees. *Wiley Interdisciplinary Reviews: Computational Statistics*, 5(6), 448-455.
11. Farias, F., Ludermir, T. and Bastos-Filho, C. (2020) Similarity based stratified splitting: An approach to train better classifiers, *arXiv.org*. Available at: [https://arxiv.org/abs/2010.06099](https://arxiv.org/abs/2010.06099) (Accessed: 14 June 2025).
12. Goutte, C. and Gaussier, E. (2005) ‘A probabilistic interpretation of precision, recall and F-score, with implication for evaluation’, *Lecture Notes in Computer Science*, pp. 345–359. doi:10.1007/978-3-540-31865-1\_25.
13. Guo, G. et al. (1970) KNN model-based approach in classification, *SpringerLink*. Available at: [https://link.springer.com/chapter/10.1007/978-3-540-39964-3\_62](https://link.springer.com/chapter/10.1007/978-3-540-39964-3_62) (Accessed: 14 June 2025).
14. InterLir (2024) Converting ipv4 addresses to decimal: A step-by-step guide - interlir networks marketplace, *Interlir networks marketplace - InterLIR IPv4 IPv6 Rent and Lease out Marketplace*. Available at: [https://interlir.com/2024/02/19/converting-ipv4-addresses-to-decimal-a-step-by-step-guide/](https://interlir.com/2024/02/19/converting-ipv4-addresses-to-decimal-a-step-by-step-guide/) (Accessed: 30 May 2025).
15. Kamel, H., Abdulah, D. and Al-Tuwaijari, J.M. (2019) ‘Cancer classification using Gaussian Naive Bayes algorithm’, *2019 International Engineering Conference (IEC)*, pp. 165–170. doi:10.1109/iec47844.2019.8950650.
16. Kessler, G. C. (2004). An overview of TCP/IP protocols and the internet. *InterNIC Document*, Dec, 29, 42.
17. Khan, M.Y. et al. (2021) ‘Automated prediction of good dictionary examples (GDEX): A comprehensive experiment with distant supervision, machine learning, and word embedding‐based Deep learning techniques’, *Complexity*, 2021(1). doi:10.1155/2021/2553199.
18. Lastovicka, M., Dufka, A. and Komarkova, J. (2018) ‘Machine learning fingerprinting methods in cyber security domain: Which one to use?’, *2018 14th International Wireless Communications & Mobile Computing Conference (IWCMC)*, pp. 542–547. doi:10.1109/iwcmc.2018.8450406.
19. Li, P. (2024) ‘Machine learning techniques for pattern recognition in high-dimensional data mining’, *2024 4th International Conference on Electronic Information Engineering and Computer Communication (EIECC)*, pp. 1493–1497. doi:10.1109/eiecc64539.2024.10929503.
20. Liang, F. et al. (2019a) ‘Machine learning for security and the internet of things: The good, the bad, and the ugly’, *IEEE Access*, 7, pp. 158126–158147. doi:10.1109/access.2019.2948912.
21. Mohammed, R., Rawashdeh, J. and Abdullah, M. (2020) ‘Machine learning with oversampling and Undersampling Techniques: Overview Study and experimental results’, *2020 11th International Conference on Information and Communication Systems (ICICS)*, pp. 243–248. doi:10.1109/icics49469.2020.239556.
22. Nielsen, D. (2016) Tree boosting with XGBoost - why does XGBoost win ‘Every’ machine learning competition?, *NTNU Open*. Available at: [https://ntnuopen.ntnu.no/ntnu-xmlui/handle/11250/2433761](https://ntnuopen.ntnu.no/ntnu-xmlui/handle/11250/2433761) (Accessed: 14 June 2025).
23. Osei, R. et al. (2022) ‘Efficient IOT device fingerprinting approach using Machine Learning’, *Proceedings of the 19th International Conference on Security and Cryptography*, pp. 525–533. doi:10.5220/0011260500003283.
24. Oztornaci, B., Ata, B. and Kartal, S. (2024) ‘Analysing household food consumption in Turkey using machine learning techniques’, *Agris on-line Papers in Economics and Informatics*, 16(2), pp. 97–105. doi:10.7160/aol.2024.160207.
25. Patwariraghottam (2024) Mastering naive Bayes: A comprehensive Python Guide to Probabilistic Classification, *Medium*. Available at: [https://medium.com/@patwariraghottam/mastering-naive-bayes-a-comprehensive-python-guide-to-probabilistic-classification-b7fe67c6763f](https://medium.com/@patwariraghottam/mastering-naive-bayes-a-comprehensive-python-guide-to-probabilistic-classification-b7fe67c6763f) (Accessed: 20 June 2025).
26. Samal, L., Mahapatra, K. and Swain, A.K. (2024) ‘Strengthening industrial IOT security: Device fingerprinting and ML-based node authentication at gateway’, *2024 IEEE International Conference on Electronics, Computing and Communication Technologies (CONECCT)*, pp. 1–6. doi:10.1109/conecct62155.2024.10677208.
27. Schröer, C., Kruse, F. and Gómez, J.M. (2021) ‘A systematic literature review on applying CRISP-DM process model’, *Procedia Computer Science*, 181, pp. 526–534. doi:10.1016/j.procs.2021.01.199.
28. Shaza M. Abd Elrahman, & Ajith Abraham. (2013). A Review of Class Imbalance Problem. *Journal of Network and Innovative Computing*, 1, 9. Retrieved from [https://cspub-jnic.org/index.php/jnic/article/view/42](https://cspub-jnic.org/index.php/jnic/article/view/42)
29. T. M. Oshiro, P. S. Perez, and J. A. Baranauskas, “How many trees in a random forest? ” in *Proc. Int. Workshop Mach. Learn. Data Mining Pattern Recognit.*, 2012, pp. 154–168.
30. Tangirala, S. (2020) ‘Evaluating the impact of gini index and information gain on classification using decision tree classifier algorithm\*’, *International Journal of Advanced Computer Science and Applications*, 11(2). doi:10.14569/ijacsa.2020.0110277.
31. Vijayvargiya, A. et al. (2021) ‘Human knee abnormality detection from imbalanced SEMG data’, *Biomedical Signal Processing and Control*, 66, p. 102406. doi:10.1016/j.bspc.2021.102406.
32. Vrigazova, B. (2021) ‘The proportion for splitting data into training and test set for the bootstrap in Classification problems’, *Business Systems Research Journal*, 12(1), pp. 228–242. doi:10.2478/bsrj-2021-0015.
33. Wirth, R., and Hipp, J. (2000). CRISP-DM: Towards a Standard Process Model for Data Mining. Available at: [https://www.cs.unibo.it/\~danilo.montesi/CBD/Beatriz/10.1.1.198.5133.pdf](https://www.cs.unibo.it/~danilo.montesi/CBD/Beatriz/10.1.1.198.5133.pdf)
34. Yang, F.-J. (2018) ‘An implementation of naive bayes classifier’, *2018 International Conference on Computational Science and Computational Intelligence (CSCI)*, pp. 301–306. doi:10.1109/csci46756.2018.00065.

