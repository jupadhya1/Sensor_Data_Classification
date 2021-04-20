Hello !<br/>

Welcome to my submission<br/>

Here within tool-signal you find two folders:<br/>
1. notebooks:<br/>
This folder contains my .ipynb code for the modeling exercise. It is sequenced and code-commented for an easy walkthrough of the steps and my though process.

2. assets:<br/>
This folder contains data ( cleaned / meta ) and the various models I create and use in the process.

<u>A brief about the exercise:</u><br/>
1. I found the datasets for this exercise to be very noisy and cross-contaminated. This was unearthed by using mean shifts and EWMA convolving on the signal data. It also helped me find out that tools (ABC) contain patterns that are orthogonal to tools (DE). A classifier built around this observed bin classification using signal and EWMA convolved trend achieves accuracy of 85 %.
2. With this information, I proceed to iteratively extract signal patterns using LSTM autoencoders for one tool and use this to clean other tool informations, thus iteratively making the tool signal trend more prominent on EWMA and inproving the capturable information via variance.
3. Finally, once cleaned, a naive LSTM classifier to classify each signal type achieves an accuracy of 70 %
4. Please follow the short notebooks sequenced with comments, to see the stated analysis, results and steps in details.
                                                                                             
Lastly, thank you for this dataset, I enjoyed it and it was a lot of fun. Let me know in case of any issues. I would be happy to help 😊.<br/>
