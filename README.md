# Neural_Networks

## Written Analysis
Throughout my analysis and multiple attempts with deep learning models, I was unfortunately unsuccessful at reaching the target performance of 75%. My results would top out around 70% success at best.

### Optimization techniques and Initial Model

I tried multiple methods at trying to optimize my model in order to increase its predictive performance. The first Deep Learning Model used 2 Hidden layers with 10 inputs in Layer 1 and 5 in Layer 2. We used an activation function of Relu for the input layers and Sigmoid for the output layer. The optimizer I used is adam, and I tested on 50 epochs. The results from this first attempt were 69.6%.

The second model I tried, the change I made for optimization was that I tried changing the activation function in the hidden layers to sigmoid. Unfortunately, the results from this try were also unsuccessful, the model performed slightly worse, at 69.57%.

For the third model I decided to increase the number of neurons in the hidden layers. This time using 20 in Layer 1 and 10 in layer 2. This Had minimal effects, as the end result was 69.64% accuracy.

The fourth model kept these metrics the same, but I increased the epochs to 300. This didn't really work either as the performance stayed around 96.57%

The fifth model scaled back the epochs to 50, but I changes the activation function on the output layer to Relu. This helped only marginally. The accuracy ended up at 69.69%

I tried one more model, this time adding another hidden layer which contained 10 neurons. This didn't help either. The measured accuracy in the report was still edging around 70%.

### What I would do differently.
If I were to implement a different model, I would first like to try just either a logistical regression model or a Support Vector Machine for their simplicity. I would have liked to see if using a less complex model would have been significantly worse or not. Overall, after implementing all of these changes and seeing minimal results, I suspect that there is a problem with some of the features being used in the model. So while I think a different model would be a good choice, ultimately I believe that the features being used currently are confusing the model.

As a result, I would first pay more attention to the preprocessing and perhaps drop a few parameters in exchange for other ones. If that does not produce different results-good or bad, I would then opt for the simpler SVM or Logistic Regression Models.