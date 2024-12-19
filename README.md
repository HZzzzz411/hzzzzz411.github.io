# MTH113 Notes

# **The role of statistics and the Data Analysis Process**
## Important Definition
1.**Population**：entire collection of sth which information is desired

2.**Sample**：subset of the population, selected for study

3.**Descriptive statistics**：a branch of statistics that includes methods for **organizing** and **summarizing** data.

4.**Inferential statistics**：a branch of statistics that involves **generalizing** from a sample to the population 

## **Types of Data**：
1.**Univariate Dataset**: observations on a single characteristic.

2.**Bivariate Dataset**:two characteristics.

3.**Multivariate Dataset**: multiple characteristics.

4.**Categorical Dataset**: **qualitative**. categorical responses.
   
5.**Numerical Dataset**: **quantitative**. each observation is a number.

### Categorical Data：Frequency Distribution and Bar Chart
  - **Frequency distribution table**: A common way to present categorical data 
  - **Frequency**: The **number of times** a category appears in the dataset.
    
  - **Relative Frequency**: The proportion of observations that belong to a particular category.
    
     $$\boxed{ Relative Frequency = \frac{Frequency}{number of obervations in the data set}}$$
    
- **Bar Chart**: A graph of a frequency distribution for **categorical data**.The **area** of each bar **is proportional** to the corresponding frequency or relative frequency.

### Numerical Data ：Dotplots
- **Discrete Numerical Variable**: discrete data , possible values correspond to **isolated points** on the number line.
  
- **Continuous Numerical Variable**:  continuous data , possible values forms an **entire interval** on the number line.
  
- **Dotplots**：Describe the frequency distribution for **numerical data**, suitable for small numerical datasets.
  

# Collecting Data Sensibly


### Observational Study
- **Observing** data from a sample to gain insight into population characteristics.

### Variables in a Study
- **Response Variable**: The focus of the study or experiment. **Dependent Variable**
- **Explanatory Variable**: Explains changes in the response variable. **Independent Variable**

A study is interested in how variability in x affects y, **x** is **Explanatory Variable**, **y** is **Response Variable**

### Experiments
- **Observing the behavior** of response variables when **explanatory variables are manipulated.**
- **Experimental Conditions**: treatments

  Both observational studies and experiments can be used to compare groups, but **only** in an **experiment** the researcher can **controls** who is in which group

### Cause-and-Effect
- Difficult to draw clear cause-and-effect conclusions in observational studies due to **confounding variables**.
- **well-designed Experiments** can provide evidence for cause-and-effect relationships.

### Sampling and Bias
- **Selection Bias**: **Undercoverage**.Systematic exclusion of parts of the population.
- **Measurement or Response Bias**: Method of observation producing systematically different values.(machine used for measurements is not calibrated properly / Survey questions biased, leads you to a specific answer...)
- **Non-response Bias**: when responses are not obtained from all individuals in sample.

### Random Sampling
- **Simple Random Sample**: **Every possible sample of size n** has an **equal chance** of being selected.(n denotes sample size).is a sampling method **free of selection bias.**
- **Sampling without Replacement**: Once selected, an individual cannot be selected again.
- **Sampling with Replacement**: Individuals can be selected more than once.

### Sample Size n
- Small sample sizes can **accurately reflect** the population when **randomly selected**.

### Other Sampling Methods
- **Stratified Random Sampling**: Sampling from **non-overlapping** subgroups(strata).
- **Cluster Sampling**: Selecting entire clusters and including all individuals within them.
- **Systematic Sampling**: Selecting every k-th individual in a sequence after a random start.
- **Convenience Sampling**: Selecting individuals based on convenience, which can introduce bias.

# **Graphical Methods for Describing Data**

## **Displaying Categorical Data**
### Comparative Bar Charts
- Used to **visually compare** two or more groups.
- Constructed **using the same set** of horizontal and vertical axes(x,y-axis).
- use **relative frequency** rather than frequency(dealing with **different sample sizes**)

### Pie Charts
- Summarize categorical data by representing categories as **slices of a pie**.
- The size of each slice is **proportional to** the **frequency or relative frequency**.
- **Size**：angle of slice, $Angle = 360^\circ \times relative ~\ frequency$
- **Most useful for illustrating proportions** of the whole data set for various categories. **Not suitable for comparing** frequencies between groups.

### Segmented Bar Charts
- **Similar to pie charts**(illustrating proportions) but easier to draw by hand.
- Useful for comparing cumulative frequency distributions of ordered categories.
<div align="center">
    <img src="https://github.com/user-attachments/assets/746fa86f-8ffa-48be-9a7a-0418ad79ed6a" width=300 /">
</div>

- Useful to compare **cumulative frequency** distributions (for **orderd** categories)，cumulative frequencies can be easily read

## Displaying Numerical Data
### Stem-and-Leaf Displays
- An effective way to summarize numerical data.
- Each number is split into a **stem (beginning digits)** and a **leaf (final digits)**.
- easy to spot **outliers**(unusually small or large data value)
- Useful for **small to moderate** data sets.
- **Comparative Stem-and-Leaf Displays**: one group's leaves are listed to the right of the stem values and second group's are listed to the left

<div align="center">
    <img src="https://github.com/user-attachments/assets/8a535b29-502b-475b-a822-fcccf25c633f" width=400 /">
</div>

### Frequency Distributions and Histograms
- **Frequency Distribution**: A **table** showing the frequency of each value or range of values.
- **Histogram**: A graph of the frequency distribution for numerical data.(similar to bar chart but classes are contiguous, **no gaps** between bars.)
  - **Discrete Numerical Data**: Bars represent individual values or grouped intervals.
  - **Continuous Numerical Data**: Data is grouped into intervals (**class intervals**).
when class intervals are **not of equal width**,  the height of the each rectangle is given by its **density** over that interval.**(the area of the bars must be proportional to the frequency)**

<div align="center">
    <img src="https://github.com/user-attachments/assets/1c7dfd40-dac3-437b-a078-5257cd519ff8" width=500 /">
</div>

### Histogram Shapes
- **Unimodal**: A single peak.
- **Bimodal**: Two peaks.
- **Multimodal**: More than two peaks.
- **Symmetric**: Equal tails.
- **Skewed**: Unequal tails
  
     **(a).positively/right skewed**: upper(right) tail of the histogram stretches out much farther than the lower(left) tail.
  
     **(b).negatively skewed**: lower tail of the histogram stretches out much farther than the upper tail.  
  
<div align="center">
    <img src="https://github.com/user-attachments/assets/a3874ba8-7888-4c70-8e0b-865d64973a15" width=500 /">
</div>

- **Normal:** bell shaped distributions

### Cumulative Relative Frequency
- Shows the proportion of observations **falling below a specified value**.
- Cumulative relative frequency plot: pairs (upper endpoint of interval, cumulative relative frequency)

## Displaying Bivariate Numerical Data
### Scatter Plots
- Used to **detect patterns and outliers** in bivariate data.
- Each observation is a pair of numbers (x, y).
- Aspect Ratio: Plots should be almost **square**.

### Time Series Plots
- Used to observe trends over time.
- Observations are plotted with **time on the horizontal axis**.
- Multiple time series can be plotted together for comparison.
