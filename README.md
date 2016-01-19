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

###Install R Engine

* yum install r
* R

###Run R Shell (R)

* install.packages("devtools")
* install.packages('RCurl')
* library(devtools)
* install_github('armstrtw/rzmq')
* install_github("takluyver/IRdisplay")
* install_github("takluyver/IRkernel")
* IRkernel::installspec()


```
install.packages(c('rzmq','repr','IRkernel','IRdisplay'), repos = c('http://irkernel.github.io/', getOption('repos'))) 
IRkernel::installspec()
```
