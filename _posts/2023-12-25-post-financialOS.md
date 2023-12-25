---
title: "My Personal Finance System: A Reference Guide"
date: 2023-12-25
categories:
  - finance
---

In the latter half of 2023, I revamped my financial management system to operate more efficiently and autonomously. This guide outlines the tools and strategies I used to streamline my finances.

**Tools:**
* Fidelity: A versatile one-stop-shop for most financial needs.
* Monarch Money: An solid spend management app.
* Chase: My preferred credit card provider for reliable services.

## Investment Strategy

The core principle is straightforward: spend less than you earn and invest the rest. My strategy revolves around broad, low-cost index funds, with a focus on maximizing contributions in tax-advantaged accounts. I maintain levers to adapt my investments based on new insights.

**Control Levers:**
1. Diversification through five low-cost ETFs, allowing me to adjust my investment mix as needed:
    1. US Total Market (VTI)
    2. US S&P 500 Index (VOO)
    3. US Technology Sector (VGT)
    4. International Total Market (VXUS)
    5. US Total Bond Market (BND)
2. Automatic daily investments to steadily increase market exposure. By automatically investing daily, I can speed up or slow down exposure to respond to market signals.

Why bonds? Bonds are integrated as a stable alternative to cash, particularly when cash interest rates are low. They also help balance my equity exposure during portfolio rebalancing.

## Retirement Account strategy:

### Contribution order: 401k Match -> HSA -> IRA -> 401k -> 401k After-Tax

* Initially, maximize employer 401k/403b matching contributions.
* Then, focus on HSA for its triple tax advantage: deductible contributions, tax-free growth, and tax-free withdrawals for healthcare.
* Fully fund your IRA. If you are above the Roth IRA income limit, utilize the backdoor Roth IRA strategy.
* Complete your 401k/403b contributions.
* If possible, maximize after-tax 401k contributions.

### Roth vs. Traditional: I opt for Roth

I default to Roth whenever I can. Traditional accounts assume your tax rate will be lower in the future. If you are a high-earner, this is unlikely since 401(k) distributions and passive income impact your tax bracket.

Even with the additional market earnings from the pre-tax money contriubtions, breaking even requires about a 10% tax reduction at retirement. For example, you'd need to shift from a 32% today to a 22% tax rate then.

I value the peace of mind and flexibility Roth accounts offer, removing the need to navigate tax brackets during retirement. Retirement is not the time I want to be thinking about tax optimization.

[Use this calculator for a detailed comparison](https://www.capitalgroup.com/individual/planning/tools/traditional-vs-roth-401k-403b-analyzer.htm)

### Backdoors are just Doors

Backdoor contributions, initially daunting, are surprisingly straightforward. For Roth IRAs, contribute to a Traditional IRA and convert it. For Roth 401ks, inquire about "After-Tax" contributions and "Roth-In-Plan-Conversion" capabilities in your plan. This increases the contribution limit significantly ($23k -> $66k).

For the Roth IRA backdoor, you may need to ask about "pro-rata" taxation if you already have an existing Traditional IRA funded.

For the Roth-401(k) backdoor, you should ensure you don't over-contribute and block your employer contributions.

Ask your financial advisor/brokerage about these.

## Cash Flow Strategy

Efficient cash flow is crucial. I streamlined this process using Fidelity, which offers a high-interest money market fund (MMF) and a standard checking account with competitive interest rates. This setup ensures that my funds are always earning interest and readily available for investments or expenses. This setup also helped me eliminate unnecessary accounts & waiting for my transfers between accounts to "settle".

While many companies offer different accounts, Fidelity is the only one that automates money movement between them. Their free overdraft functionality  automatically pulls money from my brokerage if my checking account can't meet a large expense. It also automatically refills my checking account to ensure there is enough for standard expenses. These features eliminate micro-actions.

Fidelity also provides API-based data sharing, which is significantly more secure than traditional screen-scraping methods (like Plaid)[^2].

[^2]: Screen-scrapers are huge security holes since they require your username and password and literally log into your account to pull information

Lastly there are no minimums or any fees to worry about and can dramatically eliminate vendors.

**Banks are not necessarily better** 

After the SVB debacle in 2023, fintechs now offer more than $250k FDIC by automatically distributing your funds across multiple accounts. FDIC insurance is valuable only because banks invest your money out, and can over-leverage themselves.  Fintechs often store deposits in Money Market Funds because they aren't in the lending business. MMF's are safer than bank deposits because they have to buy safer assets (ie. treasuries) and maintain higher liquidity ratios. They arent allowed to give out consumer loans and, by nature, respond much faster to changes in real interest rates.


## Spend Management Strategy
**Credit cards:**
There are tons of websites to compare offerings, but really the tenets are simple. 
1. You should be averaging 2% back on a majority of your spend. Most cards use categories to confuse you. The only category to optimize for is Travel (if you plan to travel significantly).
2. Pick a card that has a good data-sharing API if you want to leverage other services to manage your spend. Looking at you Apple Card.

Cards with annual fees are luxury purchases. It is a tall order to recover even a \$200 fee via points. An extra 1% means you have to spend \$20k to break even. So run the numbers before being tempted. 

Certain features like travel insurance, car rental primary insurance, and purchase protections are worth consideration. Pay off your balance every month. If you get an 0% APR card, remember that racking up credit utilization will temporarily drop your FICO score, but once you clear the liability, your score will likely improve.

**Categorization:**
I use Monarch Money to bucket all my transactions. While most credit cards categorize spending into standard types, I prefer categorizing based on the "intent" of the expense. For example, an Uber to work is different than an Uber to dinner. Amazon for groceries is different than Amazon for black-friday.

My categories are simple:
1. Life Admin: Miscellaneous but necessary expenses & bills. These are unavoidable and part of routine life management.
2. Home: Costs associated with maintaining a healthy home life, including groceries. No regrets here.
3. Adventure: Discretionary expenses for enjoyment and leisure activities.
4. Items: Expenditures on depreciating physical goods, such as clothing and furniture.
5. Gifts: Spending on others, encompassing all forms of gifts.
6. Time: Subscription services that help me enjoy my time.
7. Vacation: Holiday expenses which should not impact other monthly financial metrics.

I find this form of spend tracking easier to maintain as it differentiates essential expenses from discretionary spend.

Bucketing your expenses does not mean you have to "live on a budget". Buckets can also force you to spend on categories that are being under-invested (ex: a health and fitness bucket).

## Why I chose Fidelity

**Pros:**
* Simple recurring investments to DCA even to a daily level
* Fractional buys of all ETFs and stocks - allows you to focus on the dollars going into the market instead of rounding to whole shares[^5].
* Faster liquidity - ACH transfers are ready to invest even before they settle
* Sweep to 5% on brokerage and retirement accounts, 2.5% on checking account
* Automatically over-draft from sweep account to checking account
* Good API level data sharing and standard 2FA security
* Amazing customer service. Free financial consultants who actually spend time with you.
* Free net-worth, retirement planning, asset allocation, and basic spend software baked in.

[^5]: Shares will round down to the closes 0.001 share for the dollars invested so this can lead to a miniscule amount of under-buying per transaction.

**Improvements:**
* Their credit card product has strong rewards with 2% flat on all categories, but their partner bank Elan may need to improve their of customer service.
* Their app is solid, but shows your entire portfolio without offering a primary view of just your cash/checking account.
* Their website design is stuck between their old design and new design on different pages.

---