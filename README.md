# Credit-Debit Analysis Tool

A Streamlit-based web application to analyze credit and debit transactions from an Excel file, calculate interest on overdue amounts, and generate a detailed report. The tool matches debits to credits chronologically, ensures each debit is used only once, and applies a daily interest rate of 18% of 18% (3.24%) on unpaid amounts after a 180-day due period.

## Features
- Upload an Excel file containing transaction data.
- Select a specific sheet or use the first sheet.
- Process transactions to identify overdue and pending credits.
- Calculate interest (18% of 18% daily) on overdue amounts after 180 days.
- Generate an Excel report with three sheets:
  - **Overdue Amounts**: Details of credits with unpaid amounts and interest.
  - **Pending Credits**: Credits not yet due or partially unpaid.
  - **Balance Summary**: Opening balance, total credits, total debits, and computed/actual closing balance.
- Display a summary of processed credits, overdue credits, pending credits, and total interest.
- Preview results in the app and download the output Excel file.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/credit-debit-analysis-tool.git
   cd credit-debit-analysis-tool
