README
BY-AYUSHI SINGH(B22CH005)

Analysis of Filtering Type Using Convolution and Correlation
The objective of this analysis is to determine the type of filtering applied to an input signal x(t) by comparing the filtered outputs with the given output signal y(t) using convolution and correlation.
Usage Explanation:
Functions 
The code defines functions to implement low-pass, high-pass, and band-pass filters using convolution. It also includes a function to calculate the correlation between two signals.
Loading Signals
 The code loads input and given output signals from files and plots them for visualization.
Filter Application
 Filters are applied to the input signal using the specified cutoff frequencies and sampling rate.
Correlation Calculation
The code calculates the correlation between the filtered signals and the given output signal, normalizes the correlation values, and calculates the average normalized correlation for each filter.
Best Filter Selection
It determines the best filter based on the highest average normalized correlation.

 Dependencies
numpy: Used for numerical operations like array manipulation and convolution.
matplotlib: Used for plotting the signals and correlation values.

 Report
Input Signal: The input signal (`x(t)`) is plotted to visualize the original signal.
Given Output Signal: The given output signal (`y(t)`) is plotted to visualize the desired output.
Output Signals :The output signals of the low-pass, high-pass, and band-pass filters are plotted along with the given output signal for comparison.
Normalized Correlation: The normalized correlation values of each filter with the given output signal are plotted to analyze the similarity between the filtered output and the desired output.
Best Filter Output: The output of the best filter (with the highest average normalized correlation) is plotted against the given output signal.
Report can be found in the report.pdf file attached .

 Key Findings:
- The code helps in analyzing the effectiveness of different filters (low-pass, high-pass, and band-pass) in approximating a given output signal from an input signal.
- It provides insights into which filter performs best in terms of correlation with the given output signal.
- The best filter can be chosen based on the highest average normalized correlation value, which indicates the closest match to the desired output.


README
BY-AYUSHI SINGH(B22CH005)

Analysis of Filtering Type Using Convolution and Correlation
The objective of this analysis is to determine the type of filtering applied to an input signal x(t) by comparing the filtered outputs with the given output signal y(t) using convolution and correlation.
Usage Explanation:
Functions 
The code defines functions to implement low-pass, high-pass, and band-pass filters using convolution. It also includes a function to calculate the correlation between two signals.
Loading Signals
 The code loads input and given output signals from files and plots them for visualization.
Filter Application
 Filters are applied to the input signal using the specified cutoff frequencies and sampling rate.
Correlation Calculation
The code calculates the correlation between the filtered signals and the given output signal, normalizes the correlation values, and calculates the average normalized correlation for each filter.
Best Filter Selection
It determines the best filter based on the highest average normalized correlation.

 Dependencies
numpy: Used for numerical operations like array manipulation and convolution.
matplotlib: Used for plotting the signals and correlation values.

 Report
Input Signal: The input signal (`x(t)`) is plotted to visualize the original signal.
Given Output Signal: The given output signal (`y(t)`) is plotted to visualize the desired output.
Output Signals :The output signals of the low-pass, high-pass, and band-pass filters are plotted along with the given output signal for comparison.
Normalized Correlation: The normalized correlation values of each filter with the given output signal are plotted to analyze the similarity between the filtered output and the desired output.
Best Filter Output: The output of the best filter (with the highest average normalized correlation) is plotted against the given output signal.
Report can be found in the report.pdf file attached .

 Key Findings:
- The code helps in analyzing the effectiveness of different filters (low-pass, high-pass, and band-pass) in approximating a given output signal from an input signal.
- It provides insights into which filter performs best in terms of correlation with the given output signal.
- The best filter can be chosen based on the highest average normalized correlation value, which indicates the closest match to the desired output.


