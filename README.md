# Continuous Coin Offering

Actors
---
1. PI --> Project's Investor
2. PD --> Project's Developer  

Rules
---

### General
- [ ] Only 1 token type (ERC-20 tbe) exists per 1 project
- [ ] There are 2 project's markers: Serie and Season
- [ ] The sum of all series' timeframes are equal to the timeframe of 1 season they(series) belong to
- [ ] PI can trade project's tokens in any market that accepts it(project's tokens)

### Investments
- [ ] Investments are provided for the whole season
- [ ] Investments are locked during the whole season
- [ ] Investments' batch - is a portion of the investments for the serie
- [ ] The sum of all investments' batches are equal to the season's investments
- [ ] An investments' batch unlocks for PD before beginning of a serie
- [ ] 1st season's fundrising operates by the following formula. PD sets the currency of project's tokens per ETH. PI's purchase demand is the deciding factor of how many project's tokens should be created. PRJ/ETH * TOTAL ETH = TOTAL PRJ
- [ ] By investing into the project, at the start of the project's season, PI receives the stake of project's tokens by the following formula. TOTAL PRJ / TOTAL ETH * PI's ETH
- [ ] In case of stoppping the serie / project, investments refund operates by the formula. Total ETH in the smart contract divides to the total PRJ and multiplies by the total amount of PI's PRJ tokens. TOTAL ETH / TOTAL PRJ * PI's PRJ
- [ ] Locked investments for upcoming series are deposited into AAVE

### Governance
- [ ] During 1st season's fundrising session, PD sets the percentage of total created PRJ that transfers to PD
- [ ] PD sets the timeframe of the season (e.g. 1 year)
- [ ] PD sets the amount of series for 1 season
- [ ] PD sets the timeframe of every series
- [ ] PD sets the amount of every investments' batches
- [ ] PD sets the neccessary amount of "yes" votes to continue the next serie 
- [ ] After the end of the active serie, the voting procedure for the next serie begins
- [ ] PD sets the timeframe for the voting procedure for the next serie (e.g 2 weeks)
- [ ] PI has the right to vote
- [ ] PI's voting power is measured by the amount of project's tokens held by PI
- [ ] PD sets the voting percentage type (absolute, relative)
- [ ] After exceeding voting procedure's timeframe, PI or PD can end voting count procedure
- [ ] In case "yes" votes exceeds the neccessary amount, the next serie continues. Otherwise - no


Out Of Scope [Done Later]
---
- [ ] PIs can open stablecoins' deposits for the PDs for the fixed amount of time. The APY is converted to the project's tokens
- [ ] Convertible Notes
- [ ] MakerDAO flashloans voting dilemma
