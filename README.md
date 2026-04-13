# Opaque Price Competition under Capacity Constraints

## Model Overview

We study a finite-horizon dynamic duopoly where two firms compete on prices with limited capacities. At each period, firm \(i\) chooses a price \(p_{it} \in \{p_l, p_h\}\), and demand follows a multinomial logit (MNL) model:

$$
q_i(p_t) = \frac{\exp(a - b p_i)}{1 + \sum_{k \in \{i,-i\}} \exp(a - b p_k)}
$$
Firms start with initial capacities \((s_i, s_{-i})\), and the value function under equilibrium pricing satisfies:

$$
V_i(s_i, s_{-i}, t) = \lambda \pi_i(p^*, s_i, s_{-i}, t) + (1 - \lambda)V_i(s_i, s_{-i}, t-1)
$$
We consider two information structures:

- **Transparent setting:** firms observe both capacities and solve a dynamic game via backward induction.
- **Opaque setting:** firms only observe own demand and update beliefs about competitors’ capacity, leading to a higher-dimensional state space and belief-driven dynamics.

## Preliminary Insights

- Transparent information typically yields higher firm value.
- The performance gap between opaque and transparent settings is sensitive to the demand-to-capacity ratio and can exhibit non-monotonic behavior.
- Belief misspecification and information frictions significantly affect equilibrium outcomes.

---

##  Project Status & Collaboration

This project was developed under the guidance of **[Zizhuo Wang](https://mypage.cuhk.edu.cn/academics/wangzizhuo/)** in **September 2024**.

The project is currently **paused and not under active development**.

**If you are interested in this project and would like to collaborate, please feel free to contact me and Zizhuo Wang.**

---

## License

⚠️ All rights reserved.