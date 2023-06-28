# satellite-tracker
To run the python file the following dependecies are needed:
from PyQt5 import QtCore, QtGui, QtWidgets
import sys
import numpy as np
from skyfield.api import load, wgs84
from astropy.io import fits
from IPython.display import display
import pandas as pd
from suncalc import get_position, get_times
from datetime import datetime
import datetime
from datetime import timezone
import os
Then the script can be launched from terminal by: python SSS.py

# datareduction-gratama.ipynb
This is a jupyter notebook used for the data reduction and magnitude determination of the satellite
