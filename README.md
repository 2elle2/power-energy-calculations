## Power Sampling Rate

<b>Central Question</b>: To what extent does calculated energy differ based on varying levels of power sampling frequency for a data center server? 

<b>Process</b>: Compare "true" energy against the energy calculated at different sampling rates. The process of calculating energy from subsets of the full power sample time series can be repeated for different sampling frequencies (e.g. 5s, 10s, 30s, 1 min, 5 min, 1 hr) to compare the accuracy of the calculated energy to the "true" energy value.

<b>Power vs. Energy</b>:
- Power is sampled at regular intervals (e.g. 1s)
- Energy is calculated by multiplying each power sample by the time between samples and summing the products