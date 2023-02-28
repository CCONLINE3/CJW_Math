# 基于惯性中心动力学和SE3的机器人数学库<br>

- 库中包含了基于惯性中心动力学的功能函数和SE3上的基本操作<br>

- 类模板为CJW_Math,使用数组存放矩阵，位姿计算都使用简化后的元素操作加快计算速度<br>

# 整个类包含以下功能：<br>

1. 数组矩阵显示<br>

2. 三维矢量和六维矩阵运算<br>

3. 矩阵的基本操作:

    - 方阵高斯的QR分解

    - 方阵行列式

    - 对称方阵的特征向量和特征矩阵

    - 矩阵的SVD分解

    - 高斯算法方阵逆矩阵<br>

4. 刚体旋转矩阵通用操作<br>

5. 刚体位姿矩阵通用操作<br>

6. 姿态表达切换<br>

7. 位姿矩阵基于指数坐标表达基本操作<br>

8. 位姿矩阵及其旋量的伴随变换<br>

9. 位姿矩阵基于指数坐标表达的微分运算<br>

10. 刚体位姿矩阵、速度和指数映射旋量的转换<br>

11. 刚体位姿矩阵指数坐标空间PD控制<br>

12. 广义惯性矩阵的坐标转换<br>

13. 基于惯性中心的动力学方程<br>

14. 一些简单集合关系运算<br>