MLOps: “DevOps for machine learning” 
Technique for creating policies, norms, and best practices for machine learning models
Goal: 
Guarantee the whole lifecycle of ML development — from conception to deployment — is meticulously documented and managed for the best results instead of investing a lot of time and resources in it without a strategy.
MLOps Tools:
Use: Platform administration
     Individual component management
[ 
Managing data
Design and modeling
ML model deployment and continuous upkeep
Lifecycle management from beginning to end
Management of projects and workplace
]

Tools: (Open Source)
Top in Paid and Unpaid:

Kubeflow: https://www.kubeflow.org/docs/started/introduction/
A complete open source MLOps solution, Kubeflow facilitates the deployment and orchestration of machine learning workflows. For several stages of machine learning, including training, pipeline development, and maintenance of Jupyter notebooks, Kubeflow offers specialized services and integration.

MLFlow: https://mlflow.org/ (Yannick)
MLFlow is an open-source platform that offers several components for tracking experiments, project packaging, model deployment, and registry. TensorFlow and Pytorch are just two machine learning libraries that MLFlow interfaces use to make it easier to train, deploy, and manage machine learning applications.

Metaflow: https://metaflow.org/ (Cesar) Done
The open-source MLOps platform Metaflow was created by Netflix. It is a program designed in Python and R that makes managing and building business Data Science projects simple.
Metaflow unifies Python-based Machine Learning, Deep Learning, and Big Data frameworks to train, deploy, and manage ML models.

Flyte: https://flyte.org/ (Cesar) Seen
Another open-source MLOps tool for managing and automating Kubernetes-native Machine Learning operations is called Flyte. Keeping track of model modifications, versioning it, and containerizing the model together with its dependencies guarantees that machine learning model execution is repeatable.
Flyte was created to handle sophisticated machine learning operations in Python, Java, and Scala.

ZenML: https://zenml.io/home
To deploy ML models into employment logically and simply, ZenML incorporates ML tools like Jupyter notebooks into its flexible open source MLOps platform. ZenML is used to build reproducible machine learning pipelines to develop machine learning projects.

MLRun: https://www.mlrun.org/
An open-source MLOps framework called MLRun makes it easy to manage your machine learning pipeline from the design stage to deployment in the field. Your machine learning pipeline now includes MLRun, which adds tracking, automation, quick deployment, administration, and simple model scaling.

Pachyderm: https://www.pachyderm.com/solutions/mlops/
Scalability choices, experiment construction and tracking, and data lineage. Pachyderm is a powerful MLOps solution that enables users to manage a whole machine learning cycle. Due to its quick and precise tracking knowledge and replication skills, it is a straightforward option for data scientists and teams. It supports most languages, frameworks, and libraries, and as we showed in our comparison based on supported libraries, it aids in developing scalable ML/AI pipelines.

Top Unpaid:

Data Version Control (DVC): https://dvc.org/ (Yannick)
DVC is a python written open source tool for Data Science and Machine Learning projects. It takes on a Git-like model to provide management and versioning of datasets and machine learning models. DVC is a simple command-line tool that makes machine learning projects shareable and reproducible.
DVC is a regularly updated tool with over 7.9k stars and 212 contributors on GitHub.

Kedro: https://kedro.readthedocs.io/en/stable/
Kedro is a Python-written open source MLOps framework used for creating reproducible and maintainable Data Science code. It implements software engineering practices such as versioning and modularity in Machine Learning projects.
It offers pipeline visualization, project templating, and flexible deployment of Data Science projects.
Kendro has over 3.9k stars on GitHub.

Seldon Core: https://www.seldon.io/
Seldon is an open source MLOps framework designed to streamline Machine Learning workflows with logging, advanced metrics, testing, scaling, and conversion of models into production microservices.
Seldon offers some high-level features that make it easy to containerize ML models, test the usability and security of models and make them fully auditable by integrating with several services.
A large percentage of Seldon was created with Jupyter Notebook, and it has over 2.3k stars on GitHub.

Other:

MLReef
CML
Cortex Lab
AutoKeras
H2O AutoML

Metaflow: (Python Library Needs Coding the Flow)

Manage compute resources,
Perform containerized runs, (By PID paralellisme)
Manage external dependencies,
Version, replay and resume workflow runs, (Greater control over errors need to code what will happen in case of errors)
Client API to inspect past runs suited for notebooks,
Move back and forth between local (e.g. on a laptop) vs remote (on the cloud) modes of execution




