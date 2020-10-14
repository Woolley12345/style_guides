# style_guides
Contains my custom matplotlib style guides 


These style guides can be used by following the process below:

1) Save the style guide file (with extension .mplstyle) into your /.matplotlib/stylelib/ folder. You may have to create the stylelib folder yourself if it does not exist already
2) Import matplotlib.pyplot as plt
3) Run plt.style.use('style_guide_name')   e.g. plt.style.use('scientific')


If the style of plots does not update correctly (i.e. there are no changes to the plotting style) try closing the open kernel and re-importing matplotlib in a new kernel

Note: You can find out where you matplotlib directory is by running:
import matplotlib as mpl
mpl.get_configdir()
