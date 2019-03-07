# Machine-Learning(INTRODUCTION)
               <.....This repository gives you brief details of what is machining learning actually.....>
 
Before going to start,understand the basic terminologies and types involved in Machine-Learning.The common question mostly asked is "What is machine Learning?".There are so many definitiond to it.But the basic concept is-ML(MachineLearning) gives a machine  the ability of thhinking!!.Thinking involves making own Decisions.To give a machine the ability of thinking,it should learn how to think and make decisions.This rises the concept of Learning.
                 Learning is the process of converting experience into expertise or knowledge.Learning can be broadly classified into three categories, as mentioned below, based on the nature of the learning data and interaction between the learner and the environment.

                                      -Supervised Learning
                                      
                                      -Unsupervised Learning
                                      
                                      -Reinforcement learning
1)SUPERVISED LEARNING:  
                 Supervised learning is a type of machine learning that enables the model to predict future outcomes after they are      trained based on past data.raining is done by providing a set of inputs and outputs that help the system understand what the essential features are.
             
             EXAMPLE:A model is trained on data which specifies the gender as either male or female.when a test data(of female) is fed to this model it outputs it as female based on its training on same kind of data. 

Supervised Learning is further classified into two types.they are:
         
                          a)REGRESSION(the system tries to predict a value for an input based on previous information)
                                
                                - Simple Linear Regression
                                - Multiple Linear Regression
                                - Polynomial Regression
                                - Support Vector Regression(SVR)
                                - Decision tree regression
                                - Random forest Regression
                          b)CLASSIFICATION(have a categorical output like a ‘yes’ or ‘no’, ‘1’ or ‘0’, ‘True’ or ‘false’.)
                               
                               - Logistic Regression
                                - K-Nearest Neighbours(K-NN)
                                - Support Vector Machine(SVM)
                                - Kernel SVM
                                - Navie Bayes
                                - Decision Tree Classification
                                - Random Forest Classification

2)UNSUPERVISED-LEARNING:
                  It refers to when systems are able to make sense out of the data only using what was provided as input. It would identify patterns, anomalies and similarities in the data. It makes the data more readable and organized.
                  
           EXAMPLE:You are studying facebook profiles of students of a class. Your task is to identify the groups in the class. As data, you have the number of times person A tags person B and vice-versa (let's start with a simple example).Let's assume the max number of A<->B tagging, across the class is N. Now, let person X and Y have tagged each other "p" times, (N-p) would be a measure of their distance.Now, put two people in the same group if their (N-p) distance is below a threshold. You end up with groups in the class. This is the concept of strongly connected components. Here the minimum distance between elements of two clusters is fixed. 
                 
Unsupervised-Learning is further classified into two types.They are:
                          
                          a)ASSOCIATION(we identify patterns of associations between different variables or items.)
                                
                                - Apriori
                                - Eclat
                          b)CLUSTERING(has observations divided into subsets,which are known as clusters.The observations inside these clusters are similar to each other.)
                          
                                - K-Means Clustering
                                - Hierarchical Clustering

3)REINFORCEMENT-LEARNING:
                   Reinforcement learning is a kind of Machine Learning where in the system that is to be trained to do a particular job, learns on it’s own based on its previous experiences and outcomes while doing a similar kind of a job.
                 EXAMPLE: Self-Driving cars terchnology is purely based on reinforcement learning
    
Reinforcement-Learning is further classified into two types.They are:

                           a)Natural Language Processing(the goal is to make machines understand our language) 
                           b)Deep Learning(It mainly involves training the Neural networks)
                               - Artificial Neural Networks
                               - Convolution Neural Networks
