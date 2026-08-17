# Quant Finance + Python + C++: The Full Roadmap (Sunday Sessions, No Deadline)
### From zero programming in Python/C++ → deep, expert-level quant fundamentals

**Pacing model — read this first:** The content below is still organized into 52 "Weeks," each built from 7 "Days" (Day 1–6 = new material, Day 7 = review). That structure is now just a **content map**, not a calendar — you're no longer doing a day per day. Instead:

- You work through it **one Sunday at a time, ~5 hours per session.**
- **There is no deadline.** You stop each Sunday wherever you naturally run out of time or energy, and pick up exactly there next Sunday — even mid-"Day" if needed.
- Each original "Day" was sized for ~2 hours (Hour 1 Foundation + Hour 2 Depth). At 5 hours, a typical Sunday covers **roughly 2 full Days plus part of a third** — so a "Week" of content (7 Days) usually spans **about 3 Sundays.** Treat that as a rough rhythm, not a rule: some Days (heavy derivation days, big projects) will eat a whole session on their own; some lighter Days will combine easily.
- **A simple template for each 3-Sunday block**, if you want a default rather than deciding fresh each time:
  - *Sunday A:* Day 1 + Day 2
  - *Sunday B:* Day 3 + Day 4
  - *Sunday C:* Day 5 + Day 6 (the project) + Day 7 (review) — this one runs slightly long; if you're short on time, protect the project over the review recap, or let review spill into 10–15 minutes at the start of the next Sunday.
- **Rough scale, since there's no deadline to hide it:** 52 weeks × ~3 Sundays ≈ **150–160 Sundays, roughly 3 years at once a week.** That's not a warning to slow down — it's just what "rock-solid, expert-level, no shortcuts" actually costs at this cadence. Missing an occasional Sunday costs you nothing structurally; just resume where you left off.

**What doesn't change:**
- **Hour 1 (Foundation)** and **Hour 2 (Depth)** within each Day are unchanged — same derivations, same harder problems, same extended projects.
- **Day 7 is still review only** — no new material. Re-derive the week's core idea from memory, then redo or extend the hardest exercise.
- **Phase 1 (Weeks 1–7):** Python from zero → algorithms/data structures → performance Python
- **Phase 2 (Weeks 8–36):** Quant finance curriculum — probability through capstone
- **Phase 3 (Weeks 37–52):** C++ from zero → modern C++/low-latency → applied quant C++
- **Phase 4 (Weeks 53–95):** Artificial intelligence, from perceptrons to guru-level — deep learning foundations → CNNs → RNNs/Transformers → LLMs & generative AI → reinforcement learning → MLOps → a research-level capstone, with a deliberate bridge back into the Phase 2 quant work along the way

**On Phase 4's length:** Phases 1–3 stay exactly as originally built — open-ended, no deadline, whatever it takes. Phase 4 is scoped specifically to fit within a **hard cap of 2.5 years** at the Sunday-session pace: 43 weeks × ~3 Sundays/week ≈ 129 Sundays ≈ 2.48 years. If you go straight through all four phases back to back, the honest combined total is roughly 5–5.5 years — not because anything is padded, but because this is what "from scratch to guru" across quant, systems programming, and AI genuinely costs at one 5-hour session a week. Nothing about that needs to be decided now; you're already set up to just keep going indefinitely.
- **Phase 4 (Weeks 53–96):** Artificial intelligence, from deep-learning fundamentals through transformers/LLMs, reinforcement learning, generative models, MLOps, and research-level depth — capped at ~2.5 years of Sundays, added on top of Phases 1–3

**Honest total scale:** Phases 1–3 alone run ~150–160 Sundays (~3 years). Phase 4 adds another ~130 Sundays (~2.5 years) on top. Combined, that's roughly **280–290 Sundays, ~5.5 years at once a week** — for the complete quant finance + Python + C++ + AI stack, built with genuine from-scratch understanding rather than surface coverage. There's no deadline, so this is a ceiling on ambition, not a countdown. If at any point you'd rather stop after Phase 3 (a complete, coherent, and already substantial credential on its own) that's a perfectly good place to call it done.

**Resource legend:**
- **Automate the Boring Stuff** = free book, automatetheboringstuff.com
- **Corey Schafer** = YouTube `@coreyms`
- **Real Python** = realpython.com
- **Python docs** = docs.python.org/3/tutorial
- **GeeksforGeeks** = geeksforgeeks.org
- **LeetCode** = leetcode.com (free tier)
- **numba / Cython docs** = numba.pydata.org / cython.org
- **learncpp.com**, **The Cherno** (YouTube `@TheCherno`), **cppreference** = core free C++ resources
- **Herb Sutter** = herbsutter.com (free lock-free/concurrency articles)
- **Eigen**, **Catch2** = free header-only C++ libraries
- **Stat110** = Harvard Stat 110 (Blitzstein), free video + book draft, projects.iq.harvard.edu/stat110
- **ritvikmath**, **StatQuest** = YouTube channels
- **QuantStart**, **QuantInsti** = free quant blogs
- **Patrick Boyle**, **Option Alpha** = YouTube channels
- **MIT OCW 18.S096 / 15.401** = free MIT courses
- **Khan Academy Finance**, **Investopedia** = reference
- **pandas / statsmodels docs**, **backtrader docs**, **QuantConnect**, **Ken French Data Library**, **ISL** (statlearning.com, free PDF) = as before
- **"Original paper" tasks**: for classic papers (Markowitz 1952, Black-Scholes 1973, Fama-French 1993), search the paper title — free PDF copies are widely mirrored on university course pages even when the journal itself is paywalled.

---

## PHASE 1 — Python From Zero → Algorithms → Performance (Weeks 1–7)

### Week 1: Core syntax
- **Day 1:** H1: Variables, types, operators — Python docs §3–4. H2: Solve 8 GeeksforGeeks "basic syntax" practice problems; write a script using every operator type.
- **Day 2:** H1: Control flow — Automate the Boring Stuff Ch. 2. H2: Implement FizzBuzz three different ways; solve 3 LeetCode "Easy" loop problems.
- **Day 3:** H1: Functions, `*args`/`**kwargs` — Real Python "Python Functions". H2: Write a function that accepts variable arguments and kwargs and validates types manually; read Real Python "Python args and kwargs" in full.
- **Day 4:** H1: Strings & methods — Automate the Boring Stuff Ch. 6. H2: Implement string reversal, palindrome check, and a basic Caesar cipher from scratch (no libraries).
- **Day 5:** H1: Lists & tuples — Automate the Boring Stuff Ch. 4. H2: Implement your own `min`, `max`, and `sum` functions; solve 3 LeetCode array problems.
- **Day 6:** H1: Dicts & sets — Automate the Boring Stuff Ch. 5. H2: Build a word-frequency counter from a text file using only dicts (no `collections` yet).
- **Day 7:** Review both hours — write a 30-line script combining everything, no reference material.

### Week 2: Intermediate Python
- **Day 1:** H1: Comprehensions — Real Python. H2: Rewrite 5 of your Week 1 loop-based solutions as one-line comprehensions.
- **Day 2:** H1: File I/O — Automate the Boring Stuff Ch. 9. H2: Build a script that reads a CSV, transforms it, and writes a new CSV — with proper `with` blocks and error handling.
- **Day 3:** H1: Exceptions — Real Python. H2: Read Real Python "The Most Diabolical Python Antipattern" (bare excepts); refactor Day 2's script with specific exception types + custom exceptions.
- **Day 4:** H1: Modules, pip, venv — Real Python. H2: Package your Week 1 scripts into a proper local module with `__init__.py`; install and use one third-party package end to end.
- **Day 5:** H1: Classes & objects — Corey Schafer OOP #1. H2: Full Corey Schafer OOP #1 video exercises + build a `Vector2D` class with operator overloading (`__add__`, `__repr__`).
- **Day 6:** H1: Inheritance & dunders — Corey Schafer OOP #2–3. H2: Build a 3-level class hierarchy (e.g., `Animal → Mammal → Dog`) with method overriding and `super()`.
- **Day 7:** Review — explain modules vs. packages and dunder methods unaided; redo Day 5's Vector2D class from memory.

### Week 3: Pythonic idioms & standard library
- **Day 1:** H1: Iterators & generators — Real Python. H2: Build a custom iterator class (`__iter__`/`__next__`) and a generator version of the same logic; compare memory use with `sys.getsizeof`.
- **Day 2:** H1: Decorators — Corey Schafer. H2: Write a timing decorator and a logging decorator from scratch; stack two decorators on one function.
- **Day 3:** H1: Lambda/map/filter/reduce — Real Python. H2: Solve 5 problems using only lambda + functional tools, no explicit loops.
- **Day 4:** H1: `collections` module — Corey Schafer. H2: Rebuild Week 1 Day 6's word counter using `Counter`; use `defaultdict` and `namedtuple` in a small script.
- **Day 5:** H1: `itertools` — Real Python. H2: Solve 4 combinatorics-style problems using `itertools.permutations`/`combinations`/`groupby`.
- **Day 6:** H1+H2: **Project:** a full CLI to-do list manager (add/remove/list/persist to file) — spend both hours building it properly with error handling.
- **Day 7:** Review

### Week 4: Testing, debugging, tooling
- **Day 1:** H1: `pdb` debugging — Real Python. H2: Deliberately break your to-do app in 3 ways and debug each using `pdb` breakpoints, not print statements.
- **Day 2:** H1: `pytest` — Corey Schafer "Unit Testing". H2: Write a full test suite (10+ tests, including edge cases) for the to-do app.
- **Day 3:** H1: Type hints — Real Python "Type Checking". H2: Add full type hints to the to-do app; run `mypy` against it and fix every error.
- **Day 4:** H1: Dependency management — Real Python. H2: Set up a `requirements.txt` + isolated venv workflow for the to-do app from a fresh clone.
- **Day 5:** H1: Reading tracebacks — Real Python. H2: Collect 5 real tracebacks you've hit this week and write a one-line diagnosis for each.
- **Day 6:** H1+H2: **Project:** achieve >90% test coverage on the to-do app using `pytest-cov`.
- **Day 7:** Review

### Week 5: OOP design + bridge to numpy/pandas
- **Day 1:** H1: Composition vs. inheritance — Corey Schafer OOP #4. H2: Refactor one of your Week 2 inheritance hierarchies into composition; argue in writing which is better here.
- **Day 2:** H1: `dataclasses` — Real Python. H2: Convert 3 of your existing classes to `dataclasses`; add `frozen=True` where immutability makes sense.
- **Day 3:** H1: numpy arrays — freeCodeCamp NumPy tutorial. H2: Full freeCodeCamp NumPy tutorial to completion; solve 5 numpy array-manipulation exercises (broadcasting, slicing, reshaping).
- **Day 4:** H1: pandas DataFrames — pandas docs "10 Minutes to pandas". H2: Full "10 Minutes to pandas" + load a real Kaggle CSV dataset and do groupby/merge/pivot exercises.
- **Day 5:** H1+H2: **Project:** class-based bank-account simulator (deposit/withdraw/interest/overdraft rules) with full test coverage.
- **Day 6:** H1+H2: Consolidate — combine OOP + numpy/pandas: a class that wraps a DataFrame of transactions and computes running balances/statistics.
- **Day 7:** Review — explain classes, generators, decorators, comprehensions unaided.

### Week 6: Algorithms & data structures
- **Day 1:** H1: Big-O — GeeksforGeeks "Analysis of Algorithms". H2: Derive Big-O for 8 code snippets by hand (including nested loops, recursive calls) before checking answers.
- **Day 2:** H1: Arrays & linked lists from scratch — GeeksforGeeks. H2: Implement a singly linked list class with insert/delete/reverse methods, no libraries.
- **Day 3:** H1: Stacks & queues from scratch — GeeksforGeeks. H2: Implement both using only your linked list; solve "valid parentheses" and "implement queue via two stacks" on LeetCode.
- **Day 4:** H1: Recursion & sorting (merge sort, quicksort) — GeeksforGeeks/Real Python. H2: Implement merge sort and quicksort from scratch (not from memory of pseudocode — actually derive the partition logic); benchmark both on random vs. sorted input.
- **Day 5:** H1: Binary search — GeeksforGeeks. H2: Implement binary search + 3 variants (first/last occurrence, search in rotated array) on LeetCode.
- **Day 6:** H1: Trees & basic graph concepts (new — added for depth) — GeeksforGeeks "Binary Tree" and "Graph Data Structure". H2: Implement a binary search tree with insert/search/in-order traversal; solve 2 LeetCode tree problems.
- **Day 7:** Review — re-implement merge sort, binary search, and BST insert from memory, no references.

### Week 7: Performance Python for quant workloads
- **Day 1:** H1: Why vectorization matters — profile a loop vs. numpy-vectorized equivalent. H2: Benchmark the same computation 4 ways (pure loop, list comprehension, numpy, `map`) and produce a runtime comparison table.
- **Day 2:** H1: `numba` JIT — numba.pydata.org "5 Minute Guide". H2: Apply `@njit` to your Week 6 sorting implementations; benchmark before/after.
- **Day 3:** H1: `Cython` basics — cython.org quickstart. H2: Convert one numerically heavy function to Cython, build it, and benchmark against the pure-Python and numba versions.
- **Day 4:** H1: Profiling — Real Python "Profiling Python Code". H2: Profile your Week 5 bank-simulator + transaction DataFrame code with `cProfile` and `line_profiler`; find and fix the actual bottleneck.
- **Day 5:** H1: `multiprocessing` — Real Python. H2: Parallelize a batch computation (e.g., computing statistics across 20 stock CSVs) using `multiprocessing.Pool`; measure speedup vs. sequential.
- **Day 6:** H1+H2: **Project:** take a genuinely slow loop-based backtest and optimize it using the fastest applicable technique from this week; document the speedup with real numbers.
- **Day 7:** **Phase 1 review** — self-quiz on Big-O, when to reach for numba vs. Cython vs. multiprocessing; re-derive quicksort's partition step from memory.

---

## PHASE 2 — Quant Finance Curriculum (Weeks 8–36)

### Month 1 — Probability/Stats for Finance + Applied Python + Market Basics

**Week 8 (Probability foundations):**
- Day 1: H1: Random variables & distributions — Stat110 Lecture 1. H2: Full Stat110 Lecture 1 problem set; derive the PDF-to-CDF relationship by hand for the normal distribution.
- Day 2: H1: Expectation, variance, moments — Stat110 Lectures 4–5. H2: Prove linearity of expectation from first principles; compute higher moments (skewness, kurtosis) of a sample dataset in Python.
- Day 3: H1: Covariance & correlation — Khan Academy. H2: Derive the covariance formula from expectation definitions; compute a full covariance matrix for 5 real stocks in Python.
- Day 4: H1: Conditional probability & Bayes — Stat110 Lectures 2–3. H2: Solve 6 Bayes'-theorem word problems (Stat110 problem sets) without looking at solutions first.
- Day 5: H1: Central Limit Theorem — 3Blue1Brown + StatQuest. H2: Simulate CLT in Python — sample means from a non-normal distribution (e.g., exponential) 10,000 times and plot the resulting distribution.
- Day 6: H1: Problem set — 5 Stat110 problems. H2: 5 more Stat110 problems, harder tier; write full solutions with justification, not just answers.
- Day 7: Review

**Week 9 (Statistics for finance + market vocabulary):**
- Day 1: H1: Hypothesis testing — StatQuest. H2: Run a full t-test in Python on two stocks' returns; interpret the p-value correctly in writing.
- Day 2: H1: OLS regression — StatQuest. H2: Derive the OLS normal equations by hand; implement OLS from scratch in numpy (no `statsmodels`) and verify against `statsmodels`.
- Day 3: H1: Stationarity (concept) — ritvikmath. H2: Plot 3 real series (one clearly trending, one mean-reverting, one seasonal) and classify each by eye before formal testing (Week 17 will formalize this).
- Day 4: H1: Fat tails, skewness, kurtosis — Patrick Boyle. H2: Compute and compare kurtosis of real stock returns vs. a fitted normal distribution; visualize the tail difference.
- Day 5: H1: Market basics — Khan Academy Finance. H2: Read 3 Investopedia deep-dive articles on stock/bond/derivative mechanics; write one paragraph each in your own words.
- Day 6: H1: Market participants, order types — Investopedia. H2: Read QuantStart's market microstructure primer articles in full (previewing Week 14).
- Day 7: Review

**Week 10 (Quant Python stack):**
- Day 1: H1: numpy for finance data. H2: Vectorize 3 calculations you previously wrote as loops in Week 9's exercises.
- Day 2: H1: pandas for time series — pandas docs. H2: Full pandas "Time Series" documentation section; practice resample/rolling/shift on real data.
- Day 3: H1: `yfinance` — Sentdex/freeCodeCamp. H2: Pull 10 years of data for 10 stocks; handle missing data, splits, and dividends correctly.
- Day 4: H1: Resampling/cleaning — pandas docs. H2: Build a reusable data-cleaning pipeline function (handles NaNs, outliers, reindexing) you'll reuse for the rest of Phase 2.
- Day 5: H1: Plotting — matplotlib quickstart. H2: Build a multi-panel plot (price, returns, rolling volatility) for one stock; style it properly (labels, legend, titles).
- Day 6: H1+H2: **Project:** script pulling 10 stocks' data, cleaning it, and producing a summary statistics table + plots for each.
- Day 7: **Month 1 review**

**Week 11 (Returns & risk fundamentals):**
- Day 1: H1: Simple vs. log returns — QuantStart. H2: Prove algebraically why log returns are time-additive and simple returns aren't; verify numerically in Python.
- Day 2: H1: Volatility — Investopedia. H2: Compute rolling 30/60/90-day volatility for 5 stocks; compare annualized vol across them.
- Day 3: H1: Sharpe ratio — Investopedia. H2: Compute Sharpe ratio for 10 stocks using 3 different risk-free rate assumptions; discuss sensitivity.
- Day 4: H1: Correlation & diversification — Khan Academy. H2: Build a full correlation heatmap for 10 stocks across 2 sectors; identify diversification opportunities.
- Day 5: H1: Efficient frontier (concept) — Khan Academy. H2: Read QuantStart's efficient frontier article in full, working through its math by hand before Week 12 codes it.
- Day 6: H1+H2: **Project:** returns/vol/Sharpe/correlation for 10 stocks, packaged into one reusable analysis module.
- Day 7: **Month 1 review**

### Month 2 — Markets & Portfolio Theory

**Week 12 (MPT):**
- Day 1: H1: Markowitz mean-variance — MIT OCW 15.401. H2: Derive the two-asset portfolio variance formula by hand; search and skim the original Markowitz (1952) paper's core argument.
- Day 2: H1: Efficient frontier derivation — MIT OCW 15.401. H2: Solve the constrained optimization (minimize variance for target return) by hand using Lagrange multipliers.
- Day 3: H1: CAPM — Khan Academy. H2: Derive CAPM from the efficient frontier + market portfolio argument; read the QuantStart CAPM article in full.
- Day 4: H1: Beta — Investopedia. H2: Compute beta for 10 stocks via regression against a market index; compare to reported betas (Yahoo Finance) and explain discrepancies.
- Day 5: H1: Multi-factor models — Patrick Boyle. H2: Read the original Fama-French (1993) paper's abstract/intro and methodology section; note the three factors precisely.
- Day 6: H1+H2: **Project:** efficient frontier for 10 stocks via `scipy.optimize`, with a plotted Capital Market Line and tangency portfolio.
- Day 7: Review — derive CAPM from memory.

**Week 13 (Fixed income & macro):**
- Day 1: H1: Bond yield/duration/convexity — Khan Academy. H2: Derive Macaulay duration formula by hand; compute duration and convexity for a real bond in Python.
- Day 2: H1: Yield curve — Investopedia. H2: Pull real Treasury yield curve data (FRED, free) and plot curve shape changes over the last 12 months.
- Day 3: H1: Interest rate risk — Khan Academy. H2: Compute price sensitivity (ΔP) of a bond for a 100bps rate move using duration/convexity approximation vs. exact repricing.
- Day 4: H1: Macro drivers — Patrick Boyle. H2: Read 2 QuantInsti/Investopedia deep-dives on how Fed policy transmits to asset prices.
- Day 5: H1: FX basics — Investopedia. H2: Compute covered interest rate parity for a currency pair using real rates; verify it roughly holds.
- Day 6: H1+H2: Practice — build a small yield-curve analysis notebook (fetch, plot, interpret shape, compute a bond's duration/convexity).
- Day 7: Review

**Week 14 (Market microstructure):**
- Day 1: H1: Order book & bid-ask spread — QuantStart. H2: Read QuantStart's full microstructure series; sketch how a limit order book updates on a new order by hand.
- Day 2: H1: Market making — Patrick Boyle. H2: Read QuantInsti's market-making strategy article in full; write out the inventory-risk tradeoff in your own words.
- Day 3: H1: Liquidity & slippage — QuantInsti. H2: On a real order-book dataset (Kaggle), compute the effective spread and estimate slippage for a hypothetical market order.
- Day 4: H1: Order types — Investopedia. H2: Read Investopedia's full glossary of order types (stop-limit, iceberg, FOK, IOC); write one-line definitions from memory afterward.
- Day 5: H1: Transaction costs — QuantStart. H2: Model transaction costs (fixed + proportional to size) into your Week 11 Sharpe-ratio calculations; see how much they erode returns.
- Day 6: H1+H2: Practice — deep analysis of a sample order-book dataset (Kaggle): compute spread, depth, and imbalance metrics over time.
- Day 7: Review

**Week 15 (Applied portfolio theory):**
- Days 1–6: H1: Coursera "Financial Engineering and Risk Management I" (Columbia) Week 1 module, audit free. H2: Do every graded exercise in that week's module even though it's audited (no certificate needed) — the exercises are the value, not the certificate.
- Day 7: **Month 2 review**

**Week 16 (Advanced portfolio construction):**
- Day 1: H1: Limitations of vanilla Markowitz — QuantStart "Markowitz Problems". H2: Demonstrate the estimation-error problem yourself: resample your 10-stock return data and show how wildly the "optimal" weights swing.
- Day 2: H1: Black-Litterman intuition — QuantStart "Black-Litterman". H2: Work through the Black-Litterman math by hand on a 2-asset toy example before coding it.
- Day 3: H1: Black-Litterman implementation. H2: Implement full Black-Litterman on your 10-stock universe with your own market views.
- Day 4: H1: Risk parity — QuantStart "Risk Parity". H2: Derive why risk parity weights ∝ 1/volatility in the simplified (uncorrelated) case; verify numerically.
- Day 5: H1: Implement risk parity in Python. H2: Implement true risk parity (equal risk contribution, correlated case) via numerical optimization, not just the 1/vol approximation.
- Day 6: H1+H2: **Project:** compare mean-variance vs. Black-Litterman vs. risk-parity weights and out-of-sample performance on the same 10 stocks over a held-out period.
- Day 7: Review — explain why Black-Litterman helps with estimation error, unaided.

### Month 3 — Time Series Econometrics

**Week 17 (Time series fundamentals):**
- Day 1: H1: Stationarity/ADF test — ritvikmath. H2: Derive the ADF test's null hypothesis logic; run ADF on your Week 9 three series and confirm your earlier "by eye" classification.
- Day 2: H1: ACF/PACF — ritvikmath. H2: Compute ACF/PACF by hand for a tiny synthetic AR(1) series (5–6 points) before letting `statsmodels` do it for real data.
- Day 3: H1: White noise & random walks — ritvikmath. H2: Simulate a random walk vs. white noise in Python; run ADF on both and confirm expected results.
- Day 4: H1: AR(p) — ritvikmath. H2: Derive the AR(1) unconditional mean/variance formula by hand; fit AR(1)–AR(3) to real returns and compare AIC.
- Day 5: H1: MA(q) — ritvikmath. H2: Simulate an MA(1) process and show its ACF cuts off after lag 1, matching theory.
- Day 6: H1: ARMA + `statsmodels`. H2: Fit ARMA(p,q) via grid search over (p,q) using AIC/BIC on a real series; justify your chosen order.
- Day 7: Review

**Week 18 (ARIMA & volatility):**
- Day 1: H1: ARIMA — ritvikmath. H2: Difference a non-stationary series until stationary (by hand, checking ADF each time) before fitting ARIMA.
- Day 2: H1: Fit ARIMA to real data — statsmodels docs. H2: Fit ARIMA to 3 different stocks; forecast 30 days out and backtest forecast accuracy against actuals.
- Day 3: H1: Volatility clustering — Patrick Boyle. H2: Plot squared returns for a real stock and visually confirm clustering; compute the autocorrelation of squared returns.
- Day 4: H1: ARCH — ritvikmath. H2: Derive the ARCH(1) conditional variance recursion by hand; fit ARCH(1) manually via MLE in Python (not just the `arch` package) for a small dataset.
- Day 5: H1: GARCH — ritvikmath. H2: Compare ARCH(1) vs. GARCH(1,1) fit on the same series; explain why GARCH usually fits better with fewer parameters.
- Day 6: H1+H2: **Project:** GARCH(1,1) via the `arch` package on 5 stocks; forecast volatility and compare against realized volatility out-of-sample.
- Day 7: Review

**Week 19 (Cointegration & pairs trading):**
- Day 1: H1: Cointegration — ritvikmath. H2: Explain (in writing) why two individually non-stationary series can have a stationary linear combination; find a candidate pair by eye first.
- Day 2: H1: Engle-Granger test — QuantStart. H2: Run Engle-Granger on 5 candidate stock pairs; identify which (if any) are genuinely cointegrated.
- Day 3: H1: Pairs-trading logic — QuantStart. H2: Read the full QuantStart pairs-trading article series (not just the intro article).
- Day 4: H1: Implement pairs-trading skeleton. H2: Add entry/exit z-score thresholds and position-sizing logic to the skeleton.
- Day 5: H1: Mean-reversion strategies — QuantInsti. H2: Read 2 more QuantInsti mean-reversion articles; note how they handle regime changes.
- Day 6: H1+H2: **Project:** full backtest of your pairs trade including transaction costs from Week 14, with a proper performance report (Sharpe, drawdown, hit rate).
- Day 7: Review

**Week 20 (Factor regressions & Month 3 wrap):**
- Day 1: H1: Multiple regression pitfalls — StatQuest. H2: Deliberately construct a multicollinear regression example and show how coefficient estimates become unstable.
- Day 2: H1: Fama-French 3-factor — Ken French Data Library. H2: Download real Fama-French factor data and run the regression on 5 real stocks; interpret each factor loading.
- Day 3: H1: Rolling regressions in pandas. H2: Plot rolling factor loadings over time for one stock; identify a period where its factor exposure clearly shifted.
- Day 4: H1: Residual diagnostics. H2: Check residuals for autocorrelation (Durbin-Watson) and heteroskedasticity on your Day 2 regression; discuss implications.
- Day 5: H1+H2: **Project:** factor regression on 10 real stocks, packaged as a reusable function, with a written interpretation of each stock's factor profile.
- Day 6: Consolidate — write a one-page summary connecting stationarity → ARIMA → GARCH → cointegration → factor models.
- Day 7: **Month 3 review**

### Month 4 — Derivatives & Stochastic Calculus

**Week 21 (Options fundamentals):**
- Day 1: H1: Calls & puts — Option Alpha. H2: Work through 5 payoff-calculation problems by hand for various strikes/spot prices.
- Day 2: H1: Payoff diagrams — Option Alpha. H2: Plot payoff AND profit (net of premium) diagrams for calls, puts, and a straddle in matplotlib.
- Day 3: H1: Put-call parity — Investopedia. H2: Derive put-call parity from a no-arbitrage argument by hand; verify it numerically on real option-chain data if accessible, or synthetic data otherwise.
- Day 4: H1: Intrinsic vs. time value — Option Alpha. H2: Decompose 5 real option quotes (any free options-chain viewer) into intrinsic + time value.
- Day 5: H1: Basic spreads — Option Alpha. H2: Build payoff diagrams for 3 more spread types (bull call spread, iron condor, calendar spread).
- Day 6: H1+H2: **Project:** an interactive-in-notebook payoff diagram tool that takes strike/premium/type as inputs for any combination of legs.
- Day 7: Review

**Week 22 (Black-Scholes & Greeks):**
- Day 1: H1: Brownian motion — MIT OCW 18.S096 Lecture 1. H2: Simulate a Wiener process in Python (multiple paths) and verify its variance grows linearly with time.
- Day 2: H1: Itô's Lemma — MIT OCW 18.S096 Lecture 2 + QuantStart. H2: Work through the full Itô's Lemma derivation by hand for a specific function (e.g., f(S,t) = ln(S)); this is the actual proof, not just the statement.
- Day 3: H1: Black-Scholes derivation — MIT OCW 18.S096. H2: Derive the Black-Scholes PDE from the replicating-portfolio argument, step by step, on paper.
- Day 4: H1: Implement BS formula in Python. H2: Verify your implementation against known benchmark values; test edge cases (deep ITM/OTM, near-zero time-to-expiry).
- Day 5: H1: The Greeks — Option Alpha. H2: Derive delta and gamma analytically (partial derivatives of the BS formula) and verify against finite-difference numerical derivatives of your Day 4 pricer.
- Day 6: H1+H2: **Project:** full BS pricer + all 5 Greeks, validated against finite-difference approximations, with a plotted Greeks-vs-spot-price chart for each Greek.
- Day 7: Review

**Week 23 (Monte Carlo & numerical pricing):**
- Day 1: H1: Monte Carlo concept — QuantStart. H2: Estimate π via Monte Carlo as a warm-up; discuss convergence rate (error ~ 1/√N).
- Day 2: H1: Simulating GBM paths — Python. H2: Simulate 10,000 GBM paths and verify the terminal distribution matches the theoretical lognormal.
- Day 3: H1: Pricing European options via Monte Carlo. H2: Price the same option via Monte Carlo with 100, 1,000, 10,000, 100,000 paths; plot convergence to the BS closed-form price.
- Day 4: H1: Variance reduction — QuantStart. H2: Implement antithetic variates AND control variates; measure the variance reduction achieved by each.
- Day 5: H1: Binomial tree pricing — QuantStart. H2: Derive the risk-neutral up/down probabilities from the no-arbitrage condition by hand; implement a tree with 500+ steps and confirm convergence to BS.
- Day 6: H1+H2: **Project:** one unified pricer comparing BS closed-form, Monte Carlo (with variance reduction), and binomial tree — with a runtime AND accuracy comparison table.
- Day 7: Review

**Week 24 (Advanced derivatives & Month 4 wrap):**
- Day 1: H1: Implied volatility & vol smile — Patrick Boyle. H2: Implement an implied-vol solver (Newton-Raphson or bisection) that inverts your BS pricer; run it against real option-chain data to plot an actual smile.
- Day 2: H1: American options — QuantStart. H2: Extend your binomial tree to handle early exercise; compare American vs. European put prices for the same parameters and confirm American ≥ European.
- Day 3: H1: Exotic options overview — Investopedia. H2: Price a barrier option (up-and-out call) via Monte Carlo, checking the barrier condition at each path step.
- Day 4: H1: Risk-neutral pricing — MIT OCW 18.S096. H2: Read/work through the Girsanov theorem's role in the risk-neutral measure change at an intuitive level (full rigor isn't necessary here, but the "why" should be clear).
- Day 5: H1: Problem-set day — hardest exercises from Weeks 21–23. H2: Redo the BS PDE derivation and the binomial no-arbitrage derivation from memory, unaided.
- Day 6: Consolidate — write a one-page summary connecting Brownian motion → Itô → BS PDE → risk-neutral pricing → Monte Carlo/tree numerics.
- Day 7: **Month 4 review**

**Week 25 (Fixed income derivatives & credit risk):**
- Day 1: H1: FRAs & interest rate swaps — Investopedia. H2: Derive the fixed-rate that makes a swap's initial value zero, for a simple 2-period example, by hand.
- Day 2: H1: Swap pricing intuition — Khan Academy/Investopedia. H2: Price a plain-vanilla interest rate swap in Python using a bootstrapped discount curve.
- Day 3: H1: Credit default swaps — Investopedia. H2: Read a QuantStart or Investopedia deep-dive on CDS pricing (hazard-rate approach); write the core intuition in your own words.
- Day 4: H1: Credit risk basics — default probability, recovery rate — Khan Academy. H2: Compute expected loss = PD × LGD × EAD for a toy loan portfolio; discuss how correlation between defaults changes portfolio-level risk.
- Day 5: H1: Bond pricing with credit spread — Investopedia. H2: Price a corporate bond using a risk-free curve + credit spread; compare to its risk-free-equivalent price.
- Day 6: H1+H2: **Project:** price a simple interest rate swap AND a simplified CDS in Python, with a written explanation of how each transfers risk.
- Day 7: Review — explain how a CDS transfers credit risk, unaided.

### Month 5 — Algorithmic Trading & Backtesting

**Week 26 (Strategy design):**
- Day 1: H1: Strategy types — QuantStart. H2: Read the full QuantStart strategy-taxonomy article series; classify 5 real, well-known strategies (that you research) by type.
- Day 2: H1: Signal generation — QuantInsti. H2: Generate 3 different signals (MA crossover, RSI, Bollinger Band breakout) on the same stock and compare when they'd trigger.
- Day 3: H1: Momentum strategy logic — QuantStart. H2: Implement a 12-month momentum ranking strategy across 20 stocks (long top decile).
- Day 4: H1: Backtesting pitfalls — QuantStart. H2: Deliberately introduce lookahead bias into a backtest, show the inflated (fake) performance, then fix it and show the real (worse) performance.
- Day 5: H1: Performance metrics — Investopedia. H2: Compute Sharpe, Sortino, Calmar ratio, and max drawdown for your Day 3 momentum strategy; interpret each.
- Day 6: H1+H2: **Project:** MA-crossover AND momentum signals combined into one strategy, with full performance metrics.
- Day 7: Review

**Week 27 (Backtesting frameworks):**
- Day 1: H1: Intro to `backtrader` — backtrader docs. H2: Work through 2 full backtrader example strategies from their docs, not just the quickstart.
- Day 2: H1: Basic backtest with backtrader. H2: Port your Week 26 momentum strategy into backtrader properly (not just a manual loop).
- Day 3: H1: Commission/slippage modeling. H2: Add realistic commission + slippage models and see how much they change your Sharpe ratio.
- Day 4: H1: Position sizing & risk controls — QuantInsti. H2: Implement volatility-targeted position sizing (size ∝ 1/vol) instead of fixed sizing.
- Day 5: H1: Walk-forward analysis — QuantStart. H2: Implement a walk-forward test (train on rolling window, test out-of-sample) rather than one static backtest.
- Day 6: H1+H2: **Project:** full backtest with realistic costs, vol-targeted sizing, and walk-forward validation — the "real" version of Week 26's strategy.
- Day 7: Review

**Week 28 (Alternative strategies & robustness):**
- Day 1: H1: Statistical arbitrage — QuantInsti. H2: Extend your Week 19 pairs trade to a basket of 3+ cointegrated assets.
- Day 2: H1: Regime detection — Patrick Boyle. H2: Implement a simple regime filter (e.g., 200-day MA trend filter) and apply it as an on/off switch to your momentum strategy.
- Day 3: H1: Multi-asset backtesting. H2: Run your strategy across 3 asset classes (equities, an FX pair, a commodity ETF) and compare performance.
- Day 4: H1: Transaction-cost refinement. H2: Model market-impact costs that scale with trade size (not just fixed bps), using a simple square-root impact model.
- Day 5: H1: Overfitting risk — QuantStart. H2: Run a parameter sweep (e.g., MA windows 5–100) and plot the "performance surface" — identify if your chosen parameters sit in a stable region or a lucky spike.
- Day 6: H1+H2: **Project:** optimize parameters properly (train/validation split, not just in-sample maximization); report both in-sample and out-of-sample Sharpe.
- Day 7: Review

**Week 29 (QuantConnect & Month 5 wrap):**
- Days 1–5: H1: QuantConnect free Boot Camp tutorials. H2: Extend each day's tutorial — add your own signal logic, run it over a longer/different universe, and inspect QuantConnect's built-in performance reports in depth.
- Day 6: Consolidate — compare your backtrader-based project against your QuantConnect algorithm; note differences in results and why.
- Day 7: **Month 5 review**

**Week 30 (Market microstructure & HFT overview):**
- Day 1: H1: How HFT firms make money — Patrick Boyle. H2: Read QuantStart's full HFT article series; write a one-page summary of the main HFT strategy families.
- Day 2: H1: Latency arbitrage & colocation — QuantStart. H2: Research (via free articles) a real historical example of a latency-arbitrage strategy and how exchanges responded (e.g., speed bumps).
- Day 3: H1: Market-making strategies in depth — QuantInsti. H2: Model a simple market-maker's P&L (spread capture minus adverse-selection losses) in a toy Python simulation.
- Day 4: H1: Order flow toxicity, adverse selection — QuantStart. H2: Read about the VPIN metric (volume-synchronized probability of informed trading) and compute a simplified version on real order-book data.
- Day 5: H1: Why HFT infrastructure is built in C++. H2: Read 2 practitioner blog posts on quant infra architecture (search "HFT system architecture blog") to set concrete expectations for Phase 3.
- Day 6: H1+H2: Practice — design (on paper/diagram) a market-making strategy's full decision logic, including inventory limits and quote-skewing based on inventory.
- Day 7: Review — **Month 5.5 review**, bridges into Phase 3.

### Month 6 — ML in Finance, Risk Management, Capstone

**Week 31 (ML foundations refresher):**
- Day 1: H1: Train/test split, cross-validation — StatQuest. H2: Implement k-fold CV from scratch (not `sklearn`'s built-in) to understand the mechanics.
- Day 2: H1: Linear vs. logistic regression — StatQuest. H2: Derive the logistic regression log-loss gradient by hand; implement logistic regression via gradient descent from scratch.
- Day 3: H1: Decision trees & random forests — StatQuest. H2: Implement a basic decision-tree split (Gini impurity) from scratch on a toy dataset.
- Day 4: H1: Regularization — StatQuest. H2: Fit Ridge and Lasso on the same regression problem; plot how coefficients shrink as the regularization strength increases.
- Day 5: H1: Feature engineering — Kaggle Learn. H2: Full Kaggle Learn "Feature Engineering" course to completion, with all exercises.
- Day 6: H1+H2: **Project:** classifier predicting next-day up/down move using proper time-aware train/test splitting (not random shuffling — that leaks future information).
- Day 7: Review

**Week 32 (ML applied to finance):**
- Day 1: H1: Feature importance/SHAP — StatQuest. H2: Compute SHAP values for your Week 31 classifier; identify which features actually drive predictions.
- Day 2: H1: Time-series cross-validation — ISL free PDF. H2: Read the ISL resampling chapter in full; implement proper walk-forward CV (not k-fold) for your classifier.
- Day 3: H1: ML for factor investing — Patrick Boyle. H2: Read 2 QuantStart/QuantInsti articles on ML-based factor discovery; note the overfitting warnings each gives.
- Day 4: H1: Why ML overfits in finance — QuantInsti. H2: Deliberately overfit a model (too many features, too little data) and show the in-sample vs. out-of-sample performance gap.
- Day 5: H1+H2: **Project:** ML-based signal, properly walk-forward validated, backtested with realistic costs from Month 5.
- Day 6: Consolidate — write a one-page comparison of your rule-based (Week 26–28) vs. ML-based strategy's out-of-sample robustness.
- Day 7: Review

**Week 33 (Risk management):**
- Day 1: H1: VaR — Investopedia/Khan Academy. H2: Compute VaR three ways (historical, parametric/variance-covariance, Monte Carlo) for the same portfolio and compare.
- Day 2: H1: Expected Shortfall/CVaR — QuantStart. H2: Derive why CVaR is a coherent risk measure while VaR isn't (subadditivity); compute CVaR for your portfolio.
- Day 3: H1: Stress testing — Investopedia. H2: Stress-test your portfolio against 2 real historical crisis periods (e.g., 2008, March 2020) using actual historical returns.
- Day 4: H1: Portfolio risk decomposition — QuantStart. H2: Decompose total portfolio VaR into each position's marginal contribution to risk.
- Day 5: H1+H2: **Project:** full risk report — VaR/CVaR (3 methods), stress tests, and risk contribution breakdown — for your Week 16 portfolio.
- Day 6: Consolidate
- Day 7: Review

**Week 34 (Capstone — build):**
- Day 1: H1+H2: Choose final scope — a full pipeline: signal generation (rule-based or ML) → portfolio construction (Black-Litterman or risk parity from Week 16) → backtest (walk-forward, realistic costs) → risk report (VaR/CVaR/stress tests), across 5–10 assets.
- Days 2–5: H1+H2 each day: build incrementally — one component per day (signal, portfolio construction, backtest engine, risk report, integration).
- Day 6: Finalize working end-to-end version.
- Day 7: Rest.

**Week 35 (Capstone — polish):**
- Days 1–4: H1: Polish code (clean functions, docstrings, remove dead code). H2: Write a proper methodology report explaining every choice (why this signal, why this portfolio method, why these risk metrics).
- Day 5: H1: Post for feedback (r/quant, QuantConnect forums). H2: While waiting, write unit tests for the capstone's core functions.
- Day 6: Incorporate feedback.
- Day 7: Rest.

**Week 36 (Python-side wrap):**
- Day 1: H1: Probability brainteasers. H2: 5 more, harder tier (search "quant interview brainteasers pdf" — many free sets); write full solutions, not just answers.
- Day 2: H1: Flashcard review — BS, CAPM, Sharpe, VaR, Black-Litterman, swap pricing. H2: Derive each formula from scratch on blank paper, timed.
- Day 3: H1: Practice explaining capstone aloud. H2: Record yourself (audio is fine) explaining it in under 3 minutes, then critique your own clarity.
- Day 4: H1: Quant coding questions in Python. H2: 4 LeetCode medium problems under interview time pressure (30 min each).
- Day 5: H1: Full review pass — weakest month. H2: Redo that month's hardest project from scratch, no reference to old code.
- Day 6: Consolidate — **Phase 2 complete.**
- Day 7: Rest before starting C++.

---

## PHASE 3 — C++ From Zero → Modern C++/Low-Latency → Applied Quant (Weeks 37–52)

### Week 37: Core C++ syntax
- Day 1: H1: Compiling, variables, types — learncpp.com Ch. 1. H2: Compile and run programs manually via g++ (no IDE magic) to understand the compile/link process; solve 5 learncpp quizzes.
- Day 2: H1: Operators, expressions. H2: Write a small calculator program using every arithmetic/logical operator.
- Day 3: H1: Control flow. H2: Reimplement 3 of your Week 1 (Phase 1) Python exercises (FizzBuzz, palindrome check) in C++.
- Day 4: H1: Functions. H2: Practice function overloading and default parameters with 5 examples.
- Day 5: H1: Arrays. H2: Implement array-based bubble sort and linear search from scratch.
- Day 6: H1+H2: Practice — learncpp.com quizzes Ch. 1–5, all of them, not a sample.
- Day 7: Review

### Week 38: Pointers & memory
- Day 1: H1: Pointers — learncpp.com Ch. 9. H2: Draw memory diagrams by hand for 5 pointer examples before running them, then verify with a debugger.
- Day 2: H1: References. H2: Write functions using pass-by-value, pass-by-pointer, and pass-by-reference for the same task; compare behavior when mutating the argument.
- Day 3: H1: Dynamic memory (`new`/`delete`). H2: Deliberately create and then fix a memory leak; run it through `valgrind` if available, or reason through it manually.
- Day 4: H1: Pointers vs. references, pitfalls — The Cherno. H2: Implement a dynamic array class manually (your own mini `std::vector`) using raw pointers.
- Day 5: H1: `const` correctness — learncpp.com. H2: Add proper `const` qualifiers throughout your Week 37–38 code and fix resulting compiler errors.
- Day 6: H1+H2: Practice exercises — extend your dynamic array class with resize logic.
- Day 7: Review — explain pointer vs. reference, and draw a stack/heap diagram, unaided.

### Week 39: OOP in C++
- Day 1: H1: Classes & objects — learncpp.com. H2: Port your Python `Vector2D` class (Phase 1, Week 2) to C++ with operator overloading.
- Day 2: H1: Constructors/destructors. H2: Add copy constructor and destructor to your dynamic array class from Week 38; trace through what happens on copy.
- Day 3: H1: Encapsulation, access specifiers. H2: Refactor a class to properly encapsulate its internals (private members, public interface only).
- Day 4: H1: Inheritance. H2: Port your Python 3-level class hierarchy (Phase 1, Week 2) to C++.
- Day 5: H1: Polymorphism & virtual functions — learncpp.com/The Cherno. H2: Add a virtual base-class method and override it in 2 derived classes; demonstrate dynamic dispatch through a base-class pointer.
- Day 6: H1+H2: **Project:** small class hierarchy for financial instruments (`Instrument → Bond, Option`) with virtual `price()` methods.
- Day 7: Review

### Week 40: STL fundamentals
- Day 1: H1: `std::vector` — cppreference + The Cherno. H2: Replace your Week 38 hand-rolled dynamic array with `std::vector` everywhere; compare code size/clarity.
- Day 2: H1: `std::map`, `std::unordered_map`. H2: Build a word-frequency counter (like Phase 1 Week 1) in C++ using `unordered_map`; benchmark vs. a manual hash table if time allows.
- Day 3: H1: `std::string`. H2: Implement string reversal and palindrome check (Phase 1 exercises) in C++ using `std::string` methods.
- Day 4: H1: Iterators. H2: Practice iterating with raw iterators, range-based for, and `std::for_each` on the same container.
- Day 5: H1: `<algorithm>` (sort, find, etc.). H2: Solve 5 small problems using only STL algorithms, no manual loops.
- Day 6: H1+H2: **Project:** re-implement your Phase 1 CLI to-do tool in C++ using STL containers throughout.
- Day 7: Review

### Week 41: Templates & generic programming
- Day 1: H1: Function templates — learncpp.com. H2: Write a generic `max`/`min`/`swap` template function and test with multiple types.
- Day 2: H1: Class templates. H2: Templatize your Week 38 dynamic array class so it works for any type.
- Day 3: H1: Templates + STL. H2: Write a generic function that works over any STL container using iterator templates.
- Day 4: H1: Smart pointers (`unique_ptr`, `shared_ptr`). H2: Refactor your Week 39 financial-instrument hierarchy to use `unique_ptr` instead of raw pointers; explain why this prevents leaks.
- Day 5: H1: RAII concept — The Cherno "RAII". H2: Write a small RAII wrapper class (e.g., a file handle or timer) that cleans up automatically on scope exit.
- Day 6: H1+H2: Practice exercises — combine templates + smart pointers in one small generic container class.
- Day 7: Review

### Week 42: Modern C++ & light template metaprogramming
- Day 1: H1: `auto`, range-based for, structured bindings — learncpp.com. H2: Refactor Weeks 37–41's code to use modern idioms throughout; note where `auto` helps vs. obscures.
- Day 2: H1: Lambda expressions — cppreference. H2: Rewrite 3 of your `<algorithm>` calls from Week 40 to use custom lambdas instead of named functions.
- Day 3: H1: `constexpr` and compile-time computation — learncpp.com. H2: Write a `constexpr` function (e.g., compile-time factorial) and verify via `static_assert` that it computes at compile time, not runtime.
- Day 4: H1: Variadic templates — cppreference. H2: Write a simple variadic `print(args...)` function that accepts any number/type of arguments.
- Day 5: H1: `std::optional`, `std::variant` — cppreference. H2: Refactor a function that previously used a sentinel value (e.g., -1 for "not found") to return `std::optional` instead.
- Day 6: H1+H2: Practice — rewrite a Week 41 exercise using modern-C++ idioms throughout (auto, lambdas, optional, constexpr where applicable).
- Day 7: Review — explain when `constexpr` actually saves runtime cost, unaided.

### Week 43: Memory & performance
- Day 1: H1: Stack vs. heap, memory layout — The Cherno. H2: Write a program that prints addresses of stack vs. heap variables and reason about the layout you observe.
- Day 2: H1: Move semantics, rvalue references — learncpp.com. H2: Add a move constructor to your Week 39/41 classes; benchmark copy vs. move for a large object.
- Day 3: H1: Copy vs. move constructors. H2: Trace through (with print statements) exactly when copy vs. move constructors fire in a small program with vectors of objects.
- Day 4: H1: Compiler optimization flags, timing code — The Cherno "Benchmarking". H2: Benchmark the same function at `-O0` vs. `-O2` vs. `-O3`; discuss the difference.
- Day 5: H1: Cache-friendliness — The Cherno "Performance" series. H2: Benchmark row-major vs. column-major traversal of a 2D array/matrix; measure the real cache-miss penalty.
- Day 6: H1+H2: Practice — apply one cache-friendliness fix to your Week 40 to-do tool or Week 39 instrument hierarchy and measure the actual speedup.
- Day 7: Review

### Week 44: Concurrency basics
- Day 1: H1: Threads (`<thread>`) — cppreference/The Cherno. H2: Write a program that launches 4 threads doing independent work and joins them properly.
- Day 2: H1: Mutexes & race conditions — The Cherno. H2: Deliberately create a data race (shared counter, no mutex), observe incorrect results, then fix it with a mutex.
- Day 3: H1: Atomics (intro) — cppreference. H2: Replace your Day 2 mutex-protected counter with `std::atomic<int>`; benchmark mutex vs. atomic for this simple case.
- Day 4: H1: Why concurrency matters in trading systems — QuantStart. H2: Read 1–2 QuantStart articles on multi-threaded trading system design.
- Day 5: H1+H2: **Project:** simple multi-threaded program — e.g., one thread generating simulated market data, another consuming and processing it (a preview of producer-consumer, formalized properly in Week 45).
- Day 6: Consolidate
- Day 7: Review

### Week 45: Lock-free & low-latency system design
- Day 1: H1: What "lock-free" means and why HFT wants it — Herb Sutter's lock-free articles. H2: Read the full Herb Sutter article on lock-free programming (not a summary — the actual piece); note every subtlety about memory ordering he raises.
- Day 2: H1: Compare-and-swap (CAS) — Herb Sutter/cppreference `std::atomic`. H2: Implement a simple CAS-based spinlock and compare its behavior to `std::mutex` under contention.
- Day 3: H1: A simple lock-free queue — Herb Sutter/The Cherno. H2: Implement (carefully, following a known-correct reference design) a single-producer/single-consumer lock-free ring buffer.
- Day 4: H1: Latency vs. throughput tradeoffs — QuantStart "Low Latency". H2: Benchmark your Week 44 mutex-based producer-consumer vs. your new lock-free version under load; measure actual latency difference.
- Day 5: H1: Kernel bypass & networking basics (conceptual) — QuantStart article. H2: Read a practitioner article on kernel-bypass networking (e.g., DPDK/kernel-bypass overview) — conceptual understanding is the goal, not implementation.
- Day 6: H1+H2: **Project:** finalize your lock-free SPSC queue with tests proving correctness (no dropped/duplicated messages) under concurrent stress.
- Day 7: Review — explain why locks are costly at the microsecond scale, unaided.

### Week 46: Numerical computing in C++
- Day 1: H1: Newton's method in C++. H2: Implement Newton's method generically (templated on the function) and test convergence on 3 different functions.
- Day 2: H1: Linear algebra with Eigen — Eigen docs. H2: Full Eigen "Getting Started" + "Matrix and Vector Arithmetic" doc pages, working every example.
- Day 3: H1: Matrix operations with Eigen. H2: Port your Python Week 12 efficient-frontier optimization's core linear algebra (covariance matrix operations) into Eigen.
- Day 4: H1: Random number generation (`<random>`). H2: Implement Box-Muller or use `<random>`'s normal distribution to generate GBM shocks; verify the distribution statistically.
- Day 5: H1+H2: **Project:** simulate GBM paths in C++ using Eigen for vectorized path generation; benchmark against your Python Week 23 version.
- Day 6: Consolidate
- Day 7: Review

### Week 47: Quant applications — pricers
- Day 1: H1: QuantStart's "C++ for Quantitative Finance" series — intro. H2: Read the full series (not just part 1) to understand their design patterns before writing your own.
- Day 2: H1: Black-Scholes pricer in C++. H2: Add all 5 Greeks (analytical, matching your Week 22 Python derivations) to the C++ pricer.
- Day 3: H1: Monte Carlo option pricer in C++. H2: Add both variance-reduction techniques from Week 23 (antithetic, control variates) to the C++ version.
- Day 4: H1: Binomial tree pricer in C++. H2: Extend it to handle American exercise, mirroring your Week 24 Python logic.
- Day 5: H1: Compare C++ vs. Python runtime for the same pricer. H2: Build a proper benchmark harness (varying number of simulations/tree steps) and produce a runtime-vs-accuracy chart for both languages.
- Day 6: H1+H2: Consolidate all three pricers (BS, Monte Carlo, binomial) into one header-only C++ library with a consistent interface.
- Day 7: Review

### Week 48: Building a mini backtester in C++
- Day 1: H1: Reading CSV data (`<fstream>`). H2: Write a robust CSV parser handling missing fields/malformed rows gracefully (don't just assume clean data).
- Day 2: H1: Representing OHLC data with structs/classes. H2: Design a `Bar` struct and a `TimeSeries` class wrapping a `std::vector<Bar>` with useful accessor methods.
- Day 3: H1: Moving-average signal logic in C++. H2: Implement both SMA and EMA; unit test them against known hand-computed values.
- Day 4: H1: Basic backtest loop. H2: Add position tracking and P&L accounting to the loop, mirroring your Python Week 27 backtrader logic.
- Day 5: H1: Computing Sharpe/drawdown in C++. H2: Cross-validate your C++ Sharpe/drawdown numbers against your Python results on the identical dataset — they must match exactly.
- Day 6: H1+H2: **Project:** full mini backtester with realistic costs (from your Week 27/28 Python model, ported to C++).
- Day 7: Review

### Week 49: Order-book / matching engine simulator
*(Ties together Week 30's HFT overview and Week 45's lock-free work)*
- Day 1: H1: Order-book data structure design (price levels, FIFO queues). H2: Design the class interfaces on paper first (what operations does the book need to support, and at what complexity) before writing code.
- Day 2: H1: Implementing a limit order book in C++. H2: Choose and justify your underlying data structure (e.g., `std::map<price, queue<Order>>`); discuss the Big-O of insert/cancel/best-bid-ask lookup.
- Day 3: H1: Basic matching logic (price-time priority). H2: Write thorough unit tests covering partial fills, exact fills, and no-match cases.
- Day 4: H1: Adding market orders & partial fills. H2: Handle the edge case of a market order that exhausts the entire book on one side.
- Day 5: H1: Generating synthetic order flow to test the engine. H2: Generate a stress test of 100,000+ synthetic orders and measure throughput (orders processed per second).
- Day 6: H1+H2: **Project:** working matching-engine simulator, stress-tested, with a short write-up of its complexity guarantees and throughput numbers.
- Day 7: Review

### Week 50: Build systems & testing
- Day 1: H1: Compilers & flags (g++/clang, `-O2`). H2: Set up a proper multi-file project (headers + source files) compiled manually with the right flags, understanding each flag's purpose.
- Day 2: H1: CMake basics — "An Introduction to Modern CMake" (free). H2: Convert your Week 49 matching-engine project to a proper CMake build.
- Day 3: H1: Unit testing with Catch2 (free). H2: Migrate all your ad-hoc "print and check" tests from Weeks 47–49 into a proper Catch2 test suite.
- Day 4: H1: Debugging with `gdb` basics. H2: Deliberately introduce a bug into the matching engine and find it using `gdb` breakpoints/watchpoints, not print statements.
- Day 5: H1+H2: **Project:** one unified CMake project with Catch2 tests covering the pricer library, backtester, and matching engine.
- Day 6: Consolidate
- Day 7: Review

### Week 51: Capstone, part 1 — build & polish
- Day 1: H1+H2: Decide final capstone scope — a unified C++ project combining the pricer library, backtester, and matching-engine simulator into one coherent system (e.g., a simulated exchange that prices, matches, and reports).
- Days 2–5: H1+H2 each day: integrate the three components; one integration milestone per day; add documentation as you go, not at the end.
- Day 6: Finalize working version; run the full stress test from Week 49 against the integrated system.
- Day 7: Rest.

### Week 52: Capstone, part 2 — interview prep & wrap-up
- Day 1: H1: Get feedback on capstone (r/quant, r/cpp, relevant forums). H2: While waiting, write a proper README covering architecture, design decisions, and complexity/performance numbers.
- Day 2: H1: Incorporate feedback. H2: Add 3 more tests covering whatever the feedback exposed as a gap.
- Day 3: H1: Common C++ quant interview topics — memory management, OOP, STL, concurrency. H2: Do 5 timed practice explanations (30 seconds each, out loud) of concepts: RAII, move semantics, lock-free vs. mutex, virtual dispatch cost, cache locality.
- Day 4: H1: Practice explaining Python-vs-C++ tradeoffs and your Black-Litterman/HFT reasoning from Phase 2. H2: Practice explaining the full matching-engine design decision-by-decision as if in a system-design interview.
- Day 5: H1: Mock-interview yourself: walk through the full journey — probability → portfolio theory → derivatives → ML → risk → matching engine. H2: Do it again, but have someone else (friend, forum) ask you follow-up questions if at all possible.
- Day 6: Full review pass on whichever topic across all 12 months still feels shakiest — spend both hours there, no exceptions.
- Day 7: **Done.** You now have: a Python quant research capstone (signal → portfolio construction → backtest → risk report) and a C++ systems capstone (pricing library + backtester + matching engine, properly tested and benchmarked) — with the full quant finance stack, rigorously derived rather than just referenced, underneath both.

---

## PHASE 4 — Artificial Intelligence: From Scratch to Guru (Weeks 53–96, ~2.5 years at Sunday pace)

**Assumptions:** Your Python (Phase 1) is fluent, and applied ML basics — train/test splits, regression, trees, regularization, cross-validation, SHAP — are already covered (Phase 2, Weeks 31–32). This phase skips straight to deep learning and goes through to research-level depth. It stands somewhat independently of Phases 1–3 pacing-wise — treat it as its own ~2.5-year block once you finish (or in parallel with, if you prefer to interleave — your call, no deadline either way).

**New resource legend for this phase:**
- **Nielsen** = "Neural Networks and Deep Learning," free full online book, neuralnetworksanddeeplearning.com
- **3Blue1Brown NN series** = free YouTube playlist "Neural Networks"
- **Karpathy Zero-to-Hero** = Andrej Karpathy's free YouTube series "Neural Networks: Zero to Hero" — builds backprop and a GPT from scratch; the single best free resource for this phase
- **fast.ai** = free course "Practical Deep Learning for Coders," course.fast.ai
- **PyTorch docs/tutorials** = pytorch.org/tutorials (free, official)
- **CS231n** = Stanford's free CV course notes + YouTube lectures
- **CS224n** = Stanford's free NLP course notes + YouTube lectures
- **Illustrated Transformer** = free blog by Jay Alammar, jalammar.github.io
- **Attention Is All You Need** = free on arXiv
- **Hugging Face Course** = free, huggingface.co/course
- **Sutton & Barto** = "Reinforcement Learning: An Introduction," free official PDF, incompleteideas.net/book/the-book.html
- **OpenAI Spinning Up** = free deep RL course, spinningup.openai.com
- **Lilian Weng's blog** = lilianweng.github.io, free deep-dive posts (diffusion models, attention, etc.)
- **deeplearningbook.org** = Goodfellow/Bengio/Courville, free online
- **Made With ML** = madewithml.com, free MLOps course
- **MLflow / FastAPI / Docker docs** = official, free

### Block A: Deep Learning Foundations (Weeks 53–58)

**Week 53 (Neural network basics):**
- Day 1: H1: The single neuron, perceptron — 3Blue1Brown NN ep. 1. H2: Implement a single perceptron from scratch in numpy; train it on a linearly separable toy dataset.
- Day 2: H1: Forward propagation, activation functions — 3Blue1Brown ep. 2 / Nielsen Ch. 1. H2: Implement a 2-layer network's forward pass from scratch (no frameworks); compare sigmoid/ReLU/tanh outputs on the same inputs.
- Day 3: H1: Loss functions (MSE, cross-entropy) — Nielsen Ch. 1. H2: Derive cross-entropy loss's gradient with respect to the output layer by hand.
- Day 4: H1: Why depth helps — universal approximation intuition — 3Blue1Brown ep. 1. H2: Read Nielsen Ch. 4 (universal approximation) in full.
- Day 5: H1: Gradient descent — 3Blue1Brown ep. 2. H2: Implement gradient descent from scratch on a toy 2-parameter loss surface; visualize the descent path.
- Day 6: H1+H2: **Project:** a from-scratch 2-layer neural net (forward pass + manual gradient descent, no autograd yet) trained on a toy classification dataset.
- Day 7: Review

**Week 54 (Backpropagation from scratch):**
- Day 1: H1: Chain rule refresher for backprop — 3Blue1Brown "Backpropagation" ep. H2: Derive backprop for a single hidden layer by hand, step by step, before coding it.
- Day 2: H1: Backprop through multiple layers — Karpathy Zero-to-Hero "Building micrograd". H2: Follow along fully with Karpathy's micrograd build — implement your own tiny autograd engine.
- Day 3: H1: Backprop for common layer types (linear, ReLU). H2: Extend your micrograd engine with a few more operations (power, exp).
- Day 4: H1: Gradient checking — verifying backprop numerically. H2: Implement numerical gradient checking and use it to catch a deliberately introduced bug in your backprop code.
- Day 5: H1: Computational graphs — Karpathy's explanation. H2: Draw the computational graph for a 3-layer network by hand and trace both forward and backward passes on it.
- Day 6: H1+H2: **Project:** extend your Week 53 from-scratch net to use your own backprop engine instead of manually-derived gradients; verify it matches your Week 53 results.
- Day 7: Review — re-derive backprop for one hidden layer from memory.

**Week 55 (Optimization & loss functions):**
- Day 1: H1: SGD vs. batch gradient descent — Nielsen Ch. 1. H2: Implement mini-batch SGD from scratch; compare convergence speed/noise vs. full-batch.
- Day 2: H1: Momentum — intuition and math. H2: Implement momentum-based SGD from scratch; visualize how it smooths the descent path on a noisy loss surface.
- Day 3: H1: Adam optimizer — derivation/intuition. H2: Implement Adam from scratch (bias correction included); compare against SGD+momentum on the same toy problem.
- Day 4: H1: Learning rate schedules — step decay, cosine annealing. H2: Train the same model with 3 different LR schedules; compare convergence.
- Day 5: H1: Loss landscape intuition — why non-convexity isn't fatal in practice. H2: Visualize a 2D slice of a small network's loss landscape.
- Day 6: H1+H2: Practice — retrain your Week 54 project using Adam instead of manual SGD; document the improvement.
- Day 7: Review

**Week 56 (Regularization & initialization):**
- Day 1: H1: Overfitting in deep nets — why it's different from classical ML overfitting. H2: Deliberately overfit a small network on a tiny dataset; observe the train/val loss divergence.
- Day 2: H1: Dropout — Nielsen Ch. 3. H2: Implement dropout from scratch (not via a framework); verify it's disabled correctly at inference time.
- Day 3: H1: Batch normalization — intuition. H2: Read the original BatchNorm paper's abstract/intro; implement a simplified version from scratch.
- Day 4: H1: Weight decay / L2 regularization in neural nets. H2: Compare a network with and without weight decay on a small overfitting-prone dataset.
- Day 5: H1: Weight initialization (Xavier, He) — why it matters. H2: Train the same network with 3 different initializations; observe which ones fail to converge.
- Day 6: H1+H2: Practice — combine dropout + batchnorm + proper initialization into your ongoing project; measure the generalization improvement.
- Day 7: Review

**Week 57 (PyTorch fundamentals):**
- Day 1: H1: Tensors & basic ops — PyTorch official "60 Minute Blitz". H2: Rewrite your Week 53–56 from-scratch operations using PyTorch tensors; verify identical results.
- Day 2: H1: Autograd — PyTorch tutorials. H2: Compare PyTorch's autograd gradients against your hand-derived Week 54 gradients on the same small network — they must match.
- Day 3: H1: `nn.Module`, building models the PyTorch way. H2: Rebuild your from-scratch network as a proper `nn.Module` subclass.
- Day 4: H1: Optimizers & loss functions in PyTorch. H2: Swap in `torch.optim.Adam` and `nn.CrossEntropyLoss`; confirm training matches your from-scratch version.
- Day 5: H1: DataLoaders & Datasets. H2: Build a custom `Dataset` class for a real dataset (e.g., a CSV of financial features) and wrap it in a `DataLoader`.
- Day 6: H1+H2: **Project:** fully port your from-scratch project to idiomatic PyTorch, with proper `Dataset`/`DataLoader`/`nn.Module`/training loop structure.
- Day 7: Review

**Week 58 (Training pipelines & first real project):**
- Day 1: H1: Train/val/test splits for deep learning, early stopping. H2: Add early stopping (based on validation loss) to your PyTorch training loop.
- Day 2: H1: Debugging training — loss not decreasing, exploding gradients. H2: Deliberately induce 2 common training failures (too-high LR, no normalization) and diagnose them from the loss curves alone.
- Day 3: H1: Logging & visualization — TensorBoard basics. H2: Add TensorBoard logging to your training loop; visualize loss curves and a sample of predictions.
- Day 4: H1: GPU basics — moving tensors/models to GPU (if available) or understanding the workflow conceptually. H2: Benchmark CPU vs. GPU training time if you have access; otherwise read about typical speedups and why.
- Day 5: H1: MNIST — the classic first real dataset. H2: Full pipeline — download, preprocess, build a small CNN-free MLP classifier for MNIST.
- Day 6: H1+H2: **Project:** train an MLP on MNIST end-to-end (data loading → training with early stopping → evaluation → logged metrics), hitting a reasonable accuracy benchmark (>97%).
- Day 7: **Block A review** — explain backprop, Adam, and dropout from memory; re-derive one gradient by hand.

### Block B: Computer Vision (Weeks 59–63)

**Week 59 (Convolutions & CNN basics):**
- Day 1: H1: What a convolution actually does — 3Blue1Brown "Convolutions" or CS231n Lecture 5. H2: Implement 2D convolution from scratch in numpy (no frameworks); apply hand-crafted edge-detection kernels to a real image.
- Day 2: H1: Pooling layers — CS231n notes. H2: Implement max-pooling from scratch; verify against PyTorch's `MaxPool2d`.
- Day 3: H1: Building a CNN architecture — CS231n notes. H2: Design (on paper) a small CNN's layer-by-layer output shapes before coding it, then verify in PyTorch.
- Day 4: H1: Receptive fields — why depth matters for CNNs. H2: Compute the receptive field size of a 3-layer CNN by hand.
- Day 5: H1: Padding & stride — CS231n notes. H2: Implement convolution with variable stride/padding from scratch; verify output shapes match the standard formula.
- Day 6: H1+H2: **Project:** a from-scratch-designed (but PyTorch-implemented) small CNN trained on MNIST; compare accuracy/speed to Week 58's MLP.
- Day 7: Review

**Week 60 (CNN architectures):**
- Day 1: H1: LeNet & AlexNet — CS231n Lecture 9. H2: Read the AlexNet paper's abstract/architecture section; reproduce its architecture (scaled down) in PyTorch.
- Day 2: H1: VGG — deeper networks with small filters — CS231n. H2: Implement a small VGG-style block (stacked 3x3 convs) and compare parameter count to an equivalent single large-filter conv.
- Day 3: H1: ResNet & skip connections — CS231n. H2: Read the ResNet paper's core argument (degradation problem); implement a residual block from scratch and show it trains where a plain deep net struggles.
- Day 4: H1: Batch norm placement in CNNs, modern CNN design patterns. H2: Read a comparison article of CNN architectures over time (search "CNN architecture evolution blog").
- Day 5: H1: Parameter efficiency — why architecture choices matter for compute. H2: Compute FLOPs/parameter counts for 3 architectures you've built this week.
- Day 6: H1+H2: **Project:** implement a small ResNet-style network from scratch (a few residual blocks) trained on CIFAR-10.
- Day 7: Review

**Week 61 (Transfer learning & fine-tuning):**
- Day 1: H1: Why transfer learning works — CS231n Lecture 11. H2: Read about feature reuse across layers in pretrained CNNs.
- Day 2: H1: Using pretrained models in PyTorch (`torchvision.models`). H2: Load a pretrained ResNet, freeze all but the final layer, and fine-tune on a small custom dataset.
- Day 3: H1: Fine-tuning strategies — freeze vs. unfreeze, differential learning rates. H2: Compare frozen-feature-extraction vs. full fine-tuning on the same small dataset; measure accuracy and training time.
- Day 4: H1: Data augmentation for CV — flips, crops, color jitter. H2: Add an augmentation pipeline (`torchvision.transforms`) and measure its effect on validation accuracy.
- Day 5: H1: Overfitting signs specific to small datasets. H2: Deliberately train without augmentation on a small dataset and compare overfitting behavior to Day 4's results.
- Day 6: H1+H2: **Project:** fine-tune a pretrained model on a real small custom image dataset (e.g., a Kaggle dataset) end to end.
- Day 7: Review

**Week 62 (Training tricks & object detection overview):**
- Day 1: H1: Learning rate finders, warmup — fast.ai lesson on training tricks. H2: Implement an LR range test on one of your existing models.
- Day 2: H1: Mixed precision training (concept). H2: Read about FP16 training tradeoffs; if hardware allows, try enabling it and measure speedup.
- Day 3: H1: Object detection overview — CS231n Lecture 11 (detection section). H2: Read the YOLO paper's abstract/intro to understand the single-shot detection paradigm.
- Day 4: H1: Bounding boxes, IoU, non-max suppression — CS231n notes. H2: Implement IoU calculation and non-max suppression from scratch.
- Day 5: H1: Segmentation overview (semantic vs. instance) — CS231n Lecture 11. H2: Read about U-Net architecture's encoder-decoder design.
- Day 6: H1+H2: Consolidate — write a one-page summary of the CV landscape: classification → detection → segmentation, and where each is used.
- Day 7: Review

**Week 63 (CV capstone):**
- Day 1–5: H1+H2 each day: build a full image-classification project on a real dataset — proper train/val/test split, augmentation, transfer learning, hyperparameter tuning, and a written report of results.
- Day 6: Polish and document the project (README, architecture diagram, results table).
- Day 7: **Block B review**

### Block C: NLP & Sequence Models (Weeks 64–68)

**Week 64 (RNN basics):**
- Day 1: H1: Why sequences need different architectures — CS224n Lecture 5. H2: Implement a vanilla RNN cell from scratch in numpy.
- Day 2: H1: RNN forward pass over a sequence — CS224n notes. H2: Run your from-scratch RNN over a toy sequence-prediction task (e.g., predict next character in a short string).
- Day 3: H1: Backprop through time (BPTT) — CS224n Lecture 5. H2: Derive BPTT for a 3-step unrolled RNN by hand.
- Day 4: H1: Vanishing/exploding gradients in RNNs — CS224n notes. H2: Empirically demonstrate vanishing gradients by training your from-scratch RNN on a long-dependency toy task and watching it fail.
- Day 5: H1: Gradient clipping. H2: Add gradient clipping to your RNN training loop; show it fixes the exploding-gradient case.
- Day 6: H1+H2: **Project:** a from-scratch character-level RNN that generates short text sequences.
- Day 7: Review

**Week 65 (LSTMs/GRUs):**
- Day 1: H1: LSTM architecture — gates, cell state — CS224n Lecture 5 / Chris Olah's "Understanding LSTMs" blog (free). H2: Derive the LSTM gate equations and explain (in writing) why the cell-state highway solves vanishing gradients.
- Day 2: H1: Implementing LSTM from scratch. H2: Implement an LSTM cell from scratch in numpy (forward pass only is fine given the complexity); verify against PyTorch's `nn.LSTM` output on tiny inputs.
- Day 3: H1: GRUs — a simpler alternative. H2: Compare GRU vs. LSTM parameter counts and read arguments for when each is preferred.
- Day 4: H1: Using `nn.LSTM`/`nn.GRU` in PyTorch properly (batching, packing sequences). H2: Handle variable-length sequences properly with `pack_padded_sequence`.
- Day 5: H1: Sequence-to-sequence basics — encoder-decoder — CS224n Lecture 8. H2: Read the original seq2seq paper's abstract/architecture.
- Day 6: H1+H2: **Project:** rebuild Week 64's character-level generator using an LSTM in PyTorch; compare quality/coherence to the vanilla RNN.
- Day 7: Review

**Week 66 (Word embeddings):**
- Day 1: H1: word2vec — skip-gram and CBOW — CS224n Lecture 1–2. H2: Read the original word2vec paper's core method section.
- Day 2: H1: GloVe — CS224n notes. H2: Load pretrained GloVe embeddings and explore nearest-neighbor words for a few query words.
- Day 3: H1: Embedding arithmetic (king - man + woman ≈ queen) — CS224n. H2: Reproduce 3 classic embedding-arithmetic examples yourself and discuss when/why they fail.
- Day 4: H1: Using embeddings as input features for downstream tasks. H2: Build a simple sentiment classifier using averaged word embeddings as features + a small MLP.
- Day 5: H1: Subword tokenization preview (setting up for Week 72's BPE). H2: Read about why subword tokenization solves the out-of-vocabulary problem.
- Day 6: H1+H2: Practice — compare your Day 4 embedding-based classifier against a bag-of-words baseline on the same dataset.
- Day 7: Review

**Week 67 (Attention, pre-transformer):**
- Day 1: H1: The seq2seq bottleneck problem — CS224n Lecture 8. H2: Read Bahdanau et al.'s original attention paper's motivation section.
- Day 2: H1: Attention mechanism math — CS224n Lecture 8. H2: Derive the attention-weighted context vector computation by hand for a toy 3-token sequence.
- Day 3: H1: Implementing basic additive attention from scratch. H2: Implement it in numpy/PyTorch; verify attention weights sum to 1 and visualize them as a heatmap.
- Day 4: H1: Attention visualization — what the model "looks at". H2: Add attention on top of your Week 65 LSTM seq2seq setup and visualize weights on a real example.
- Day 5: H1: Self-attention preview — the key idea that leads to transformers. H2: Read the intro of "Attention Is All You Need" (full paper reading happens in Week 69) — just the motivation section for now.
- Day 6: H1+H2: Consolidate — write a one-page summary of the path RNN → LSTM → attention, and why each step was necessary.
- Day 7: Review

**Week 68 (NLP capstone):**
- Day 1–5: H1+H2 each day: build a full NLP project — either a sentiment classifier with proper embeddings/attention, or a text generator (character or word-level) with LSTM+attention — with proper evaluation.
- Day 6: Polish and document.
- Day 7: **Block C review** — you now have every prerequisite for transformers.

### Block D: Transformers & LLMs (Weeks 69–75)

**Week 69 (Transformer architecture):**
- Day 1: H1: Read "Attention Is All You Need" (arXiv, free) sections 1–3. H2: Re-read section 3 slowly; sketch the full encoder-decoder architecture diagram by hand from the paper's description, not by looking at the paper's own diagram.
- Day 2: H1: Illustrated Transformer blog — full walkthrough. H2: Annotate a copy of the paper's architecture diagram with what you now understand each component does.
- Day 3: H1: Multi-head attention — why multiple heads. H2: Derive the scaled dot-product attention formula by hand, including why the √d_k scaling matters.
- Day 4: H1: Positional encoding — why transformers need it (no recurrence). H2: Implement sinusoidal positional encoding from scratch; plot it to see the pattern.
- Day 5: H1: Layer norm, residual connections in transformer blocks. H2: Read about pre-norm vs. post-norm transformer variants and why modern models mostly use pre-norm.
- Day 6: H1+H2: Practice — implement a single multi-head self-attention layer from scratch in PyTorch (no `nn.MultiheadAttention`); verify output shapes.
- Day 7: Review — explain self-attention and positional encoding from memory.

**Week 70 (Self-attention implementation):**
- Day 1: H1: Karpathy Zero-to-Hero "Let's build GPT" part 1. H2: Follow along and type every line yourself — don't copy-paste from the video/repo.
- Day 2: H1: Continue "Let's build GPT". H2: Continue building; make sure you understand every tensor shape at every step.
- Day 3: H1: Causal masking for autoregressive generation. H2: Implement causal masking from scratch; verify a token can't attend to future tokens by testing directly.
- Day 4: H1: Stacking transformer blocks. H2: Extend your implementation to N stacked blocks; verify gradients flow through all of them.
- Day 5: H1: Continue "Let's build GPT" to completion. H2: Get your mini-GPT training on a small text corpus (Karpathy uses Shakespeare — any similar-sized free text corpus works).
- Day 6: H1+H2: **Project:** your own from-scratch mini-GPT training and generating (even if low quality) text.
- Day 7: Review

**Week 71 (Building it out further):**
- Day 1: H1: Tokenization deep-dive setup — why character-level isn't what production models use. H2: Read about the tradeoffs of char-level vs. word-level vs. subword tokenization.
- Day 2: H1: Byte-Pair Encoding (BPE) — Karpathy's "Let's build the GPT Tokenizer" video. H2: Implement BPE from scratch on a small corpus; train a small vocabulary and encode/decode text with it.
- Day 3: H1: Continue BPE video/implementation. H2: Swap your mini-GPT's character-level tokenizer for your own BPE tokenizer; retrain.
- Day 4: H1: Scaling considerations — why bigger models need more data (brief, conceptual). H2: Read a short accessible explainer on scaling laws (search "Chinchilla scaling laws blog explainer").
- Day 5: H1: Sampling strategies — greedy, top-k, top-p (nucleus) sampling. H2: Implement all three sampling strategies for your mini-GPT and compare generated text quality/diversity.
- Day 6: H1+H2: Consolidate your mini-GPT with BPE tokenization + proper sampling into one clean, documented project.
- Day 7: Review

**Week 72 (Pretrained models & Hugging Face):**
- Day 1: H1: BERT — architecture and pretraining objective (masked language modeling) — Illustrated BERT (Jay Alammar, free) or CS224n. H2: Read the BERT paper's abstract/method section.
- Day 2: H1: GPT-family — architecture and pretraining objective (next-token prediction). H2: Compare BERT (encoder-only) vs. GPT (decoder-only) vs. T5 (encoder-decoder) in a written summary.
- Day 3: H1: Hugging Face `transformers` library basics — HF Course Ch. 1–2. H2: Load a pretrained model and tokenizer; run inference on a real text classification task.
- Day 4: H1: HF `datasets` and `Trainer` API — HF Course Ch. 3. H2: Fine-tune a small pretrained model on a real classification dataset using the `Trainer` API.
- Day 5: H1: Evaluating classification models properly (beyond accuracy — F1, confusion matrix). H2: Compute and interpret a full evaluation report on your Day 4 fine-tuned model.
- Day 6: H1+H2: **Project:** fine-tune a pretrained transformer on a real dataset (e.g., financial news sentiment) end to end.
- Day 7: Review

**Week 73 (Fine-tuning at scale — LoRA/PEFT):**
- Day 1: H1: Why full fine-tuning gets expensive at scale — HF Course PEFT section. H2: Compute the parameter count of a mid-size pretrained model and estimate full fine-tuning memory cost.
- Day 2: H1: LoRA — Low-Rank Adaptation — read the original LoRA paper's core idea (arXiv, free). H2: Derive why constraining the weight update to a low-rank matrix reduces trainable parameters so drastically.
- Day 3: H1: Implementing/using LoRA via `peft` library. H2: Fine-tune a model with LoRA instead of full fine-tuning; compare trainable-parameter count and resulting performance to Week 72's Day 6 result.
- Day 4: H1: Quantization basics (concept) — why it enables running larger models. H2: Read a short explainer on 8-bit/4-bit quantization tradeoffs.
- Day 5: H1: Prompt engineering fundamentals — zero-shot, few-shot prompting. H2: Design and test 5 different prompts for the same task; compare output quality systematically, not just by eye.
- Day 6: H1+H2: Practice — compare full fine-tuning vs. LoRA vs. few-shot prompting on the same small task; write up tradeoffs (cost, performance, flexibility).
- Day 7: Review

**Week 74 (RAG & applied LLM systems):**
- Day 1: H1: Retrieval-Augmented Generation — motivation (hallucination, stale knowledge) — search "RAG explained" free blog posts. H2: Sketch a RAG pipeline diagram by hand (embed → retrieve → augment prompt → generate) before building it.
- Day 2: H1: Embeddings for retrieval — sentence embeddings (`sentence-transformers`, free library). H2: Embed a small document collection and implement cosine-similarity retrieval from scratch (no vector DB yet).
- Day 3: H1: Vector databases (concept) — free docs for an open-source option (e.g., Chroma, FAISS — both free). H2: Set up a local FAISS or Chroma index over your document collection; run retrieval queries.
- Day 4: H1: Building the full RAG pipeline — retrieval + prompt augmentation + generation. H2: Wire retrieval into your Week 72/73 fine-tuned or pretrained model's prompt.
- Day 5: H1: LLM evaluation challenges — why standard metrics fall short for generation. H2: Read about evaluation approaches (human eval, LLM-as-judge, task-specific metrics) and pick one to apply to your RAG outputs.
- Day 6: H1+H2: **Project:** a working RAG system over a small document collection (e.g., a set of financial reports or your own notes from this curriculum).
- Day 7: Review

**Week 75 (Block D capstone):**
- Day 1–5: H1+H2 each day: build a capstone LLM project — options include: a fine-tuned + RAG-augmented Q&A system, a from-scratch mini-GPT trained on a domain-specific corpus, or an agentic tool-use system. Pick one and go deep rather than shallow across several.
- Day 6: Polish, document, write a methodology report.
- Day 7: **Block D review** — explain self-attention, LoRA, and RAG from memory, unaided.

### Block E: Reinforcement Learning (Weeks 76–80)

**Week 76 (MDPs & Bellman equations):**
- Day 1: H1: Markov Decision Processes — states, actions, rewards, transitions — Sutton & Barto Ch. 3. H2: Formalize a simple toy environment (e.g., gridworld) as an MDP on paper.
- Day 2: H1: Policies and value functions — Sutton & Barto Ch. 3. H2: Compute state values by hand for a tiny 3-state MDP under a given policy.
- Day 3: H1: The Bellman equation — Sutton & Barto Ch. 3. H2: Derive the Bellman equation from the definition of value function, step by step.
- Day 4: H1: Bellman optimality equation. H2: Solve for the optimal policy of your Day 1 gridworld by hand via value iteration (a few iterations, small grid).
- Day 5: H1: Dynamic programming for RL — policy iteration, value iteration — Sutton & Barto Ch. 4. H2: Implement value iteration from scratch in Python for a small gridworld.
- Day 6: H1+H2: **Project:** a from-scratch value-iteration solver for a custom gridworld with obstacles/rewards.
- Day 7: Review

**Week 77 (Q-learning):**
- Day 1: H1: Model-free RL — why we can't always assume known dynamics — Sutton & Barto Ch. 6. H2: Explain in writing the difference between model-based (Week 76) and model-free RL.
- Day 2: H1: Temporal difference learning — Sutton & Barto Ch. 6. H2: Derive the TD(0) update rule from the Bellman equation.
- Day 3: H1: Q-learning algorithm — Sutton & Barto Ch. 6. H2: Implement tabular Q-learning from scratch on your Week 76 gridworld.
- Day 4: H1: Exploration vs. exploitation — epsilon-greedy — Sutton & Barto Ch. 2. H2: Compare 3 different epsilon-decay schedules on your Q-learning agent's convergence speed.
- Day 5: H1: SARSA — on-policy vs. off-policy learning. H2: Implement SARSA and compare its learned policy to Q-learning's on the same gridworld.
- Day 6: H1+H2: Practice — extend your gridworld to be stochastic (actions sometimes fail) and confirm Q-learning still converges.
- Day 7: Review — derive the Q-learning update rule from memory.

**Week 78 (Deep Q-Networks):**
- Day 1: H1: Why tabular methods fail at scale — need for function approximation — Sutton & Barto Ch. 9. H2: Compute the state-space size of a slightly larger problem to make the scaling issue concrete.
- Day 2: H1: DQN architecture — replacing the Q-table with a neural net — read the original DQN paper's abstract/method (arXiv, free). H2: Sketch the DQN architecture (state → network → Q-values per action) for a simple environment.
- Day 3: H1: Experience replay — why it stabilizes training. H2: Implement a replay buffer from scratch (fixed-size, random sampling).
- Day 4: H1: Target networks — why a second, slowly-updated network helps. H2: Read the DQN paper's ablation on target networks; implement target-network updates.
- Day 5: H1: Putting DQN together — OpenAI Spinning Up's DQN explanation. H2: Implement a full DQN agent (network + replay buffer + target network) for a simple environment (e.g., CartPole via a free Gym-compatible library).
- Day 6: H1+H2: **Project:** train your DQN agent to solve CartPole (or an equivalent free simple control environment) to a defined performance threshold.
- Day 7: Review

**Week 79 (Policy gradients):**
- Day 1: H1: Policy-based vs. value-based RL — Sutton & Barto Ch. 13. H2: Explain in writing why directly parameterizing the policy can help with continuous action spaces.
- Day 2: H1: The policy gradient theorem — Sutton & Barto Ch. 13 / OpenAI Spinning Up. H2: Work through the policy gradient theorem's derivation at the level of detail Spinning Up provides.
- Day 3: H1: REINFORCE algorithm. H2: Implement REINFORCE from scratch for a simple environment.
- Day 4: H1: Variance reduction — baselines. H2: Add a value-function baseline to your REINFORCE implementation; compare training stability with/without it.
- Day 5: H1: PPO — intuition (clipped objective) — OpenAI Spinning Up "PPO". H2: Read the PPO paper's core clipping idea; explain in writing why it prevents destructively large policy updates.
- Day 6: H1+H2: Practice — use an existing well-tested PPO implementation (e.g., via `stable-baselines3`, free) on your environment and compare results to your from-scratch REINFORCE.
- Day 7: Review

**Week 80 (RL capstone):**
- Day 1–5: H1+H2 each day: build an RL capstone — e.g., a DQN or PPO agent for a slightly harder environment, or (tying back to quant finance) a simplified RL-based portfolio-rebalancing or trading agent on synthetic/historical price data, being honest about how toy the setup necessarily is.
- Day 6: Polish and document, including an honest discussion of RL's real limitations for live trading (non-stationarity, sim-to-real gap).
- Day 7: **Block E review**

### Block F: Generative Models (Weeks 81–84)

**Week 81 (Autoencoders):**
- Day 1: H1: Autoencoder architecture — encoder/decoder, bottleneck — search "autoencoders explained" (many free blog explainers) or fast.ai. H2: Implement a simple autoencoder from scratch in PyTorch for MNIST reconstruction.
- Day 2: H1: What the bottleneck actually learns — dimensionality reduction intuition. H2: Visualize the 2D latent space of an autoencoder trained with a 2-unit bottleneck; compare to PCA on the same data.
- Day 3: H1: Denoising autoencoders. H2: Train a denoising autoencoder (add noise to inputs, reconstruct clean images); compare robustness to a vanilla autoencoder.
- Day 4: H1: Autoencoders for anomaly detection (conceptual link to quant risk work). H2: Use reconstruction error from your autoencoder to flag anomalous samples in a toy dataset.
- Day 5: H1: Limitations of vanilla autoencoders as generative models. H2: Try sampling random points in the latent space and decoding them; observe why the results are often poor (motivates VAEs).
- Day 6: H1+H2: Consolidate — write a one-page summary of what autoencoders are good/bad for.
- Day 7: Review

**Week 82 (VAEs):**
- Day 1: H1: The VAE idea — probabilistic latent space — Lilian Weng's VAE blog post (free). H2: Read the full post carefully; note where it departs from a vanilla autoencoder.
- Day 2: H1: The reparameterization trick. H2: Derive why direct sampling breaks backprop and how the reparameterization trick fixes it.
- Day 3: H1: The VAE loss (reconstruction + KL divergence). H2: Derive the ELBO (evidence lower bound) at an intuitive level; implement the VAE loss from scratch.
- Day 4: H1: Implementing a VAE in PyTorch. H2: Build and train a VAE on MNIST.
- Day 5: H1: Sampling from a trained VAE. H2: Sample random latent vectors and decode them; compare generation quality to Week 81's vanilla autoencoder.
- Day 6: H1+H2: **Project:** a working VAE with latent-space interpolation (morph one digit into another by interpolating in latent space).
- Day 7: Review

**Week 83 (GANs):**
- Day 1: H1: GAN architecture — generator vs. discriminator, adversarial training — search "GANs explained" free resources. H2: Read the original GAN paper's abstract/intro (arXiv, free).
- Day 2: H1: The minimax objective. H2: Derive why the generator's and discriminator's objectives are opposed; explain the equilibrium intuition.
- Day 3: H1: GAN training instability — mode collapse, vanishing gradients. H2: Read about common GAN training pathologies and mitigation tricks (label smoothing, etc.).
- Day 4: H1: Implementing a simple GAN in PyTorch. H2: Build and train a simple GAN on MNIST.
- Day 5: H1: DCGAN — convolutional GANs for images. H2: Read the DCGAN paper's architecture guidelines; adapt your Day 4 GAN to use convolutional layers.
- Day 6: H1+H2: **Project:** a working (simple) image-generating GAN; document training instability you observed and how you addressed it.
- Day 7: Review

**Week 84 (Diffusion models & Block F capstone):**
- Day 1: H1: Diffusion models — the forward/reverse noising process — Lilian Weng's diffusion models blog post (free, thorough). H2: Read the post in full; sketch the forward and reverse processes by hand.
- Day 2: H1: Why diffusion models train more stably than GANs (conceptual). H2: Read a comparison article contrasting GAN vs. diffusion training dynamics.
- Day 3: H1: The denoising objective. H2: Work through the simplified training objective (predict the noise) at the level Lilian Weng's post presents it.
- Day 4: H1: A minimal diffusion model implementation (small-scale, e.g., on MNIST) — search for a free minimal diffusion tutorial/notebook. H2: Implement or closely follow a minimal diffusion model training on MNIST.
- Day 5: H1: Sampling from a diffusion model (the reverse process at inference). H2: Generate samples from your trained model; observe generation quality vs. training compute spent.
- Day 6: H1+H2: **Block F capstone:** consolidate autoencoders/VAEs/GANs/diffusion into one written comparison document (architecture, training stability, sample quality, use cases) plus your best generative model artifact.
- Day 7: **Block F review**

### Block G: MLOps & Production ML (Weeks 85–88)

**Week 85 (Experiment tracking & reproducibility):**
- Day 1: H1: Why reproducibility breaks in ML projects — Made With ML "Experiment Tracking". H2: Audit one of your earlier projects (e.g., Week 63's CV capstone) for reproducibility gaps (seeds, versioning, config management).
- Day 2: H1: MLflow basics — MLflow docs. H2: Instrument one of your existing training scripts with MLflow tracking (params, metrics, artifacts).
- Day 3: H1: Config management — avoiding hardcoded hyperparameters. H2: Refactor a training script to use a proper config file (YAML/JSON) instead of hardcoded values.
- Day 4: H1: Data versioning (concept) — why it matters alongside code versioning. H2: Read about DVC (Data Version Control, free) at a conceptual level.
- Day 5: H1: Random seeds & determinism in ML. H2: Audit your training pipeline for every source of randomness; set seeds everywhere and verify runs are reproducible.
- Day 6: H1+H2: Practice — fully instrument one project (from any earlier block) with MLflow tracking + proper config + reproducibility guarantees.
- Day 7: Review

**Week 86 (Model serving & containerization):**
- Day 1: H1: Serving models — batch vs. real-time inference — Made With ML "Serving". H2: Read the tradeoffs section in full; identify which your quant Phase 2 capstone would need.
- Day 2: H1: FastAPI basics — FastAPI official docs (free, excellent). H2: Build a minimal FastAPI app with one endpoint.
- Day 3: H1: Serving a model via FastAPI. H2: Wrap one of your trained models (e.g., Week 68's sentiment classifier) in a FastAPI endpoint that accepts input and returns a prediction.
- Day 4: H1: Docker basics — Docker official "Get Started" (free). H2: Containerize your FastAPI model-serving app; run it locally via Docker.
- Day 5: H1: Handling model loading, batching requests for efficiency. H2: Add basic request batching or async handling to your serving endpoint.
- Day 6: H1+H2: **Project:** a containerized FastAPI model-serving app for one of your trained models, with a simple test client demonstrating it works end to end.
- Day 7: Review

**Week 87 (Monitoring & CI/CD):**
- Day 1: H1: Model monitoring — what to track in production (latency, prediction distribution) — Made With ML "Monitoring". H2: Design a monitoring dashboard's metric list for your Week 86 serving app (on paper).
- Day 2: H1: Data drift & model drift — concept. H2: Read about statistical tests for detecting drift (e.g., population stability index, KS test); implement a simple drift check comparing two data batches.
- Day 3: H1: CI/CD concepts for ML — Made With ML "CI/CD". H2: Read about GitHub Actions (free for public repos) at a conceptual level for ML pipelines.
- Day 4: H1: Setting up a basic GitHub Actions workflow. H2: Add a CI workflow to one of your repos that runs your test suite automatically on push.
- Day 5: H1: Model retraining triggers — when and why to retrain. H2: Sketch (on paper) a retraining pipeline trigger policy for a hypothetical production model.
- Day 6: H1+H2: Consolidate — add basic drift-checking logic and a CI pipeline to your Week 86 serving project.
- Day 7: Review

**Week 88 (MLOps capstone):**
- Day 1–5: H1+H2 each day: build a full MLOps capstone — train a model with tracked experiments (MLflow) → serve it (FastAPI + Docker) → add monitoring/drift checks → add CI. Use a model from any earlier block (CV, NLP, or a quant-finance model from Phase 2).
- Day 6: Polish, document architecture.
- Day 7: **Block G review**

### Block H: Guru-Level Depth & Final Capstone (Weeks 89–96)

**Week 89 (Reading research papers effectively):**
- Day 1: H1: How to read a paper — Andrew Ng's "How to Read a Paper" guidance (free, widely available) — the three-pass method. H2: Apply the three-pass method to a paper you've already partially read this phase (e.g., the original Transformer paper) — do a full, careful third pass this time.
- Day 2: H1: Reading math-heavy sections without getting stuck. H2: Pick one equation from that paper you didn't fully understand before and derive it from scratch now.
- Day 3: H1: Finding good papers — arXiv, Papers With Code (free), following citation trails. H2: Build a reading list of 5 papers relevant to your interests (quant + AI intersection is a good anchor) using these tools.
- Day 4: H1: Reading a second paper fully (choose from your list). H2: Write a structured summary (problem, method, result, limitation) of it.
- Day 5: H1: Critically evaluating claims — what would make you skeptical of a result. H2: Identify 2 potential weaknesses/limitations in the paper you just read that the authors don't fully address.
- Day 6: H1+H2: Practice — read and summarize a third paper end to end, unaided by summaries/blog posts this time.
- Day 7: Review

**Week 90 (Reproduce a paper's core result):**
- Day 1: H1: Choosing a reproducible target — pick a foundational, implementable result (e.g., a specific ablation from a paper you've read, or a smaller architecture from this curriculum). H2: Scope exactly what "reproducing" means for your chosen target (what metric, what dataset, what compute budget).
- Days 2–5: H1+H2 each day: implement and run the reproduction.
- Day 6: Compare your results to the paper's reported numbers; write an honest discussion of any gap and likely causes (compute, data, hyperparameters).
- Day 7: Review

**Week 91 (Distributed training basics):**
- Day 1: H1: Why distributed training exists — models/data too large for one device (concept). H2: Read a practitioner explainer on data parallelism vs. model parallelism.
- Day 2: H1: Data parallelism — splitting batches across devices. H2: Read PyTorch's `DistributedDataParallel` docs; understand the gradient-averaging mechanism even if you can't run it multi-GPU yourself.
- Day 3: H1: Model parallelism — splitting the model itself. H2: Read about pipeline parallelism and tensor parallelism at a conceptual level (relevant to how large LLMs are actually trained).
- Day 4: H1: Gradient accumulation — simulating larger batches on limited hardware. H2: Implement gradient accumulation in one of your existing training loops; verify it's mathematically equivalent to a larger batch.
- Day 5: H1: Mixed precision & memory optimization tricks (checkpointing, etc.) — conceptual. H2: Read about gradient checkpointing's memory/compute tradeoff.
- Day 6: H1+H2: Consolidate — write a one-page explainer (in your own words) of how a large model is actually trained across many GPUs, as if explaining it to a peer.
- Day 7: Review

**Week 92 (Advanced optimization theory):**
- Day 1: H1: Second-order methods (Newton's method for optimization) — brief, conceptual. H2: Compare Newton's method vs. gradient descent convergence on a small convex problem (you have the C++ Newton's method implementation from Phase 3, Week 46 — reuse/adapt it).
- Day 2: H1: Why second-order methods aren't used directly for deep nets (Hessian cost). H2: Estimate the memory cost of storing a full Hessian for a network with 1M parameters; contrast with Adam's memory cost.
- Day 3: H1: Adaptive methods revisited — AdamW, why weight decay coupling matters. H2: Read the AdamW paper's core argument; compare Adam vs. AdamW on one of your existing training setups.
- Day 4: H1: Learning rate warmup + cosine schedules in modern training recipes. H2: Implement a warmup+cosine schedule from scratch and apply it to a training run.
- Day 5: H1: Loss landscape visualization techniques (filter normalization, concept). H2: Read about why naive 2D loss-landscape plots can be misleading, and what filter-normalization fixes.
- Day 6: H1+H2: Practice — write up a comparison of every optimizer/schedule you've used across this entire AI phase, with your own recommendations for when to use each.
- Day 7: Review

**Week 93 (Contributing to open source):**
- Day 1: H1: Finding a good first issue — search GitHub "good first issue" label on an ML library you use (PyTorch, Hugging Face, a smaller tool). H2: Read that project's contribution guidelines fully.
- Day 2: H1: Understanding a real codebase — navigating a large unfamiliar repo. H2: Trace through the code path for one feature you've used (e.g., how `nn.Linear`'s forward pass is actually implemented) in the source.
- Day 3: H1: Writing your first contribution (docs fix, small bug fix, or test addition — start small deliberately). H2: Write it, including tests.
- Day 4: H1: The PR review process — what maintainers look for. H2: Open the PR; while waiting for feedback, look for a second small issue to tackle.
- Day 5: H1: Responding to review feedback professionally. H2: Address feedback if it's arrived, or start the second contribution.
- Day 6: H1+H2: Consolidate — whatever state your contribution(s) are in, document what you learned about production ML codebases from this process.
- Day 7: Review

**Week 94 (Capstone design — quant + AI):**
- Day 1: H1+H2: Design the final capstone — combine your quant finance stack (Phase 2) with your AI stack (this phase). Options: an LLM-augmented research assistant that reads financial filings and generates factor hypotheses (RAG-based), a deep-learning volatility forecasting model compared against your GARCH baseline (Phase 2, Week 18), or a transformer-based time-series model for the return-prediction task from Phase 2 Week 31–32.
- Day 2: H1: Scope precisely what "done" looks like — specific metrics, specific comparison baselines (your existing Phase 2 models). H2: Write the full project spec.
- Day 3: H1: Data pipeline setup. H2: Build/adapt the data pipeline, reusing Phase 2 infrastructure where possible.
- Day 4: H1: Baseline model setup (your existing Phase 2 model as the baseline to beat). H2: Confirm the baseline's performance is correctly reproduced before building the new model.
- Day 5: H1: Model architecture design for the new (AI-based) approach. H2: Justify in writing why this architecture suits the problem, referencing specific concepts from Blocks A–D.
- Day 6: H1+H2: Begin implementation.
- Day 7: Review

**Week 95 (Capstone build):**
- Days 1–5: H1+H2 each day: full implementation — training, tuning, evaluation against the baseline, with proper walk-forward validation (Phase 2 discipline applied here too — don't let the AI model cheat with lookahead any more than the quant models were allowed to).
- Day 6: Finalize; produce a clean comparison table (your AI model vs. your Phase 2 baseline) on the same held-out data.
- Day 7: Rest.

**Week 96 (Capstone polish, interview prep, full wrap-up):**
- Day 1: H1: Polish code and write a full methodology report (problem, baseline, approach, results, honest limitations). H2: Get feedback (r/MachineLearning, r/quant, relevant Discord/forums — free).
- Day 2: H1: Incorporate feedback. H2: Add any missing tests/documentation the feedback surfaced.
- Day 3: H1: AI/ML interview topics — backprop, attention, bias-variance, common architecture questions. H2: Practice deriving 3 things from memory, timed: backprop for one layer, self-attention's formula, the VAE loss.
- Day 4: H1: Practice explaining your quant+AI capstone aloud, focusing on *why* each design choice was made. H2: Do it again with a focus on the honest limitations and what you'd do with more compute/data.
- Day 5: H1: Full review pass — whichever Block (A–H) still feels shakiest. H2: Redo that block's hardest exercise from scratch, unaided.
- Day 6: Final consolidation — update your running Python/C++ repos with this phase's work; make sure everything is documented as a coherent portfolio.
- Day 7: **Done.** You now hold: the full quant finance stack (Phase 2), a systems-level C++ practitioner's toolkit (Phase 3), and depth across deep learning, CV, NLP, transformers/LLMs, RL, generative models, and MLOps (Phase 4) — capped off by a capstone that puts the AI and quant stacks in direct, honest comparison with each other. That combination — quant finance + systems programming + modern AI, each with genuine from-scratch understanding rather than surface familiarity — is a genuinely rare profile.

---

## PHASE 4 — Artificial Intelligence: From Scratch to Guru (Weeks 53–95)

**New resources introduced in this phase (all free):**
- **3Blue1Brown "Neural Networks"** — YouTube series, the best free visual intuition for backprop
- **Andrej Karpathy "Neural Networks: Zero to Hero"** — free YouTube series; builds autograd, an MLP, and a GPT from scratch, line by line
- **CS231n** (Stanford, Convolutional Neural Networks) and **CS224n** (Stanford, NLP with Deep Learning) — free lecture notes/videos
- **PyTorch official docs/tutorials** — pytorch.org/tutorials, free
- **fast.ai** — free practical deep learning course
- **Chris Olah's blog** (colah.github.io) — free, canonical LSTM explainer
- **Jay Alammar's blog** (jalammar.github.io) — free, "The Illustrated Transformer"
- **Hugging Face course** — huggingface.co/course, free
- **Lilian Weng's blog** (lilianweng.github.io) — free, excellent diffusion-model explainer
- **arXiv.org** — free access to all papers referenced (Attention Is All You Need, DQN, PPO, GAN, DDPM, CLIP, LoRA, InstructGPT, etc.)
- **Sutton & Barto, "Reinforcement Learning: An Introduction"** — official free PDF, incompleteideas.net/book/the-book.html
- **David Silver's RL Course** (UCL/DeepMind) — free YouTube
- **OpenAI Gymnasium** — free RL environments, gymnasium.farama.org
- **stable-baselines3** — free/open-source RL library
- **FastAPI, Docker, MLflow, DVC** — official free docs
- **Papers With Code** — paperswithcode.com, free SOTA tracking

### Module A: Deep Learning Foundations + CNNs/Vision (Weeks 53–58)

**Week 53 (Neural network foundations — the math):**
- Day 1: H1: What is a perceptron — 3Blue1Brown "But what is a neural network?" H2: Implement a perceptron from scratch in numpy; train it on a linearly separable toy dataset.
- Day 2: H1: Gradient descent — 3Blue1Brown "Gradient descent, how neural networks learn." H2: Derive the gradient-descent update rule by hand for a 1-parameter loss; implement from scratch.
- Day 3: H1: Backprop intuition — 3Blue1Brown "What is backpropagation really doing?" H2: Full derivation — 3Blue1Brown "Backpropagation calculus"; derive the chain rule for a 2-layer network by hand.
- Day 4: H1: Karpathy "Zero to Hero" Ep. 1 — micrograd (autograd from scratch). H2: Follow along fully, building your own autograd engine.
- Day 5: H1: Loss functions (MSE, cross-entropy) — derive gradients for each. H2: Implement both from scratch; verify gradients via numerical gradient checking.
- Day 6: H1+H2: **Project:** full MLP from scratch (numpy + your Day 4 autograd engine), trained on MNIST.
- Day 7: Review — re-derive backprop for a 2-layer network from memory.

**Week 54 (Optimization & regularization):**
- Day 1: H1: SGD, momentum — Sebastian Ruder's free blog "An overview of gradient descent optimization algorithms." H2: Implement SGD with momentum from scratch; compare convergence to vanilla SGD.
- Day 2: H1: Adam optimizer — Ruder's blog / original Adam paper (arXiv). H2: Derive Adam's bias-correction terms; implement from scratch.
- Day 3: H1: Overfitting & regularization — StatQuest "Dropout." H2: Add L2 + dropout to your Week 53 MLP; compare train/val curves.
- Day 4: H1: Batch normalization — original BatchNorm paper (arXiv). H2: Implement batchnorm from scratch; add it to your MLP.
- Day 5: H1: Weight initialization (Xavier/He) — key results from the original papers. H2: Compare training stability across random/Xavier/He init on a deeper MLP.
- Day 6: H1+H2: **Project:** retrain your MNIST MLP with Adam + dropout + batchnorm + good init; compare accuracy to Week 53's naive version.
- Day 7: Review

**Week 55 (PyTorch fundamentals):**
- Day 1: H1: Tensors & autograd — PyTorch "60 Minute Blitz." H2: Full tutorial; reimplement Week 53's MLP using PyTorch's autograd.
- Day 2: H1: `nn.Module` — PyTorch docs. H2: Refactor into a proper `nn.Module` class.
- Day 3: H1: Datasets & DataLoaders — PyTorch docs. H2: Build a custom `Dataset` for a CSV dataset (e.g., your Phase 2 stock data).
- Day 4: H1: Training loops, device handling — PyTorch docs. H2: Write a reusable training-loop function (train/val split, early stopping) for reuse across this phase.
- Day 5: H1: Checkpointing — PyTorch docs. H2: Add checkpointing; simulate a crash and resume.
- Day 6: H1+H2: **Project:** full PyTorch MNIST pipeline (Dataset, DataLoader, Module, training loop, checkpointing) as a reusable template.
- Day 7: Review

**Week 56 (Convolutional building blocks):**
- Day 1: H1: What convolution does — CS231n notes. H2: Implement 2D convolution from scratch in numpy; verify against `torch`'s output.
- Day 2: H1: Pooling — CS231n notes. H2: Implement max-pooling from scratch.
- Day 3: H1: CNN backprop — CS231n backprop notes. H2: Work through the conv-layer gradient case in full.
- Day 4: H1: Padding, strides, receptive fields — CS231n notes. H2: Compute output dims and receptive field by hand for a 3-layer toy CNN.
- Day 5: H1: Feature-map visualization — fast.ai lesson. H2: Visualize learned filters/feature maps of a small trained CNN.
- Day 6: H1+H2: **Project:** small CNN (2–3 conv layers) in PyTorch, trained on CIFAR-10.
- Day 7: Review

**Week 57 (Classic CNN architectures):**
- Day 1: H1: LeNet/AlexNet history — CS231n "CNN Architectures." H2: Implement LeNet-5 from scratch; train on MNIST.
- Day 2: H1: VGG design — CS231n notes. H2: Implement a small VGG-style network; compare params/performance to LeNet.
- Day 3: H1: ResNet & skip connections — CS231n notes + original ResNet paper (arXiv). H2: Implement a ResNet block from scratch; explain why skip connections help gradient flow.
- Day 4: H1: Learning-rate schedules — PyTorch `lr_scheduler` docs. H2: Add cosine/step decay to your training loop.
- Day 5: H1: Transfer learning — PyTorch "Transfer Learning Tutorial." H2: Full tutorial; fine-tune a pretrained ResNet on a small custom dataset.
- Day 6: H1+H2: **Project:** transfer-learning image classifier with data augmentation on a dataset of your choice.
- Day 7: Review

**Week 58 (Augmentation, evaluation, Module A/B wrap):**
- Day 1: H1: Data augmentation — `torchvision.transforms` docs. H2: Apply 5 augmentations; visualize effects.
- Day 2: H1: Precision/recall/F1/confusion matrix — StatQuest. H2: Compute full confusion matrix + per-class metrics for Week 57's classifier.
- Day 3: H1: Class imbalance handling — fast.ai notes. H2: Simulate imbalance; apply weighted loss/oversampling; compare.
- Day 4: H1: Object detection overview (concept) — CS231n "Detection and Segmentation." H2: Read YOLO's core idea at a conceptual level.
- Day 5: H1: Grad-CAM interpretability — original paper's core idea (arXiv). H2: Implement Grad-CAM on your Week 57 classifier.
- Day 6: H1+H2: Consolidate — one-page summary: perceptron → backprop → CNNs → transfer learning → interpretability.
- Day 7: **Module A/B review** — re-derive backprop, explain skip connections and Grad-CAM unaided.

### Module C: Sequence Models, NLP, and Transformers (Weeks 59–64)

**Week 59 (RNNs):**
- Day 1: H1: Why sequences need different architectures — Karpathy's "The Unreasonable Effectiveness of RNNs" (free blog). H2: Implement a vanilla RNN cell from scratch; run on a toy sequence task.
- Day 2: H1: Backprop through time — CS224n notes. H2: Derive BPTT gradients by hand for a 2-timestep RNN.
- Day 3: H1: Vanishing/exploding gradients — CS224n notes. H2: Demonstrate vanishing gradients empirically on a long-sequence toy task.
- Day 4: H1: LSTM architecture — Chris Olah's "Understanding LSTM Networks." H2: Implement an LSTM cell from scratch (all gates).
- Day 5: H1: GRU architecture — Olah's blog/CS224n. H2: Implement a GRU cell from scratch; compare parameter count to LSTM.
- Day 6: H1+H2: **Project:** train an LSTM (`nn.LSTM`) on character-level text generation; generate sample text.
- Day 7: Review

**Week 60 (Word embeddings & attention):**
- Day 1: H1: Word2Vec — CS224n notes. H2: Read the original paper's core idea; train a small word2vec model with `gensim` on a toy corpus.
- Day 2: H1: GloVe — CS224n notes. H2: Load pretrained GloVe vectors; explore analogy tasks yourself.
- Day 3: H1: Attention (Bahdanau) — CS224n notes. H2: Derive the attention-weighted context vector by hand for a toy example.
- Day 4: H1: Self-attention — Jay Alammar's "The Illustrated Transformer." H2: Work the full walkthrough, computing Q/K/V manually for a tiny example.
- Day 5: H1: Multi-head attention — Alammar's post continued. H2: Implement scaled dot-product attention from scratch (matrix ops only).
- Day 6: H1+H2: **Project:** implement multi-head self-attention from scratch; verify it matches `nn.MultiheadAttention`'s output.
- Day 7: Review — explain why attention solves RNNs' long-range dependency problem, unaided.

**Week 61 (The Transformer architecture):**
- Day 1: H1: Read "Attention Is All You Need" (arXiv) directly. H2: Annotate the architecture diagram by hand, labeling every component.
- Day 2: H1: Positional encoding — Illustrated Transformer. H2: Implement sinusoidal positional encoding from scratch; visualize it.
- Day 3: H1: Layer norm & residuals in transformers — paper + Illustrated Transformer. H2: Implement a full transformer encoder block from scratch.
- Day 4: H1: Masked self-attention — Illustrated Transformer. H2: Implement causal (masked) self-attention for autoregressive generation.
- Day 5: H1: Karpathy's "Let's build GPT" — first half. H2: Code along, typing every line yourself.
- Day 6: H1+H2: Finish Karpathy's GPT video; train your own mini-GPT on a small text corpus.
- Day 7: Review — re-derive the transformer block's data flow from memory.

**Week 62 (Training & scaling transformers):**
- Day 1: H1: Tokenization (BPE) — Karpathy's "Let's build the GPT Tokenizer." H2: Implement a BPE tokenizer from scratch.
- Day 2: H1: LR warmup & why it matters — practitioner blog posts. H2: Add warmup + decay schedule to your mini-GPT's training loop.
- Day 3: H1: Scaling laws (Kaplan/Chinchilla) — read the papers' abstracts/key figures (arXiv). H2: Summarize compute/data/parameter tradeoffs in your own words.
- Day 4: H1: Perplexity — CS224n notes. H2: Compute perplexity for your mini-GPT on held-out text.
- Day 5: H1: Hugging Face `transformers` intro — HF course Ch. 1. H2: Load and run inference with a pretrained model (e.g., GPT-2).
- Day 6: H1+H2: **Project:** train your mini-GPT on a larger corpus; compare its completions to GPT-2's on the same prompt.
- Day 7: Review

**Week 63 (Fine-tuning & NLP applications):**
- Day 1: H1: Fine-tuning pretrained transformers — HF course Ch. 3. H2: Fine-tune DistilBERT for text classification using HF `Trainer`.
- Day 2: H1: Sentiment analysis — HF course. H2: Fine-tune on a financial-news sentiment dataset (free, Kaggle/HF Hub) — a direct bridge to your quant work.
- Day 3: H1: NER & sequence labeling — HF course Ch. 7. H2: Fine-tune a token-classification model.
- Day 4: H1: Question answering — HF course Ch. 7. H2: Fine-tune/evaluate a QA model on SQuAD (free dataset).
- Day 5: H1: LoRA — read the paper's core idea (arXiv) + HF PEFT docs. H2: Fine-tune via LoRA instead of full fine-tuning; compare trainable-param count and time.
- Day 6: H1+H2: **Project:** LoRA fine-tune on financial-news headlines for sentiment/direction — a signal feedable into your Phase 2 backtester.
- Day 7: Review

**Week 64 (NLP wrap & Module C review):**
- Day 1: H1: Retrieval-Augmented Generation (RAG) — free practitioner explainers. H2: Build a minimal RAG pipeline: embed documents, retrieve via cosine similarity, feed into a prompt.
- Day 2: H1: Vector search — FAISS docs (free, Meta). H2: Index your documents in FAISS; benchmark vs. brute-force search.
- Day 3: H1: Prompt engineering — promptingguide.ai (free). H2: Test zero-shot/few-shot/chain-of-thought on the same task; compare outputs.
- Day 4: H1: LLM limitations (hallucination, context limits) — practitioner/research summaries. H2: Design a test set probing your RAG pipeline for hallucination; document failures.
- Day 5: H1: Problem-set day — hardest exercises from Weeks 59–63. H2: Redo multi-head attention from scratch, from memory.
- Day 6: Consolidate — one-page summary: RNN → LSTM → attention → transformer → fine-tuning → RAG.
- Day 7: **Module C review**

### Module D: LLMs & Generative AI (Weeks 65–70)

**Week 65 (LLM architecture deep dive):**
- Day 1: H1: GPT-1 → GPT-2 → GPT-3 evolution — read the papers' abstracts/key results (arXiv). H2: Build a comparison table of architecture/scale differences yourself.
- Day 2: H1: In-context learning — GPT-3 paper's findings. H2: Test in-context learning on a free-tier/local model; vary example count.
- Day 3: H1: Instruction tuning & RLHF — InstructGPT paper's core idea (arXiv). H2: Diagram the 3-stage RLHF pipeline (SFT → reward model → PPO) yourself.
- Day 4: H1: Reward modeling — InstructGPT paper section. H2: Write out the reward-model loss function from the paper.
- Day 5: H1: Alignment & safety (conceptual) — a lab's public research blog (free). H2: One-page reflection on why alignment is hard, with concrete examples.
- Day 6: H1+H2: Read one recent (last 12 months) LLM paper of your choosing; write a structured summary (problem/method/results/limitations).
- Day 7: Review

**Week 66 (Diffusion models):**
- Day 1: H1: Generative models landscape — Lilian Weng's "What are Diffusion Models?" (free). H2: Diagram the forward/reverse diffusion process by hand.
- Day 2: H1: Forward diffusion process — Weng's post. H2: Implement forward noising from scratch on a toy image.
- Day 3: H1: Reverse process & denoising — Weng's post. H2: Implement a minimal denoising network trained to predict noise on MNIST.
- Day 4: H1: DDPM training objective — original paper's key equations (arXiv). H2: Derive the simplified predict-the-noise loss from the paper's math.
- Day 5: H1: Sampling — Weng's post. H2: Implement the reverse sampling loop to generate an image from noise.
- Day 6: H1+H2: **Project:** train a small diffusion model on MNIST/Fashion-MNIST end to end.
- Day 7: Review — explain forward/reverse diffusion from memory.

**Week 67 (GANs):**
- Day 1: H1: Generator vs. discriminator — original GAN paper's intro (arXiv). H2: Write out G and D's loss functions from the minimax objective, by hand.
- Day 2: H1: Training dynamics & mode collapse — freeCodeCamp GAN tutorial. H2: Implement a simple GAN from scratch on a toy 2D dataset.
- Day 3: H1: DCGAN architecture — original paper's guidelines (arXiv). H2: Implement DCGAN; train on MNIST.
- Day 4: H1: Training-stability tricks — free practitioner posts. H2: Apply 2 tricks; compare training curves.
- Day 5: H1: Conditional GANs — original paper's core idea (arXiv). H2: Extend your DCGAN to be class-conditional.
- Day 6: H1+H2: Consolidate — compare your diffusion model (Week 66) and GAN outputs; discuss stability/diversity/quality tradeoffs.
- Day 7: Review

**Week 68 (Multimodal models & applied generative AI):**
- Day 1: H1: CLIP — original paper's core idea (arXiv). H2: Use a pretrained CLIP model (HF, free) for zero-shot image classification on your own images.
- Day 2: H1: How Stable Diffusion combines CLIP + diffusion (conceptual) — free explainer. H2: Diagram how CLIP embeddings condition the diffusion process, in your own words.
- Day 3: H1: Text-to-image in practice — HF `diffusers` library (free). H2: Run inference with a pretrained Stable Diffusion model; experiment with prompts.
- Day 4: H1: FID score concept — free explainer. H2: Compute a simplified quality-comparison metric between your generated and real samples.
- Day 5: H1: Ethical/practical considerations (deepfakes, copyright, misuse) — free overview articles. H2: One-page reflection: what would a responsible-use checklist for a generative-AI feature look like?
- Day 6: H1+H2: Practice — combine CLIP-based retrieval with your Week 64 RAG pipeline (multimodal search).
- Day 7: Review

**Week 69 (Advanced fine-tuning & efficient training):**
- Day 1: H1: Quantization — free practitioner explainer. H2: Quantize a fine-tuned model (`bitsandbytes`, free); compare speed/memory vs. full precision.
- Day 2: H1: Knowledge distillation — original paper's core idea (Hinton et al., arXiv). H2: Distill your Week 63 classifier into a smaller student model; compare accuracy/size tradeoff.
- Day 3: H1: Mixed-precision training — PyTorch AMP docs. H2: Add AMP to a training loop; measure speedup.
- Day 4: H1: Gradient accumulation — free practitioner posts. H2: Implement it to simulate a larger batch size.
- Day 5: H1: KV-caching for efficient inference — free explainer. H2: Implement basic KV-caching in your mini-GPT.
- Day 6: H1+H2: **Project:** apply quantization + KV-caching to your mini-GPT; benchmark generation speed before/after.
- Day 7: Review

**Week 70 (Module D wrap & AI-for-finance bridge):**
- Day 1: H1: LLMs in quant finance — free QuantStart/QuantInsti articles. H2: Design (on paper) an LLM-augmented research pipeline for your Phase 2 capstone.
- Day 2: H1: Temporal Fusion Transformer concept — paper's abstract/core idea (arXiv). H2: Compare TFT's approach to your Phase 2 ARIMA/GARCH models — what does deep learning add, and what does it cost?
- Day 3: H1: Sequence models for price prediction, with efficient-markets caveats — QuantInsti article + a skeptical counterpoint. H2: Implement an LSTM-based price-direction predictor, walk-forward validated (Week 32's methodology).
- Day 4: H1: Combining traditional quant features with deep-learning features — practitioner posts. H2: Build a hybrid model: Phase 2 factor features + an LSTM-derived feature.
- Day 5: H1: Problem-set day — hardest exercises from Weeks 65–69. H2: Redo the DDPM loss derivation and GAN minimax objective from memory.
- Day 6: Consolidate — one-page summary: GPT → RLHF → diffusion → GANs → multimodal → efficient training → finance applications.
- Day 7: **Module D review**

### Module E: Reinforcement Learning (Weeks 71–75)

**Week 71 (MDPs):**
- Day 1: H1: Markov Decision Processes — Sutton & Barto Ch. 3 (free). H2: Work the chapter's exercises; define a toy grid-world MDP by hand.
- Day 2: H1: Value functions & Bellman equations — S&B Ch. 3. H2: Derive the Bellman expectation equation from the value function's definition, step by step.
- Day 3: H1: Policy evaluation/improvement — S&B Ch. 4. H2: Implement policy iteration from scratch on your Day 1 grid world.
- Day 4: H1: Value iteration — S&B Ch. 4. H2: Implement it on the same grid world; compare convergence to policy iteration.
- Day 5: H1: David Silver's RL Course, Lecture 1 (free). H2: Lecture 2 — MDPs, working the slides' examples yourself.
- Day 6: H1+H2: **Project:** solve FrozenLake (Gymnasium, free) with value iteration.
- Day 7: Review — re-derive the Bellman equation from memory.

**Week 72 (Q-learning):**
- Day 1: H1: Monte Carlo methods for RL — S&B Ch. 5. H2: Implement first-visit Monte Carlo policy evaluation from scratch.
- Day 2: H1: Temporal difference learning — S&B Ch. 6. H2: Derive the TD(0) update from the Bellman equation; implement it.
- Day 3: H1: Q-learning — S&B Ch. 6. H2: Implement tabular Q-learning on FrozenLake; plot the learning curve.
- Day 4: H1: SARSA — S&B Ch. 6. H2: Implement SARSA on the same environment; compare learned policies.
- Day 5: H1: Exploration vs. exploitation — S&B Ch. 2. H2: Compare 3 exploration schedules.
- Day 6: H1+H2: **Project:** solve Taxi-v3 (Gymnasium) with tuned tabular Q-learning.
- Day 7: Review

**Week 73 (Deep Q-Networks):**
- Day 1: H1: Why function approximation is needed at scale — DQN paper's motivation (arXiv). H2: Explain in your own words why a neural net replaces the Q-table.
- Day 2: H1: DQN architecture — original paper (arXiv). H2: Implement a basic DQN from scratch on CartPole.
- Day 3: H1: Experience replay — DQN paper. H2: Implement a replay buffer from scratch; observe the stability improvement.
- Day 4: H1: Target networks — DQN paper. H2: Add one; compare stability with/without.
- Day 5: H1: Double/Dueling DQN concepts — follow-up papers (arXiv). H2: Implement Double DQN's modification; compare to vanilla DQN.
- Day 6: H1+H2: **Project:** fully train a DQN on CartPole-v1; plot reward-per-episode.
- Day 7: Review — explain why replay and target networks stabilize training, unaided.

**Week 74 (Policy gradient methods):**
- Day 1: H1: Policy gradient theorem — S&B Ch. 13. H2: Derive it from first principles (log-derivative trick), step by step.
- Day 2: H1: REINFORCE — S&B Ch. 13. H2: Implement from scratch on CartPole; compare sample efficiency to Week 73's DQN.
- Day 3: H1: Variance reduction (baselines) — S&B Ch. 13. H2: Add a value-function baseline; measure the stability improvement.
- Day 4: H1: Actor-Critic — S&B Ch. 13. H2: Implement a basic Actor-Critic from scratch.
- Day 5: H1: PPO concept — original paper's core idea (arXiv). H2: Write out why the clipped objective prevents destructive policy updates.
- Day 6: H1+H2: **Project:** train a PPO agent via `stable-baselines3` (free); compare sample efficiency to your from-scratch Actor-Critic.
- Day 7: Review

**Week 75 (RL applications & Module E wrap):**
- Day 1: H1: RL for trading as an MDP — free QuantStart/QuantInsti article. H2: Design a trading MDP on paper (state, action, reward for a single-asset agent).
- Day 2: H1: Reward-shaping pitfalls in trading RL — a skeptical practitioner article (free). H2: Identify 3 traps in your design; revise it.
- Day 3: H1: Custom Gymnasium environments — free docs. H2: Implement your trading MDP as a Gymnasium environment using Phase 2 data.
- Day 4: H1: Train a DQN/PPO agent on it. H2: Evaluate against a buy-and-hold baseline — expect it to struggle; that's realistic and instructive.
- Day 5: H1: Multi-armed bandits — S&B Ch. 2 revisited. H2: Implement UCB from scratch.
- Day 6: H1+H2: Consolidate — honest write-up of why RL-for-trading is notoriously hard (non-stationarity, sparse reward, backtest overfitting).
- Day 7: **Module E review** — re-derive the policy gradient theorem from memory.

### Module F: MLOps & Production AI Systems (Weeks 76–80)

**Week 76 (Model serving):**
- Day 1: H1: FastAPI basics — official free tutorial. H2: Wrap Week 63's sentiment classifier in a `/predict` endpoint.
- Day 2: H1: Request validation (Pydantic) — FastAPI docs. H2: Add validation and error handling.
- Day 3: H1: Batching for efficiency — free practitioner posts. H2: Add simple request batching.
- Day 4: H1: Async serving — FastAPI docs. H2: Convert to async; benchmark under concurrent load (`locust`, free).
- Day 5: H1: API docs & testing — FastAPI's built-in Swagger UI. H2: Write integration tests (`pytest` + `httpx`).
- Day 6: H1+H2: **Project:** fully tested, documented FastAPI service.
- Day 7: Review

**Week 77 (Containerization & deployment):**
- Day 1: H1: Docker basics — official free "Get Started" guide. H2: Containerize your Week 76 service.
- Day 2: H1: Docker Compose — Docker docs. H2: Add a Compose file with your API + a Postgres logging DB.
- Day 3: H1: Reproducible builds — Docker best-practices docs. H2: Write a multi-stage Dockerfile minimizing image size.
- Day 4: H1: CI with GitHub Actions (free for public repos). H2: Set up a workflow running your test suite on every push.
- Day 5: H1: Free-tier deployment (Render/Fly.io/HF Spaces) — platform's free docs. H2: Deploy your API; confirm it's reachable.
- Day 6: H1+H2: **Project:** full CI/CD — push → tests → deploy.
- Day 7: Review

**Week 78 (Experiment tracking & versioning):**
- Day 1: H1: MLflow — official free "Quickstart." H2: Instrument a training loop with MLflow logging.
- Day 2: H1: Comparing runs — MLflow docs. H2: Run a small hyperparameter sweep; compare in the MLflow UI.
- Day 3: H1: Data versioning — DVC docs (free) "Get Started." H2: Set up DVC for one dataset; track a change.
- Day 4: H1: Model registries — MLflow docs. H2: Register your best model with a version tag.
- Day 5: H1: Reproducibility best practices — free practitioner posts. H2: Audit and fix an earlier training script.
- Day 6: H1+H2: **Project:** a fully tracked, versioned, reproducible training pipeline.
- Day 7: Review

**Week 79 (Monitoring & model drift):**
- Day 1: H1: Data drift vs. concept drift — free explainer. H2: Simulate drift on a model; show the resulting degradation.
- Day 2: H1: Statistical drift detection (KS test) — free explainer. H2: Implement a simple KS-test drift check for one feature.
- Day 3: H1: Logging predictions — free practitioner posts. H2: Add prediction logging to your Week 76 API.
- Day 4: H1: Alerting concepts — free practitioner posts. H2: Write a script flagging when accuracy drops below a threshold.
- Day 5: H1: A/B testing for model rollouts — free explainer. H2: Design an A/B test plan on paper.
- Day 6: H1+H2: Consolidate — add drift monitoring, closing the loop from training to production to monitoring.
- Day 7: Review

**Week 80 (Module F wrap):**
- Day 1: H1: Cost/latency tradeoffs — free practitioner posts. H2: Benchmark your deployed model vs. its quantized (Week 69) version; decide which you'd ship.
- Day 2: H1: API security basics — FastAPI security docs. H2: Add rate limiting and input sanitization.
- Day 3: H1: MLOps maturity models — free overview (e.g., Google's MLOps whitepaper). H2: Assess your own pipeline against it; note what's missing.
- Day 4: H1: Problem-set day — weakest MLOps topic. H2: Fix the biggest gap identified.
- Day 5: H1+H2: Consolidate — one-page architecture diagram of your full training→deployment→monitoring pipeline.
- Day 6: Practice explaining the pipeline aloud as if to a hiring manager.
- Day 7: **Module F review**

### Module G: Research Depth, AI-for-Finance Capstone, and Guru Wrap (Weeks 81–95)

**Week 81 (Research methodology):**
- Day 1: H1: The "three-pass" paper-reading method — Keshav's free "How to Read a Paper." H2: Apply it to a paper from your Phase 4 reading list; write pass-1/pass-2 notes.
- Day 2: H1: Finding good papers — explore Papers With Code (free). H2: Build a 10-paper reading list, finance+AI intersection encouraged.
- Day 3: H1: Why reproduction is hard and valuable — free ML-reproducibility checklist. H2: Attempt to reproduce a simple result you've partially implemented already.
- Day 4: H1: Continue reproduction. H2: Debug discrepancies; document hidden implementation details papers often omit.
- Day 5: H1: Structure of an ML experiment report. H2: Write up your reproduction attempt.
- Day 6: H1+H2: Practice the three-pass method on 2 more papers, building speed.
- Day 7: Review

**Week 82 (Staying current & the AI landscape):**
- Day 1: H1: What major labs publish — OpenAI/Anthropic/DeepMind/Meta AI's free public research blogs. H2: Read one recent post from each of 3 labs; summarize each in 3 sentences.
- Day 2: H1: Free newsletters (e.g., "The Batch" by DeepLearning.AI). H2: Read a week's back-issues; note 3 new things.
- Day 3: H1: Benchmark leaderboards — Papers With Code/HF leaderboards (free). H2: Compare your own implementations' performance to current SOTA on 2 tasks; note the gap and why.
- Day 4: H1: AI safety/alignment landscape (conceptual) — a lab's public "Core Views"-style post (free). H2: One-page reflection on what seems most tractable to you.
- Day 5: H1: Open-source AI ecosystem — Hugging Face Hub docs (free). H2: Read 2 model cards for open models relevant to your interests.
- Day 6: H1+H2: Consolidate — a dated "state of AI as I understand it" one-pager to revisit in a year.
- Day 7: Review

**Week 83 (AI-for-finance deep bridge):**
- Day 1: H1: Alternative data in quant finance — free QuantStart/QuantInsti articles. H2: Design (on paper) a vision-based feature pipeline (e.g., satellite imagery → retail traffic estimate).
- Day 2: H1: NLP for financial documents — free practitioner article. H2: Build a pipeline extracting sentiment from real, free earnings-call transcripts.
- Day 3: H1: Combining your Week 70 hybrid model with the Day 2 sentiment feature. H2: Add it; walk-forward validate whether it improves out-of-sample performance.
- Day 4: H1: Does the added complexity actually help? — 1–2 skeptical practitioner articles. H2: Rigorous, honest comparison vs. your Phase 2 pure-factor model, same protocol, same costs.
- Day 5: H1: Explainability on the richer feature set — StatQuest SHAP recap. H2: Compute SHAP values; check whether the AI features contribute or just add overfitting risk.
- Day 6: H1+H2: Consolidate into a proper research-style writeup with an honest conclusion.
- Day 7: Review

**Week 84 (Guru capstone — scoping):**
- Day 1: H1: Choose your capstone (pick one or propose your own): **(a)** a from-scratch mini-GPT trained on a financial-text corpus with a working RAG Q&A interface; **(b)** a full trading-signal research pipeline combining vision/NLP/time-series features with walk-forward validation and a risk report, tying Phase 2 + Phase 4 together; **(c)** a reproduction + extension of a recent (last 12 months) arXiv paper, with a novel small experiment of your own. Weigh against realistic free compute (Google Colab/Kaggle free-tier GPUs). H2: Write a one-page proposal — goal, method, success criteria, rough plan for Weeks 85–93.
- Day 2: H1: Set up the repo properly (structure, README, environment). H2: Set up MLflow tracking (Week 78) from day one.
- Day 3: H1: Data collection/preparation plan. H2: Begin collecting/cleaning the core dataset.
- Day 4: H1: Baseline — the simplest thing that could possibly work. H2: Implement and run it; record its performance as your benchmark.
- Day 5: H1: Literature check — 2–3 papers/posts most relevant to your approach (Week 81's method). H2: Note 2–3 concrete techniques to try.
- Day 6: H1+H2: Refine your plan based on the baseline and literature; finalize scope.
- Day 7: Review — confirm the plan is realistic given your time/compute; scale down if needed. Finishing smaller and well beats abandoning ambitious.

**Weeks 85–86 (Capstone build — core components 1 and 2):**
Each week: Day 1–2 design + implement the component (mini-GPT training loop / signal pipeline / paper's core method, depending on your choice), Day 3 write tests as you go (Phase 1 discipline), Day 4 finish a working version + debug against the Week 84 baseline, Day 5 profile it and read one supporting resource for any rough edge hit, Day 6 consolidate — component complete, tested, documented — Day 7 review and log progress in the README.

**Week 87 (Integration):**
- Day 1: H1: Design the integration point between components 1 and 2. H2: Begin wiring them together.
- Day 2: H1: Continue integration. H2: Write integration tests covering the full pipeline end to end.
- Day 3: H1: Debug integration issues (usually the hardest bugs). H2: Add logging at each pipeline stage to make failures visible.
- Day 4: H1: Run the full pipeline on a small test case. H2: Fix what breaks.
- Day 5: H1: Run on a larger, realistic case. H2: Fix what breaks (there will be more).
- Day 6: H1+H2: Consolidate — full pipeline runs reliably end to end at realistic scale.
- Day 7: Review

**Week 88 (Evaluation & ablation studies):**
- Day 1: H1: Design your evaluation protocol properly (Week 32's walk-forward discipline if finance-related). H2: Implement it.
- Day 2: H1: Run full evaluation; record headline metrics. H2: Quantify improvement (or honest lack thereof) vs. your Week 84 baseline.
- Day 3: H1: Design an ablation study — free ML-methodology posts if unfamiliar. H2: Run the first ablation.
- Day 4: H1: Run 2 more ablations. H2: Analyze — which design choices actually mattered?
- Day 5: H1: Error analysis on worst failure cases. H2: Categorize failure modes — fixable vs. fundamental.
- Day 6: H1+H2: Consolidate results into tables/plots for the final writeup.
- Day 7: Review

**Week 89 (Robustness & literature check-in):**
- Day 1: H1: Stress-test with edge-case inputs. H2: Fix what breaks.
- Day 2: H1: Revisit Weeks 81/82's reading habits — 1–2 very recent papers/posts relevant to your project. H2: Note anything worth trying in your remaining time.
- Day 3: H1: Implement one improvement, if high-value and time allows. H2: Re-run Week 88's evaluation to check if it actually helped.
- Day 4: H1: Code cleanup — dead code, naming, docstrings. H2: Continue cleanup.
- Day 5: H1: Security/safety pass if user-facing (Week 80's practices). H2: Apply fixes.
- Day 6: H1+H2: Consolidate — clean, robust, well-documented codebase.
- Day 7: Review

**Week 90 (Scaling up):**
- Day 1: H1: Decide deliberately what "more" would help most (data/training/compute). H2: Implement the chosen scaling change.
- Day 2: H1: Run the scaled version. H2: Monitor it properly (Week 78's tracking) rather than letting it run unobserved.
- Day 3: H1: Continue monitoring/waiting on long jobs. H2: Analyze intermediate results.
- Day 4: H1: Evaluate the scaled version against Week 88's baseline. H2: Decide, and document, whether scaling was worth it.
- Day 5: H1: Integrate the scaled version if it helped (or keep the smaller one and document why, if not). H2: Update evaluation tables.
- Day 6: H1+H2: Consolidate.
- Day 7: Review

**Week 91 (Polish & final robustness):**
- Day 1: H1: Read through your codebase as if reviewing a stranger's PR. H2: Fix what would confuse them.
- Day 2: H1: Reproducibility audit (fresh clone, fresh environment). H2: Fix any gaps.
- Day 3: H1: Finalize meaningful test coverage. H2: Add missing critical tests.
- Day 4: H1: Write the project's final README (what/how/results/limitations). H2: Draft it fully.
- Day 5: H1: Create 2–3 clear result visualizations. H2: Polish them properly.
- Day 6: H1+H2: Full dry run — walk through your own README from scratch to confirm it works.
- Day 7: Review

**Week 92 (Final integration & stress test):**
- Day 1: H1: Combine everything into a final, presentable package. H2: One more full end-to-end run.
- Day 2: H1: Write a project abstract (150–250 words). H2: Draft the methodology section (problem/method/results/limitations/future work), paper-style.
- Day 3: H1+H2: Continue writing.
- Day 4: H1: Self-review for clarity and honesty (don't oversell). H2: Revise.
- Day 5: H1: Prepare a 5–10 minute verbal walkthrough. H2: Practice delivering it, timed.
- Day 6: H1+H2: Final polish pass.
- Day 7: Rest — capstone complete.

**Week 93 (Feedback & iteration):**
- Day 1: H1: Post for feedback (r/MachineLearning, r/quant if finance-related, relevant Discords — free). H2: Re-read your own writeup fresh; note changes.
- Day 2: H1: Continue gathering feedback. H2: Triage into "must fix" / "nice to have" / "disagree and that's OK."
- Day 3: H1: Implement highest-value "must fix" items. H2: Continue.
- Day 4: H1: Finish "must fix" and quick wins. H2: Update writeup accordingly.
- Day 5: H1: Final proofread of code and writeup. H2: Proofread again — worth the redundancy.
- Day 6: H1+H2: Publish/finalize (clean public repo or portfolio site).
- Day 7: Rest

**Week 94 (Full-journey review — Phases 1–4):**
- Day 1: H1: Review Phase 1 — redo 2 old exercises from memory. H2: Re-solidify anything genuinely forgotten.
- Day 2: H1: Review Phase 2 — redo the Black-Scholes derivation and Black-Litterman implementation from memory. H2: Re-derive/re-implement gaps.
- Day 3: H1: Review Phase 3 — redo the lock-free queue and matching-engine core logic from memory. H2: Rebuild the weakest part.
- Day 4: H1: Review Phase 4 — redo the transformer block and DQN from memory. H2: Rebuild the weakest part.
- Day 5: H1: Write an "everything I know now" map connecting all 4 phases. H2: Identify your strongest and weakest areas, honestly.
- Day 6: H1+H2: Spend both hours entirely on your weakest area — no new content, just solidifying.
- Day 7: Review

**Week 95 (Interview & portfolio wrap — the whole journey):**
- Day 1: H1: Assemble a portfolio linking all major capstones (quant, C++ systems, AI). H2: Write an intro paragraph tying them into one story.
- Day 2: H1: Practice explaining the full journey in under 5 minutes, timed. H2: Refine based on where you stumbled.
- Day 3: H1: Compile a master formula/concept list across all 4 phases for spaced repetition (Anki, free). H2: Build the actual deck so this knowledge doesn't decay.
- Day 4: H1: Research real job postings in your target roles; map your projects to their requirements. H2: Note any gap worth a future focused sprint.
- Day 5: H1: Mock-interview yourself across all 4 phases. H2: Do it again with harder follow-ups.
- Day 6: H1+H2: Final consolidation — an honest per-phase self-assessment (solid/strong/expert) and what you'd tackle next.
- Day 7: **Done.** Four phases complete: Python foundations, C++ systems, quantitative finance, and artificial intelligence — each with a working, tested, documented capstone, and a portfolio that tells one coherent story.

---

## Notes on staying fluent, not just informed
1. **Never skip Day 7**, and use both hours on it — Hour 1 recall, Hour 2 harder redo.
2. **Type every line of code yourself.** No copy-pasting, ever — including from your own past solutions when Hour 2 asks you to redo something "from memory."
3. **Keep two running repos**: Python (Phase 1 onward), C++ (Phase 3 onward). By Week 52 both are serious portfolio pieces with tests, benchmarks, and documentation.
4. **The Hour 2 "derive by hand" tasks are not optional extras** — they're what converts "I've seen Black-Scholes" into "I could re-derive Black-Scholes." This is the actual difference 2 hrs/day buys you over 1 hr/day.
5. **If a week overruns, shift the calendar right** rather than compress — 52 weeks at 2 hrs/day with this level of rigor is already an ambitious, realistic pace.
6. **Total: 52 weeks = 12 months, ~2 hrs/day.**
