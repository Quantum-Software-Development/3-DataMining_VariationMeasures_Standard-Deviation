
<br>

**\[[🇧🇷 Português](README.pt_BR.md)\] \[**[🇺🇸 English](README.md)**\]**


<br><br>



# <p align="center">  3- [Data Mining]() / [Statistic Review - Variation Measures and Standard Deviation]()



<!-- =======================================END DEFAULT HEADER ===========================================  -->


<br><br>


[**Institution:**]() Pontifical Catholic University of São Paulo (PUC-SP)  
[**School:**]() Faculty of Interdisciplinary Studies  
[**Program:**]() Humanistic AI and Data Science
[**Semester:**]() 2nd Semester 2025  
Professor:  [***Professor Doctor in Mathematics Daniel Rodrigues da Silva***](https://www.linkedin.com/in/daniel-rodrigues-048654a5/)

<br><br>

#### <p align="center"> [![Sponsor Quantum Software Development](https://img.shields.io/badge/Sponsor-Quantum%20Software%20Development-brightgreen?logo=GitHub)](https://github.com/sponsors/Quantum-Software-Development)


<br><br>

<!--Confidentiality statement -->

#

<br><br><br>

> [!IMPORTANT]
> 
> ⚠️ Heads Up
>
> * Projects and deliverables may be made [publicly available]() whenever possible.
> * The course emphasizes [**practical, hands-on experience**]() with real datasets to simulate professional consulting scenarios in the fields of **Data Analysis and Data Mining** for partner organizations and institutions affiliated with the university.
> * All activities comply with the [**academic and ethical guidelines of PUC-SP**]().
> * Any content not authorized for public disclosure will remain [**confidential**]() and securely stored in [private repositories]().  
>


<br><br>

#

<!--END-->




<br><br><br><br>



<!-- PUC HEADER GIF
<p align="center">
  <img src="https://github.com/user-attachments/assets/0d6324da-9468-455e-b8d1-2cce8bb63b06" />
-->


<!-- video presentation -->


##### 🎶 Prelude Suite no.1 (J. S. Bach) - [Sound Design Remix]()

https://github.com/user-attachments/assets/4ccd316b-74a1-4bae-9bc7-1c705be80498

####  📺 For better resolution, watch the video on [YouTube.](https://youtu.be/_ytC6S4oDbM)


<br><br>


> [!TIP]
> 
>  This repository is a review of the Statistics course from the undergraduate program Humanities, AI and Data Science at PUC-SP.
>
>   ### ☞ **Access Data Mining [Main Repository](https://github.com/Quantum-Software-Development/1-Main_DataMining_Repository)**
> 
>  If you’d like to explore the full materials from the 1st year (not only the review), you can visit the complete repository [here](https://github.com/FabianaCampanari/PracticalStats-PUCSP-2024).
>
>



<!-- =======================================END DEFAULT HEADER ===========================================  -->


<br><br>




## 1. What is Variation?

**Variation** is the difference between the maximum and minimum entries in a quantitative data set.

<br><br>


$$
\Huge
\text{Variation} = \text{Maximum Value} - \text{Minimum Value}
$$


<br><br>


- The data must be quantitative (numerical).



<br>


**Example: Calculating Variation**

A company hired 10 graduates. Their starting salaries (in thousand dollars):


<br>

```
41, 38, 39, 45, 47, 41, 44, 41, 37, 42
```

Ordered data:

<br>

```
37, 38, 39, 41, 41, 41, 42, 44, 45, 47
```

- Minimum: 37  
- Maximum: 47


<br>


\[
\text{Variation} = 47 - 37 = 10
\]



<br><br>


## 2. Deviation, Variance, and Standard Deviation

<br>

### 2.1. Deviation

**Deviation** for a value $x$ from the data set is:

- Population: $x - \mu$
- Sample: $x - \bar{x}$


<br><br>


### 2.2. Variance and Standard Deviation – Population

**Formulas:**

<br>

\[
\mu = \frac{\sum x}{N}
\]
\[
\sigma^2 = \frac{\sum (x - \mu)^2}{N}
\]
\[
\sigma = \sqrt{\frac{\sum (x - \mu)^2}{N}}
\]

<br>

where:
- $\mu$ is the population mean
- $N$ is the population size
- $\sigma^2$ is the variance
- $\sigma$ is the standard deviation


<br><br>


### Population Example

<br>

Salaries: `41, 38, 39, 45, 47, 41, 44, 41, 37, 42`  
Sum: $415$  
$\mu = 415 / 10 = 41.5$

<br>


| Salary ($x$) | $x - \mu$ | $(x - \mu)^2$ |
|--------------|-----------|--------------|
| 41           | -0.5      | 0.25         |
| 38           | -3.5      | 12.25        |
| 39           | -2.5      | 6.25         |
| 45           | 3.5       | 12.25        |
| 47           | 5.5       | 30.25        |
| 41           | -0.5      | 0.25         |
| 44           | 2.5       | 6.25         |
| 41           | -0.5      | 0.25         |
| 37           | -4.5      | 20.25        |
| 42           | 0.5       | 0.25         |
| **Total**    |           | **88.5**     |


<br>

\[
\sigma^2 = \frac{88.5}{10} = 8.85
\]
\[
\sigma = \sqrt{8.85} \approx 3.0
\]

> The population standard deviation is about $3.0$ (\$3,000).


<br><br>


### 2.3. Variance and Standard Deviation – Sample

**Formulas:**

\[
\bar{x} = \frac{\sum x}{n}
\]
\[
s^2 = \frac{\sum (x - \bar{x})^2}{n - 1}
\]
\[
s = \sqrt{s^2}
\]

where:
- $\bar{x}$ is the sample mean
- $n$ is the sample size
- $s^2$ is the sample variance
- $s$ is the sample standard deviation

---

#### Step-by-step Table (Sample Standard Deviation)

| Salary ($x$) | $x - \bar{x}$ | $(x - \bar{x})^2$ |
|--------------|---------------|-------------------|
| 41           | -0.5          | 0.25              |
| 38           | -3.5          | 12.25             |
| 39           | -2.5          | 6.25              |
| 45           | 3.5           | 12.25             |
| 47           | 5.5           | 30.25             |
| 41           | -0.5          | 0.25              |
| 44           | 2.5           | 6.25              |
| 41           | -0.5          | 0.25              |
| 37           | -4.5          | 20.25             |
| 42           | 0.5           | 0.25              |
| **Total**    |               | **88.5**          |

\[
s^2 = \frac{88.5}{10-1} = \frac{88.5}{9} = 9.83
\]
\[
s = \sqrt{9.83} \approx 3.1
\]

> The sample standard deviation is about $3.1$ (\$3,100).

---

## 3. Standard Deviation for Grouped Data (Frequency Distribution)

Formula for sample standard deviation from a frequency distribution (using midpoints $x$):

\[
s = \sqrt{\frac{\sum (x - \bar{x})^2 f}{n - 1}}
\]
where $f$ is the frequency for each class, $n = \sum f$

### Example

Number of children in 50 households (frequency table):

| $x$ (children) | $f$ | $x \cdot f$ |
|----|----|-----|
| 0  | 10 | 0   |
| 1  | 19 | 19  |
| 2  | 7  | 14  |
| 3  | 7  | 21  |
| 4  | 2  | 8   |
| 5  | 1  | 5   |
| 6  | 4  | 24  |
|**Total:**| **50** | **91** |

Sample mean:

\[
\bar{x} = \frac{91}{50} = 1.82
\]

Now, calculate squared deviations for each group and sum:

| $x$ | $f$ | $x - \bar{x}$ | $(x - \bar{x})^2$ | $(x - \bar{x})^2 \cdot f$ |
|---|---|-----------|--------------------|------------------|
| 0 | 10 | -1.82    | 3.31              | 33.10            |
| 1 | 19 | -0.82    | 0.67              | 12.73            |
| 2 | 7  | 0.18     | 0.03              | 0.21             |
| 3 | 7  | 1.18     | 1.39              | 9.73             |
| 4 | 2  | 2.18     | 4.75              | 9.50             |
| 5 | 1  | 3.18     | 10.11             |10.11             |
| 6 | 4  | 4.18     | 17.47             |69.88             |
| **Total** |  |  |  | **145.26**        |

Compute sample standard deviation:

\[
s = \sqrt{\frac{145.26}{49}} \approx \sqrt{2.965} \approx 1.72
\]

---

## 4. Quartiles, Interquartile Range and Boxplot

- **Quartile $Q_1$:** 25% of data below
- **Quartile $Q_2$:** (median) 50% of data below
- **Quartile $Q_3$:** 75% of data below

Interquartile Range (IQR):

\[
\text{IQR} = Q_3 - Q_1
\]

### Example

Test scores (ordered):

```

5, 7, 9, 10, 11, 13, 14, 15, 16, 17, 18, 18, 20, 21, 37

```

- $Q_1 = 10$
- $Q_2 = 15$
- $Q_3 = 18$

\[
\text{IQR} = 18 - 10 = 8
\]

---

## 5. Calculating Quartiles and Boxplots in Python

**Code Example:**

```

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

df = pd.read_csv('banco.csv')

# Quartiles for the 'age' column

q1 = np.quantile(df['age'], 0.25)
q2 = np.quantile(df['age'], 0.5)
q3 = np.quantile(df['age'], 0.75)
print(f'Q1 = {q1}, Q2 (median) = {q2}, Q3 = {q3}')

# Boxplot

plt.boxplot(df['age'])
plt.title("Boxplot of Age")
plt.show()

```

---

## 6. Percentiles and Standard Scores (z-scores)

- **Percentiles ($P_k$):** Divide data into 100 equal parts
- **z-score:** Tells how many standard deviations a value is from the mean

\[
z = \frac{x - \mu}{\sigma}
\]

### Example

Forest Whitaker, age 45, won Best Actor. Average: 43.7, SD: 8.8  
Helen Mirren, age 61, won Best Actress. Average: 36, SD: 11.5

- Forest: $z = \frac{45 - 43.7}{8.8} \approx 0.15$
- Helen: $z = \frac{61 - 36}{11.5} \approx 2.17$

---

## 7. Summary Tables

### Types of Fractiles

| Fractile   | What it Divides             | Symbols       |
|:-----------|:---------------------------|:--------------|
| Quartiles  | Into 4 equal parts          | $Q_1, Q_2, Q_3$ |
| Deciles    | Into 10 equal parts         | $D_1, D_2, ..., D_9$ |
| Percentiles| Into 100 equal parts        | $P_1, P_2, ..., P_{99}$ |

---

## 8. Key Takeaways

- **Variation** and **standard deviation** measure the spread or scatter of data
- **Variance** uses squared deviations; **standard deviation** is the square root of variance
- **Sample** formulas use $n-1$ in denominator for unbiased estimation
- **Grouped data:** Use midpoints for classes; frequency-weighted calculations
- **Interquartile range (IQR)** is a robust measure of spread
- **Boxplot** visually displays data spread, median, quartiles, and outliers
- **z-scores** allow comparison between different data sets by standardizing values

---

# 9. Python Code: Population and Sample Standard Deviation (Cell by Cell)

```


# Cell 1: Define data (salaries)

salaries =

```

```


# Cell 2: Calculate population mean

pop_mean = sum(salaries) / len(salaries)
pop_mean  \# Output expected: 41.5

```

```


# Cell 3: Calculate deviations squared for population

pop_sq_dev = [(x - pop_mean) ** 2 for x in salaries]
pop_sq_dev  \# Output: list of squared deviations

```

```


# Cell 4: Calculate population variance and std deviation

pop_variance = sum(pop_sq_dev) / len(salaries)
pop_std_dev = pop_variance ** 0.5
print(f"Population variance: {pop_variance}")
print(f"Population standard deviation: {pop_std_dev}")

```

```


# Cell 5: Calculate sample mean (same as population mean here)

sample_mean = pop_mean
sample_mean  \# Output: 41.5

```

```


# Cell 6: Calculate deviations squared for sample

sample_sq_dev = pop_sq_dev

```

```


# Cell 7: Calculate sample variance and std deviation

sample_variance = sum(sample_sq_dev) / (len(salaries) - 1)
sample_std_dev = sample_variance ** 0.5
print(f"Sample variance: {sample_variance}")
print(f"Sample standard deviation: {sample_std_dev}")

```

---

## 6. Grouped Data Standard Deviation Example

Suppose you have frequency data of children per household:

| Children $(x)$ | Frequency $(f)$ |
|----------------|-----------------|
| 0              | 10              |
| 1              | 19              |
| 2              | 7               |
| 3              | 7               |
| 4              | 2               |
| 5              | 1               |
| 6              | 4               |

Calculate mean and standard deviation with:

\[
\bar{x} = \frac{\sum (x \cdot f)}{N}
\]

\[
s = \sqrt{\frac{\sum f (x - \bar{x})^2}{N-1}}
\]

---

## 7. Python Code for Grouped Data (Cell by Cell)

```


# Cell 1: Define frequencies and values

x =[^1][^2][^3][^4][^5][^6]
f =[^1][^2][^4][^7][^10][^19]

```

```


# Cell 2: Calculate total frequency

N = sum(f)
N  \# Output expected: 50

```

```


# Cell 3: Calculate mean using weighted sum

mean = sum([xi * fi for xi, fi in zip(x, f)]) / N
mean  \# Output expected about: 1.82

```

```


# Cell 4: Calculate squared deviations (x - mean)^2

sq_dev = [(xi - mean) ** 2 for xi in x]
sq_dev  \# Output: list of squared deviations

```

```


# Cell 5: Calculate weighted squared deviations

weighted_sq_dev = [fi * sd for fi, sd in zip(f, sq_dev)]
weighted_sq_dev  \# Output: weighted squared deviations

```

```


# Cell 6: Calculate sample variance and std deviation

sample_variance = sum(weighted_sq_dev) / (N - 1)
sample_std_dev = sample_variance ** 0.5
print(f"Grouped data sample variance: {sample_variance}")
print(f"Grouped data sample standard deviation: {sample_std_dev}")

```

---

This completes the comprehensive guide on variation and standard deviation with formulas and stepwise Python code ready for running in Google Colab.



---


## 10. Quartiles and Interquartile Range (IQR)

### Definitions:

- **Quartiles** divide an ordered data set into four approximately equal parts.
  
  | Quartile    | Description                        |
  |-------------|----------------------------------|
  | $Q_1$       | First quartile (25% data below)  |
  | $Q_2$       | Second quartile (Median) (50%)   |
  | $Q_3$       | Third quartile (75%)              |

- **Interquartile Range (IQR):**  
\[
\text{IQR} = Q_3 - Q_1
\]

### Example:

Data:  
`5, 7, 9, 10, 11, 13, 14, 15, 16, 17, 18, 18, 20, 21, 37`

- $Q_1 = 10$
- $Q_2 = 15$
- $Q_3 = 18$
- IQR = $18 - 10 = 8$

---

## 3. Percentiles

- Divide data into 100 equal parts.
- Example: The 72nd percentile means 72% of data fall below this value.

---

## 4. Boxplot

A graphical display showing:

- Minimum
- First quartile ($Q_1$)
- Median ($Q_2$)
- Third quartile ($Q_3$)
- Maximum

Useful for identifying spread, center, and potential outliers.

---

## 5. Python Code: Quartiles, Percentiles, and Boxplot (Step by step for Colab)

```


# Cell 1: Import necessary packages

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

```

```


# Cell 2: Create sample data (can replace with actual data)

data =[^5][^7][^9][^10][^11][^13][^14][^15][^16][^17][^18][^20]

```

```


# Cell 3: Calculate quartiles

Q1 = np.percentile(data, 25)
Q2 = np.percentile(data, 50)  \# Median
Q3 = np.percentile(data, 75)

print(f"Q1 (25th percentile): {Q1}")
print(f"Q2 (Median, 50th percentile): {Q2}")
print(f"Q3 (75th percentile): {Q3}")

```

```


# Cell 4: Calculate Interquartile Range (IQR)

IQR = Q3 - Q1
print(f"Interquartile Range (IQR): {IQR}")

```

```


# Cell 5: Calculate specific percentile (e.g. 72nd percentile)

p72 = np.percentile(data, 72)
print(f"72nd percentile: {p72}")

```

```


# Cell 6: Generate boxplot

plt.boxplot(data)
plt.title("Boxplot of Sample Data")
plt.ylabel("Values")
plt.show()

```

---

## 6. Optional: Loading Numeric Columns from a CSV File for Quartile Analysis and Boxplots

```


# Cell 1: Import packages and load CSV file

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

df = pd.read_csv('your_file.csv')  \# Replace 'your_file.csv' with your filename

```

```


# Cell 2: View numeric columns

numeric_cols = df.select_dtypes(include=np.number).columns
print("Numeric columns in dataset:", numeric_cols)

```

```


# Cell 3: Calculate quartiles for a numeric column, e.g. 'age'

col = 'age'  \# Replace with your column name
Q1 = np.percentile(df[col], 25)
Q2 = np.percentile(df[col], 50)
Q3 = np.percentile(df[col], 75)

print(f"{col} Q1: {Q1}, Q2 (Median): {Q2}, Q3: {Q3}")

```

```


# Cell 4: Plot boxplot for the column

plt.boxplot(df[col])
plt.title(f"Boxplot of {col}")
plt.ylabel(col)
plt.show()

```





<br><br>


<!-- ========================== [Bibliographr ====================  -->

<br><br>


## [Bibliography]()

[1](). **Castro, L. N. & Ferrari, D. G.** (2016). *Introduction to Data Mining: Basic Concepts, Algorithms, and Applications*. Saraiva.

[2](). **Ferreira, A. C. P. L. et al.** (2024). *Artificial Intelligence – A Machine Learning Approach*. 2nd Ed. LTC.

[3](). **Larson & Farber** (2015). *Applied Statistics*. Pearson.


<br><br>

      
<!-- ======================================= Bibliography Portugues ===========================================  -->

<!--

## [Bibliography]()


[1](). **Castro, L. N. & Ferrari, D. G.** (2016). *Introdução à mineração de dados: conceitos básicos, algoritmos e aplicações*. Saraiva.

[2](). **Ferreira, A. C. P. L. et al.** (2024). *Inteligência Artificial - Uma Abordagem de Aprendizado de Máquina*. 2nd Ed. LTC.

[3](). **Larson & Farber** (2015). *Estatística Aplicada*. Pearson.


<br><br>
-->

<!-- ======================================= Start Footer ===========================================  -->





## 💌 [Let the data flow... Ping Me !](mailto:fabicampanari@proton.me)

<br><br>



#### <p align="center">  🛸๋ My Contacts [Hub](https://linktr.ee/fabianacampanari)


<br>

### <p align="center"> <img src="https://github.com/user-attachments/assets/517fc573-7607-4c5d-82a7-38383cc0537d" />




<br><br><br>

<p align="center">  ────────────── 🔭⋆ ──────────────


<p align="center"> ➣➢➤ <a href="#top">Back to Top </a>

<!--
<p align="center">  ────────────── ✦ ──────────────
-->



<!-- Programmers and artists are the only professionals whose hobby is their profession."

" I love people who are committed to transforming the world "

" I'm big fan of those who are making waves in the world! "

##### <p align="center">( Rafael Lain ) </p>   -->

#

###### <p align="center"> Copyright 2025 Quantum Software Development. Code released under the [MIT License license.](https://github.com/Quantum-Software-Development/Math/blob/3bf8270ca09d3848f2bf22f9ac89368e52a2fb66/LICENSE)










