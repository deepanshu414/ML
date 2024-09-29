# ML

## NumPy Array Cheatsheet

### Basic Array Operations

| Operation | Description | Example |
|-----------|-------------|---------|
| `array` | Create a NumPy array | `np.array([1, 2, 3])` |
| `ndim` | Get the number of dimensions | `arr.ndim` |
| `size` | Get the total number of elements | `arr.size` |
| `shape` | Get the shape of the array | `arr.shape` |
| `dtype` | Get the data type of the array | `arr.dtype` |

### Array Creation

| Function | Description | Example |
|----------|-------------|---------|
| `ones` | Create an array filled with ones | `np.ones((3, 3))` |
| `zeros` | Create an array filled with zeros | `np.zeros((2, 4))` |
| `arange` | Create an array with a range of elements | `np.arange(0, 10, 2)` |
| `reshape` | Reshape an array | `arr.reshape(2, 3)` |

### Mathematical Operations

| Operation | Description | Example |
|-----------|-------------|---------|
| `add` | Element-wise addition | `np.add(arr1, arr2)` |
| `subtract` | Element-wise subtraction | `np.subtract(arr1, arr2)` |
| `multiply` | Element-wise multiplication | `np.multiply(arr1, arr2)` |
| `divide` | Element-wise division | `np.divide(arr1, arr2)` |

### Array Statistics

| Function | Description | Example |
|----------|-------------|---------|
| `argmax` | Index of maximum element | `np.argmax(arr)` |
| `max` | Maximum value | `np.max(arr)` |
| `min` | Minimum value | `np.min(arr)` |
| `argmin` | Index of minimum element | `np.argmin(arr)` |
| `mean` | Mean of array elements | `np.mean(arr)` |
| `std` | Standard deviation of array elements | `np.std(arr)` |

### Mathematical Functions

| Function | Description | Example |
|----------|-------------|---------|
| `sqrt` | Square root of each element | `np.sqrt(arr)` |
| `exp` | Exponential of each element | `np.exp(arr)` |

Note: Replace `arr`, `arr1`, and `arr2` with your actual array variable names.
