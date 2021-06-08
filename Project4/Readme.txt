Configuring R:

1. Install R for your operating system. For Mac OS X: https://cran.r-project.org/bin/macosx/

2. Install the following packages using R console:

install.packages("igraph")

3. Install Jupyter Lab from https://jupyter.org/

4. Configure Jupyter to work with R. Make sure path is present in:
a. https://www.chrisjmendez.com/2018/12/04/configure-jupyter-notebook-to-work-with-r/
b. https://www.r-bloggers.com/2017/05/how-to-install-r-kernel-for-jupyter-on-mac-os-x/ 
c. https://stackoverflow.com/questions/44336345/running-r-from-mac-osx-terminal 

5. Download the stock market dataset from https://www.dropbox.com/s/83l60htndqpn3fv/finance_data.zip?dl=0. Extract the compressed file and make sure the folder 'finance data' is in the same directory as the notebooks. We already provided the dataset for easier running

6. Launch Jupyter Lab from terminal and open the notebook titled "Saha_Young_Proj4_1-5.ipynb". Go through all the sections sequentially.

Configuring Python:

Python: 3.7.9 (setup via Conda environment)

Make sure Jupyter Lab is installed.

Required Python Packages and versions (installed in Conda environment):

matplotlib                3.3.2
numpy                     1.19.1
pandas                    1.1.3 
igraph                    0.9.2
python-igraph             0.8.3
scipy                     1.6.3
networkx                  2.5
cairo                     1.16.0
cairocffi                 1.2.0
pulp                      2.4
gmaps                     0.9.0
googlemaps                2.5.1

Steps to run:
1. Make sure your conda environment and jupyter notebook are appropriately set up.
2. Make sure all the Python packages are installed. 
3. Download the Uber Movement Dataset from https://drive.google.com/drive/folders/1cDcXtH7Lx0lnUxczInDeep9JxipyUz-m?usp=sharing and keep the two files in the same directory as the notebooks.
3. Activate your conda environment, navigate to the folder where the notebook is located and type "jupyter notebook"
4. Open the notebooks "Saha_Young_Proj4_6-15" and "Own_Task.ipynb" and just sequentially run all the sections.
5. For running "Own_Task.ipynb", you will need an API key from Google. Go to https://console.cloud.google.com/home and set up an API key. Check on Google to see how to setup the API key.

