# Test of jupyter notebook interactive widget embeded in html page



__Objective__: Share interactive functions and plots without installing python environment based on this developper [JupyterCon presentation](https://www.youtube.com/watch?v=jln6h-dE2-0).  
__Method__: The package [nbinteract](https://www.nbinteract.com/) generates an html page from the notebook.  
__Result__: [click here](https://github.com/Alienor134/html_widgets/blob/master/plot_spectra.html)  



__Behind the scene__: The widgets are connected to a python environment hosted on [Binder](https://mybinder.org/).
Binder builds a docker based on the content of the Github repo. The whole notebook and environment is available and editable if you [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Alienor134/html_widgets/master)
