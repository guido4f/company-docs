# UK Pension Planner - User Guide

A comprehensive guide to using the UK Pension Planner mobile app for retirement planning and pension drawdown forecasting.

## Table of Contents

1. [Overview](#overview)
2. [Operating Modes](#operating-modes)
3. [Crystallisation Strategies](#crystallisation-strategies)
4. [Drawdown Strategies](#drawdown-strategies)
5. [Configuration Guide](#configuration-guide)
6. [How to Use](#how-to-use)
7. [Glossary](#glossary)

---

## Overview

UK Pension Planner is a mobile application designed to help UK residents plan their retirement by forecasting pension drawdown scenarios. The app simulates various strategies for withdrawing from pensions and ISAs while minimising tax and maximising income sustainability.

### Key Features

- **Multi-person support**: Plan for individuals or couples
- **Multiple pension types**: Defined Contribution (DC) and Defined Benefit (DB) pensions
- **Tax-efficient strategies**: Optimise withdrawals to minimise income tax
- **Mortgage integration**: Account for mortgage payments and payoff strategies
- **Sensitivity analysis**: Test different growth rate assumptions
- **Year-by-year forecasting**: See detailed projections of income, tax, and balances

---

## Operating Modes

The app offers four operating modes, each suited to different planning objectives.

### 1. Fixed Income Mode

**Purpose**: Determine how long your funds will last given a specified monthly income requirement.

**How it works**:
- You specify how much monthly income you need (e.g., £4,000/month)
- The simulator calculates how long your pension and ISA funds will last
- Results show the year when funds run out or reach your target age

**Best for**:
- People with a specific lifestyle cost in mind
- Understanding if current savings are adequate
- Comparing different withdrawal strategies

### 2. Depletion Mode

**Purpose**: Calculate the sustainable income that will last exactly until your target age.

**How it works**:
- You specify a target depletion age (e.g., age 90)
- The simulator uses binary search to find the maximum sustainable income
- It finds the income level that depletes funds to zero at exactly your target age

**Best for**:
- Maximising income while ensuring funds last
- People who want to "die with zero"
- Understanding maximum sustainable withdrawal rates

### 3. Pension Only Mode

**Purpose**: Deplete pensions while preserving ISAs for inheritance or emergencies.

**How it works**:
- Withdrawals come exclusively from pension pots
- ISAs remain untouched and continue growing
- Useful for preserving tax-free inheritance (ISAs are typically outside your estate for IHT)

**Best for**:
- Estate planning and inheritance tax considerations
- Preserving ISAs as emergency reserves
- Those wanting to use pension first due to potential IHT advantages

### 4. Pension to ISA Mode

**Purpose**: Efficiently transfer pension wealth into ISAs by filling tax bands.

**How it works**:
- Withdraws from pension to fill your personal allowance and basic rate tax band
- Excess over your income needs is deposited into ISAs
- Gradually shifts wealth from taxable pension to tax-free ISA

**Best for**:
- Long-term tax efficiency
- Those with large pension pots relative to income needs
- Building tax-free wealth for later years
- Couples who can use both ISA allowances (£20,000 each per year)

---

## Crystallisation Strategies

When accessing a Defined Contribution pension, you must choose how to crystallise (access) your funds. The app supports two main strategies:

### Gradual Crystallisation

**How it works**:
- Crystallise pension in portions as needed
- Each crystallisation provides 25% tax-free, 75% taxable
- The tax-free portion is called PCLS (Pension Commencement Lump Sum)
- Once crystallised, funds move to a "crystallised pot" and future withdrawals are fully taxable

**Advantages**:
- Spread tax-free allowance over time
- Maintain flexibility on when to access funds
- Keep more in tax-advantaged pension wrapper longer

**Considerations**:
- Requires more active management
- 75% of each crystallisation is immediately taxable income

### UFPLS (Uncrystallised Funds Pension Lump Sum)

**How it works**:
- Each withdrawal is 25% tax-free, 75% taxable
- No formal crystallisation - withdraw directly from uncrystallised pot
- Every withdrawal maintains the 25/75 split

**Advantages**:
- Simple - every withdrawal has same tax treatment
- Always get 25% tax-free on each withdrawal
- No need to track crystallised vs uncrystallised

**Considerations**:
- Cannot take large tax-free lump sums
- Not compatible with some advanced strategies (e.g., Pension to ISA)

---

## Drawdown Strategies

Drawdown strategies determine the order and method of accessing your various pots. The app offers multiple strategies to suit different objectives.

### Savings First

**Description**: Use ISAs first, then pension.

**How it works**:
- Withdraws from ISA until depleted
- Then moves to pension withdrawals
- Pension continues to grow tax-free while ISA is used

**Best for**:
- Those wanting maximum pension growth time
- Situations where ISA growth rate is lower than pension
- Preserving pension for later when in lower tax bracket

### Pension First

**Description**: Use pension first, preserve ISAs.

**How it works**:
- Withdraws from pension (with tax) first
- ISA preserved for later years
- ISA provides tax-free income when pension depleted

**Best for**:
- Those with large pensions relative to ISAs
- Wanting tax-free income in later years
- Estate planning (ISAs may have IHT advantages)

### Tax Optimised

**Description**: Minimise total tax paid through optimal withdrawal mix.

**How it works**:
- Analyses tax position of both people in a couple
- Balances withdrawals to use both personal allowances
- Fills tax bands efficiently before moving to higher rates
- Uses spouse with lower income to take more taxable withdrawals

**Best for**:
- Couples with different income levels
- Maximising use of personal allowances
- Minimising lifetime tax paid

### Pension to ISA

**Description**: Over-draw pension to fill tax bands, deposit excess to ISA.

**How it works**:
- Calculates space in personal allowance and basic rate band
- Withdraws pension to fill these bands (up to £50,270 in 2024/25)
- After paying expenses and tax, excess goes into ISA
- Effectively shifts money from pension to ISA at 0-20% tax

**Best for**:
- Those with income needs less than £50,270/year
- Building ISA wealth for inheritance
- Long-term tax efficiency
- Early retirees before state pension starts

### Pension to ISA (Proactive)

**Description**: Same as Pension to ISA, but extracts pension even when work income covers expenses.

**How it works**:
- Even when salary covers living costs, still extracts from pension
- Uses any remaining tax band space after work income
- Accelerates pension-to-ISA transfer during working years

**Best for**:
- Those still working with spare tax band capacity
- Maximising tax-efficient transfers before retirement
- High earners wanting to rebalance wealth

### Pension Only

**Description**: Only use pension, never touch ISAs.

**How it works**:
- All withdrawals come from pension
- ISA balance preserved entirely
- Used in "Pension Only" operating mode

**Best for**:
- Estate planning
- Emergency fund preservation
- Understanding pension-only sustainability

### Fill Basic Rate

**Description**: Withdraw pension exactly to the basic rate limit.

**How it works**:
- Targets filling income up to £50,270 (2024/25 basic rate limit)
- Crystallises pension at 20% tax maximum
- Excess over income needs goes to ISA

**Best for**:
- Avoiding higher rate tax entirely
- Controlled, predictable pension extraction
- Those who want to pay no more than 20% tax on withdrawals

### State Pension Bridge

**Description**: Draw heavily before state pension, reduce after.

**How it works**:
- Before state pension age: Withdraw heavily from private pension (fill basic rate band)
- After state pension starts: Reduce private pension withdrawals
- Uses personal allowance fully when state pension isn't occupying it

**Best for**:
- Early retirees before state pension age
- Maximising use of personal allowance pre-67
- Those with large private pensions

### Bucket Strategy

**Description**: Divide portfolio into "safe bucket" (near-term) and "growth bucket" (long-term).

**How it works**:
- ISA acts as "safe bucket" for 3-5 years of expenses
- Pension acts as "growth bucket" for long-term growth
- Withdraw from safe bucket for income
- Refill safe bucket from growth bucket when markets are up

**Best for**:
- Managing sequence of returns risk
- Psychological comfort during market volatility
- Those wanting income stability regardless of market conditions

### Constant Pound Withdrawal

**Description**: Fixed inflation-adjusted withdrawal amount each year.

**How it works**:
- Set a specific annual withdrawal amount (e.g., £30,000)
- Amount adjusts for inflation each year
- Withdraw this amount regardless of portfolio size

**Best for**:
- Predictable, stable income
- Simple budgeting
- Those who don't want income to vary with markets

### Floor with Upside

**Description**: Guaranteed minimum income with potential upside from good market years.

**How it works**:
- Set a "floor" - minimum guaranteed income (e.g., £20,000)
- When markets are up, take a percentage of gains as bonus income
- Cap total withdrawal at a ceiling (e.g., 150% of floor)

**Best for**:
- Income stability with flexibility
- Sharing in good market returns
- Those wanting guaranteed minimum but willing to vary spending

---

## Configuration Guide

### Person Configuration

Each person in the household can be configured with:

#### Basic Details
| Field | Description | Example |
|-------|-------------|---------|
| Name | Identifier for the person | "James" |
| Birth Date | Date of birth (YYYY-MM-DD) | "1970-06-15" |
| Retirement Date | When you stop working | "2030-07-01" |
| Retirement Age | Legacy: age when income needs start | 60 |
| Pension Access Age | Minimum age to access DC pension (may differ from retirement) | 55 |
| State Pension Age | Age when state pension begins | 67 |

#### Assets
| Field | Description | Example |
|-------|-------------|---------|
| Tax-Free Savings (ISA) | Current ISA balance | £150,000 |
| Pension | Uncrystallised DC pension pot | £500,000 |
| LISA | Lifetime ISA balance (accessible from age 60) | £30,000 |
| ISA Annual Limit | Annual ISA contribution limit | £20,000 |

#### Defined Benefit (DB) Pension
| Field | Description | Example |
|-------|-------------|---------|
| DB Pension Amount | Annual pension at normal retirement age | £15,000 |
| DB Pension Start Age | Age when DB pension payments begin | 60 |
| DB Pension Name | Scheme name | "Teachers' Pension" |
| Normal Retirement Age | Scheme's standard retirement age | 65 |
| Early Retirement Factor | Reduction per year if taken early | 4% per year |
| Late Retirement Factor | Increase per year if taken late | 5% per year |
| Commutation | Fraction to exchange for lump sum (0-25%) | 25% |
| Commutation Factor | £ lump sum per £1 pension given up | £12 |

#### State Pension
| Field | Description | Example |
|-------|-------------|---------|
| State Pension Defer Years | Years to defer past state pension age | 2 years |

*Note: Deferring state pension increases it by ~5.8% per year compounded*

#### Work Income (Pre-Retirement)
| Field | Description | Example |
|-------|-------------|---------|
| Work Income | Annual salary while employed | £60,000 |
| Salary Growth Rate | Annual increase in salary | 2% |
| Use Contribution Rates | Calculate contributions as % of salary | Yes |
| Pension Contribution Rate | Your pension contribution (% of salary) | 5% |
| Employer Contribution Rate | Employer's contribution (% of salary) | 3% |

#### Part-Time / Phased Retirement
| Field | Description | Example |
|-------|-------------|---------|
| Part-Time Income | Annual income from part-time work | £15,000 |
| Part-Time Start Age | Age when part-time work begins | 55 |
| Part-Time End Age | Age when part-time work ends | 62 |

#### Pre-Retirement Contributions
| Field | Description | Example |
|-------|-------------|---------|
| Pension Contribution | Annual pension contribution | £5,000 |
| ISA Contribution | Annual ISA/LISA contribution | £10,000 |
| LISA Opt Out | Disable auto-allocation to LISA | No |
| ISA Growth Mode | How ISA contributions grow: static, income, or inflation | "income" |

#### ISA to SIPP Transfers
| Field | Description | Example |
|-------|-------------|---------|
| ISA to SIPP Enabled | Enable pre-retirement ISA to pension transfers | No |
| Pension Annual Allowance | Maximum annual pension contribution | £60,000 |
| ISA to SIPP Max Percent | Max % of allowance to use | 100% |
| ISA to SIPP Preserve Months | Months of expenses to keep in ISA | 12 |

### Financial Configuration

#### Growth Rates
| Field | Description | Default |
|-------|-------------|---------|
| Growth Rate Source | Manual or from stock index | Custom |
| Pension Growth Rate | Annual pension pot growth | 5% |
| Savings Growth Rate | Annual ISA growth | 5% |
| Income Inflation Rate | Annual increase in income needs | 3% |
| State Pension Inflation | Annual state pension increase | 3% |
| Tax Band Inflation | Tax band adjustment (0 = frozen) | 3% |
| State Pension Deferral Rate | Enhancement per year deferred | 5.8% |

#### Emergency Fund
| Field | Description | Default |
|-------|-------------|---------|
| Emergency Fund Months | Months of expenses to preserve in ISA | 0 |
| Inflation Adjusted | Adjust emergency fund for inflation | No |

#### Gradual Growth Decline (Age-in-Bonds)
| Field | Description | Default |
|-------|-------------|---------|
| Growth Decline Enabled | Enable reducing growth rates with age | No |
| Pension Growth End Rate | Target pension growth rate | 4% |
| Savings Growth End Rate | Target ISA growth rate | 4% |
| Growth Decline Target Age | Age when growth reaches end rate | 80 |

### Income Configuration

#### Fixed Income Mode
| Field | Description | Default |
|-------|-------------|---------|
| Monthly Before Age | Income need before threshold age | £4,000 |
| Monthly After Age | Income need after threshold age | £2,500 |
| Age Threshold | Age when income requirement changes | 67 |

#### Tiered Income (Advanced)
Create multiple income tiers for different life phases:

| Tier Type | Description | Example |
|-----------|-------------|---------|
| Fixed | Specific £/month amount | £4,000/month until 67 |
| Percentage | Annual % of initial portfolio | 4% per year |
| Investment Gains | Live on real returns (growth minus inflation) | Varies |

#### Depletion Mode
| Field | Description | Default |
|-------|-------------|---------|
| Target Depletion Age | Age to deplete funds by | 90 |
| Income Ratio Phase 1 | Relative income before threshold | 5 |
| Income Ratio Phase 2 | Relative income after threshold | 3 |

*Example: 5:3 ratio means phase 1 income is 5/3 times higher than phase 2*

#### Guardrails (Guyton-Klinger)
Dynamic withdrawal adjustments based on portfolio performance:

| Field | Description | Default |
|-------|-------------|---------|
| Guardrails Enabled | Enable dynamic adjustments | No |
| Upper Limit | Withdrawal rate trigger (above initial) | 120% |
| Lower Limit | Withdrawal rate trigger (below initial) | 80% |
| Adjustment | Percentage adjustment when triggered | 10% |

*Example: If initial withdrawal rate was 4% but due to market falls it becomes 4.8% (120% of 4%), reduce withdrawals by 10%*

#### VPW (Variable Percentage Withdrawal)
| Field | Description | Default |
|-------|-------------|---------|
| VPW Enabled | Enable variable percentage withdrawals | No |
| VPW Floor | Minimum as fraction of initial | 80% |
| VPW Ceiling | Maximum as fraction of initial | 150% |

### Mortgage Configuration

| Field | Description | Example |
|-------|-------------|---------|
| Parts | List of mortgage parts | See below |
| End Year | Year when mortgage naturally ends | 2031 |
| Early Payoff Year | Earliest year for early payoff (lock-in) | 2028 |

#### Mortgage Parts
Each mortgage part can be configured:

| Field | Description | Example |
|-------|-------------|---------|
| Name | Description | "Main mortgage" |
| Principal | Outstanding balance | £150,000 |
| Interest Rate | Annual rate | 3.89% |
| Is Repayment | Repayment vs interest-only | Yes |
| Term Years | Years remaining | 10 |

#### Mortgage Options in Simulation
| Option | Description |
|--------|-------------|
| Early Payoff | Pay off at early payoff year (after lock-in) |
| Normal Payoff | Pay off at normal end year |
| Extended | Extend by 10 years beyond normal |
| PCLS Payoff | Use 25% pension lump sum to pay off mortgage |

### Simulation Settings

| Field | Description | Default |
|-------|-------------|---------|
| Start Year | Year to start simulation | Next year |
| End Age | Age to end simulation | 90 |
| Reference Person | Whose age to use for end calculation | Person 1 |

### Sensitivity Analysis

Test different growth scenarios:

| Field | Description | Default |
|-------|-------------|---------|
| Pension Growth Min | Minimum pension growth to test | 4% |
| Pension Growth Max | Maximum pension growth to test | 12% |
| Savings Growth Min | Minimum ISA growth to test | 4% |
| Savings Growth Max | Maximum ISA growth to test | 12% |
| Step Size | Increment between rates | 1% |

### Tax Configuration

| Field | Description | 2024/25 Value |
|-------|-------------|---------------|
| Personal Allowance | Tax-free income amount | £12,570 |
| Tapering Threshold | Income where PA reduces | £100,000 |
| Tapering Rate | PA lost per £1 over threshold | 50p |

*Note: Personal allowance is fully removed at £125,140 income*

### Tax Bands (2024/25)

| Band | Income Range | Rate |
|------|--------------|------|
| Personal Allowance | £0 - £12,570 | 0% |
| Basic Rate | £12,571 - £50,270 | 20% |
| Higher Rate | £50,271 - £125,140 | 40% |
| Additional Rate | Over £125,140 | 45% |

---

## How to Use

### Getting Started

1. **Add People**: Configure yourself (and partner if applicable) in the People section
2. **Enter Assets**: Input current pension pots, ISA balances, and any DB pensions
3. **Set Income Needs**: Define your monthly income requirements
4. **Configure Dates**: Set retirement date/age and simulation parameters

### Running a Simulation

1. **Choose Operating Mode**:
   - Fixed Income: See how long funds last
   - Depletion: Find sustainable income to target age
   - Pension Only: Deplete pensions, preserve ISAs
   - Pension to ISA: Transfer pension wealth to ISAs

2. **Select Optimisation Goal**:
   - Minimize Tax: Find strategy paying least total tax
   - Maximize Income: Find strategy providing most total income
   - Maximize Balance: Find strategy leaving largest final balance

3. **Run Simulation**: The app tests multiple strategy combinations and recommends the best

### Understanding Results

#### Results Tab
- **Best Strategy**: The optimal combination of crystallisation and drawdown strategies
- **Depletion Year/Age**: When funds run out (Fixed Income mode)
- **Sustainable Income**: Maximum monthly income (Depletion mode)
- **Total Tax Paid**: Lifetime tax across all years

#### Analysis Tab
- **Year-by-Year Breakdown**: Detailed view of each simulation year
- **Income Sources**: State pension, DB pension, withdrawals
- **Tax Analysis**: Tax paid each year and cumulative
- **Balance Progression**: How pots change over time

#### Reports Tab
- **Strategy Comparison**: Side-by-side comparison of all strategies
- **Sensitivity Analysis**: How results change with different growth rates
- **Income Timeline**: Visual representation of income sources over time

### Tips for Best Results

1. **Be Realistic About Growth**: 5% real growth is reasonable for a diversified portfolio; 7%+ is optimistic

2. **Account for Inflation**: Use 2-3% inflation assumption for income needs

3. **Consider Tax Band Inflation**: Set to 0% for "frozen bands" scenario (pessimistic) or 2-3% for normal

4. **Test Multiple Scenarios**: Use sensitivity analysis to see impact of different assumptions

5. **Review Annually**: Update assumptions and rerun simulation each year

6. **Don't Forget State Pension**: It's valuable - £12,500+/year that's inflation protected

7. **Consider Part-Time Work**: Even small amounts extend fund longevity significantly

---

## Glossary

| Term | Definition |
|------|------------|
| **Crystallisation** | The process of accessing pension funds, converting uncrystallised to crystallised |
| **DC Pension** | Defined Contribution - a pension pot that you draw from directly |
| **DB Pension** | Defined Benefit - a guaranteed annual pension based on salary/service |
| **Drawdown** | Withdrawing money from your pension pot |
| **ISA** | Individual Savings Account - tax-free savings wrapper |
| **LISA** | Lifetime ISA - ISA with government bonus, accessible from 60 |
| **PCLS** | Pension Commencement Lump Sum - 25% tax-free lump sum |
| **Personal Allowance** | Income you can earn tax-free (£12,570 in 2024/25) |
| **SIPP** | Self-Invested Personal Pension |
| **State Pension** | Government pension, currently starting at age 67 |
| **UFPLS** | Uncrystallised Funds Pension Lump Sum - withdrawal method |
| **VPW** | Variable Percentage Withdrawal - withdrawal method based on portfolio and age |

---

## Support

For questions, feedback, or bug reports, please contact the development team or visit the app's support page.

---

*Last updated: January 2026*
