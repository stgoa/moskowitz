# _"Do Industries Explain Momentum?"_ by Tobias J. Moskowitz and Mark Grinblatt (1999)

A landmark paper in *The Journal of Finance* exploring the source of stock return momentum.

---

## 🧭 Overview and Motivation

Moskowitz and Grinblatt (1999) investigate whether industry-level effects explain the well-documented momentum phenomenon — the tendency of stocks that have performed well (winners) to continue performing well, and vice versa for losers, over 6–12 month horizons.

Their central finding is that a significant portion of individual stock momentum is driven by industry momentum. Once stock returns are adjusted for industry effects, the profitability of traditional momentum strategies declines dramatically.

---

## 📊 Data and Methodology

- **Sample period**: July 1963 – July 1995
- **Data sources**: CRSP and COMPUSTAT
- **Universe**: NYSE, AMEX, and NASDAQ stocks
- **Industry definition**: 20 value-weighted portfolios based on 2-digit SIC codes (each with ~230 firms on average)
- **Adjustments**: Returns adjusted for size and book-to-market (BE/ME) effects using the Daniel & Titman (1997) methodology

Momentum strategies are constructed by:

- Ranking stocks or industries based on past L-month returns (commonly 6 months)
- Holding a long position in top performers (winners) and short in bottom performers (losers) for the next H months (commonly 6 months)

---

## ⚙️ Key Findings

### 1. Strong Industry Momentum

- Industries exhibit significant positive autocorrelation in returns over 6–12 month horizons
- A portfolio that buys the top 3 industries and sells the bottom 3 (based on past 6-month returns) earns ~0.43% per month, comparable to standard individual stock momentum returns
- This profitability persists after adjusting for:
  - Size
  - BE/ME
  - Individual stock momentum
  - Cross-sectional mean return dispersion
  - Market microstructure effects

**Conclusion**: Industry-level effects explain much of the momentum anomaly.

---

### 2. Individual Momentum Weakens After Industry Adjustment

- When stock returns are adjusted for contemporaneous industry performance, momentum profits in individual equities drop sharply and often become statistically insignificant
- The residual (firm-specific) momentum component contributes little to overall profits, suggesting that what looks like "individual" momentum is largely industry-driven

---

### 3. Industry vs. Stock Momentum Characteristics

| Feature | Industry Momentum | Individual Stock Momentum |
|---------|-------------------|--------------------------|
| Primary profit source | Long (buy-side) positions | Short (sell-side) positions |
| Most profitable horizon | 1–12 months (peaks at 1 month) | 6–12 months |
| Long-term behavior | Reverses after 12–24 months | Also reverses after ~2 years |
| Liquidity sensitivity | Profitable even among large, liquid stocks | Driven by small, illiquid stocks |
| Diversification | Poor (stocks in same industries) | Appears diversified, but isn't once industries are considered |

---

### 4. Robustness Checks

The paper conducts numerous robustness analyses:

- Skipping a month between ranking and holding periods (to mitigate microstructure effects) does not eliminate industry momentum
- **Lead-lag effects**: Large, liquid stocks within industries drive most of the profits, not illiquid or small firms, indicating momentum is not an artifact of delayed price adjustments
- **"Random industry" tests**: Constructing pseudo-industries from random stocks eliminates the momentum effect — confirming that true industry structure matters

---

## 🧩 Cross-Sectional Regression Results

Using Fama–MacBeth regressions, the authors regress adjusted stock returns on:

- Market beta, size, BE/ME
- Individual and industry past returns (1, 6, 12, and 36-month windows)

**Findings**:

- Industry momentum subsumes individual stock momentum at most horizons
- Only the 12-month individual stock momentum remains marginally significant — possibly due to tax-loss selling seasonality (as later shown in Grinblatt & Moskowitz, 1999)

---

## 🧠 Interpretation and Theoretical Implications

### Behavioral Explanations

The authors discuss how behavioral models could explain industry momentum:

- **Underreaction / overconfidence** (Daniel et al., 1998): Investors may overreact to industry trends and underreact to new information
- **Conservatism / representativeness** (Barberis et al., 1998): Investors adjust too slowly to changing industry prospects or overextrapolate past performance
- **Slow information diffusion** (Hong & Stein, 1999): Industry leaders react first; information spreads gradually to peers

### Rational Explanations

- **Changing risk premia**: Systematic risk related to industry growth options (Berk, Green & Naik, 1999) or irreversible investment (Kogan, 1999) may drive return persistence within industries

---

## 💡 Practical Implications

- **Portfolio design**: Momentum strategies targeting industries may be more profitable, diversified, and implementable than stock-level momentum trades
- **Market efficiency**: Momentum is not a pure arbitrage — industry effects imply it carries undiversifiable risk
- **Behavioral finance**: Industry momentum supports models emphasizing investor biases and information diffusion, not pure risk-based explanations

---

## 🧾 Conclusion

**Core Insight**: Most of the profitability in stock-level momentum strategies arises from momentum in industry components. Once industry effects are controlled for, the "momentum anomaly" largely disappears.

- Industry momentum is strong, pervasive, and robust
- It is distinct from size, value, and firm-specific factors
- It offers a bridge between behavioral explanations of momentum and rational models incorporating correlated industry shocks

---

## Citation

Moskowitz, Tobias J., and Mark Grinblatt (1999). "Do Industries Explain Momentum?" *Journal of Finance*, 54(4): 1249–1290.

[American Finance Association Annual Meeting, 1999]
