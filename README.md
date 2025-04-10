# Audiobook App Customer Return Prediction

This project aims to develop a deep learning model that predicts whether a customer will purchase again from an audiobook app. By identifying customers with a low probability of returning, the company can save on advertising costs and focus marketing efforts on customers likely to convert.

## Data

The dataset contains customer purchase history and engagement metrics, including:

- Book length (overall and average)
- Price paid (overall and average)
- Review (Boolean and rating out of 10)
- Total listening minutes
- Completion rate
- Support requests
- Last visited

## Model

The model uses a TensorFlow Keras sequential neural network with three hidden layers (50 nodes each, ReLU activation) and an output layer (softmax activation for binary classification). The model is trained using the Adam optimizer and sparse categorical crossentropy loss function. Early stopping is implemented to prevent overfitting.

## Results

The model achieves an accuracy of around 82% on the training set and 80% on the validation set. Test accuracy varies slightly with each run.

## Future Work

- Explore alternative model architectures and hyperparameters to potentially improve performance.
- Incorporate additional features to enhance predictive power.
- Deploy the model for real-time predictions and integrate with the app's marketing system.
