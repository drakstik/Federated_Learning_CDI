# Privately Predicting Child Developmental Delays using Federated Learning

This project explores the use of Federated Learning to predict CDD scores depending on child data. 

Due to the nature of child data, it is important it remains private. Federated Learning is a recent solution that allows clients' edge devices to transmit locally-ran model weights to a central server. The central server can then aggregate the weights and evaluate the model, if the central server has any raw test data thy can further evaluate the model resulting from client train data. 

The idea is that parents and edge devices can record child developmental data and help train a model predicting devlopmental delays, while preserving their data's privacy. Note that FL alone does not provide complete privacy and differential attacks could still lead to client information being divulged. To protect against this, the model can be made into a Differentially Private Federated Learning Model. This comes with a privacy and model performance tradeoff that is dependent on the size of clients. Future work would be to evaluate the cost of adding Differential Privacy to our FL model.

The dataset in this project is propriatery and will not be divulged. However, the dataset is proprietary, and as such will not be stored on any public platforms. The project is therefor only accessible to authorized individuals. To get access to the dataset, please contact dmbering@andrew.cmu.edu or ggopi@andrew.cmu.edu.

This project simulates training and evaluating an FL model, however, it cannot be extrapolated to any real world scenario. We measure the theoretical differences between our centralized model and federated learning model. 

## Contributors
<a href="https://github.com/OWNER/REPO/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=drakstik/Federated_Learning_CDI" />
</a>
