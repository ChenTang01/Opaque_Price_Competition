# Opaque Price Competition under Capacity Constraints

## Model Overview

We study a finite-horizon dynamic duopoly where two firms compete on prices with limited capacities. At each period, firm \(i\) chooses a price \(p_{it} \in \{p_l, p_h\}\), and demand follows a multinomial logit (MNL) model:

```math
q_i(p_t) = \frac{\exp(a - b p_i)}{1 + \sum_{k \in \{i,-i\}} \exp(a - b p_k)}
```

Firms start with initial capacities \((s_i, s_{-i})\). Under equilibrium pricing, the value function satisfies:

```math
V_i(s_i, s_{-i}, t) = \lambda \pi_i(p^*, s_i, s_{-i}, t) + (1-\lambda)V_i(s_i, s_{-i}, t-1)
```

We compare two information structures:

- **Transparent setting:** firms observe both their own and their competitor's remaining capacities, and solve the dynamic game by backward induction.
- **Opaque setting:** firms only observe their own demand realizations and update beliefs about the competitor's capacity, which leads to a higher-dimensional state space and belief-driven dynamics.

## Preliminary Insights

- In most numerical cases, the **transparent setting yields higher firm value** than the opaque setting.
- The performance gap between the opaque and transparent settings is **sensitive to the demand-to-capacity ratio** and can be non-monotonic.
- **Belief misspecification and information frictions** can materially affect equilibrium outcomes.

---

## Project Status & Collaboration

This project was completed under the guidance of **[Zizhuo Wang](https://mypage.cuhk.edu.cn/academics/wangzizhuo/)** in **September 2024**.

The project is currently **paused** and is **not under active development**.

> **If you are interested in this project and would like to collaborate, please feel free to contact both Chen Tang and Zizhuo Wang.**

## License

All rights reserved.