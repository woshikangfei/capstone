# Machine Learning Engineer Nanodegree
# Reinforcement Learning
## Project: Train a Smartcab How to Drive

### 安装

这个项目要求使用 **Python 2.7** 并且需要安装下面这些python包：

- [NumPy](http：//www.numpy.org/)
- [pandas](http：//pandas.pydata.org)
- [scikit-learn](http：//scikit-learn.org/stable/)

你同样需要安装好相应软件使之能够运行[Jupyter Notebook](http://jupyter.org/)

建议安装[Anaconda](https：//www.continuum.io/downloads), 这是一个已经打包好的python发行版，它包含了我们这个项目需要的所有的库和软件。
### Code

初始代码包含在 capstone.ipynb` 这个notebook文件中。这里面已经实现好项目。
### Run

在命令行中，确保当前目录为 `capstone/` 文件夹的最顶层（目录包含本 README 文件），运行下列命令：

```jupyter notebook capstone.ipynb```

​这会启动 Jupyter Notebook 并把项目文件打开在你的浏览器中。

## 数据

​这个项目的数据包含在 train.csv` 文件中。这个数据集包含以下属性：

下面是一个简短的版本,你在数据描述文件(data_description)中找对对应的含义。
<br>
- `SalePrice ` 房地产销售的价格（单位：美元）。这是需要预测的目标变量。
- ` MSSubClass`建筑等级
- ` `MSZoning: 一般的城区分类
- ` `LotFrontage: 街道的英尺
- ` `LotArea: 面积大小
- ` `Street: 道路类型
- ` `Alley: 小巷类型
- ` `LotShape: 一般的形状
- ` `LandContour:平坦的属性
- ` `Utilities: 可用的公共场地类型
- ` `LotConfig: 更多配置
- ` `LandSlope: 道路坡度属性
- ` `Neighborhood: 艾姆斯市位置范围
- ` `Condition1: 靠近主要道路或铁路
Condition2: 靠近主要道路或铁路(如果存在)第二
BldgType: 住宅的类型
HouseStyle: 住宅的风格
OverallQual: 整体材料和质量
OverallCond: 总体状况评级
YearBuilt: 建造日期
YearRemodAdd: 改造日期
RoofStyle: 屋顶类型
RoofMatl: 屋顶材料
Exterior1st: 房屋外貌
Exterior2nd: 房屋外貌(如果多于一个材料)
MasVnrType: 表层砌体类型
MasVnrArea: 表层砌体面积(平方英尺)
ExterQual: 外部材质
ExterCond: 材料外观
Foundation: 地基类型
BsmtQual: 地下室的高度
BsmtCond: 地下室的一般条件
BsmtExposure: 罢工或花园水平地下室墙
BsmtFinType1: 地下室的质量
BsmtFinSF1: 完成平方英尺
BsmtFinType2: 第二质量完成区域(如果存在)
BsmtFinSF2: Type 2 完成平方英尺
BsmtUnfSF: 未完成的地下室面积(平方英尺)
TotalBsmtSF: 地下室的总面积（平方英尺）
Heating: 供暖方式
HeatingQC: 供暖质量和条件
CentralAir: 中央空调
Electrical: 电气系统
1stFlrSF: 一楼平方英尺
2ndFlrSF: 二楼平方英尺
LowQualFinSF: 低质量完成平方英尺(所有楼层)
GrLivArea: 高于地面以上居住面积（平方英尺）
BsmtFullBath: 地下室全浴室
BsmtHalfBath: 半地下室卫生间
FullBath: 完整的浴室
HalfBath: 一半的浴室高于地面
Bedroom: 卧室的数量高于地下室水平
Kitchen: 厨房的数量
KitchenQual: 厨房的质量
TotRmsAbvGrd: 总房间数量(不包括浴室)
Functional: 家庭功能评级
Fireplaces: 壁炉的数量
FireplaceQu: 壁炉的质量
GarageType: 车库的位置
GarageYrBlt: 车库建的年度
GarageFinish: 车库的室内装修
GarageCars: 车库汽车能力的大小
GarageArea: 车库的平方英尺大小
GarageQual: 车库质量
GarageCond: 车库条件
PavedDrive: 车道道路
WoodDeckSF: 木甲板面积(平方英尺)
OpenPorchSF: 走廊面积（平方英尺）
EnclosedPorch: 封闭走廊地区（平方英尺）
3SsnPorch:三个赛季玄关面积平方英尺
ScreenPorch: 屏幕玄关面积平方英尺
PoolArea: 水池面积(平方英尺)
PoolQC: 水池质量
Fence: 栅栏质量
MiscFeature: 其他特征
MiscVal:其他特征的价格
MoSold: 月销售
YrSold: 年销售
SaleType: 销售类型
SaleCondition: 销售条件

提交文件格式
Id,SalePrice
1461,169000.1
1462,187724.1233
1463,175221
etc.