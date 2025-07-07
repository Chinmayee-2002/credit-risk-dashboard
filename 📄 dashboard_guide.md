Guide to Recreate Dashboard

Here’s how to build the Power BI visuals using cleaned_customer_data.csv:

KPI Cards: :

Visual Type: Card

Drag:

AvgIncome

AvgCreditScore

DefaultRate

Style: White text, dark background, emoji titles



Bar Chart – RiskLevel Distribution

Visual Type: Clustered Column Chart

Axis: RiskLevel

Values: Count of CustomerID

Colors: Red (High), Yellow (Medium), Green (Low)



Pie Chart – Default Breakdown

Visual Type: Pie Chart

Legend: Defaulted

Values: Count of CustomerID



Scatter Plot – CreditScore vs LoanAmount

X-Axis: CreditScore

Y-Axis: LoanAmount

Size: Income (optional)

Color: RiskLevel

Tooltip: Add CustomerID, NumOfLatePayments



Slicers

Add 3 slicers:

Gender

RiskLevel

Defaulted

Style: Vertical layout on left or right side

Title/Header

Insert → Text box → Add “Credit Risk Scoring Dashboard”

Font: Segoe UI or Calibri, Size: 22–28, Bold

Summary Text Box

Insert → Text box → Write:
This dashboard visualizes credit risk using score, income, and repayment history.
It supports proactive decision-making by identifying high-risk customers.
