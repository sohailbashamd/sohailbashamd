![X28_1.jpg](attachment:71061e72-69c1-42a6-be67-21d2a0836245.jpg)
import numpy as np
import plotly
import imageio.v2 as imageio
import plotly.express as px
import plotly.graph_objects as go
import matplotlib.pyplot as plt
import matplotlib.patches as mpatches
import pandas as pd
import os
import cv2 
from skimage import img_as_ubyte
from skimage import exposure
from skimage.color import rgb2gray
from skimage import data, filters, measure, morphology
from skimage.measure import label, regionprops, regionprops_table
from skimage.filters import difference_of_gaussians, gaussian, threshold_local, threshold_yen
from skimage.morphology import square, disk
import scipy.stats as ss # for statistical testing
import scikit_posthocs as sp # for posthoc testing
