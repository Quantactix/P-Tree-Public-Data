# P-Tree-Public-Data
This folder is to share the test assets and factors generated by Panel Trees in paper "Growing the Efficient Frontier on Panel Trees."

# Download Data

- **P-Tree factors** [20 factor](Train_1981_2020/factors.csv)
- **P-Tree test assets** [P-Tree 1](Train_1981_2020/test_asset_ptree_1.csv)[P-Tree 2](Train_1981_2020/test_asset_ptree_2.csv)[P-Tree 3](Train_1981_2020/test_asset_ptree_3.csv)[P-Tree 4](Train_1981_2020/test_asset_ptree_4.csv)[P-Tree 5](Train_1981_2020/test_asset_ptree_5.csv)[P-Tree 6](Train_1981_2020/test_asset_ptree_6.csv)[P-Tree 7](Train_1981_2020/test_asset_ptree_7.csv)[P-Tree 8](Train_1981_2020/test_asset_ptree_8.csv)[P-Tree 9](Train_1981_2020/test_asset_ptree_9.csv)[P-Tree 10](Train_1981_2020/test_asset_ptree_10.csv)[P-Tree 11](Train_1981_2020/test_asset_ptree_11.csv)[P-Tree 12](Train_1981_2020/test_asset_ptree_12.csv)[P-Tree 13](Train_1981_2020/test_asset_ptree_13.csv)[P-Tree 14](Train_1981_2020/test_asset_ptree_14.csv)[P-Tree 15](Train_1981_2020/test_asset_ptree_15.csv)[P-Tree 16](Train_1981_2020/test_asset_ptree_16.csv)[P-Tree 17](Train_1981_2020/test_asset_ptree_17.csv)[P-Tree 18](Train_1981_2020/test_asset_ptree_18.csv)[P-Tree 19](Train_1981_2020/test_asset_ptree_19.csv)[P-Tree 20](Train_1981_2020/test_asset_ptree_20.csv)

# More Notes

If you want to use PTree test assets, (1) Folder [Train_1981_2020](Train_1981_2020) is recommended. 

If you do need in-sample and out-of-sample analyses, we provide (2) Folder [Train_1981_2000_Test_2001_2020](Train_1981_2000_Test_2001_2020) and (3) Folder [Train_2001_2020_Test_1981_2000](Train_2001_2020_Test_1981_2000).

The returns of test assets are in excess of the risk-free rate.

# Folders

There are three folders for different train-test schemes:

(1) Folder "Train_1981_2020" trains over 40 years from 1981 to 2020. "factors.csv" contains 20 factors. The remaining files are the returns of test assets of 20 boosted PTrees, where each PTree generates 10 test assets.

(2) Folder "Train_1981_2000_Test_2001_2020" trains over 20 years from 1981 to 2000 and test over 20 years from 2001 to 2020. The test sample data are named "*_test.csv".

(3) Folder "Train_2001_2020_Test_1981_2000" trains over 20 years from 2001 to 2020 and test over 20 years from 1981 to 2000. The test sample data are named "*_test.csv".

# Reference

Cong, L. W., G. Feng, J. He, and X. He (2024). Growing the Efficient Frontier on Panel Trees. Forthcoming, Journal of Financial Economics.

# Contact 

Xin He

<xin.he@ustc.edu.cn>

*Tenure-Track Associate Professor of Finance at School of Management University of Science and Technology of China.*
