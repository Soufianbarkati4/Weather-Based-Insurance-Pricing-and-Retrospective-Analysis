# Weather-Based-Insurance-Pricing-and-Retrospective-Analysis
ActuarIA SOFTWARE Weather-Based Insurance Pricing and Retrospective Analysis

*Project Overview :*

This Django-based project enables insurance providers to offer tailored meteorological insurance, factoring in rainfall data to assess and calculate premiums. The application allows users to simulate their potential gains or losses with and without insurance across past years, based on historical precipitation data retrieved from Infoclimat. Key features include personalized quotes and retrospective analysis with visualizations, making it a valuable tool for weather risk management in business.

*Features :*

Real-Time Insurance Quote Generation: Calculates premiums based on chosen parameters such as daily turnover, rainfall thresholds, and location.
Historical Retrospective Analysis: Compares annual gains/losses for users with and without insurance using historical data.
Data Visualization: Graphical representation of annual turnover with insurance, without insurance, and cumulative benefits/losses.
*Project Structure :*
- Views and Templates: The views.py file contains methods for data retrieval, premium calculation, and rendering visual results, which are displayed on index.html, contact.html, and other pages.
- Static Assets: CSS and JavaScript for styling and functionality, ensuring a clear and interactive user experience.
- Backend Logic: Organized code to fetch, process, and render precipitation data for selected cities, using real-time data from Infoclimat.

*Key Components :*
  1. Insurance Quote Generation
User Input: Allows users to input city, start date, daily turnover, rainfall threshold, and fixed daily costs.
Calculation: The app fetches real-time rainfall data, calculates the daily premium, and displays the estimated insurance cost.
  2. Retrospective Analysis
Data Collection: Uses historical precipitation data to simulate the impact on revenue with and without insurance.
Visualization: Provides line charts showing annual turnover and benefits/losses for easy comparison.
  3. Data Visualizations
Annual turnover comparison (insured vs. non-insured).
Net benefits/losses from weather-based insurance.
  4. Usage
Quotes: Enter required details under the "Get a Quote" section for real-time insurance pricing.
Analysis: Access retrospective analysis graphs for informed decision-making on insurance impact over the years.
Additional Information
Refer to the user guide included in the repository for further installation, troubleshooting, and in-depth project explanations.
