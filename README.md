#election

###Contributors
+ Jun Seo Park
+ Athan Diep
+ Emma Duncan

##Abstract
The 2016 U.S. presidential election yielded an unexpected result for many - while an overwhelming majority of polls were thought to point to Hillary Clinton as the winner, Donald Trump emerged the victor. In this project, we dive into the election poll data provided by [FiveThirtyEight](https://projects.fivethirtyeight.com/2016-election-forecast/) with the goal of visualizing the data to see where the predictions may have gone awry. 
+ We used IPython notebooks to write our script, but we have assembled our findings in Markdown. **include link/description to markdown file for presentation** More information about the two IPython notebooks can be found below.
+ We have included both a ZIP and CSV of the election poll data in the repository. If you wish to download or import the dataset using a link, it is available at [http://projects.fivethirtyeight.com/general-model/president_general_polls_2016.csv](http://projects.fivethirtyeight.com/general-model/president_general_polls_2016.csv).

##IPython notebooks
There are two IPython notebooks: [Election 2016 (Bokeh).ipynb](../master/Election 2016 (Bokeh).ipynb) and [Election 2016 (Plotly).ipynb](../master/Election 2016 (Plotly).ipynb).
+ Election 2016 (Bokeh) was the initial iteration, built upon the data visualization package [Bokeh](http://bokeh.pydata.org/en/latest/#). Though Bokeh is a beautiful package with straightforward syntax, we ran into some major roadblocks with the lack of documentation and crucial missing features.
+ Election 2016 (Plotly) is the current iterattion, using the data visualization package [Plotly](https://plot.ly). Plotly has a variety of available charts, complete with [detailed documentation for Python](https://plot.ly/python/).

##System requirements
This project was built on virtual environments running Python 3.6 through Anaconda, and we have also included two separate requirements.txt files for [Windows](..blob/master/requirements_windows.txt) and [OSX/macOS](..blob/master/requirements_mac.txt).
To create a virtual environment, enter the following in a command-line interpreter (Anaconda Prompt, Terminal, etc.):
```sh
conda create python=3.6 --name [envname] --file [filepath]
```
+ filepath refers to the path of the respective requirements.txt file.
To activate the environment on Windows:
```sh
activate [envname]
```
And on OS X/macOS:
```sh
source activate [envname]
```
Jupyter notebooks can be opened using the command:
```sh
jupyter notebook
```
And virtual environments can be closed by (preceded by `source` on OS X/macOS):
```sh
deactivate [envname]
```
For more information regarding virtual environments, reference the [official Conda documentation](https://conda.io/docs/using/envs.html).