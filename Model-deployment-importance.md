- To start using a Machine Learning Model, it needs to be effectively deployed into production, so that they can provide predictions to other software systems
- To maximize the value of the Machine Learning Model, we need to be able to reliably extract the predictions and share them with other systems
- Real-time Predictions: Deployed models enable businesses to make real-time predictions or decisions based on new data, facilitating quick responses and proactive decision-making.
- Automation: By integrating models into production systems, businesses can automate processes that rely on data analysis, reducing manual effort and improving operational efficiency.
- Scalability: Model deployment allows organizations to scale their machine learning capabilities to handle large volumes of data and serve multiple users or applications simultaneously.
- Consistency and Reliability: Deployed models ensure consistent and reliable predictions or decisions, minimizing human errors and biases that may arise in manual decision-making.
- Continuous Improvement: Monitoring and updating deployed models enable organizations to continuously improve model performance and adapt to changing business needs.


<img width="822" alt="Screenshot 2024-04-27 at 9 59 41 PM" src="https://github.com/andysingal/mlops/assets/20493493/29e55068-b9b0-4057-9ead-add557268ef7">

CHECKLIST
It's also useful to observe the links and dependencies across different best practices:
- Without model specification review and version control, it would be hard for reproducible training
- Without reproducible training, the effectiveness and predictability of canary releases are significantly reduced
- Without knowing the impact of model staleness, it's hard to implement effective monitoring

Serving ML Models - Formats
- Serializing the model object with pickle
- MLFlow provides a common serialization format for exporting/importing Spark, Scikit-Learn and Tensorflow models
- Language-agnostic exchange formats to share models, such as PMML, PFA, and ONNX

## Architecture 1: 
<img width="1035" alt="Screenshot 2024-05-04 at 8 34 27 PM" src="https://github.com/andysingal/mlops/assets/20493493/ade9cd85-6bf7-4ad1-aaf4-1e83fa969539">

