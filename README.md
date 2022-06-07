Create the custom Data loader for Image classification.
We can face the issue of dataset loading. In order to avoid this issue, we can do multiprocessing by using keras sequence class. 
The custom Data loader loads the single Batch in a RAM and use it for fitting the model during training. 
While trainig a batch due to multiprocessing it will load the 2nd batch in RAM.
