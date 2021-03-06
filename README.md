## Install

### Python
- Make sure that python and pip are installed on your machine.
- You can check your current default version of Python by executing
```
$ python -V
```
- Version should be >= 2.7.12+

- After we have successfully installed Python, we can execute pip from the command line terminal to install additional Python packages:
```
pip install SomePackage
```
- Install all the required python packages using the below commands.
```
$ pip install -r requirements.txt
$ pip install .
```

### NodeJs
- Once you have installed python packages now you have to install js packages.
- Update your local package index:
```
$ sudo apt-get update
```
- Install Node.js:
```
$ sudo apt-get install nodejs 
```
- You will also want to install NPM, which lets you easily manage your different Node.js packages.
```
$ sudo apt-get install npm 
```
- Now install the npm packages(babel, etc) present in package.json using the following command.
```
$ npm install
```

### Babel
- Babel has been used to transcompile the ES6(EmaScript) js code to ES5 and runs the ES5 script.
- You can see more detailed documentation of Babel [here](https://kleopetrov.me/2016/03/18/everything-about-babel/).

## Usage

- Execute the bash script file 'run.sh' to classify users and generate the offers.
```
$ ./run.sh
```

- After the exectution of the above command users are classified and offers are generated.
- The final output can be seen [here](golive/output/final_output/output.json).
