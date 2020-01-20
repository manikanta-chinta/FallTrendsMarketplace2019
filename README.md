# Model Performance Decay
## Stay Tuned With Your Model

The data science world as we know is obsessed with building most innovative and effective predict models. But model building part is just half the predictve life cycle there is another side to it, a very important one, the model deployment and monitoring which is very less talked about or discussed.

A model which shows good performance during the training phase slowly decays in production environment and the main reason behind this is the change in evrironment or in terms of data, the change in the new incoming data. This throws the model off because it is stil trying to predict the target variable based on the assumptions we made and the boundaries that the model calcluated based on the old training data.

**The consequences** - Wrong predictions, loss of time, money and additional risk in case of regulatory line of work.

**Solution** - To avoid the performance decay we have to re train the model often. But when is the right time? what is the right duration to wait before we can train. We need a way to know when there is a change in data and to solve this we implemented a solution where when there is significant enough change, we notify the respective stake holders about the change and possibile need to retrain the model.

Our project will help the business to avoid all the above consequences mentioned above and also on how to get the best use of the new data.

*Presentation Voice Thread:* https://auth.voicethread.com/share/13430906/

https://www.cs.waikato.ac.nz/~abifet/PAKDD2011/PAKDD11Tutorial_Handling_Concept_Drift.pdf

https://mlinproduction.com/model-retraining/

https://towardsdatascience.com/why-machine-learning-models-degrade-in-production-d0f2108e9214
