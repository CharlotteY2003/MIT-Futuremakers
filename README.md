# MIT-Futuremakers

# Responses
7/6 - I'm hoping to learn the fundamentals of AI and apply it to sofware projects focusing on social impact. <br> <br>
7/7 - Our identity isn't individual - we are part of communities. First step to reach our shared goal is crafting a well-thought out narrative (story telling). Need head and heart to execute mindful action successfully (strategy analysis and story motivation). Emotions can affect whether we take our actions (inhibitors or motivators). All good stories have choice, challenge, and outcome. Most have some type of moral or lesson. Story of us (community), self (call to leadership), and now (strategy and action). Pick one or two key choice points that relate to your calling today. Before the leadership session, I thought that my story wasn't worth sharing, but after lisetening to other people's stories and hearing about how well-crafted stories can convey people's stories no matter the persepctive, I realize that everyone's stories need to be heard. <br><br>
7/8 - i.) Supervised learning uses labelled datsets that already have actual results to train the model. Unsupervised learning uses no labelled data during the training process and usually is used to find patterns/relationships among the dataset <br>
ii.) Sklearn does not have the ability to visualize data without additional libraries as sklearn was created for a software engineer's perspecive - focusing on machine learning and data modeling. <br><br>
7/9 - <a href = 'https://www.kaggle.com/adityakadiwal/water-potability'>Dataset</a> <br>
  I would use convonlutional neural networks to develop a solution to detecting clean water because they can be have the benefits of recurrent or feed-forward, while needing fewer weights. They are also faster to count and less prone to overfitting.  <br><br>
7/12 - Tensors are multidimensional arrays that are a combination of components and basic vectors, making them unique. They are used to encode multidimensional data in machine learning. I noticed that the interactive programs I ran in the TensorFlow programs it was able to handle larger datasets and produce more computations in less time.  <br><br>
7/13 - I learned several aspects of Natural Language Processing while I was building my neural network. Input data, which is represented in a string of text, is broken down into individual units in a process called tokenization. Stopwords, also known as common words that do not add meaning, are removed from the training data to streamline the computing process and allow the NN only to extract the most salient features. Lemminization is used to reduce words based on actual dictionary meaning without chopping words into forms that do not make sense semantically. Then words are converted into arrays of numbers through word vectorization for the NN to understand and train through. <br><br>
7/14 - CNNs are composed convolutional layers, pooling layers, activation layers, flattening layers, and fully connected layers. They can house multiple channels, making it useful for image recgonition and detection. <br><br>
7/15 - Machine Learning was used to determine which applicants were considered "hireable" material or not for the startup. Using machine learning models and the data of the user selecting recruits, the model mimicked our recruting choices. However, it also brought up human biases propogated in machine leanring, as the model picked up on our unconcious bias of preferring orange over blue people. The model uninteionally learned to amplify our biases, discriminating against qualified blue canidates due to the training set having more ornage people that were hired and possibly the model learning to make an assoication that orange people = more qualified. A real world example of a biased machine learning model is the google image recongition model, where the model may inaccuretly label minorities due to having biased datasets/sample sizes. I would make this model more fair and inclusive by collecting trained datasets that are not similar in distrubtion and collect the data from multiople sources, making sure that the sample sizes for each subgroup are around equal and the data is representative, not prepretuating any stereotypes among the groups. I chose the model because if image recongition continues to provide unfair treatment to certain subgroups, and as technology becomes even more prevalent in our everyday lives, than these people may suffer from the same prejudice explicityly banned in legislations that are propogarted through technology. I intend to avoid algorithmic biases by making sure that my training dataset has a near equal representation of all subgroups and is representative of the range between them. For my evaluation of the model, I'll aslo check to see if my model performs around the same in each subgruop, making sure that one or more subgroups are not being marginilizied. <br><br>
7/16 - CNNs have sparse interaction, meaning that every input does not connect to every output. However, in fully connected NNs, each input is connected to all neurons. CNNs can take in multidimensional (3d) inputs like images, while fully connected NNs can not without modifications to the input. CNNs also have shared parameters, meaning that for getting output, weights applied to one input are the same as the weights applied to all other inputs. Unlike CNNs, fully connected NNs use each element of the weight matrix once and do not revisit it. A CNN is typically composed of convolutional layers, activation layers, pooling layers, flattening layer, and fully connected layers. A convolutional layer is a feature extraction layer returning a 2d feature map. Activation layers apply nonlinearity to the outputs from the previous layer and used to learn more complex features. Pooling layers decrease the size of the feature map and extract only the most important features. Flattening layers convert the 2d feature maps into single linear vector for the fully connected layer. Fully connected layers utualize all features from the previous layers to classify, predict, and return an output. Fully connceted NNs have activation layers that are fully connected to each other and return an output at the last layer. They are composed of an input, activation, and output layer. CNNs can be used for image recongition and classification. Fully connected NNs can be used for more generalized purposes, including regression and classification of stock prices, objects, and grade predictions. <br><br>
7/19 - Loss functions can determine how fast a neural networks learns from the training data and their outputs help with optimization of the model's weights. Several different types of loss functions can be used depending on the type of value the model is predicting, and certain functions can penalize heavily or be more lenient on value ranges. <br><br>
7/20 - One advantage of relu is that it solves the vanishing graident problem found in sigmoid and tanh activation functions, where the graident is effectively killed during backproprogation when the input values go towards both extremes. Relu is simple coputationally, requiring only a max function and does not use exponentials unlike sig or tanh. Unlike the previous functions, relu can output a true 0, meaning it allows for sparse representaiton and accelereates learning and simplifies the model. Relu activation functions also mostly behave like linear functions, making them easier to optimize. One use case for relu function is CNNs or MLPS, as they typically have many hidden layers that do not need any more computional complexity from their activaiton functions. <br><br>
7/21 - Software devleopers need to understand what biases their dataset holds and the context/impact of their project. If they do not account for pre-existing bias, bias in their data, and technical bias, where the algorithm is programmed in some way where it does not account for the context its purpose is for, then the bias can be amplified during the model's deployment. One way of evaluating a model's scope of impact and identification of any problems is through the use of algorithmic impact assessments, which provide a framewok on the project's scope and how to identify any potential problems arising in the project. Developers could also use FairML, LIME, and DEON as ethic checkers to their code. <br><br>
7/22 - I figured out how to download files into my computer locally through colab. I learned that Xception is a special type of CNN and used data augmentation to artifically increase the dataset through transfomations. <br><br>
7/23 - When I changed the loss function from binary_cross entropy to regression based loss functions, the model loss seemed to be similar regardless of what loss function was used. However, the model accuracy for the regression based loss functions was worse than the model that used binary_cross_entropy. 
  
