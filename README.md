HPC Cloud Benchmarking
======================

Description
---
This repository contains the files required to test two of the most used apps on KAUST clusters. The tests here measures the required time to finish VASP and Gaussian jobs and compare it to the baremetal performance.

Usage
---
* Clone the repo to your scratch directory.
    * `git clone git@github.com:kaust-rc/cloudtest.git`
* Run `./start-testing` script with the required parameters.
    * Example `./start-testing -a vasp -c azure -q vasp -j small`
        * This will submit vasp test to the aws cloud and get the results in the results directory.
    * For further information `./start-testing -h`
