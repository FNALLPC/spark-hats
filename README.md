# Big Data with Spark HATS

This Hands on Advanced Tutorial Session 
([HATS](http://lpc.fnal.gov/programs/schools-workshops/hats.shtml)) is
presented by the LPC to demonstrate a CMS analysis using
[Apache Spark](http://spark.apache.org/),
[Spark-ROOT](https://github.com/diana-hep/spark-root),
[Histogrammar](http://histogrammar.org/), and
[MatplotLib](https://matplotlib.org/). After introducing Spark and
the paradigm it brings with it, students will learn some
basic building blocks then combine them to perform a basic measurement
of the Z-boson mass using CMS data recorded in 2016.

## Getting Started

Students of the HATS will be provided access to Vanderbilt's
[Jupyter](https://jupyter.accre.vanderbilt.edu) instance using their
CERN username. The jupyter instance contains this repository and
all necessary software preconfigured.

### Pre-Exercises

The day before the tutorial, it's critical that each student perform the
pre-exercises. This way, any potential technical/login issues can be cleared
up beforehand. To perform the pre-exercises, connect to
[Jupyter](https://jupyter.accre.vanderbilt.edu). You will first need to log
in to CERN and authorize Jupyter to authenticate (don't worry, CERN
doesn't transfer your password, just a secret authentication token).

Once you've given [Jupyter](https://jupyter.accre.vanderbilt.edu) permission
to authenticate, click "Start My Server" to start your Jupyter instance.

Once your server starts, you'll be placed into the Jupyter file browser. Then,
navigate to
```
spark-hats/notebooks/10-building-blocks.ipynb
```
to begin the tutorial.

### Accessing this Tutorial in Jupyter

Once logged into [Jupyter](https://jupyter.accre.vanderbilt.edu), navigate to the `spark-hats`
directory and open the notebook named `setup-libraries.ipynb`

## Built With

* [Jupyter](http://jupyter.org/) - Interactive python notebook interface
* [Apache Spark](http://spark.apache.org/) - Fast and general engine for large-scale data processing
* [Spark-ROOT](https://github.com/diana-hep/spark-root) - Scala-based ROOT/IO interface to Spark
* [Histogrammar](http://histogrammar.org/) - Functional historgamming framework, optimized for Spark
* [MatplotLib](https://matplotlib.org/) - Python plotting library

## Authors

* **Andrew Melo** - [http://lpc.fnal.gov/fellows/2017/Andrew_Melo.shtml]

## Acknowledgments

* The LPC Distinguished Researcher Program ([link](http://lpc.fnal.gov/fellows/2017.shtml)) - *Support for the author*
* Advanced Computing Center for Research and Education (ACCRE) ([link](http://www.accre.vanderbilt.edu/)) - *Host facility and sysadmin support*
* The Diana-HEP project ([link](http://diana-hep.org/) - *Interoperability and compatibility libaries*
* Vanderbilt Trans Institutional Program (TIPs) Award ([link](https://vanderbilt.edu/provost/occi/tips.php)) - *Big Data hardware seed funding*
