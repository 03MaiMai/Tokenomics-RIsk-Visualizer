Tokenomics Risk Visualizer A RugCheck bounty tool to visualize tokenomics, profile wallet risks, and alert on suspicious patterns. Built with real Solscan data, it offers interactive charts (wallet distribution, price impact, liquidity, history), detailed risk scoring, and live alerts for insider dumps and liquidity shifts. Designed to empower users to spot rug pulls before they strike. 

Setup 
1. Open index.html in a browser. 
2. Enter a Solana token address (e.g., CKfatsPMUf8SkiURsDXs7eK6GWb4Jsd6UDbs7twMCWxo) or manual %s.

Features 
1. Real-time data from Solscan (supply, holders). 

2. Interactive charts for wallet distribution, price impact, liquidity, and history
 - Wallet Distribution Pie Chart: Visualizes the percentage distribution of token holdings across different wallets.
 - Price Impact Over Time Line Chart: Tracks historical price impact percentages to identify volatility and potential manipulation.
 - Liquidity Timeline: Monitors changes in liquidity percentage over time to detect sudden withdrawals.
3.  Wallet History: Tracks historical changes in wallet percentages to identify unusual movements.

4. Calculates a risk score based on various factors such as wallet concentration, liquidity levels, and burn rates.

5. Data export/import functionality

6. Customizable Parameters: Enables users to input custom wallet percentages and other parameters for manual analysis.

Technical Details
- Built with: HTML5, CSS3, JavaScript, Chart.js
- Data Sources: Solscan API for real-time token and holder data.
- Responsive Design: Works on both desktop and mobile devices.

