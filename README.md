# **Evaluation of the models**
## *Closing Price VS FNG*
   ### The closing price model works better than the fng model since the closing price model has a lower loss value. 
## *Experiment with window sizes* 
   ### Smaller window size works best for the closing price model. 
   ### The closing price model with window_size=1 has the lower loss % than that with window_size=10.

## *Experiment with batch sizes with the closing price model, window_size=1*
   ### Batch size 1 loss: 0.0255
   ### Batch size 2 loss: 0.0084
   ### Batch size 3 loss: 0.0035
   ### The loss % with batch size 1 is already less than 5%. It becomes less than 1% by changing the batch size to 2. 
   ### Changing to 3 makes the loss value further down. However, the declining amount from 2 to 3 
   ### is not as much as it happened from 1 to 2.

## In conclusion, 
## the closing price model with window_size = 1 and batch size = 2 would be the best model in this case. 
   
