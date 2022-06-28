# Development Setup

To develop/test you need:
- Python 3 installed
- pip3 installed
- apache beam installed through pip

## Install Pythong/Pip

Note: If on a mac, installing through Home Brew is generally considered the best way:
[Python Home Brew](https://formulae.brew.sh/formula/python@3.9)

It will likely install pytoin3 and pip3 binaries, without python and pip symbolic links. Thus, when you see tutorial/instrictions to use **python** you type **python3**, and the same with **pip** and **pip3**

Alternatively, you can create symbolic links python -> python3 and pip -> pip3

You can find the location of python3 and pip3 using the 'which' command:

```which python3```

## Create an Environment

In the directory of your project:

```python -m venv ./```

then:

```./bin/activate```

## Install Apache Beam

Using pip/pip3, you install apache beam with:

```pip install apache-beam```

see: (https://beam.apache.org/get-started/quickstart-py/)
