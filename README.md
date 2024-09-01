# project-1

# ORIGINAL DATASET INFORMATION
    url:            https://www.federalreserve.gov/econres/scfindex.htm
    link to file:   "CSV extract data (2 MB ZIP)"

    file name:      SCFP2022.csv     -- We uploaded a copy of this csv on 8-30-2024.

# CLEANED DATASET INFORMATION
    file name:      output.csv          -- we used Survey_Consumer_Finances.ipynb to filter the dataset to only the appropriate columns.

# COLUMN HEADERS AND DESCRIPTIONS
    AGE	            Age of reference person
    AGECL	        Age group of the reference person
    EDCL	        Education category of reference person
    EDUC	        Highest completed grade by reference person
    FAMSTRUCT	    Family structure of household
    KIDS	        Total number of children in household
    MARRIED	        Marital status of reference person
    OCCAT1	        Occupation categories for reference person
    OCCAT2	        Occupation classification for reference person
    RACE	        Race/ethnicity of respondent
    RACECL	        Class of race of respondent
    RACECL4	        Alternate class of race of respondent
    LIFECL	        Life cycle of reference person
    LF	            Labor force participation of reference person
    INDCAT	        Industry classifications for reference person
    ASSET	        Total value of assets held by household, 2019 dollars
    EQUITY	        Total value of financial assets held by household that are invested in stock, 2019 dollars
    HOMEEQ	        Total value of equity in primary residence of household, 2019 dollars
    RETEQ	        Total value of equity in quasi-liquid retirement assets, 2019 dollars
    ANYPEN	        Pension exists for either reference person or spouse
    ACTBUS	        Total value of actively managed business(es), 2019 dollars
    NONACTBUS	    Value of non-actively managed business(es), 2019 dollars
    IRAKH	        Total value of IRA/Keogh accounts, 2019 dollars
    ANNUIT      	Amount R would receive if they cashed in annuities, 2019 dollars
    TRUSTS	        Amount R would receive if they cashed in trusts, 2019 dollars
    EQUITINC	    ratio of equity to normal income
    HBROK	        have a brokerage account
    PIRMORT	        ratio of monthly mortgage payments to monthly income
    PIRTOTAL	    Ratio of monthly debt payments to monthly income
    DEBT2INC	    Ratio of total debt to total income
    KNOWL	        Respondent's knowledge of personal finances
    SAVRES1	        Reason for saving: can't save
    SAVRES2	        Reason for saving: education
    SAVRES3	        Reason for saving: family
    SAVRES4	        Reason for saving: home
    SAVRES5	        Reason for saving: purchases
    SAVRES6	        Reason for saving: retirement
    SAVRES7	        Reason for saving: liquidity/the future
    SAVRES8	        Reason for saving: investment
    SAVRES9	        Reason for saving: no particular reason
    INCOME	        Total amount of income of household, 2019 dollars
    INCCAT	        Income percentile groups
    INCPCTLECAT	    Alternate income percentile groups
    SSRETINC	    Social security and pension income, 2019 dollars
    WAGEINC	        Wage and salary income, 2019 dollars
    NETWORTH	    Total net worth of household, 2019 dollars

    Definitions:

    age of the reference person, and categorical variable:
    1:<35, 2:35-44, 3:45-54, 4:55-64, 5:65-74, 6:>=75
    
    Education of the reference person, and categorical variable:
    1=no high school diploma/GED, 2=high school diploma or GED
    3=some college or Assoc. degree, 4=Bachelors degree or higher

    marital status of the reference person: 1=married/living with partner,
    2=neither married nor living with partner
   

    number of children (including natural children/step-children/
    foster children of reference person/spouse/partner)

    labor force participation: 1=working in some way, 0=not working
    at all

    life cycle variables: 1=reference person under 55 + not married/LWP + no
    children, 2=reference person under 55 + married/LWP + no children, 3=reference person
    under 55 + married/LWP + children, 4=reference person under 55 + not
    married/LWP + children, 5=reference person 55 or older and working,
    6=reference person 55 or older and not working

    family structure: 1=not married/LWP + children,
    2=not married/LWP + no children + reference person under 55,
    3=not married/LWP + no children + reference person 55 or older,
    4=married/LWP+ children, 5=married/LWP + no children

    racecl5 1=white non-Hispanic, 2=black/African-American non-Hispanic,
    3=Hispanic or Latino, 4=Asian, 5=Other or Multiple race

    work status categories for reference person:
    1=work for someone else, 2=self-employed/partnership,
    3=retired/disabled + (student/homemaker/misc. not working and
    age 65 or older), 4=other groups not working (mainly those under
    65 and out of the labor force)

    occupation classification for reference person:
    1=managerial/professional 2=technical/sales/services,
    3=other (incl. production/craft/repair workers, operators,
    laborers, farmers, foresters, fishers) 4=not working

    industry classifications for reference person: 1=mining + construction +
    manufacturing, 2=transportation + communications + utilities and
    sanitary services + wholesale trade + finance, insurance and
    real estate, 3=agriculture + retail trade + services + public
    administration

    Census regions: 1=northeast, 2=north central, 3=south, 4=west

    Urbanicity: 1=MSA, 2=non-MSA

    WSAVED: 1=spending exceeded income, 2=spending equaled income,
    3=spending less than income;

    reasons for saving: 1=cant save, 2=education, 3=family, 4=home,
    5=purchases, 6=retirement, 7=liquidity/the future, 8=investment,
    9=no particular reason. 
    NOTE: multiple saving reasons may be reported: here choosing only
    first (most important) reason

    Households overall expenses over last 12 months:
    1=unusually high, 2=unusually low, 3=normal

    household had any late payments in last year;
    LATE=(X3004=5);
    household had any payments more than 60 days past due in last year;
    LATE60=(X3005=1)

    have a payday loan

    bankruptcy in the last five years

    PEU knowledge of personal finance;
    1=not at all knowledgeable...10=very knowledgeable

    foreclosure

    how would deal with hypothetical financial emergency?
    (NOTE: only asked if X7510 NE 1).
    1=borrow from others, 2=spend from own savings,
    3=postpone payments, 4=cut back spending, 5=work more

    If work more, would it be on existing job (1),
    or on new job (2)?

    quasi-liquid retirement accounts (IRAs and thrift-type accounts);
    individual retirement accounts/Keoghs
    account-type pension plans

    total quasi-liquid: sum of IRAs, thrift accounts, and future pensions;
    this version includes currently received benefits
    have quasi-liquid assets: 1=yes, 0=no

    other managed assets (trusts, annuities and managed investment
    accounts in which HH has equity interest)
    have other managed assets: 1=yes, 0=no

    
    

