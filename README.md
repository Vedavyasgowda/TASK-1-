 # Task 1 – Data Cleaning & Preprocessing
For this task, I worked with the Medical Appointment No-Shows dataset. The goal was to clean and prepare the raw data by fixing issues like missing values, duplicates, inconsistent formatting, and incorrect data types.

# Steps I Followed:
Renamed all columns to lowercase with underscores (e.g., ScheduledDay → scheduled_day) for better readability and consistency.

Removed duplicate rows to ensure there’s no repetition of patient records.

Checked for missing values – luckily, this dataset didn’t have any major null issues.

Standardized categorical values:

Changed gender entries to 'Male' and 'Female'

Cleaned the no_show column to have clear 'Yes' or 'No' values

Converted date columns like scheduled_day and appointment_day into proper datetime format.

Filtered invalid ages – removed any rows where age was negative.

Fixed data types for columns like age to ensure everything was properly formatted.

# Final Output
The cleaned dataset is saved as cleaned_medical_appointments.csv and is now ready for analysis, visualization, or modeling.

This exercise helped me understand how important proper preprocessing is before jumping into any kind of data science work. Even a “clean-looking” dataset can have hidden issues!
