
import vispy.plot as vp
import numpy as np

# Generate random data
x = np.random.normal(size=100)
y = np.random.normal(size=100)
z = np.random.normal(size=100)

# Create the plot
fig = vp.Fig()
scatter = fig[0, 0].scatter((x, y, z), size=5)

# Show the plot
fig.show()

