# step_sleep_analysis
Forked from https://jovian.ai/sourabhrohilla8399/sleep-analysis/v/3/files?filename=sleep_data_analysis.ipynb

# Note:  
- converting totalSleep to HH:MM:  
  `merged_df['totalSleep_hhmm']=pd.to_datetime(merged_df.totalSleep, unit='m').dt.strftime('%H:%M')`
