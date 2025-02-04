# Measures of Central Tendency

## 1. Arithmetic Mean
**Formula:**
$$
\mu = \frac{\sum X}{N}
$$

- **Where:** 
  - \( \mu \) = Population mean
  - \( \sum X \) = Sum of all values
  - \( N \) = Number of values

**Example:**
For the data set \( 5, 10, 15, 20 \):
$$
\mu = \frac{5 + 10 + 15 + 20}{4} = \frac{50}{4} = 12.5
$$


## 2. Weighted Mean
**Formula:**
$$
\bar{x}_w = \frac{\sum (x_i w_i)}{\sum w_i}
$$

- **Where:** 
  - \( x_i \) = Data values
  - \( w_i \) = Weights assigned to each data value

**Example:**
Midterm score (83) with weight (0.4) and final exam score (95) with weight (0.6):
$$
\bar{x}_w = (83 \times 0.4) + (95 \times 0.6) = 33.2 + 57 = 90.2
$$


## 3. Median
**Formula:**
- If \( n \) is odd: 
$$
\text{Median} = X_{\left(\frac{n+1}{2}\right)}
$$

- If \( n \) is even:
$$
\text{Median} = \frac{X_{\left(\frac{n}{2}\right)} + X_{\left(\frac{n}{2}+1\right)}}{2}
$$


**Example:**
For the ordered set \( [3, 4, 5, 7, 8] \):
- Odd count (5): Median is the middle value (5).
For \( [3, 4, 5, 6] \):
- Even count (4): Median is 
$$ 
\frac{4 + 5}{2} = 4.5 
$$
.

## 4. Mode
**Definition:** The most frequently occurring value in a data set.

**Example:** In the set \( [1, 2, 2, 3] \), the mode is \( 2 \).

## 5. Percentiles
**Formula:**
$$
P_k = \frac{k(n+1)}{100}
$$

- **Where:** 
   - \( P_k \) is the k-th percentile,
   - \( n \) is the number of data points.

**Example:**
For a data set of size \( n=8 \), to find the 30th percentile:
$$
P_{30} = \frac{30(8+1)}{100} = 2.7
$$

The value at position \( i=3 \) in the ordered array gives the percentile.

# Measures of Dispersion

## 1. Range
**Formula:**
$$
\text{Range} = X_{\text{max}} - X_{\text{min}}
$$


**Example:**
For the data set \( [3, 7, 8, 12] \):
$$
\text{Range} = 12 - 3 = 9
$$


## 2. Variance
**Population Variance Formula:**
$$
\sigma^2 = \frac{\sum (X_i - \mu)^2}{N}
$$


**Sample Variance Formula:**
$$
s^2 = \frac{\sum (X_i - \bar{x})^2}{n-1}
$$


**Example for Population Variance:**
For data set \( [5, 10, 15] \):
1. Calculate mean (\(10\)).
2. Calculate variance:
   $$
   \sigma^2 = \frac{(5-10)^2 + (10-10)^2 + (15-10)^2}{3} = \frac{25 + 0 + 25}{3} = \frac{50}{3} ≈16.67
   $$

## 3. Standard Deviation
**Formula:**
- For population:
$$
\sigma = \sqrt{\sigma^2}
$$


- For sample:
$$
s = \sqrt{s^2}
$$


**Example:**
Continuing from the variance example:
Population standard deviation:
$$
\sigma ≈ √16.67 ≈ 4.08
$$


## Conclusion
These formulas provide a comprehensive toolkit for analyzing data through measures of central tendency and dispersion. Each formula can be applied based on the type of data and specific analysis requirements you encounter in various fields such as statistics, finance, and research.
