# Dynamic Banking System Simulation Data

This repository contains data from a dynamic, multi-agent simulation of a banking system with central bank involvement. The data includes multiple banks with various financial parameters, modeling their capital, risk tolerance, deposit fluctuations, interbank lending activities, and liquidity management. This dataset helps illustrate the impact of network structures and central bank policies on the resilience and systemic risk of the banking system.

## Data Overview

The data simulates several aspects of a banking system where banks actively manage portfolios, take interbank loans, and interact with central bank facilities. Each bank’s behavior is influenced by factors such as risk tolerance, initial capital, and fluctuations in deposit levels.

### Columns

- **bank_id**: Unique identifier for each bank.
- **initial_capital**: The starting capital for the bank.
- **risk_tolerance**: A measure of the bank's risk appetite; higher values indicate greater willingness to take risks.
- **deposit_fluctuation**: Represents the fluctuations in deposits, simulating unpredictable deposit flows.
- **optimal_risky_fraction**: The portion of capital optimally allocated to risky investments.
- **utility**: Calculated utility value based on the bank's investment and liquidity preferences.
- **deposits**: Total deposits held by the bank.
- **bank_capital**: The current capital level of the bank.
- **interbank_loans**: Net amount of interbank loans; positive values indicate lending, negative values indicate borrowing.
- **central_bank_loans**: Amount borrowed from the central bank.
- **risky_investments**: The value of assets allocated to risky investments.
- **liquidity**: Bank’s liquidity level, important for meeting sudden withdrawals and demands.
