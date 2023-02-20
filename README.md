# SquareCBwK
 This is the numerical simulation code for SquareCBwK, the main algorithm in our paper [Optimal Contextual Bandits with Knapsacks under Realizibility
via Regression Oracles](https://arxiv.org/pdf/2210.11834.pdf), which is accepted by AISTATS2023. We present simulation results for linear CBwK to demonstrate the dependency on time horizon ($T$), dimension ($m$), and number of arms ($K$) of SquareCBwK utilizing Newtonized GLMtron and Online Gradient Descent oracles. In comparison with the performance of [LinUCB (Agrawal and Devanur, 2016)]（https://dl.acm.org/doi/pdf/10.5555/3157382.3157484）, SquareCBwK with Newtonized GLMtron oracles exhibits an improve dependency on dimension $m$ although with additional dependence on K.
