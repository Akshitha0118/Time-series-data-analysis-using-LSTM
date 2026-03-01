# Time-series-data-analysis-using-LSTM

I recently worked through a detailed hands-on notebook on Time Series Analysis using LSTM, focused on real-world household power consumption data (4 years of minute-level measurements!).

Here’s what this project covered step-by-step:

🔹 Data preprocessing
• Handling missing values using statistical imputation
• Parsing Date & Time into a proper datetime index
• Resampling data (Hourly, Daily, Monthly)
• Understanding how resampling affects correlations

🔹 Exploratory Data Analysis
• Daily & monthly aggregation visualizations
• Correlation heatmaps (before & after resampling)
• Feature relationship analysis (e.g., Global_active_power vs Global_intensity)

🔹 Feature Engineering for Time Series
• Converting time series into supervised learning format
• Scaling features using MinMaxScaler
• Avoiding data leakage with proper train-test split

🔹 LSTM Model Architecture
• 1 LSTM layer (100 neurons)
• Dropout (20%) to prevent overfitting
• Dense output layer
• Adam optimizer + MSE loss
• Hourly resampled data for faster training

📊 Result:
Even a simple LSTM architecture was able to capture meaningful patterns in energy consumption trends.

💡 Key Takeaways:
• Resampling significantly changes feature correlations
• Proper scaling is critical for LSTM performance
• Framing time series as supervised learning is essential
• Simple architectures can still produce strong baseline results
