# interactive-plots
For sharing holoviews bokeh dynamic map plots

For instructions on how to do this:

https://pythonforundergradengineers.com/deploy-jupyter-notebook-voila-heroku.html

My notes on trying the instructions from the above link:

(base) barnett@coyote:~$ conda activate ce597

(ce597) barnett@coyote:~$ cd voila

(ce597) barnett@coyote:~/voila$ python -m venv venv

(ce597) barnett@coyote:~/voila$ source venv/bin/activate

(venv) (ce597) barnett@coyote:~/voila$ pip install voila

(venv) (ce597) barnett@coyote:~/voila$ conda install -y -c conda-forge holoviews hvplot

(ce597) (venv) barnett@coyote:~/voila$ conda install -y -c conda-forge geoviews

 All requested packages already installed.

There seems to be an issue with geoviews not being installed in the voila environment. 
I may need to nuke everything and reinstall, as Kostas directed here:
Hey everyone,

The only thing that worked in my case was to uninstall holoviews and reinstall it. Open up an Anaconda Shell and activate your environment (assume it is named ce597)

conda activate ce597

conda remove holoviews

conda install -c conda-forge holoviews hvplot

Last line should install hvplot as well. 

If your conda is getting stuck solving the environment, nuke everything and reinstall

conda remove --name ce597 --all

conda create -n ce597 jupyter holoviews numpy pandas geoviews geopandas hvplot seaborn matplotlib



https://nbviewer.jupyter.org/

https://panel.holoviz.org/user_guide/Server_Deployment.html

https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-file-manually

https://github.com/holoviz-demos/clifford/blob/master/clifford.ipynb

https://docs.bokeh.org/en/latest/docs/user_guide/server.html

My first attempt at a shareable link for interactive plots using mybinder.org:
https://hub.gke2.mybinder.org/user/jake-barnett-to-teractive-plots-es8uoryi/notebooks/Barnett_cee597_project_deploy.ipynb
