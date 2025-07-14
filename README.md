Problem Description:
One of the problems that people complain about is that weather forecasts are very unreliable. In this case we will be taking data. We will create a tool that will have a monitoring dashboard that will evauate of how our preditions margin of error changes depending of the time horinzon. Try and understans in which cases where the models has the most error and are hardest to identify.

This is a simple weather forecast application. But it is not ready!

Requirements for the project:

- Select a dataset
- Train a model on that dataset tracking your experiments
- Create a model training pipeline
- Deploy the model in batch, web service or streaming
- Monitor the performance of your model
- Follow the best practices

Tech Stack:
- Cloud: AWS
- Experiment tracking: MLFlow
- Workflow Orchestration: Airflow
- Monitoring: Evidently and Graphana
- CI/CD: Github actions
- IaC: Terraform

Best practices
- There are unit tests
- There is an integration test
- Linter and/or code formatter are used
- There's a Makefile
- There are pre-commit hooks
- There's a CI/CD pipeline