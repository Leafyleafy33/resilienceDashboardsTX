# Open Source Data Visualization Dashboard


_Open source dashboard developed for the [Identifying Resilience Factors in Texas Public Schools](2022Fall-CHERR-Poster.pdf) project_  by [Daniel Payan](https://github.com/danielpayan13) (dashboard author), [June Yu](https://j-y-yu.github.io/), ([data integration and modeling](https://github.com/DataLab12/educationDataScience)), [Li Feng](https://lifeng.wp.txstate.edu/) (domain expert), and [Jelena Tešić](jtesic.github.io) (project lead). The work has been supported by [The Center of Excellence for Community Health and Economic Resilience Research](https://www.cherr.txst.edu/) and [Data Lab](https://DataLab12.github.io) @ Texas State University.

![image](https://media.git.txstate.edu/user/1705/files/151fb0a6-9e9e-4cf5-8397-43c78586660a)

![image](https://media.git.txstate.edu/user/1705/files/e8271a6a-d2cd-4438-88a6-1c10a6e441d0)

![image](https://media.git.txstate.edu/user/1705/files/0e2cfb72-54e2-43b6-b639-5751b341e899)

![image](https://media.git.txstate.edu/user/1705/files/c2ea0a3d-74fc-4300-920f-d9d5d145329c)

![image](https://user-images.githubusercontent.com/87658834/232095006-7e8f919c-3850-43f1-ba08-db4ac3556649.png)

![image](https://user-images.githubusercontent.com/87658834/232095291-d288a16c-e0bc-48d6-a306-2cc70c996539.png)




## Jupyter Notebooks for Texas Open Source Data
* [LearningLossDashboard](LearningLossDashboard.ipynb) -> outputs 4 tabs
    * Tab 1 displays a county-level map of Texas which reflects percent changes in Staff/Student population and STAAR testing scores for three different year ranges (2019-2021, 2021-2022, 2019-2022).
    * Tab 2 displays a district-level map of Texas which reflects percent changes in Staff/Student population STAAR testing scores, and funding for three different year ranges (2019-2021, 2021-2022, 2019-2022).
    * Tab 3 displays a histogram of the percent changes in STAAR scores for three different year ranges (2019-2021, 2021-2022, 2019-2022), along with a heatmap that models change based on demographic group and grade for the three different year ranges.
    * Tab 4 displays a definition table of all variables used within the dashboard.
 
* [GradeDemo_Dashboard](GradeDemo_Dashboard.ipynb) -> outputs 2 tabs
    * Tab 1 displays a county-level map of Texas which reflects percent changes in Staff/Student population and STAAR testing scores for three different year ranges (2019-2021, 2021-2022, 2019-2022) based on demographic and grade level.
    * Tab 2 displays a heatmap that models change based on demographic group and grade for the three different year ranges.

## SETUP
  1. Download Anaconda/Juptyer Notebook for your device's operating system from [here](https://www.anaconda.com/products/distribution#Downloads)
  2. Run Anaconda Prompt app with administrative privileges
     * make sure all the conda packages are up to date: ```conda update --all```
       * answer Yes to install all packages   
     * install needed packages as follows: 
       * the [bokeh](https://anaconda.org/bokeh/jupyter_bokeh) package: ```>>conda install -c bokeh jupyter_bokeh```
       * the [hv_plot](https://anaconda.org/conda-forge/hvplot), the [panel](https://anaconda.org/conda-forge/panel), and [geopandas](https://anaconda.org/conda-forge/geopandas-base) packages: ```>>conda install -c conda-forge hvplot panel geopandas-base```

  3. close the anaconda prompt and open it up as a regular user , type ```>>jupyter notebook```
     * navigate in the browser to this folder and double click on the file [LearningLossDashboard.ipynb](LearningLossDashboard.ipynb) to open it (separate windows will open)
     * in separate windows, click `Cell` on the top taskbar and then `Run All`. This will open the the tabbed dashboard.
