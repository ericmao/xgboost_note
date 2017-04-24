# XGBoost 使用說明

XGBoost似乎強大，Kaggle中優勝隊伍的御用工具，值得深入，以下整理學習步驟：

* Step 1: XGBoost Web sites(https://xgboost.readthedocs.io/en/latest/) 大本營
原理投影片：Introduction to Boosted Tree (http://homes.cs.washington.edu/~tqchen/pdf/BoostedTree.pdf)

* Step 2: 安裝XGBoost (大本營>Get Started>Installation Guide) (https://xgboost.readthedocs.io/en/latest/build.html) ，Mac、Ubuntu及Windows都有詳細教學，分為單機版與群集版，Mac群集版會有一點問題，Ubuntu無問題。

* Step 3: Awesome XGBoost (https://github.com/dmlc/xgboost/tree/master/demo)
這是XGBoost Demo github，在README.md中，透過充足的範例，提供學習者取得起點。
(簡中介紹：http://blog.csdn.net/zc02051126/article/details/46771793)

* Step 4:  XGBoost example (如附件)
Titanic: Machine Learning from Disaster (https://www.kaggle.com/cbrogan/titanic/xgboost-example-python/code)
Microsoft Malware Competition (https://www.kaggle.com/c/malware-classification)，冠軍GitHub https://github.com/xiaozhouwang/kaggle_Microsoft_Malware (附件為CODASPY’16 dataset- https://github.com/ManSoSec/Microsoft-Malware-Challenge)

* [Update April 21th] 新增XGBoostMalwareAnalysis(路徑：malware/)

* OSX El capitan installation
    - brew tap homebrew/boneyard
    - brew install --with-clang llvm
    - brew install brew install gcc@5
    - pip install xgboost
