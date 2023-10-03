### Simple demo with Kedro framework

#### 1. Create a environment
'''bash
conda create -n kedro_env python=3.8 -y
'''
#### 2. Activate a environment
'''bash 
conda activate kedro_env 
'''

#### 3. Install Kedro
'''bash
pip install kedro
'''

#### 4. Install libraries
'''bash
pip install scikit-learn pandas numpy
'''

#### 5. To ckeck Kedro installation
'''bash
kedro info
'''
#### 5. To create a kedro project
'''bash
kedro new
'''
#### It will ask fro a project name:kedro_simple-iris