# cassandra-sigv4-layer

A lambda layer for the python cassandra driver.

Steps to create using the Cloud9 IDE:

1. Create a python virtual environment and install the cassandra-sigv4 driver.

```
mkdir cassandra-sigv4
cd cassandra-sigv4
python3 -m venv cassandra-sigv4
source cassandra-sigv4/bin/activate
pip3 install cassandra-sigv4

```
2. Create a requirements.txt file.

```
pip3 freeze > requirements.txt
```

3. Install the packages from requirements.txt into a directory called python.

```
pip3 install -r requirements.txt -t ./python
```

4. Zip the contents of the python directory into a file called python.zip.

```
zip -r python.zip python
```
