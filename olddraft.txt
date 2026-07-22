# Quant Finance + Python + C++: The Full Roadmap (1 Hour/Day, ~10 Months)
### From zero programming in Python/C++ → fluent, job-ready quant fundamentals

**Structure:** Three sequential phases, not simultaneous. Learning two new languages and a new field all at once, 20 minutes each, produces shallow recall in all three. Instead:

- **Phase 1 (Weeks 1–5):** Python from zero
- **Phase 2 (Weeks 6–31):** Quant finance curriculum (Python is now solid by the time it's needed for numpy/pandas)
- **Phase 3 (Weeks 32–43):** C++ from zero → applied to quant (pricers, a mini backtester, performance comparisons)

**Daily rhythm unchanged:** Days 1–6 = new material (1 hr). Day 7 = review only — no new content. Re-derive the week's key idea from memory or redo the hardest exercise. Never skip Day 7.

**Resource legend:**
- **Automate the Boring Stuff** = free full book at automatetheboringstuff.com
- **Corey Schafer** = YouTube channel `@coreyms` — the best free Python OOP/intermediate series
- **Real Python** = realpython.com (many free articles)
- **Python docs** = docs.python.org/3/tutorial (official, free)
- **learncpp.com** = the standard free, comprehensive C++ learning site
- **The Cherno** = YouTube channel `@TheCherno` — excellent free C++ series (performance/memory-focused)
- **cppreference** = cppreference.com (official free reference)
- **Eigen** = free header-only C++ linear algebra library, eigen.tuxfamily.org
- **Catch2** = free header-only C++ testing library, github.com/catchorg/Catch2
- **Stat110 / ritvikmath / StatQuest / QuantStart / QuantInsti / Patrick Boyle / Option Alpha / MIT OCW 18.S096 / MIT OCW 15.401 / Khan Academy Finance / Investopedia / pandas & statsmodels docs / backtrader docs / QuantConnect / Ken French Data Library / ISL** — same as before, see Phase 2.

---

## PHASE 1 — Python From Zero (Weeks 1–5)

### Week 1: Core syntax
- **Day 1:** Variables, types, operators — Python docs tutorial, sections 3–4
- **Day 2:** Control flow: if/else, while, for — Python docs / Automate the Boring Stuff, Ch. 2
- **Day 3:** Functions, default args, `*args`/`**kwargs` — Real Python "Python Functions"
- **Day 4:** Strings & string methods — Automate the Boring Stuff, Ch. 6
- **Day 5:** Lists & tuples — Automate the Boring Stuff, Ch. 4
- **Day 6:** Dictionaries & sets — Automate the Boring Stuff, Ch. 5
- **Day 7:** Review — write a 20-line script using all of the above with no reference material

### Week 2: Intermediate Python
- **Day 1:** List/dict comprehensions — Real Python "Comprehensions"
- **Day 2:** File I/O — Automate the Boring Stuff, Ch. 9
- **Day 3:** Exception handling (try/except) — Real Python "Exceptions"
- **Day 4:** Modules, packages, pip, venv — Python docs / Real Python "Virtual Environments"
- **Day 5:** Classes & objects — Corey Schafer "Python OOP Tutorial" #1
- **Day 6:** Inheritance & dunder methods — Corey Schafer OOP #2–3
- **Day 7:** Review — no notes, explain the difference between a module and a package out loud

### Week 3: Pythonic idioms & standard library
- **Day 1:** Iterators & generators — Real Python "Generators"
- **Day 2:** Decorators — Corey Schafer "Decorators"
- **Day 3:** Lambda, `map`/`filter`/`reduce` — Real Python
- **Day 4:** `collections` module (Counter, defaultdict, namedtuple) — Corey Schafer "Collections Module"
- **Day 5:** `itertools` module — Real Python "itertools"
- **Day 6:** **Project:** small CLI tool (e.g., a to-do list manager)
- **Day 7:** Review

### Week 4: Testing, debugging, tooling
- **Day 1:** Debugging with `print`/`pdb` — Real Python "Python Debugging With pdb"
- **Day 2:** Unit testing with `pytest` — Corey Schafer "Unit Testing"
- **Day 3:** Type hints — Real Python "Type Checking"
- **Day 4:** Dependency management (requirements.txt, venv recap) — Real Python
- **Day 5:** Reading tracebacks / common error patterns — Real Python "Understanding Tracebacks"
- **Day 6:** **Project:** write tests for your Week 3 CLI tool
- **Day 7:** Review

### Week 5: OOP design + bridge to numpy/pandas
- **Day 1:** Composition vs. inheritance — Corey Schafer OOP #4
- **Day 2:** `dataclasses` — Real Python "Data Classes"
- **Day 3:** Intro to numpy arrays — freeCodeCamp NumPy tutorial (YouTube)
- **Day 4:** Intro to pandas DataFrames — pandas docs "10 Minutes to pandas"
- **Day 5:** **Project:** small class-based system (e.g., a simple bank-account simulator with deposit/withdraw/interest)
- **Day 6:** Consolidate — combine OOP + numpy into one mini script
- **Day 7:** **Phase 1 review** — self-quiz: explain classes, generators, decorators, and comprehensions unaided

---

## PHASE 2 — Quant Finance Curriculum (Weeks 6–31)
*(Content identical to the original 6-month plan, renumbered to start after Python fundamentals.)*

### Month 1 — Probability/Stats for Finance + Applied Python + Market Basics

**Week 6 (Probability foundations):**
- Day 1: Random variables & key distributions — Stat110 Lecture 1
- Day 2: Expectation, variance, moments — Stat110 Lectures 4–5
- Day 3: Covariance & correlation — Khan Academy Statistics
- Day 4: Conditional probability & Bayes' theorem — Stat110 Lectures 2–3
- Day 5: Central Limit Theorem — 3Blue1Brown + StatQuest
- Day 6: Problem set — 5 problems from Stat110 Lectures 1–5
- Day 7: Review

**Week 7 (Statistics for finance + market vocabulary):**
- Day 1: Hypothesis testing, p-values — StatQuest
- Day 2: OLS regression basics — StatQuest
- Day 3: Stationarity (concept) — ritvikmath
- Day 4: Fat tails, skewness, kurtosis — Patrick Boyle
- Day 5: What is a stock/bond/derivative — Khan Academy Finance
- Day 6: Market participants, order types, exchanges — Investopedia
- Day 7: Review

**Week 8 (Quant Python stack — now fast, since Phase 1 is done):**
- Day 1: numpy vectorized ops for finance data — freeCodeCamp
- Day 2: pandas for time series — pandas docs
- Day 3: Pulling market data with `yfinance` — Sentdex/freeCodeCamp
- Day 4: Resampling/cleaning time series — pandas docs
- Day 5: Plotting price/return data — matplotlib quickstart
- Day 6: **Project:** script pulling 1 stock's data, plotting price + returns
- Day 7: Review

**Week 9 (Returns & risk fundamentals):**
- Day 1: Simple vs. log returns — QuantStart
- Day 2: Volatility in Python — Investopedia
- Day 3: Sharpe ratio — Investopedia
- Day 4: Correlation across assets, diversification — Khan Academy
- Day 5: Efficient frontier (concept) — Khan Academy
- Day 6: **Project:** returns/vol/Sharpe for 3 stocks in Python
- Day 7: **Month 1 review**

### Month 2 — Markets & Portfolio Theory

**Week 10 (MPT):**
- Day 1: Markowitz mean-variance optimization — MIT OCW 15.401
- Day 2: Efficient frontier derivation — MIT OCW 15.401
- Day 3: CAPM — Khan Academy
- Day 4: Beta, systematic vs. idiosyncratic risk — Investopedia
- Day 5: Multi-factor models intro — Patrick Boyle
- Day 6: **Project:** efficient frontier for 5 stocks via `scipy.optimize`
- Day 7: Review

**Week 11 (Fixed income & macro):**
- Day 1: Bonds — yield, duration, convexity — Khan Academy
- Day 2: Yield curve — Investopedia
- Day 3: Interest rate risk — Khan Academy
- Day 4: Macro drivers — Patrick Boyle
- Day 5: FX basics — Investopedia
- Day 6: Practice: interpret a real yield curve
- Day 7: Review

**Week 12 (Market microstructure):**
- Day 1: Order book & bid-ask spread — QuantStart
- Day 2: Market making — Patrick Boyle
- Day 3: Liquidity & slippage — QuantInsti
- Day 4: Order types — Investopedia
- Day 5: Transaction costs — QuantStart
- Day 6: Practice: analyze a sample order-book dataset (Kaggle)
- Day 7: Review

**Week 13 (Applied portfolio theory):**
- Days 1–6: Coursera "Financial Engineering and Risk Management I" (Columbia) — audit free, Week 1 module
- Day 7: **Month 2 review**

### Month 3 — Time Series Econometrics

**Week 14 (Time series fundamentals):**
- Day 1: Stationarity/ADF test — ritvikmath
- Day 2: ACF/PACF — ritvikmath
- Day 3: White noise & random walks — ritvikmath
- Day 4: AR(p) models — ritvikmath
- Day 5: MA(q) models — ritvikmath
- Day 6: ARMA + fit in `statsmodels`
- Day 7: Review

**Week 15 (ARIMA & volatility):**
- Day 1: ARIMA — ritvikmath
- Day 2: Fit ARIMA to real data — statsmodels docs
- Day 3: Volatility clustering — Patrick Boyle
- Day 4: ARCH — ritvikmath
- Day 5: GARCH — ritvikmath
- Day 6: **Project:** GARCH(1,1) via the `arch` package
- Day 7: Review

**Week 16 (Cointegration & pairs trading):**
- Day 1: Cointegration — ritvikmath
- Day 2: Engle-Granger test — QuantStart
- Day 3: Pairs-trading logic — QuantStart
- Day 4: Implement pairs-trading skeleton
- Day 5: Mean-reversion strategies — QuantInsti
- Day 6: **Project:** backtest a simple pairs trade
- Day 7: Review

**Week 17 (Factor regressions & Month 3 wrap):**
- Day 1: Multiple regression pitfalls — StatQuest
- Day 2: Fama-French 3-factor model — Ken French Data Library
- Day 3: Rolling regressions in pandas
- Day 4: Residual diagnostics
- Day 5: **Project:** factor regression on real stock returns
- Day 6: Consolidate
- Day 7: **Month 3 review**

### Month 4 — Derivatives & Stochastic Calculus

**Week 18 (Options fundamentals):**
- Day 1: Calls & puts — Option Alpha
- Day 2: Payoff diagrams — Option Alpha
- Day 3: Put-call parity — Investopedia
- Day 4: Intrinsic vs. time value — Option Alpha
- Day 5: Basic spreads — Option Alpha
- Day 6: **Project:** plot payoff diagrams in matplotlib
- Day 7: Review

**Week 19 (Black-Scholes & Greeks):**
- Day 1: Brownian motion — MIT OCW 18.S096 Lecture 1
- Day 2: Itô's Lemma — MIT OCW 18.S096 Lecture 2 + QuantStart
- Day 3: Black-Scholes derivation — MIT OCW 18.S096
- Day 4: Implement BS formula in Python
- Day 5: The Greeks — Option Alpha
- Day 6: **Project:** BS pricer + Greeks calculator
- Day 7: Review

**Week 20 (Monte Carlo & numerical pricing):**
- Day 1: Monte Carlo concept — QuantStart
- Day 2: Simulating GBM paths in Python
- Day 3: Pricing European options via Monte Carlo
- Day 4: Variance reduction — QuantStart
- Day 5: Binomial tree pricing — QuantStart
- Day 6: **Project:** compare BS vs. Monte Carlo vs. Binomial tree
- Day 7: Review

**Week 21 (Advanced derivatives & Month 4 wrap):**
- Day 1: Implied volatility & vol smile — Patrick Boyle
- Day 2: American options — QuantStart
- Day 3: Exotic options overview — Investopedia
- Day 4: Risk-neutral pricing — MIT OCW 18.S096
- Day 5: Problem-set day
- Day 6: Consolidate
- Day 7: **Month 4 review**

### Month 5 — Algorithmic Trading & Backtesting

**Week 22 (Strategy design):**
- Day 1: Strategy types — QuantStart
- Day 2: Signal generation — QuantInsti
- Day 3: Momentum strategy logic — QuantStart
- Day 4: Backtesting pitfalls — QuantStart
- Day 5: Performance metrics — Investopedia
- Day 6: **Project:** MA-crossover signal
- Day 7: Review

**Week 23 (Backtesting frameworks):**
- Day 1: Intro to `backtrader` — backtrader docs
- Day 2: Basic backtest with backtrader
- Day 3: Commission/slippage modeling
- Day 4: Position sizing & risk controls — QuantInsti
- Day 5: Walk-forward analysis — QuantStart
- Day 6: **Project:** full backtest with performance metrics
- Day 7: Review

**Week 24 (Alternative strategies & robustness):**
- Day 1: Statistical arbitrage — QuantInsti
- Day 2: Regime detection — Patrick Boyle
- Day 3: Multi-asset backtesting
- Day 4: Transaction-cost refinement
- Day 5: Overfitting risk — QuantStart
- Day 6: **Project:** optimize parameters, check out-of-sample
- Day 7: Review

**Week 25 (QuantConnect & Month 5 wrap):**
- Days 1–5: QuantConnect free Boot Camp — build/backtest one algorithm live
- Day 6: Consolidate
- Day 7: **Month 5 review**

### Month 6 — ML in Finance, Risk Management, Capstone

**Week 26 (ML foundations refresher):**
- Day 1: Train/test split, cross-validation — StatQuest
- Day 2: Linear vs. logistic regression — StatQuest
- Day 3: Decision trees & random forests — StatQuest
- Day 4: Regularization — StatQuest
- Day 5: Feature engineering — Kaggle Learn
- Day 6: **Project:** classifier predicting next-day up/down move
- Day 7: Review

**Week 27 (ML applied to finance):**
- Day 1: Feature importance/SHAP — StatQuest
- Day 2: Time-series cross-validation — ISL free PDF
- Day 3: ML for factor investing — Patrick Boyle
- Day 4: Why ML overfits in finance — QuantInsti
- Day 5: **Project:** ML-based signal, backtested
- Day 6: Consolidate
- Day 7: Review

**Week 28 (Risk management):**
- Day 1: VaR — Investopedia/Khan Academy
- Day 2: Expected Shortfall/CVaR — QuantStart
- Day 3: Stress testing — Investopedia
- Day 4: Portfolio risk decomposition — QuantStart
- Day 5: **Project:** VaR/CVaR for a multi-asset portfolio
- Day 6: Consolidate
- Day 7: Review

**Week 29 (Capstone — build):**
- Day 1: Choose scope — full pipeline: signal → backtest → risk report, 3–5 assets
- Days 2–5: Build incrementally
- Day 6: Finalize
- Day 7: Rest

**Week 30 (Capstone — polish):**
- Days 1–4: Polish code, write methodology report
- Day 5: Post for feedback (r/quant, QuantConnect forums)
- Day 6: Incorporate feedback
- Day 7: Rest

**Week 31 (Python-side wrap):**
- Day 1: Probability brainteasers (search "quant interview brainteasers pdf" — many free sets)
- Day 2: Flashcard review — BS, CAPM, Sharpe, VaR
- Day 3: Practice explaining capstone aloud
- Day 4: Common quant coding questions in Python
- Day 5: Full review pass — revisit weakest month
- Day 6: Consolidate — **Phase 2 complete: full Python-based quant stack**
- Day 7: Rest before starting C++

---

## PHASE 3 — C++ From Zero → Applied to Quant (Weeks 32–43)

### Week 32: Core C++ syntax
- **Day 1:** Compiling, variables, types — learncpp.com Ch. 1
- **Day 2:** Operators, expressions — learncpp.com
- **Day 3:** Control flow (if/else, loops) — learncpp.com
- **Day 4:** Functions — learncpp.com
- **Day 5:** Arrays — learncpp.com
- **Day 6:** Practice — learncpp.com quizzes for Ch. 1–5
- **Day 7:** Review

### Week 33: Pointers & memory
- **Day 1:** Pointers — learncpp.com Ch. 9
- **Day 2:** References — learncpp.com
- **Day 3:** Dynamic memory (`new`/`delete`) — learncpp.com
- **Day 4:** Pointers vs. references, common pitfalls — The Cherno
- **Day 5:** `const` correctness — learncpp.com
- **Day 6:** Practice exercises
- **Day 7:** Review — explain the difference between a pointer and a reference, unaided

### Week 34: OOP in C++
- **Day 1:** Classes & objects — learncpp.com
- **Day 2:** Constructors/destructors — learncpp.com
- **Day 3:** Encapsulation, access specifiers — learncpp.com
- **Day 4:** Inheritance — learncpp.com
- **Day 5:** Polymorphism & virtual functions — learncpp.com / The Cherno
- **Day 6:** **Project:** small class hierarchy (e.g., shapes or financial instruments base class)
- **Day 7:** Review

### Week 35: STL fundamentals
- **Day 1:** `std::vector` — cppreference + The Cherno STL videos
- **Day 2:** `std::map`, `std::unordered_map` — cppreference
- **Day 3:** `std::string` — cppreference
- **Day 4:** Iterators — cppreference
- **Day 5:** `<algorithm>` (sort, find, etc.) — cppreference
- **Day 6:** **Project:** re-implement your Phase 1 CLI tool's logic in C++ using STL
- **Day 7:** Review

### Week 36: Templates & generic programming
- **Day 1:** Function templates — learncpp.com
- **Day 2:** Class templates — learncpp.com
- **Day 3:** Templates + STL — learncpp.com
- **Day 4:** Smart pointers (`unique_ptr`, `shared_ptr`) — learncpp.com/cppreference
- **Day 5:** RAII concept — The Cherno "RAII" video
- **Day 6:** Practice exercises
- **Day 7:** Review

### Week 37: Memory & performance
- **Day 1:** Stack vs. heap, memory layout — The Cherno
- **Day 2:** Move semantics, rvalue references — learncpp.com
- **Day 3:** Copy vs. move constructors — learncpp.com
- **Day 4:** Compiler optimization flags, timing code — The Cherno "Benchmarking"
- **Day 5:** Cache-friendliness & why it matters in trading systems — The Cherno "Performance" series
- **Day 6:** Practice
- **Day 7:** Review

### Week 38: Concurrency basics
- **Day 1:** Threads (`<thread>`) — cppreference/The Cherno
- **Day 2:** Mutexes & race conditions — The Cherno
- **Day 3:** Atomics (brief intro) — cppreference
- **Day 4:** Why concurrency matters in trading systems — QuantStart
- **Day 5:** **Project:** simple multi-threaded program
- **Day 6:** Consolidate
- **Day 7:** Review

### Week 39: Numerical computing in C++
- **Day 1:** Implementing Newton's method in C++
- **Day 2:** Linear algebra with Eigen — Eigen docs
- **Day 3:** Matrix operations with Eigen
- **Day 4:** Random number generation (`<random>`) for Monte Carlo
- **Day 5:** **Project:** simulate GBM paths in C++
- **Day 6:** Consolidate
- **Day 7:** Review

### Week 40: Quant applications — pricers
- **Day 1:** QuantStart's "C++ for Quantitative Finance" article series — intro
- **Day 2:** **Project:** Black-Scholes pricer in C++
- **Day 3:** **Project:** Monte Carlo option pricer in C++
- **Day 4:** **Project:** binomial tree pricer in C++
- **Day 5:** Compare C++ vs. Python runtime for the same pricer (timing benchmark)
- **Day 6:** Consolidate pricers into a small header-only library
- **Day 7:** Review

### Week 41: Building a mini backtester in C++
- **Day 1:** Reading CSV data (`<fstream>`)
- **Day 2:** Representing OHLC data with structs/classes
- **Day 3:** Moving-average signal logic in C++
- **Day 4:** Basic backtest loop
- **Day 5:** Computing Sharpe/drawdown in C++
- **Day 6:** **Project:** full mini backtester
- **Day 7:** Review

### Week 42: Build systems & testing
- **Day 1:** Compilers & flags (g++/clang, `-O2`) 
- **Day 2:** CMake basics — free "An Introduction to Modern CMake" (cliutils.gitlab.io/modern-cmake)
- **Day 3:** Unit testing with Catch2 (free, header-only)
- **Day 4:** Debugging with `gdb` basics
- **Day 5:** **Project:** set up a proper CMake project with Catch2 tests for your mini backtester
- **Day 6:** Consolidate
- **Day 7:** Review

### Week 43: Capstone + interview prep
- **Days 1–4:** Polish your C++ pricing/backtesting mini-library, write a README documenting design choices
- **Day 5:** Common C++ quant interview topics — memory management, OOP, STL (search "C++ quant interview questions" — many free lists)
- **Day 6:** Practice explaining Python-vs-C++ tradeoffs for different quant tasks (research/prototyping vs. low-latency execution)
- **Day 7:** Final review — **you now have a Python quant capstone, a C++ pricing/backtesting library, and the full quant finance stack underneath both.**

---

## Notes on staying fluent, not just informed
1. **Never skip Day 7** — across all three phases, this is what converts exposure into retention.
2. **Type every line of code yourself** — no copy-pasting from tutorials.
3. **Keep two running repos**: one Python (from Phase 1 onward), one C++ (from Phase 3 onward). By Week 43 both are portfolio pieces.
4. **If a week overruns, shift the calendar right** rather than compress — 43 weeks is already a realistic floor for doing this properly at 1 hr/day; rushing defeats the point of the exercise.
5. Total: **43 weeks ≈ 10 months.**
