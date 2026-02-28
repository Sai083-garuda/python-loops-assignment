**#TASK-1:**
**CODE**
import numpy as np
temps_celsius = np.array([22, 25, 28, 24, 26])
temps_fahrenheit = temps_celsius * 1.8 + 32
avg_fahrenheit = round(np.mean(temps_fahrenheit), 1)
print("Celsius:", temps_celsius)
print("Fahrenheit:", temps_fahrenheit)
print("Average Fahrenheit:", avg_fahrenheit)
<img width="754" height="336" alt="Screenshot 2026-02-28 230213" src="https://github.com/user-attachments/assets/640d727a-a5fe-447d-90fc-1a21e490adef" />

**#TASK-2
CODE**
# Test scores array
scores = np.array([85, 90, 78, 92, 88, 76, 95, 82, 89, 91, 87, 84])
print("Shape:", scores.shape)
print("Total_elements:", scores.size)
print("Highest_score:", np.max(scores))
print("Lowest_score:", np.min(scores))
print("Range:", np.max(scores) - np.min(scores))
**OUTPUT**
<img width="838" height="386" alt="Screenshot 2026-02-28 230452" src="https://github.com/user-attachments/assets/c2b11071-0c1e-4afa-9a88-e724d0d3c9fd" />

**#TASK-3
CODE:**

import time
import numpy as np

np_array = np.arange(1, 50001)
py_list = list(range(1, 50001))

start = time.time()
np_sum = np.sum(np_array)
np_time = time.time() - start

start = time.time()
py_sum = sum(py_list)
py_time = time.time() - start

speedup = py_time / np_time
print("NumPy sum:", np_sum)
print("Python sum:", py_sum)
print(f"NumPy time: {np_time:.4f} seconds")
print(f"Python time: {py_time:.4f} seconds")
print(f"NumPy is {speedup:.1f}x faster")
**OUTPUT:**
<img width="430" height="567" alt="Screenshot 2026-02-28 230618" src="https://github.com/user-attachments/assets/e13358b0-ea7b-4bee-a728-e478abea9332" />
