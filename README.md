# cassandra-sigv4-layer

A lambda layer for the python cassandra driver.

Steps to create using the Cloud9 IDE:

```
mkdir cassandra-sigv4
cd cassandra-sigv4
python3 -m venv cassandra-sigv4
source cassandra-sigv4/bin/activate
pip3 install cassandra-sigv4

```

```
pip3 freeze
```

returns the following:

boto3==1.26.129

botocore==1.29.129

cassandra-driver==3.27.0
cassandra-sigv4==4.0.2
cffi==1.15.1
click==8.1.3
cryptography==40.0.2
geomet==0.2.1.post1
importlib-metadata==6.6.0
jmespath==1.0.1
pycparser==2.21
python-dateutil==2.8.2
s3transfer==0.6.1
six==1.16.0
typing_extensions==4.5.0
urllib3==1.26.15
zipp==3.15.0


```
mkdir python
```


```
zip -r python.zip python
```
