# HW-14 Deep Learning
## Evaluation of the models
## The closing price model works better than the fng model since the closing price model has a lower loss value. 
 ## Experiment with window sizes 
 Smaller window size works best for the closing price model. The closing price model with Windo=1 has the lower loss % than that with window=10.

### Experiment with batch sizes
   ### Batch size 1 loss: 0.0120
   ### Batch size 2 loss: 0.0094
   ### Batch size 3 loss: 0.0068
   ### The loss % with batch size 1 is already less than 5%. It becomes less than 1% by changing the bach size to 2. 
   ### Thus, the batch size 1 or 2 should be acceptable for the closing price model.        
   
