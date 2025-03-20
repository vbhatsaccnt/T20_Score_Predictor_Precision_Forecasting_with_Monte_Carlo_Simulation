# T20 Score Predictor: Precision Forecasting with Monte Carlo Simulation
Role: Sole Developer | Tools: Python (NumPy), Google Sheets, Apps Script | Date: March 2025

# Overview

Cricket’s T20 format is a whirlwind of unpredictability—strike rates spike, wickets fall, and scores defy expectation. I engineered the T20 Score Predictor, a Monte Carlo-based tool that harnesses real-time match data to forecast final scores with striking accuracy. In a real IPL test, it predicted 213 runs against an actual 214 (and nailed 170 at Over 16), outpacing ESPNcricinfo’s 226 by a wide margin. This project showcases my ability to blend probabilistic modeling, innovative metrics, and user-centric design into a practical solution.

# Technical Highlights

  Core Model: Developed a Monte Carlo simulation (1,000 iterations) with a custom volatility formula:
  
  volatility = (((strike_rate1 / 100) * boundary_pct1) + ((strike_rate2 / 100) * boundary_pct2)) / (2 * wickets))
  score = (1 + np.random.normal(0, volatility)) * run_rate * overs
  
  This captures T20’s chaos using live inputs—runs, strike rates, boundary percentages, and wickets.
  
  Evolution: Iterated from Python/NumPy in Google Colab to a no-code Google Sheets interface with Apps Script, adapting to deployment challenges.
  Validation: Achieved a 1-run error vs. Cricinfo’s 12, proving superior predictive power.

# Skills Demonstrated

  Data Science: Designed and implemented a probabilistic model to handle real-time variability, outperforming industry benchmarks.
  
  Problem-Solving: Overcame Streamlit/ngrok compatibility hurdles in Colab by pivoting to a robust Apps Script solution.
  
  Software Development: Engineered a seamless transition from code-heavy Python to a no-code platform, enhancing accessibility.
  
  Analytical Thinking: Crafted a bespoke volatility metric that balances batter aggression and match context.
  
  User Experience: Delivered an intuitive interface—input data, click a button, get predictions—accessible to non-technical users.

# Impact

  Outperformed a leading cricket analytics platform in a live scenario, showcasing real-world applicability.
  Transformed a complex statistical concept into a practical tool, bridging data science and sports analytics.

# Links

   Live Demo (https://docs.google.com/spreadsheets/d/1OeqveijZJOnEypWVt8KfaVKycJhYmFHHPcj57v2vuEQ/edit?gid=0#gid=0)

# Key Takeaway

This project isn’t just about cricket—it’s a testament to my ability to tackle uncertainty with data, innovate under constraints, and deliver results that resonate. From concept to execution, it’s a slam dunk of technical skill and creative flair.


  
