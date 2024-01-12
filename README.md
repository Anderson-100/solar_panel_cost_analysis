# solar_panel_cost_analysis
Financial analysis of various solar panel installation options for a particular household. Code can be found in the `lab1.ipynb` Jupyter notebook.

In this financial analysis, an imaginary household is looking at options for installing solar panels on their house. The three installation options being compared are:
1. Solar panels with a 15 kWh battery
2. Just solar panels
3. Nothing installed

Out of these three options, solar panels with the battery is the most expensive option. If one of the other two options are picked, the money saved relative to the first option is put into an investment account, which is assumed to have 7% annual returns.

With all types of installations, we also consider three types of net metering. **Net metering** is the money a household can earn for "selling" the excess electricity they generate from solar panels back to the grid. The three types are:
1. Retail net metering: compensation per kWh is **equivalent** to the price per kWh when paying for electricity from the grid
2. Wholesale net metering: compensation per kWh is **half** the price per kWh when paying for electricity from the grid
3. No net metering: **no compensation** for excess electricity generated

Together, this makes up **nine different scenarios** for which I compared the expenses over a 30-year period.

Solar generation data was obtained from the National Renewable Energy Laboratory's [PVWatts API](https://developer.nrel.gov/docs/solar/pvwatts/v8/) given the location and specifications of this imaginary house. Electricity consumption data came from a CSV file, which is included in the repository.
