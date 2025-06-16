# cea-energy-water model
Repository for the paper "A Simplified Approach to Energy-Water Modeling for Controlled Environment Agriculture"

Provides order-of-magnitude estimates of annual energy and water consumption, as well as greenhouse gas emissions from energy consumption, at controlled environment agriculture (CEA) facilities based on location, facility type, size, crop, and technology level. Model is applied to a portfolio of 73 locations across the United States, but other locations can be modeled if meteorological data is retrieved.

Growing environment specifications are inferred based on user inputs, but can be modified in the basic_setup() function of the model.

Requirements:
Python 3.11.13
Pandas 2.2.2
Geopandas 1.0.1
