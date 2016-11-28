# Volatility Framework IDE

The volatility memory forensics framework provides a toolkit for the inspection of main memory dumps, typically from systems that require analysis of their state at the time the memory image was taken.

The standard workflow involves using the framework and it’s associated plug-ins interactively from a terminal. This analysis then has the additional step of separately documenting the steps of the  analysis and it’s results. Also, many of the tools in volatility produce output that is longer than a standard terminal window.

Using command line tools like tee can help make this process more manageable, but are still not optimal for the task.

This juypter notebook is a short tool that makes the workflow and it’s output self documenting and shows the results in easier to use and search juypter browser cells.

To setup the notebook, replace the lines that contain the paths the volatility and the image for analysis. The notebook writes these settings out the volatility.rc file in the home directory. Out of an abundance of caution and care for any existing environment setups, the old version of this file is saved to backup on each run of the notebook. It’s recommend the user clean these backups after the analysis is complete.

To use the notebook, copy the command queue and run command into a new cell, adding the commands you want to run to the queue. It’s recommended that the user stick to a small command queue in sequential cells.

Written and tested with Volatility Framework 2.5 with jupyter notebook from Anaconda2 v4.2.0 for Linux-x86_64 running on Ubuntu 16.10.
