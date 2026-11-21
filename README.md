# Amiyen

**Business mathematics and financial calculators in one Flask web application.**

[![Project status: Beta](https://img.shields.io/badge/status-beta-orange)](https://github.com/Khaiyen-Salaria/Amiyen/releases)
[![Built with Python](https://img.shields.io/badge/Python-Flask-blue)](https://flask.palletsprojects.com/)

Amiyen brings practical business, finance, and quantitative calculations into one place. Instead of switching between separate tools or spreadsheets, users can choose a calculator, enter their values, and review the calculated results and visual summaries.

> **Beta notice:** Amiyen is still under active development. Results and workflows may change between releases. Verify important calculations independently before using them for business, accounting, tax, investment, or lending decisions.

## Preview

![Amiyen – Basic Business Math calculator](docs/screenshots/basic-business-math.png)

*The application includes a dashboard-style interface with calculation summaries and visual charts.*

## Why Amiyen

- **24 focused calculators** for day-to-day business mathematics, finance, and quantitative analysis.
- **Results at a glance** with summary values and visual charts where supported by the calculator.
- **Calculation history** so users can revisit previous work.
- **CSV export** for taking calculation data into spreadsheet workflows.
- **Local SQLite storage** without requiring a separate database server for a local setup.

## Calculators

| Business and operations | Finance and planning | Mathematics and analysis |
|---|---|---|
| Basic Business Math | Simple Interest | Ratios and Proportions |
| Markup and Markdown | Compound Interest | Statistics |
| Discounts | Annuities | Probability |
| Profit and Loss | Loans | Percentage and Rate Conversions |
| Business Revenue and Cost | Present and Future Value | Financial Ratios |
| Break-Even Analysis | Depreciation | |
| Commission | Capital Budgeting | |
| Payroll and Wages | Stocks and Bonds | |
| Taxes | Insurance | |
| | Promissory Notes | |

## Installation

### Prerequisites

- Python 3 (Python 3.10 or newer is recommended).
- Git.
- `pip`, which is included with most Python installations.

### 1. Clone the repository

```bash
git clone https://github.com/Khaiyen-Salaria/Amiyen.git
cd Amiyen
```

### 2. Create a virtual environment

Choose the commands for your operating system.

**Windows — PowerShell**

```powershell
py -3 -m venv .venv
.\.venv\Scripts\Activate.ps1
```

If PowerShell blocks activation, you can use Command Prompt instead:

```bat
.venv\Scripts\activate.bat
```

**Linux and macOS**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

Run this command with the virtual environment activated:

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

### 4. Start Amiyen

```bash
python app.py
```

Open the local address shown in the terminal. With Flask's default development-server settings, this is usually:

```text
http://127.0.0.1:5000
```

To stop the local server, press `Ctrl+C` in the terminal.

## Usage

1. Open Amiyen in your browser.
2. Select the calculator for the task you need.
3. Enter the values requested by that calculator.
4. Run the calculation and review the result and any available visual breakdown.
5. Use the history and CSV export options to keep or reuse your work where available.

Start with **Basic Business Math** for a general overview, or choose a specific tool such as **Break-Even Analysis**, **Loans**, or **Financial Ratios** for a more focused calculation.

## Screenshots

The examples below show the calculator screens included in this repository's demo set. Select any image to view it at full size.

<details>
<summary>View all 24 calculator screenshots</summary>

<table>
<tr><td align="center" width="33%"><a href="docs/screenshots/basic-business-math.png"><img src="docs/screenshots/basic-business-math.png" alt="Basic Business Math calculator" width="280"></a><br><sub>Basic Business Math</sub></td><td align="center" width="33%"><a href="docs/screenshots/markup-and-markdown.png"><img src="docs/screenshots/markup-and-markdown.png" alt="Markup and Markdown calculator" width="280"></a><br><sub>Markup and Markdown</sub></td><td align="center" width="33%"><a href="docs/screenshots/discounts.png"><img src="docs/screenshots/discounts.png" alt="Discounts calculator" width="280"></a><br><sub>Discounts</sub></td></tr>
<tr><td align="center" width="33%"><a href="docs/screenshots/profit-and-loss.png"><img src="docs/screenshots/profit-and-loss.png" alt="Profit and Loss calculator" width="280"></a><br><sub>Profit and Loss</sub></td><td align="center" width="33%"><a href="docs/screenshots/simple-interest.png"><img src="docs/screenshots/simple-interest.png" alt="Simple Interest calculator" width="280"></a><br><sub>Simple Interest</sub></td><td align="center" width="33%"><a href="docs/screenshots/compound-interest.png"><img src="docs/screenshots/compound-interest.png" alt="Compound Interest calculator" width="280"></a><br><sub>Compound Interest</sub></td></tr>
<tr><td align="center" width="33%"><a href="docs/screenshots/annuities.png"><img src="docs/screenshots/annuities.png" alt="Annuities calculator" width="280"></a><br><sub>Annuities</sub></td><td align="center" width="33%"><a href="docs/screenshots/loans.png"><img src="docs/screenshots/loans.png" alt="Loans calculator" width="280"></a><br><sub>Loans</sub></td><td align="center" width="33%"><a href="docs/screenshots/present-and-future-value.png"><img src="docs/screenshots/present-and-future-value.png" alt="Present and Future Value calculator" width="280"></a><br><sub>Present and Future Value</sub></td></tr>
<tr><td align="center" width="33%"><a href="docs/screenshots/depreciation.png"><img src="docs/screenshots/depreciation.png" alt="Depreciation calculator" width="280"></a><br><sub>Depreciation</sub></td><td align="center" width="33%"><a href="docs/screenshots/commission.png"><img src="docs/screenshots/commission.png" alt="Commission calculator" width="280"></a><br><sub>Commission</sub></td><td align="center" width="33%"><a href="docs/screenshots/payroll-and-wages.png"><img src="docs/screenshots/payroll-and-wages.png" alt="Payroll and Wages calculator" width="280"></a><br><sub>Payroll and Wages</sub></td></tr>
<tr><td align="center" width="33%"><a href="docs/screenshots/taxes.png"><img src="docs/screenshots/taxes.png" alt="Taxes calculator" width="280"></a><br><sub>Taxes</sub></td><td align="center" width="33%"><a href="docs/screenshots/break-even-analysis.png"><img src="docs/screenshots/break-even-analysis.png" alt="Break-Even Analysis calculator" width="280"></a><br><sub>Break-Even Analysis</sub></td><td align="center" width="33%"><a href="docs/screenshots/business-revenue-and-cost.png"><img src="docs/screenshots/business-revenue-and-cost.png" alt="Business Revenue and Cost calculator" width="280"></a><br><sub>Business Revenue and Cost</sub></td></tr>
<tr><td align="center" width="33%"><a href="docs/screenshots/ratios-and-proportions.png"><img src="docs/screenshots/ratios-and-proportions.png" alt="Ratios and Proportions calculator" width="280"></a><br><sub>Ratios and Proportions</sub></td><td align="center" width="33%"><a href="docs/screenshots/statistics.png"><img src="docs/screenshots/statistics.png" alt="Statistics calculator" width="280"></a><br><sub>Statistics</sub></td><td align="center" width="33%"><a href="docs/screenshots/probability.png"><img src="docs/screenshots/probability.png" alt="Probability calculator" width="280"></a><br><sub>Probability</sub></td></tr>
<tr><td align="center" width="33%"><a href="docs/screenshots/percentage-and-rate-conversions.png"><img src="docs/screenshots/percentage-and-rate-conversions.png" alt="Percentage and Rate Conversions calculator" width="280"></a><br><sub>Percentage and Rate Conversions</sub></td><td align="center" width="33%"><a href="docs/screenshots/financial-ratios.png"><img src="docs/screenshots/financial-ratios.png" alt="Financial Ratios calculator" width="280"></a><br><sub>Financial Ratios</sub></td><td align="center" width="33%"><a href="docs/screenshots/capital-budgeting.png"><img src="docs/screenshots/capital-budgeting.png" alt="Capital Budgeting calculator" width="280"></a><br><sub>Capital Budgeting</sub></td></tr>
<tr><td align="center" width="33%"><a href="docs/screenshots/stocks-and-bonds.png"><img src="docs/screenshots/stocks-and-bonds.png" alt="Stocks and Bonds calculator" width="280"></a><br><sub>Stocks and Bonds</sub></td><td align="center" width="33%"><a href="docs/screenshots/insurance.png"><img src="docs/screenshots/insurance.png" alt="Insurance calculator" width="280"></a><br><sub>Insurance</sub></td><td align="center" width="33%"><a href="docs/screenshots/promissory-notes.png"><img src="docs/screenshots/promissory-notes.png" alt="Promissory Notes calculator" width="280"></a><br><sub>Promissory Notes</sub></td></tr>
</table>

</details>

## Configuration and data

- The local application uses SQLite; a separate database service is not needed for a basic local run.
- The default startup command is `python app.py`.
- Review the application's settings in the source before changing its host, port, database location, or debug behavior.
- Before deploying publicly, set a strong secret key if the application uses Flask sessions, disable debug mode, and run behind a production WSGI server. Do not expose Flask's development server to the public internet.

If a future version introduces environment-based configuration, document each required variable, what it controls, its default (if any), and whether it contains a secret.

## Contributing

Bug reports, ideas, and pull requests are welcome. For substantial changes, open an issue first so the proposed change can be discussed. Please include clear reproduction steps for bug reports and screenshots for user-interface changes.

## License

This README does not assign a license. Add the project's selected license as a `LICENSE` file and replace this section with the license name and a link before inviting reuse or redistribution. If no license file is present, users should not assume permission to copy, modify, or redistribute the code.

## Project

- **Repository:** [Khaiyen-Salaria/Amiyen](https://github.com/Khaiyen-Salaria/Amiyen)
- **Releases:** [Amiyen releases](https://github.com/Khaiyen-Salaria/Amiyen/releases)
- **Status:** Beta
