# Open Source Data Visualization Dashboard


_Open source dashboard developed for the [Identifying Resilience Factors in Texas Public Schools](2022Fall-CHERR-Poster.pdf) project_  by [Daniel Payan](https://github.com/danielpayan13) (dashboard author), [June Yu](https://j-y-yu.github.io/), ([data integration and modeling](https://github.com/DataLab12/educationDataScience)), [Li Feng](https://lifeng.wp.txstate.edu/) (domain expert), and [Jelena Tešić](jtesic.github.io) (project lead). The work has been supported by [The Center of Excellence for Community Health and Economic Resilience Research](https://www.cherr.txst.edu/) and [Data Lab](https://DataLab12.github.io) @ Texas State University.

![image](https://user-images.githubusercontent.com/87658834/211226776-9752ff91-5155-4490-9340-4b20241aaa15.png)

![image](https://user-images.githubusercontent.com/87658834/211226780-a75b2d64-8dd1-4d8f-8f34-46d01a24f92c.png)

![image](https://user-images.githubusercontent.com/87658834/211226781-f1d5c36b-df33-43b5-bca9-e87d01c67621.png)

![image](https://user-images.githubusercontent.com/87658834/211226783-eb6b54df-d7b7-421a-beb3-bcb0533975d7.png)



## Jupyter Notebooks for Texas Open Source Data
* [LearningLossDashboard](LearningLossDashboard.ipynb) -> outputs 4 tabs
    * Tab 1 displays a county-level map of Texas which reflects percent changes in Staff/Student population, STAAR testing scores, and the labor force from 2019 to 2021.
    * Tab 2 displays a district-level map of Texas which reflects percent changes in Staff/Student population, STAAR testing scores, and also learning loss labels from 2019 to 2021.
    * Tab 3 displays a histogram of the percent changes in STAAR scores along with a heatmap that models change based on demographic group and grade from 2019 to 2021.
    * Tab 4 displays a definition table of all variables used within the dashboard.

## SETUP
  1. Download Anaconda/Juptyer Notebook for your device's operating system from [here](https://www.anaconda.com/products/distribution#Downloads)
  2. Run Anaconda Prompt app with administrative privileges
     * make sure all the conda packages are up to date: ```conda update --all```
       * answer Yes to install all packages   
     * install needed packages as follows: 
       * the [bokeh](https://anaconda.org/bokeh/jupyter_bokeh) package: ```>>conda install -c bokeh jupyter_bokeh```
       * the [hv_plot](https://anaconda.org/conda-forge/hvplot), the [panel](https://anaconda.org/conda-forge/panel), and [geopandas](https://geopandas.org/en/stable/getting_started/install.html) packages: ```>>conda install -c conda-forge hvplot panel geopandas```
       * [openpyxl](https://anaconda.org/anaconda/openpyxl) package: ```conda install -c anaconda openpyxl```
       * [plotly express](https://anaconda.org/plotly/plotly_express) package: ```conda install -c plotly plotly_express```
  3. close the anaconda prompt and open it up as a regular user , type ```>>jupyter notebook```
     * navigate in the browser to this folder and double click on the [JointDashboard.ipynb](JointDashboardh.ipynb) or [District_CountyDashboard.ipynb](District_CountyDashboard.ipynb) to open them (separate windows will open)
     * in separate windows, click `Cell` on the top taskbar and then `Run All`. This will open the the tabbed dashboard.
