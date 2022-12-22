.. _howto/env/kernels:

======================================
Add kernels for other languages
======================================
TLJH comes with a default python kernel installed, but other kernels can be used to install other programming languages.



R
======================================

Install the R language, kernel, & dependencies with conda:

```
sudo -E conda install r-base r-essentials r-irkernel 
sudo -E chown -R `whoami` /opt/tljh/user/lib/R
```
