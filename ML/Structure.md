# ML Cheatsheet: NumPy and Pandas

## NumPy Array Operations

### Numpy_array_1.ipynb

#### Basic Array Operations
| Operation | Description | Example |
|-----------|-------------|---------|
| `array` | Create a NumPy array | `np.array([1, 2, 3])` |
| `ndim` | Get the number of dimensions | `arr.ndim` |
| `size` | Get the total number of elements | `arr.size` |
| `shape` | Get the shape of the array | `arr.shape` |
| `dtype` | Get the data type of the array | `arr.dtype` |

#### Array Creation
| Function | Description | Example |
|----------|-------------|---------|
| `ones` | Create an array filled with ones | `np.ones((3, 3))` |
| `zeros` | Create an array filled with zeros | `np.zeros((2, 4))` |
| `arange` | Create an array with a range of elements | `np.arange(0, 10, 2)` |
| `reshape` | Reshape an array | `arr.reshape(2, 3)` |

#### Mathematical Operations
| Operation | Description | Example |
|-----------|-------------|---------|
| `add` | Element-wise addition | `np.add(arr1, arr2)` |
| `subtract` | Element-wise subtraction | `np.subtract(arr1, arr2)` |
| `multiply` | Element-wise multiplication | `np.multiply(arr1, arr2)` |
| `divide` | Element-wise division | `np.divide(arr1, arr2)` |

#### Array Statistics
| Function | Description | Example |
|----------|-------------|---------|
| `argmax` | Index of maximum element | `np.argmax(arr)` |
| `max` | Maximum value | `np.max(arr)` |
| `min` | Minimum value | `np.min(arr)` |
| `argmin` | Index of minimum element | `np.argmin(arr)` |
| `mean` | Mean of array elements | `np.mean(arr)` |
| `std` | Standard deviation of array elements | `np.std(arr)` |

#### Mathematical Functions
| Function | Description | Example |
|----------|-------------|---------|
| `sqrt` | Square root of each element | `np.sqrt(arr)` |
| `exp` | Exponential of each element | `np.exp(arr)` |

### Numpy_array_2.ipynb

| Operation | Description | Example |
|-----------|-------------|---------|
| `slicing` | Extract a portion of an array | `arr[1:4]` |
| `concatenation` | Join arrays | `np.concatenate((arr1, arr2))` |
| `vstack` | Stack arrays vertically | `np.vstack((arr1, arr2))` |
| `hstack` | Stack arrays horizontally | `np.hstack((arr1, arr2))` |
| `split` | Split array into sub-arrays | `np.split(arr, 3)` |
| `sin` | Sine of each element | `np.sin(arr)` |
| `cos` | Cosine of each element | `np.cos(arr)` |
| `tan` | Tangent of each element | `np.tan(arr)` |
| `matplotlib.plot` | Plot data | `plt.plot(x, y)` |

## Pandas Operations

### Pandas_1.ipynb

| Operation | Description | Example |
|-----------|-------------|---------|
| `Series` | Create a Pandas Series | `pd.Series([1, 2, 3])` |
| `Series slicing` | Slice a Series | `s[1:3]` |
| `min` | Minimum value in Series | `s.min()` |
| `max` | Maximum value in Series | `s.max()` |
| `conditional slicing` | Slice based on condition | `s[s > 2]` |
| `DataFrame` | Create a Pandas DataFrame | `pd.DataFrame()` |
| `DataFrame from list` | Create DataFrame from list | `pd.DataFrame([[1, 2], [3, 4]])` |
| `DataFrame from dict` | Create DataFrame from dict | `pd.DataFrame({'A': [1, 2], 'B': [3, 4]})` |

### Pandas_2.ipynb

| Function | Description | Example |
|----------|-------------|---------|
| `read_csv` | Read CSV file | `pd.read_csv('file.csv')` |
| `nrows` | Limit number of rows to read | `pd.read_csv('file.csv', nrows=100)` |
| `usecols` | Specify columns to use | `pd.read_csv('file.csv', usecols=['A', 'B'])` |
| `skiprows` | Skip specified rows | `pd.read_csv('file.csv', skiprows=[1, 2])` |
| `index_col` | Set column as index | `pd.read_csv('file.csv', index_col='ID')` |
| `header` | Specify header row | `pd.read_csv('file.csv', header=0)` |
| `prefix` | Add prefix to column names | `pd.read_csv('file.csv', prefix='Col_')` |
| `names` | Rename columns | `pd.read_csv('file.csv', names=['A', 'B', 'C'])` |

### Pandas_3.ipynb

| Function | Description | Example |
|----------|-------------|---------|
| `read_csv` | Read CSV file | `pd.read_csv('file.csv')` |
| `head` | View first n rows | `df.head()` |
| `tail` | View last n rows | `df.tail()` |
| `dtype` | Specify data types | `pd.read_csv('file.csv', dtype={'A': int})` |
| `true_values` | Specify true values | `pd.read_csv('file.csv', true_values=['yes'])` |
| `false_values` | Specify false values | `pd.read_csv('file.csv', false_values=['no'])` |

### Pandas_4.ipynb

| Function | Description | Example |
|----------|-------------|---------|
| `na_values` | Specify NA values | `pd.read_csv('file.csv', na_values=['N/A'])` |
| `keep_default_na` | Keep default NA values | `pd.read_csv('file.csv', keep_default_na=True)` |
| `isnull` | Check for null values | `df.isnull()` |
| `notnull` | Check for non-null values | `df.notnull()` |
| `sum` | Sum of values | `df.sum()` |
| `dropna` | Drop rows with NA values | `df.dropna()` |
| `how` | Specify how to drop | `df.dropna(how='all')` |
| `subset` | Specify columns for dropping | `df.dropna(subset=['A', 'B'])` |
| `inplace` | Modify the DataFrame in place | `df.dropna(inplace=True)` |
| `fillna` | Fill NA values | `df.fillna(0)` |

Note: Replace `arr`, `arr1`, `arr2`, `s`, and `df` with your actual variable names.
