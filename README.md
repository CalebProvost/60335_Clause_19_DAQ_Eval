# IEC 60335 clause 19 temperature evaluation

### Determines the delta 2% of change to decide the equilibrium state for units whose operations are under 30 minutes.


This program automatically determines the cycle start points and end points by looking for a negative number indicator.

Upon determining the cycles, it then evaluates the mean and max of the cycles and creates a new table to display those results.

The stylized results are to show if the values are less than 2% delta than the previous cycle and the max throughout the entire data (last two are recommended to not be max per Intertek).

Red text represents the values which are above 2% delta compared to the previous cycle. Steady state conditions, or "equilibrium", is defined when the temperatures' delta is not above 2% after 20 minutes of operation.

Highlighted backgrounds are to notate the values which are the max value. Intertek recommends that two cycles to not be the max to be considered in equilibrium. 
