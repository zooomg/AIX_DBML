# AIX_BDML

# Algorithms

## Explaining the black-box model: A survey of local interpretation methods for deep neural networks

### data-driven
- perturebation-based
  - LIME (2016, SIGKDD) [https://arxiv.org/abs/1602.04938]
  - SHAP (2017, NIPS) [https://arxiv.org/abs/1705.07874]
  - CXPlain (2019, NIPS) [https://arxiv.org/abs/1910.12336]
  - ZFNet (2013, ECCV) [https://arxiv.org/abs/1311.2901]
  - Fong et al. (2017, ICCV) [https://arxiv.org/abs/1704.03296]
  - Dabkowski et al. (2017, NIPS) [https://arxiv.org/abs/1705.07857]
  - Rise (2018, ESA) [https://arxiv.org/abs/1806.07421]
  - RMA (2018, ICCV) [https://arxiv.org/abs/1807.11720]
  - FIDO (2019, ICLR) [https://arxiv.org/abs/1807.08024]
  - He et al. (2019, ICCV) [https://arxiv.org/abs/1903.02501]
  - CEM-MAF (2019, ICML) [https://arxiv.org/abs/1905.12698v1]
  - CEM (2018, NIPS) [https://arxiv.org/abs/1802.07623]
  - Fong et al. (2019, ICCV) [https://arxiv.org/abs/1910.08485]
  - Yeh et al. (2018, NIPS) [https://arxiv.org/abs/1811.09720]
  - Zhang et al. (2018, AAAI) [https://arxiv.org/abs/1710.10577]
- adversarial-based
  - Tao et al. (2018, NIPS) [https://arxiv.org/abs/1810.11580]
  - Anchor (2018, AAAI) [https://www.semanticscholar.org/paper/Anchors%3A-High-Precision-Model-Agnostic-Explanations-Ribeiro-Singh/1d8f4f76ac6534627ef8a1c24b9937d8ab2a5c5f]
  - IF (2017, ICML) [https://arxiv.org/abs/1703.04730]
  - Etmann et al. (2019, ICML) [https://arxiv.org/abs/1905.04172]
  - Mudrakarta et al. (2018, ACL) [https://arxiv.org/abs/1805.05492]
  - FGVE (2019, CVPR) [https://arxiv.org/abs/1908.02686]
- concept-based
  - TCAV (2018, ICML) [https://arxiv.org/abs/1711.11279]
  - ND (2018, TPAMI) [https://arxiv.org/abs/1711.05611]
  - Zhou et al. (2018, ECCV) [https://openaccess.thecvf.com/content_ECCV_2018/html/Antonio_Torralba_Interpretable_Basis_Decomposition_ECCV_2018_paper.html]
  - Fong et al. (2018, ICCV) [https://arxiv.org/abs/1801.03454]
  - Ghorbani et al. (2019, NIPS) [https://arxiv.org/abs/1902.03129]
  - Chen et al. (2019, NIPS) [https://arxiv.org/abs/1806.10574]
### model-driven
- gradient-based
  - Simonyan et al. (2013, CVPR) [https://arxiv.org/abs/1312.6034]
  - Springenberg et al. (2014, ICLR) [https://arxiv.org/abs/1412.6806]
  - Mahendrran et al. (2015, ICCV) [https://arxiv.org/abs/1412.0035]
  - Ross et al. (2018, AAAI) [https://arxiv.org/abs/1711.09404]
  - Du et al. (2018, SIGKDD) [https://arxiv.org/abs/1804.00506v1]
  - Integrated Grad (2017, ICML) [https://arxiv.org/abs/1703.01365]
  - Srinivas et al. (2019, NIPS) [https://arxiv.org/abs/1905.00780]
  - Zhang et al. (2018, IJCV) [https://arxiv.org/abs/1608.00507]
  - Zhang et al. (2018, ICCV) [https://arxiv.org/abs/1710.00935]
- corrlation-score
  - LRP (2015, PLoS One) [https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0130140]
  - LRL (2016, ICANN) [https://arxiv.org/abs/1604.00825]
  - DeepLIFT (2016, ICML) [https://arxiv.org/abs/1605.01713]
  - CASO (2019, ICML) [https://arxiv.org/abs/1902.00407]
  - Sevaraju et al. (2018, ECCV) [https://arxiv.org/abs/1808.02861]
- class activation map
  - CAM (2016, ICCV) [https://arxiv.org/abs/1512.04150]
  - Grad-CAM (2017, ICCV) [https://arxiv.org/abs/1610.02391]
  - U-cam (2019, ICCV) [https://arxiv.org/abs/1908.06306]
  - GFI (2018, SIGKDD) [https://arxiv.org/abs/1804.00506]
  - Grad++ (2018, WACV) [https://ieeexplore.ieee.org/document/8354201]
