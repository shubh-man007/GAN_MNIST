
# GAN based on MNIST
* This model is trained on the MNIST Dataset.
* The model tries to create images similar to that present in the dataset.




## Dependencies and Output Generation:

* Install required dependencies [make sure to install Jupyter Notebook]
```text
  torch
  torchvision
  tensorboard
```

```bash
  pip install -r requirements.txt
```

* Run the Jupyter Notebook
```bash
  jupyter nbconvert --to notebook --execute GAN_MNIST.ipynb
```

* Run TensorBoard
```bash
  tensorboard --logdir=runs
```




  


## Input:

![Alt text](https://github.com/user-attachments/assets/e2080f13-ed86-4f37-96ea-a444cae47318 "Real Input")

## Output

![Alt text](https://github.com/user-attachments/assets/9d3a9412-44a6-455e-8fb3-966ea812e85d "Generated Output")
