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



https://nbviewer.jupyter.org/

https://panel.holoviz.org/user_guide/Server_Deployment.html

https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-file-manually

https://github.com/holoviz-demos/clifford/blob/master/clifford.ipynb

https://docs.bokeh.org/en/latest/docs/user_guide/server.html

My first attempt at a shareable link for interactive plots using mybinder.org:
https://hub.gke2.mybinder.org/user/jake-barnett-to-teractive-plots-es8uoryi/notebooks/Barnett_cee597_project_deploy.ipynb
