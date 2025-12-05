# Data

## loans_data.csv

### Source
This dataset comes from the `openintro` package, specifically the `loans_full_schema` dataset from Lending Club.

### Dimensions
- Rows: 10,000 loans
- Columns: [number of columns - run `ncol(loans_full_schema)` to find out] [55]

### Codebook (Data Dictionary)

| Variable | Description |
|----------|-------------|
| loan_amount | The amount of the loan in dollars |
| interest_rate | Interest rate of the loan |
| term | Length of the loan (in months) |
| grade | Loan grade assigned by Lending Club |
| state | Borrower's state |
| annual_income | Borrower's annual income |
| ... | ... |
### Data purpose/description
This data represents a widespread issue of loans with determining factors 
such as annual income, loan grade and term, as well as interest rates. 
I am using the data to see how these variables affect interest rates, and
what patterns there are to takeaway.