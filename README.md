# roger-dog-space-time
# Azure AI first workspace notes and raw code with step-by-step instructions </br>
# Setting up your Azure environment </br>
To start, create a notebook called _test.ipynb_ and make sure that it is working under the latest kernel version of Azure ML. Then type in the following code in the noteboook shell:</br>
_import tensorflow as tf_ </br>
_print("TensorFlow Version: " + tf.__version__)_ </br>
You will see error messages because the following pertains to GPU when we are using CPU. </br>
After, stop running the compute instance to *avoid extra charges.*

