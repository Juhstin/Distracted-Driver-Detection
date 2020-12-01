# Distracted Driver Detection

### Distracted Driving Problem
- One in five car accidents is caused by a distracted driver. 
- This translates to 425,000 people injured and 3,000 people killed by distracted driving every year.

### Objective
- Given a dataset of 2D dashboard camera images, classify each driver's behavior 

### Data
- Training Data: 22,424 images 
- Testing Data: 79,700~ unlabeled images
- Classifications
  - Safe Driving, Texting-Right, Talking on Phone-Right, Texting-Left, Talking on Phone-Left, Operating the Radio, Drinking, Reaching Behind, Hair and Makeup, Talking to Passengers
  
### Model
- ResNet18 with an input size of 224x224x3
- Trained model by utilizing Stochastic Gradient Descent with cross entropy loss, SGD optimizer with a learning rate of 0.001, a momentum of 0.9, and Nesterov momentum
- Training Accuracy: 98.1%
- Validation Accuracy: 96.6%
