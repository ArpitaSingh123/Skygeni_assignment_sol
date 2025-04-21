# Data Analysis and Visualization for Client Subscription and Payment Insights

This project involves analyzing and visualizing client subscription data, payment information, and industry details to extract key insights. The data consists of various aspects like subscription renewals, payment history, inflation rates at the time of renewals, and client industry breakdowns.

## Data Files:
- **`subscription_information.csv`**: Contains details about client subscriptions, including renewal status and end dates.
- **`payment_information.csv`**: Contains payment amounts and payment dates for clients.
- **`industry_client_details.csv`**: Contains client information along with their associated industry (e.g., Finance Lending, Blockchain).
- **`finanical_information.csv`**: Contains inflation rates and financial data tied to subscription renewal dates.

## Key Features:
1. **Q1: Number of Finance Lending & Blockchain Clients**  
   Identifies the number of clients in the Finance Lending and Blockchain industries, followed by a visualization of the client distribution.
   ![image](https://github.com/user-attachments/assets/39f13bb1-131f-40cf-8ef0-d79206844df1)


3. **Q2: Industry with Highest Renewal Rate**  
   Analyzes subscription renewal rates by industry and visualizes the industry with the highest renewal rate.
   ![image](https://github.com/user-attachments/assets/e0ab1831-7979-4447-8558-63384fed4215)


5. **Q3: Average Inflation Rate at Time of Renewal**  
   Calculates and visualizes the average inflation rate for subscriptions renewed during a specific period.
   ![image](https://github.com/user-attachments/assets/b92bae77-af41-4b7d-86ca-0e5f14f7ddb2)

   

7. **Q4: Median Amount Paid Per Year**  
   Computes the median amount paid by clients each year and visualizes the data to understand yearly payment trends.
   ![image](https://github.com/user-attachments/assets/fdbdcea8-8580-42b7-8e21-4a6490a4ace5)


## Technologies Used:
- **Python**: For data manipulation and analysis using Pandas.
- **Matplotlib**: For data visualization (bar charts, histograms, etc.).
- **Google Colab**: Used for executing and sharing the code.

## Project Structure:
- **`data_analysis.py`**: Contains the code for performing the analysis (e.g., calculating renewal rates, inflation rates, etc.).
- **`visualizations/`**: Folder to store visualizations generated from the analysis.
- **`requirements.txt`**: Lists the Python libraries needed to run the project.

## How to Run:
1. Clone this repository.
2. Install the necessary Python libraries using the following command:
3. Place the CSV files (`subscription_information.csv`, `payment_information.csv`, `industry_client_details.csv`, `finanical_information.csv`) in the project directory.
4. Run `data_analysis.py` to perform the analysis and generate the visualizations.

## Output:
- The analysis produces insights about subscription renewals, industry comparisons, inflation rates, and payment trends.
- Visualizations will be saved in the `visualizations/` folder.

## Contributions:
Feel free to fork this repository, submit issues, and create pull requests for improvements.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
