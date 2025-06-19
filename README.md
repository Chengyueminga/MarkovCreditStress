# MarkovCreditStress

**Simulating Credit Risk Transitions under Stress: A Markov Approach**

This project simulates corporate credit rating migration and capital impact under stress scenarios using a **discrete-time Markov model**. It is designed to illustrate how credit quality deteriorates in a macroeconomic downturn and how this affects **downgrafe rates, default probabilities, and regulatory capital requirements**.

## Project Overview

- **Goal**: Model credit rating migration for a portofolio of 500 synthetic companies over 1 10-year horizon.
- **Methodology**: Uses **Markov transition matrices** to simulate rating paths under:
    - A **baseline matrix** (stable economy)
    - A **stress matrix** (economic downturn with elevated downgrade/default risk)
- **Output**: Visual and statistical comaprisons of:
    - Rating distributions over time
    - Cumulative default rates
    - Capital requirements under Basel-style assumptions

## Key Components

- `Section 2`: Construction of baseline and stress transition matrices  
- `Section 3`: Stress scenario impact visualization (rating paths, downgrade counts, default frequencies)
- `Section 4`: Estimation of regulatory capital needs using:

  - Simulated default rates
  - Assumed **Exposure at Default (EAD)** and **Risk Weights**
  - Capital ratio approximations

## Sample Visualizations

- Heatmaps of transition matrices  
- Bar charts of rating downgrades and defaults  
- Year-by-year capital impact comparisons

>  Note: All simulations are based on synthetic data for **educational and regulatory modeling purposes**.

##  Technical Details

- Language: Python (Jupyter Notebook)  
- Dependencies: `numpy`, `pandas`, `matplotlib`, `seaborn`  
- Simulation Type: Monte Carlo path-based transitions with yearly snapshots

##  Regulatory Context

This simulation mirrors **Basel III internal model frameworks**, where capital requirements depend on default probabilities and credit migration. The stress matrix is designed to mimic recessionary conditions, offering insight into **procyclicality and capital buffer needs** during downturns.

## Use Cases

- Regulatory capital planning under stress  
- Teaching and academic illustration of credit rating models  
- Scenario analysis for risk management teams

## References

The methodology and design of this simulation are informed by the following references:

1. Jarrow, R. A., Lando, D., & Turnbull, S. M. (1997). A Markov model for the term structure of credit risk spreads. *Review of Financial Studies*, 10(2), 481–523.  
2. Basel Committee on Banking Supervision (BCBS). (2005). *International Convergence of Capital Measurement and Capital Standards*. Bank for International Settlements.  
3. Löffler, G., & Posch, P. N. (2011). *Credit Risk Modeling using Excel and VBA*. Wiley Finance.  
4. Hull, J. C. (2018). *Risk Management and Financial Institutions*. Wiley.  

> For educational use only. If you use or adapt this project, please cite the original references where appropriate.

## Author

**Yueming Cheng** – [LinkedIn](https://www.linkedin.com/in/yuemingcheng/) 
*Risk Professional | Financial Modeler | Basel & Credit Risk Enthusiast*

## License

This project is licensed under the [MIT License](./LICENSE).

## Disclaimer

This project is provided under the [MIT License](./LICENSE) and is intended for educational use only. All simulations use synthetic data and simplified assumptions.

The views expressed are solely those of the author and do not represent the views of any current or former employer.
