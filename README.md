# Using machine learning to predict loan default

### About the company: 
LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California.[1](http://www.businessinsider.com/r-avantcredit-raises-225-million-from-tiger-global-peter-thiel-2014-12) It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.[2](https://www.economist.com/blogs/schumpeter/2013/01/lending-club) The company claims that $15.98 billion in loans had been originated through its platform up to December 31, 2015.[3](https://www.lendingclub.com/info/statistics.action)

LendingClub enables borrowers to create unsecured personal loans between $1,000 and $40,000. The standard loan period is three years. Investors can search and browse the loan listings on LendingClub website and select loans that they want to invest in based on the information supplied about the borrower, amount of loan, loan grade, and loan purpose. Investors make money from interest. LendingClub makes money by charging borrowers an origination fee and investors a service fee.

LendingClub also makes traditional direct to consumer loans, including automobile refinance transactions, through WebBank, an FDIC-insured, state-chartered industrial bank that is headquartered in Salt Lake City Utah. The loans are not funded by investors but are assigned to other financial institutions.

The company raised $1 billion in what became the largest technology IPO of 2014 in the United States. Though viewed as a pioneer in the fintech industry and one of the largest such firms, LendingClub experienced problems in early 2016, with difficulties in attracting investors, a scandal over some of the firm's loans and concerns by the board over CEO Renaud Laplanche's disclosures leading to a large drop in its share price and Laplanche's resignation.

### Credit Risk 
When initially founded, LendingClub positioned itself as a social networking service and set up opportunities for members to identify group affinities, based on a theory that borrowers would be less likely to default to lenders with whom they had affinities and social relationships. **It developed an algorithm called LendingMatch for identifying common relationship factors such as geographic location, educational and professional background, and connectedness within a given social network.**[4](https://www.lendingclub.com/info/how-it-works.action),[5](https://web.archive.org/web/20110713200446/http://blog.lendingclub.com/images/7920.pdf),[6](https://www.usatoday.com/money/perfi/credit/2007-12-25-peerlending-pers_N.htm)

It offers the algorithm as a search tool for investors to find Notes they would like to purchase, using borrower and loan attributes such as the length of a loan term, target weighted average interest rate, borrower credit score, employment tenure, home ownership status, and others.[7](https://www.lendingclub.com/extdata/Clean_As_Filed_20101015.pdf) To reduce default risk, LendingClub focuses on high-credit-worthy borrowers, declining approximately 90% of the loan applications it received as of 2012[8](https://www.lendingclub.com/info/statistics.action) and assigning higher interest rates to riskier borrowers within its credit criteria.[9](https://www.sec.gov/Archives/edgar/data/1409970/000119312512151868/d306143ds1a.htm#rom306143_20) Only borrowers with FICO score of 660 or higher can be approved for loans.[10](https://www.lendingclub.com/public/how-we-set-interest-rates.action)

The statistics on LendingClub's website state that, as of December 31, 2016, 62.3 percent of borrowers report using their loans to refinance other loans or pay credit card debt.[11](https://www.lendingclub.com/info/statistics.action)

### Project goal

Can we use Machine Learning to build a model that predicts whether a borrower will default on a loan, that matches or exceeds LendingClub's own algorithm? Can we identify the most important features that determine the lean outcome?
