# Deploying-a-Machine-Learning-Model-on-Kubernetes-with-Kubeflow

Key Topics Covered:

Building a Machine Learning Model:

    Machine Learning deployment is becoming a crucial part of the pipeline.
    Kubeflow is an open-source ML toolkit that simplifies deployment at scale on Kubernetes.
    Built a simple Support Vector Machine (SVM) classifier using Scikit-Learn.
    Used the Iris dataset, containing measurements for 150 iris flowers, to classify the flowers into three species.
    Accuracy of the trained model should be around 97%.

Deploying a Model on Kubernetes with Kubeflow:

    Packaged the model as a Docker container using a Dockerfile.
    Created a Kubernetes manifest file to deploy the model using Kubeflow's TensorFlow Serving component.
    Used Minikube to deploy a Kubernetes cluster locally.
    The manifest file defines a service and a deployment that specifies how many replicas of the service should run.
    The service maps the container port to a target port.
    The deployment specifies the container image and the environment variables needed to run the service.
    Kubeflow provides other components such as Jupyter Notebooks and Argo Workflows to simplify the entire ML workflow.

Conclusion:

    Kubeflow simplifies deploying machine learning models at scale on Kubernetes.
    Using Kubeflow, we were able to deploy the model with ease.
    Kubeflow provides many other components such as Jupyter Notebooks and Argo Workflows to simplify the entire ML workflow.
    The article hopes to have given readers a good introduction to deploying machine learning models on Kubernetes with Kubeflow.
    
    
    
Check out the blog post here: https://medium.com/@haider.zaidiy/deploying-a-machine-learning-model-on-kubernetes-with-kubeflow-15322a69ea1f

#Kubernetes #DevOps #Kubeflow
