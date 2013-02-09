Data & ipython notebooks for code for O'Reilly book by Wes McKinney:

[Python for Data Analysis.](http://shop.oreilly.com/product/0636920023784.do)

To get ipython notebooks up and running on Ubuntu run:

* sudo aptitude install `cat debs.txt`
* mkvirtualenv --system-site-packages pydata-book
* pip install -r requirements.txt
* ipython notebook --pylab inline
