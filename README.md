# Applience-energy-prediction
# Name: Md Musfikur Rahman Parvej
# ID: 2011954642
## Aim
Experimental data used to create regression models of appliances' energy use in a low energy building.

**Note:** If the ipynb (code) file doesn't load, you can view it [here](https://nbviewer.jupyter.org/github/axn170037/ML-Project_-Data/blob/master/ML%20Project%202%20(1).ipynb).

## Regression

### About the Data
- **Date:** time (yr:mon:day:hr:min:sec)
- **Appliances:** energy use in Wh
- **Lights:** Energy use of light fixtures in the house (Wh)

**Temperature and Humidity:**
- **T1:** Temperature in kitchen area (C) | **RH_1:** Humidity in kitchen area (%)
- **T2:** Temperature in living room area (C) | **RH_2:** Humidity in living room (%)
- **T3:** Temperature in laundry room (C) | **RH_3:** Humidity in laundry room area (%)
- **T4:** Temperature in office room (C) | **RH_4:** Humidity in office room (%)
- **T5:** Temperature in bathroom (C) | **RH_5:** Humidity in bathroom (%)
- **T6:** Temperature outside the building (north side) (C) | **RH_6:** Humidity outside the building (north side)%
- **T7:** Temperature in ironing room (C) | **RH_7:** Humidity in ironing room (%)
- **T8:** Temperature in teenager room 2 (C) | **RH_8:** Humidity in teenager room 2 (%)
- **T9:** Temperature in parents' room (C) | **RH_9:** Humidity in parents' room (%)

**External Conditions:**
- **To:** Temperature outside (from Chievres weather station) (C)
- **Pressure (from Chievres weather station):** in mm Hg
- **RH_out:** Humidity outside (from Chievres weather station) (%)
- **Wind speed (from Chievres weather station):** in (m/s)
- **Visibility (from Chievres weather station):** Ordinal data
- **Tdewpoint (from Chievres weather station):** Categorical data

**Random Variables:**
- **rv1:** Random variable 1 (nondimensional)
- **rv2:** Random variable 2 (nondimensional)

Where indicated, hourly data (then interpolated) from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis, rp5.ru. Permission was obtained from Reliable Prognosis for the distribution of the 4.5 months of weather data.
