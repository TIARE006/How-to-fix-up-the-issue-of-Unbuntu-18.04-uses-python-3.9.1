1、Download the package of python 3.9.1 in the repository and extract

2、Open your terminal in the package location
> tar -xf Python-3.9.1.tgz

3、Check dependencies and test
> cd Python-3.9.1 && ./configure --enable-optimizations

4、Build using make file
> make -j 12

5、Install python
> sudo make altinstall

6、Check version and location
> python3.9 --version
Python 3.9.1

> which python3.9
/usr/local/bin/python3.9

7、 Add Python version to update-alternatives
> sudo update-alternatives --install /usr/bin/python python /usr/local/bin/python3.9

> sudo update-alternatives --install /usr/bin/python python /usr/bin/python3.6 2

8、Select the default Python version and Select the number of the Python version you want to use and press Enter.
> sudo update-alternatives --config python

9、python --version
