# HW14
Homework 14

Please find homework files in folder "Code".

Please find answers to the evaluation questions below:

> Which model has a lower loss?
The fng_value model has a lower loss (when using a batch size of 45)

> Which model tracks the actual values better over time?
The model based on closing prices seems to better track actual gold values over time. This conclusion is supported by the fact that the evaluation of the closing price model results in a value of 0.010992800816893578 while evaluation of the fng_value model results in a value of 0.06558142602443695

> Which window size works best for the model?
Window size of 10 seems to work better than a window size of 5. Evalution of the closing price model using a window size of 5 results in a value of 0.057066116482019424, whereas evalution of the closing price model using a window size of 10 results in a value of 0.010992800816893578
