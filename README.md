# TUBE: Tangent Upper Bound on Evidence for Discrete Diffusion Language Models

<p align="center">
  <img src="assets/method.png" width="92%" alt="TUBE method figure">
</p>

**Code for the paper _TUBE: Tangent Upper Bound on Evidence for Discrete Diffusion Language Models_.**

[📄 Paper (arXiv:2605.24292)](https://arxiv.org/abs/2605.24292) · [🌐 Project page](https://arseny5.github.io/tube/)

TUBE is a variational **upper** bound on the log-likelihood of discrete diffusion and any-order
models that admits an **unbiased Monte Carlo estimator**. Combined with the ELBO it two-sidedly
localizes the true log-likelihood,

$$\mathrm{ELBO}(x) \le \log p_{\mathrm{model}}(x) \le \mathrm{TUBE}_\psi(x).$$

Applied to block masked-diffusion models and any-order ARMs, TUBE reveals that these models lie
strictly below the exact autoregressive baseline in likelihood.

## Code

⏳ Code will be released soon.

## Citing

If you find this work useful, please cite:

```bibtex
@article{ivanov2026tube,
  title   = {TUBE: Tangent Upper Bound on Evidence for Discrete Diffusion Language Models},
  author  = {Ivanov, Arseny and Kholkin, Sergei and Gromadskii, Vladislav and
             Ksenofontov, Grigoriy and Oseledets, Ivan and Korotin, Alexander},
  journal = {arXiv preprint arXiv:2605.24292},
  year    = {2026}
}
```
