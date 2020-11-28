- 1 代码平台语言及版本：Win7+Python3.6
- 2 使用程序库及版本号：
    - numpy  1.15.4
    - pandas  0.23.4
    - seaborn  0.9.0
    - matplotlib  3.0.2
    - sklearn  0.20.1
    - xgboost  1.1.1
    - lightgbm  3.0.0
    - re  2.2.1
- 3 程序运行方法：
    - 运行“注塑成型工艺的虚拟量测和调机优化-特征工程 - 决赛.ipynb”，得到《test_taskA_add_mean_std_max_min.csv》和《test_taskA_add_mean_std_max_min_median_indiv_features.csv》两个文件
    - 运行“注塑成型工艺的虚拟量测和调机优化-建模 - 决赛.ipynb”,得到提交结果
- 4 数据存放路径及方式：
    - Middle_result：中间结果。文件夹主要文件，初赛生成的特征工程文件，只是选择了其中的列名，决赛taskA只是借助了其中的列名。《test - new.csv》是初赛的预测结果
    - taskA 存放了决赛taskA的数据
    - Train 只是存放了data_set文件

- 5 决赛A虚拟量测结果：sub_file_taskA

- 6 联系方式：
    - 如有问题，请联系“”
    - 电话：
    - QQ：776573296

- 7 技术原理：
    - 结合传感器实际图形，将对应相关信号的相关统计特征加入特征；
    - 分别生成3个模型（x_train1,x_train2,x_train3），利用lightgbm建立回归模型，调参得到最终的模型。
