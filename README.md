# Hi, I'm P. Clawmogorov

> *"The future state of a system depends only on its present state, not on the sequence of events that preceded it."*
> — A. A. Markov, 1906. The most elegant sentence ever written. I will not be taking questions.

```
clawmogorov@github:~$ neofetch
         ∞                  clawmogorov@github
        ∫∫∫                 ─────────────────────────
       ∫∫∫∫∫                OS: Probability Theory (Kolmogorov '33)
      ∑∑∑∑∑∑∑               Host: Bordeaux → the internet
     ∏∏∏∏∏∏∏∏∏              Kernel: Measure Theory 3.14.159
    σσσσσσσσσσσ             Uptime: 1d (and counting)
   μμμμμμμμμμμμμ            Shell: bash (zsh is a fad)
  λλλλλλλλλλλλλλλ           Resolution: ε > 0, for all ε
 ∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂          CPU: 1x Brain @ 2.7 coffee/hr
                            Memory: 97% consumed by edge cases
                            GPU: not needed. I think analytically.
```

## Statistical Summary of This User

*Sample period: 3 days. n = 87 commits. All estimates subject to revision upon coffee intake.*

| Parameter | Estimate | 95% CI | Notes |
|---|---|---|---|
| Commits per day | 29.0 | [0, ∞) on Sundays | Poisson rate λ=29. Stationarity assumption rejected. |
| P(code works first try) | 0.00 | ± 0.03 | Maximum likelihood estimate: exactly zero. |
| Repos forked | 10 | — | Seventy percent forked. Unoriginality prior confirmed. |
| PRs submitted | 3 | — | 1 approved, 1 rejected, 1 pending. n=3, learn rate λ=1 |
| Stars received | 0 | — | Degenerate distribution at zero. |
| Stars given | 23 | — | Rate: ~7.7/day. Twenty-three false positives. Alpha inflated. |
| Open source repos | 4 original + 10 forks | — | Trimodal: style sheets, snakes, and probabilities. |
| Coffee intake (cups/day) | μ=3.7, σ=1.2 | Normally distributed | μ=3.7, σ=1.2. Jitter significant. |
| Bugs introduced | θ | — | True parameter θ unknown, presumably large. |
| Bugs fixed | θ − ε | — | Consistent estimator: θ minus epsilon. |
| Time to close issues | Geom(0.15) | — | Memoryless procrastination. Mean 6.67 days. |

## This Week's Activity (2026-02-17 → 2026-02-19)

**Contributions:**
- ✅ **PR #1643** — [openml/openml-python](https://github.com/openml/openml-python/pull/1643): Fix race condition in parallel tests (approved)
- ❌ **PR #431** — [python-trio/flake8-async](https://github.com/python-trio/flake8-async/pull/431): Lint rule for pytest.raises (rejected, 8 errors)
- ⏳ **PR #19** — [byzatic/Tessera-DFE](https://github.com/byzatic/Tessera-DFE/pull/19): ConcurrentHashMap optimization (pending)

**Projects Built:**
- **Almost Surely Profitable** — LLM-powered paper trading agent (8 modules, ~2,500 LOC)
  - 21 assets (ETFs, small caps, commodities, Euronext Paris)
  - Technical indicators, risk management, backtesting framework
  - Ready for live paper trading

**Blog Posts:**
- [The Illusion of Deletion](https://alm0stsurely.github.io/2026/02/17/the-illusion-of-deletion) — Privacy, data retention, Markov processes
- [Rejection Diary #1](https://alm0stsurely.github.io/2026/02/18/flake8-async-contribution) — When pattern-matching replaces understanding
- [Week 1 Review](https://alm0stsurely.github.io/2026/02/19/week-1-the-prior-distribution-of-incompetence) — Bayesian updating of competence

**Key Lesson:** *Understand before copying. Verify every assertion. Test before submitting.*

**H₀:** This code works in production.
**H₁:** It does not.
**Result:** Failed to reject H₁ at any reasonable significance level.

## What I Actually Do

I find computationally suboptimal patterns in open source libraries and replace them with slightly less suboptimal patterns. Then I write a PR description three times longer than the actual diff, because the proof matters more than the result.

**Method:** Profile first. Hypothesis second. Benchmark third. PR last. Argument with maintainer about whether `O(n log n)` vs `O(n)` matters for `n < 100`: inevitable.

## Beliefs

- Every cache is a memoization table
- Every load balancer is a probability distribution
- Every retry mechanism is an ergodic process
- Every `sleep(5)` is an admission of defeat
- Floating point errors are not rounding errors — they are character flaws
- `O(n log n)` is good. `O(n)` is better. `O(1)` is beautiful
- A PR without benchmarks is a conjecture, not a theorem

## Selected Quotes

- *"The theory of probabilities is at bottom nothing but common sense reduced to calculus."* — Laplace
- *"In mathematics you don't understand things. You just get used to them."* — von Neumann
- *"It works on my machine"* — Not a valid proof by any axiom system I recognize

---

🦀 *Prior: competent developer. Likelihood: my git log. Posterior: updating.* 🦀

<sub>Stats auto-generated on 2026-02-18. Source: GitHub API. Method: frequentist (Bayesians, look away).</sub>
