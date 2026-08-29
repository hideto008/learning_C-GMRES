# learning_C-GMRES

大塚先生が開発したC/GMRESに関する学習

### 理論

- 最適化問題
    - [テイラー展開](Notes/taylor_expansion.ipynb)
    - [ラグランジュの未定載数](Notes/Lagrange_multipliers.ipynb)
        - 等式制約における最適値の探索
    - [KKT条件](Notes/KKT.ipynb)
        - 不等式制約における最適値の探索
    - [バリア関数](Notes/barrier_function.ipynb)
        - 制約を目的関数へ組み込む方法
        - ニュートン法
            - 制約なし最適化の数値解法
        - 内点法
            - 制約付き最適化の数値解法

- 最適制御
    - [変分法](Notes/variational_method.ipynb)
        - 等式制約における最適関数の探索
    - [PMP条件](Notes/PMP.ipynb)
        - 最適制御問題に対する必要条件

- [GMRES](Notes/GMRES.ipynb)
    - Arnoldi法
    - QR 分解
    - Givens回転

- 数値計算
    - [Euler 法](Notes/Euler_Method.ipynb)

- 非線形最適制御
    - [C/GMRES](Notes/C-GMRES.ipynb)

- 制約の考慮
    - [ダミー変数](Notes/Inequality_constraint.ipynb)

### 適用

- 非線形バネモデル
    - [1質点 等式制約](Application/nonlinear_spring.ipynb)
    - [1質点 ダミー変数による制御入力制約](Application/nonlinear_spring_with_constraint.ipynb)