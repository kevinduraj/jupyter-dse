Jupyter Notebook with DSE
=========================

### Install Jupyter
```
pip install -U jupyter
pip install --upgrade "ipython[all]"
```

###Location: Root Directory
* /root/kernel-0.1.4.4-cassandra
* [Source : DSE Spark Kernels for Scala and Python](https://github.com/slowenthal/spark-kernel)
* [Release: DSE Spark Kernels for Scala and Python](https://github.com/slowenthal/spark-kernel/releases)

###Location: DSE Kernels
* /root/.local/share/jupyter/kernels

###Spark Examples:
[DS320: DataStax Enterprise Analytics with Apache Spark](https://academy.datastax.com/courses/getting-started-apache-spark)

###Install R Kernel for Jupyter
* yum install r

* http://conda.pydata.org/miniconda.html
  * conda install numpy
  * conda create -n py3k anaconda python=3
  * conda install -c r ipython-notebook r-irkernel
  * conda create -n myenv python
  * conda install -c r r-essentials
    * conda create -n my-r-env -c r r-essentials

* ipython notebook

### References:

[http://blog.revolutionanalytics.com/2015/09/using-r-with-jupyter-notebooks.html](http://blog.revolutionanalytics.com/2015/09/using-r-with-jupyter-notebooks.html)
[https://www.continuum.io/blog/developer/jupyter-and-conda-r](https://www.continuum.io/blog/developer/jupyter-and-conda-r)

