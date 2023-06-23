![MLOPS](https://github.com/andysingal/mlops/blob/main/Screenshot%202023-05-25%20at%201.43.11%20PM.png)
![MLOPS tools](https://github.com/andysingal/mlops/blob/main/Screenshot%202023-05-25%20at%201.49.23%20PM.png)


| Books and Resources | Status of Completion |
| ----- | -----|
| 1. **Practicing Trustworthy Machine Learning** | |
| 2. **Hands-On Unsupervised Learning Using Python** | |
| 3. **Hands-On Gradient Boosting with XGBoost and scikit-learn** | |
| 4. **XAI-for-practitioners** | |

COOKIECUTTER:
- https://github.com/cookiecutter/cookiecutter
- https://github.com/khuyentran1401/data-science-template

MLOPS
- https://pub.towardsai.net/mlops-build-and-deploy-first-machine-learning-application-with-kubernetes-a528961fd0e7
- https://github.com/trainindata/deploying-machine-learning-models

FAIRNESS IN AI: 
- Use Evaluate Library in Hugging face to check for Toxicity, Polarity, and Hurtfulness: Please further check the following :
- https://huggingface.co/blog/evaluating-llm-bias
- https://www.amazon.science/publications/bold-dataset-and-metrics-for-measuring-biases-in-open-ended-language-generation
- https://aif360.readthedocs.io/en/latest/modules/sklearn.html

<h1>you will know how to:</h1>

- design a batch-serving architecture
- use Hopsworks as a feature store
- design a feature engineering pipeline that reads data from an API
- build a training pipeline with hyper-parameter tunning
- use W&B as an ML Platform to track your experiments, models, and metadata
- implement a batch prediction pipeline
- use Poetry to build your own Python packages
- deploy your own private PyPi server
- orchestrate everything with Airflow
- use the predictions to code a web app using FastAPI and Streamlit
- use Docker to containerize your code
- use Great Expectations to ensure data validation and integrity
- monitor the performance of the predictions over time
- deploy everything to GCP
- build a CI/CD pipeline using GitHub Actions

![21](https://github.com/andysingal/mlops/blob/main/Images/Screenshot%202023-06-14%20at%208.47.14%20PM.png)

- Feature Store: the feature store stays at the heart of any ML system. Using a feature store, you can easily store and share features across the system. You can intuitively see a feature store as a fancy database that adds the following features:

- data versioning and lineage
- data validation
- the ability to create datasets
- the ability to hold train/validation/test splits
- two types of storage: offline (cheap, but high latency) and online (more expensive, but low latency).
- time-travel: easily access data given a time window
- hold feature transformation in addition to the feature themselves
- data monitoring
