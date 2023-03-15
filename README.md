# statistical-data-analysis
<p align="justify">
Statistical data analysis is a wide range of quantitative research practices in which you collect and analyze categorical data to find meaningful patterns and trends. Statistical data analysis is often applied to survey responses and observational data, but it can be applied to many other business metrics as well. In this project I will do an analysis with a statistical approach. This is especially useful on variables with numeric values 
</p>

<h6>
Author&ensp;&ensp;&ensp;&nbsp; : &ensp;Achmad Adyatma Ardi <br>
Email&ensp;&ensp;&ensp;&ensp;&ensp;&nbsp;: &ensp;adyatmaardi@gmail.com <br>
LinkedIn&ensp;&ensp; :&ensp; https://www.linkedin.com/in/adyatmaardi/ <br>
</h6>
<hr>
<div align="justify">
<h4>Prerequisites :</h4>
<ol>
  <li> Install necessary Python-module 
        <ul>
          <li><a href ="https://pypi.org/project/statistics/" target="_blank">statistics</a> (built-in) module - used to calculate mathematical statistics of numeric data. <br>install >>> [pip install statistics]</li>
          <li><a href ="https://pypi.org/project/python-math/">math</a> module - Used to perform various mathematical calculations, such as numeric, trigonometric, logarithmic, and exponential calculations. <br>install >>> [pip install python-math]</li>
          <li><a href ="https://numpy.org/install/">numpy</a> module - used to perform a wide variety of mathematical operations on arrays. <br>install >>> [pip install numpy]</li>
          <li><a href ="https://pandas.pydata.org/docs/getting_started/install.html">pandas</a> module - It provides ready to use high - performance data structures and data analysis tools. It runs on top of NumPy and it is popularly used for data science and data analytics. <br>install >>> [pip install pandas]</li>
          <li><a href ="https://matplotlib.org/stable/users/installing/index.html">matplotlib</a> module - used to create 2D graphs and plots by using python scripts. <br>install >>> [python -m pip install -U matplotlib]</li>
          <li><a href ="https://pypi.org/project/seaborn/">seaborn</a> module - used to visualize data and exploratory data analysis. <br>install >>> [pip install seaborn]</li> 
          <li><a href ="https://scipy.org/install/">SciPy</a> module - used to solve scientific and mathematical problems. <br>install >>> [python -m pip install scipy]</li>        
          <li><a href ="https://ipython.org/install.html">from IPython.display Import Image</a> module - used to load images from files, and to create new images. <br>install >>> [pip install ipython]</li>
          <li><a href ="https://pypi.org/project/pytest-warnings/">warnings</a> module - used to issue warning messages. <br>install >>> [pip install pytest-warnings]</li>
        </ul>
  </li>
</ol>
</div>
<hr>
<div align="justify">
<h4>Data preparation</h4>
  <ol>
    <li>NumPy array
        <ul>(1) Speed
            <ol>
              <li>data : [99, 86, 87, 88, 111, 86, 103, 87, 94, 78, 77, 85, 86] </li>
              <li>number of observation : 13</li>
              <li>datatype : int (integer)</li>
            </ol>
        </ul>
        <ul>(2) Age
            <ol>
              <li>data : [5, 31, 43, 48, 50, 41, 7, 11, 15, 39, 80, 82, 32, 2, 8, 6, 25, 36, 27, 61, 31] </li>
              <li>number of observation : 21</li>
              <li>datatype : int (integer)</li>
            </ol>
        </ul>
    </li>
    <li>Pandas dataframe
        <ul>(1) Cars
            <ol>
              <li>data : 'Car', 'Model', 'Volume', 'Weight', 'CO2'</li>
              <li>number of observation : 37 rows (headers included)</li>
              <li>datatype : <br>
              &ensp;&ensp;&ensp; 'Car' = String (str) / character (chr)<br>
              &ensp;&ensp;&ensp; 'Model' = String (str) / character (chr)<br>
              &ensp;&ensp;&ensp; 'Volume' = Integer (int)<br>
              &ensp;&ensp;&ensp; 'Weight' = Integer (int)<br>
              &ensp;&ensp;&ensp; 'CO2' = Integer (int)<br>
              </li>
            </ol>
        </ul>
        <ul>(2) Health
            <ol>
              <li>data : 'Duration', 'Average_Pulse', 'Max_Pulse', 'Calorie_Burnage', 'Hours_Work', 'Hours_Sleep'</li>
              <li>number of observation : 164 rows (headers included)</li>
              <li>datatype : <br>
              &ensp;&ensp;&ensp; 'Duration' = Integer (int)<br>
              &ensp;&ensp;&ensp; 'Average_Pulse' = Integer (int)<br>
              &ensp;&ensp;&ensp; 'Max_Pulse' = Integer (int)<br>
              &ensp;&ensp;&ensp; 'Calorie_Burnage' = Integer (int)<br>
              &ensp;&ensp;&ensp; 'Hours_Work' = Floating points (float)<br>
              &ensp;&ensp;&ensp; 'Hours_Sleep' = Floating point (float)<br>
              </li>
            </ol>
        </ul>
    </li>
  </ol>
</div>
<hr>
<div align="justify">
<h4>Objectives :</h4>
<ol>
  <li>Descriptive statistics
      <ul>
        <li>Measure central tendency (array & dataframe method)<br>
        &ensp;&ensp;(1) mean <br>
        &ensp;&ensp;(2) median <br>
        &ensp;&ensp;(3) mode <br>
        </li>
        <li>Measure variability (array & dataframe method)<br>
        &ensp;&ensp;(1) min, max, and range <br>
        &ensp;&ensp;(2) percentiles <br>
        &ensp;&ensp;(3) variance <br>
        &ensp;&ensp;(4) standard deviation <br>
        &ensp;&ensp;(5) distribution <br>
        &ensp;&ensp;(6) skewness <br>
        &ensp;&ensp;(7) kurtosis <br>
        </li>
        <li>Summarize data (describe())</li>
      </ul>
  </li>
  <li>Inferential statistics
      <ul>
        <li>Correlation between pairs of data<br>
        &ensp;&ensp;(1) covariance matrix<br>
        &ensp;&ensp;(2) correlation matrix <br>
        &ensp;&ensp;(3) heatmap<br>
        &ensp;&ensp;(4) correlation coefficient (CC)<br>
        &ensp;&ensp;&ensp;&ensp; (4.1) Perfect linear relationship (CC = 1)<br>
        &ensp;&ensp;&ensp;&ensp; (4.2) Perfect negative linear relationship (CC = -1)<br>
        &ensp;&ensp;&ensp;&ensp; (4.3) No linear relationship (CC = 0)<br>
        </li>
        <li>Perform simple linear regression analysis<br>
        &ensp;&ensp;(1) Data preparation<br>
        &ensp;&ensp;(2) Plot the given data points<br>
        &ensp;&ensp;(3) Add needed columns (x-x̄), (y-ȳ), (x-x̄)*(y-ȳ), (x-x̄)^2, (y-ȳ)^2<br>
        &ensp;&ensp;(4) Sum up (x-x̄)*(y-ȳ), (x-x̄)^2, (y-ȳ)^2 columns<br>
        &ensp;&ensp;(5) Calculate Pearson's correlation coefficient (r)<br>
        &ensp;&ensp;(6) Calculate standard deviation of X and Y variables<br>
        &ensp;&ensp;(7) Calculate slope (b)<br>
        &ensp;&ensp;(8) Calculate intercept (a)<br>
        &ensp;&ensp;(9) Plot the given data points and fit the regression line<br>
        &ensp;&ensp;(10) Predict value<br>
        </li>
      </ul>
  </li>
</ol>
</div>
