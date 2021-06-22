Setup Procedure for HATS
========================


Starting Jupyter
----------------

Before each session, you to start Jupyter and connect your web browser to it.
This step is documented at [HATSatLPCSetup2021](https://twiki.cern.ch/twiki/bin/view/CMS/HATSatLPCSetup2021).

Installing the Tutorial
-----------------------

Each tutorial needs to be cloned from GitHub, which can be done by following the instructions at the link above.

Once in the terminal, execute the following, replacing the URL with the URL
of the tutorial you'd like to run

```
git clone https://github.com/FNALLPC/spark-hats
```

If you had previously already checked out the spark-hats tutorial, in the terminal you should first

```
mv spark-hats spark-hats.backup
```
and then execute the git clone command above.

Installing Dependencies
-----------------------

This tutorial requires some additional libraries, which can be installed by
running the [setup notebook](setup-libraries.ipynb). This only needs to be
done once.
