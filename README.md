# Testing Data Analysis Repository
This repository contains the analysis of testing data for device twinning with the Eclipse Ditto project. We have conducted performance tests and presented our findings using Python, specifically the Behavior-driven Development (BDD) framework, Behave.

#Overview
Our tests focus on two crucial aspects:

* The time required for the first twinning of a smart device.
  
* The Ditto application performance when twinning between 1 to 10 iWatches.

# First Twinning Time
For the first twinning test, we simulate the scenario of the first-ever smart device being twinned in a real-world application and analyse the time required for each stage of the process. All required services for the twinning process were initiated and the duration of each step was logged, providing a comprehensive view of how long each stage takes. This information is analyzed using a Jupyter Notebook to generate a detailed understanding of the overall process. This can be found in the notebook first_twinning_analysis.ipynb.

# Multiple Device Twinning Performance
The second test investigates the Ditto application's performance when managing a range of 1 to 10 iWatches. This test aims to evaluate the system's scalability and handling of increased complexity. The performance metrics analyzed include CPU usage, RAM usage, network usage, and response time. The analysis can be found in the notebook multiple_device_twinning_performance.ipynb.

# Data Collection
The data collected in these tests has been logged and stored in CSV format.

# Tests
All tests were written using Behave, a behavior-driven development (BDD) framework for Python, and leverages the Gherkin language to define our test cases.
