#Unit 14 HW
##DEEP LEARNING
### Alex Waters 8/9/20
---
**LSTM Stock Predictor-LSTM RNN models**
QUESTIONS
1. Which model has a lower loss?
Model: LSTM RNN closing
loss @ window 10 is .0444, window 5 loss is .0274, window 1 is .0202
Model: LSTM RNN FNG
loss@ window 10 is .0901, window 5 loss is .0836, window 1 is .0889
The model based on closing price had the lowest loss with a window of 1, but out performed the FNG model even with its worst loss at window 10.

2. Which model tracks the actual values better over time?
The model based on the closing price seems to be a closer match than the model based on FNG

3. Which window size works best for the model?
On the closing price model I ran window sizes of 1, 5, and 10.  The window size of 1 had the real and predicted values with the most similiar line chart and with all windows seemed to be consistently better than the FNG models even after running more than 10 epochs.
