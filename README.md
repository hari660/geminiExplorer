# Gemini Explorer

## Mission
Create a chat interface using Streamlit and Google Gemini to explore large language chat models and their applications. 

## Requirments:

- Python version 3.11 or above
- [Streamlit Documentation](https://docs.streamlit.io/)
- Google Cloud account
- [Vertexai Documentation](https://cloud.google.com/vertex-ai)

## Task 1: Enabling Google Cloud

- Go to the [Google Cloud Platform](console.cloud.google.com) and select "Get Started for free".
- Sign in using your Google Account and complete the billing requirements.
- Create a new project.
- Navigation -> Artificial Intelligence -> Vertex AI -> Enable All Recommended APIs


## Task 2: Google Cloud Initialization

- Install the Google SDK using this [Link](https://cloud.google.com/sdk/docs/install).
- Run the following command to initialize the SDK:
  ```
  gcloud init
- Sign in using your Google Account credentials.
- Select an existing project or Create a new project


## Task 3: Setting up Google Gemini

- Install the streamlit framework
  ```
  pip install streamlit
- In the project, we are using Gemini Pro as the LLM.
- Use the project ID instead of the project name, like this: `project = "project_id"`. This helps avoid encountering a 403 permission denied error.


## Task 4:  Streamlit Integration
- Follow the steps given in the mission.
- Run the python file `streamlit run filename.py`.
- ![Task 4](https://github.com/hari660/radical/assets/55326522/7eb8f92e-b435-4456-93af-dc819a83066e)


## Task 5: Adding Initial Messages

![Task 5](https://github.com/hari660/radical/assets/55326522/713aa4e8-7921-47a8-8e3c-2f45e15487b5)


## Task 6: Preparing Submission

 - A GitHub repository for the project containing all the project files.
 - Loom Video to show the approach. [Loom Link]()

## Acknowledgements
Special thanks to the [Radical AI](https://lab.radicalai.app/) team for allowing me to work on this AI Mission.
