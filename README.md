How to run
=========

This program is based on Python2 and some Python packages. You can install all of them with the following commands:

 ```shell script
virtualenv --python=`which python2.7` python-env
source python-env/bin/activate
pip install -r requirements.txt
 ```

Install the licensed version of GraphQL:

```shell script
pip install --upgrade --no-cache-dir https://get.graphlab.com/GraphLab-Create/2.1/sadrnezhaad@ce.sharif.edu/138D-5B50-E111-25FF-AA35-CB81-6658-D445/GraphLab-Create-License.tar.gz
```

Run the Jupyter Server on your console:

```shell script
source python-env/bin/activate
python-env/bin/jupyter notebook
```

Open the browser and run the code.