![Preview](assets/preview.png)

![Banner](assets/banner.jpg)

# The Extra Dollar Verdict

**Live:** https://thebullbrew.github.io/extra-dollar-verdict/
**Repo:** https://github.com/thebullbrew/extra-dollar-verdict

## What it does
Judges where a homeowner's extra monthly cash should go — extra mortgage principal or the investment account. Both roads spend exactly the same money every month; the tool simulates both to the horizon, compares net positions (investments minus loan still owed), and seals the verdict: PREPAY WINS / INVEST WINS / CLOSE CALL / SPLIT IT.

## The method behind it
Prepaying earns your mortgage rate, guaranteed and tax-free — you never pay tax on interest you never paid. Investing earns an expected return that is neither guaranteed nor tax-free, so the tool subtracts your annual tax + fee drag and applies your own risk haircut: when raw math says invest but risk-adjusted math says prepay, the seal is SPLIT IT. It also solves the break-even market return — the return the market must actually deliver, after drag, to beat the guaranteed prepay return — and adjusts the guaranteed return if you itemize and deduct mortgage interest. If the loan dies early on the prepay road, the freed payment rolls into investments for the rest of the hold, so neither road gets free money.

## How to run
Open `docs/index.html` in any browser, or visit the live link above. Works offline as a PWA. No backend, no accounts, data stays in localStorage.
