### Simple demo with Kedro framework

#### 1. Create a environment
```bash
conda create -n kedro_env python=3.8 -y
```
#### 2. Activate a environment
```bash 
conda activate kedro_env 
```
#### 3. Install Kedro
```bash
pip install kedro
```
#### 4. Install libraries
```bash
pip install scikit-learn pandas numpy
```
#### 5. To ckeck Kedro installation
```bash
kedro info
```
#### 6. To create a kedro project
```bash
kedro new
```
#### It will ask fro a project name:kedro_simple-iris

#### 7. To create a kedro project
```bash
kedro new
```

#### 8. To create a specific directory in a pipeline folder we can use command like:
```bash
	$ cd kedro-simple-iris/
	$ kedro pipeline create data_engineering
```

#### 9. To run kedro project
```bash
	$ kedro run
```
#### 10. To install kedro data pipeline visualization library
```bash
	$ pip install kedro-viz
```
#### 11. To visuzalize a kedro data pipeline
```bash
	$ kedro viz
```

#### 12. To install docker on kedro and to initialize dockerfile
```bash
	$ pip install kedro_docker
	$ kedro docker init 
```

#### 13. To to build docker image on kedro
```bash
	$ kedro docker build
```