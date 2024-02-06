# Gemini Explorer
  Gemini is a family of multimodal large language models developed by Google DeepMind, serving as the successor to LaMDA and PaLM 2
 ![image](https://github.com/AnikethRai/Gemini_Explorer/assets/95706188/a86760e0-91b5-40b8-97ca-65e8c7e7b12a)

## Description

This mission is provided by the RadicalX Ai Team, where we have to integrate Gemini into our Python code of Streamlit to create an AI chat interface. Here Gemini is an API, where we need to have Gcloud account to access it.
Moreover, vertexAI is a library that provided us with the Gemini-versions, here we use Gemini-pro in our mission. To complete this mission we have to follow and complete the tasks.

## Table of Contents

- Task 1: 🌐 Enable Google Cloud
- Task 2: 🧬 Google Cloud Initialization
- Task 3: ☁️ Setting up Google Gemini
- Task 4: 📊 Streamlit Integration
- Task 5: 🗣️ Adding Initial System Messages
- Task 6: 📄 Preparing Submission

## Requirements

- Python version 3.11x or above [Python](https://www.python.org/downloads/)
- pip [pip](https://pip.pypa.io/en/stable/installation/)
- Streamlit [Streamlit](https://docs.streamlit.io/)
- Gcloud account [Gcloud](https://console.cloud.google.com/welcome/new?_ga=2.263401548.-1375459776.1706725444&hl=en&project=geminiexplorer-412918)
- Vertexai [VertexAI Document](https://pypi.org/project/google-cloud-aiplatform/)
  
## Task 1: 🌐 Enable Google Cloud
  
  - Go to the Google Cloud Platform website: Google Cloud Platform. [Gcloud](https://console.cloud.google.com/welcome/new?_ga=2.263401548.-1375459776.1706725444&hl=en&project=geminiexplorer-412918)
  - Click on "Get Started for Free" or "Try Free" button.
  - Sign in with your Google Account or create a new one.
  - Provide necessary information and billing details.
  - Accept the terms and conditions.
  - Set up billing with credit card details.
  - Access the Google Cloud Console: Google Cloud Console.
  - Create a new project.
  - Enable billing for the project.
  - Install and configure the Google Cloud SDK (optional).
  ![task1](https://github.com/AnikethRai/Gemini_Explorer/assets/95706188/91bc6eb1-0fa4-4832-bc12-0570aea82443)


## Task 2: 🧬 Google Cloud Initialization
  - Install the Google Cloud SDK: Follow the installation instructions for your operating system here.
  - Open a terminal or command prompt.
  - Run the following command to initialize the SDK:
        ```
            gcloud init
        ```
  - Sign in with your Google Account: Follow the prompts to sign in or create a new account.
  - Choose a Google Cloud project: Select an existing project or create a new one.
  - Set the default a: Choose a default compute region and zone.
  - Confirm your choices: Review your selections and confirm to complete the initialization.
  - Verify the configuration: Run the following command to verify your configuration: arduinoCopy code
    ``` gcloud config list ```
  (Optional) Install additional components: Depending on your needs, you may want to install additional components using the gcloud components install command.
  You're now ready to use gcloud commands to interact with Google Cloud Platform services!
  ![task2](https://github.com/AnikethRai/Gemini_Explorer/assets/95706188/373d51c0-fa38-48b7-a827-ef44c158f45c)


## Task 3: ☁️ Setting up Google Gemini
  - We have to install Streamlit 
  - Use command : ``` pip install streamlit ``` 
  - To verify use:  ```  streamlit hello ```  |  ```  python -m streamlit hello ```
  - Open streamlit documentation.
  - Under LLM models, you might find a section for creating chat interface.
  - Streamlit used OpenAI as an example but we are going to use Gemini-Pro by Google.
    ![task3](https://github.com/AnikethRai/Gemini_Explorer/assets/95706188/ff9e8cc2-a355-4f50-a361-e564c9b91a22)


## Task 4: 📊 Streamlit Integration
 - Follow the code provided in the Mission or you can improvise on your own through documentation.
 - Run the python file using command: ``` python -m streamlit filename.py ```
 - You should be seeing a web app pop up on yourscreen with chat interface.
   ![Task4](https://github.com/AnikethRai/Gemini_Explorer/assets/95706188/3824cc48-662e-47e2-87fb-044ed451bd38)


## Task 5: 🗣️ Adding Initial System Messages
  By adding the above snippet in your main code, it initializes an initial prompt to Gemini. Therefore the next slide shows the result of the chat interface
  ![task5](https://github.com/AnikethRai/Gemini_Explorer/assets/95706188/d1cec5fa-4de8-4e6a-8ae2-58000ba41faa)


## Task 6: 📄 Preparing Submission
  Create a GitHub and upload a video with slides, representing your approach to complete this mission.
  
##  Issues
  ⚠️ 403: Permission Denied Error 
  ✔️ Check if you have provided project_id rather than project name in your code or if the service account is activated.
  ✔️ You can follow through this document to activate the service Account. [Service Account Activation](https://cloud.google.com/sdk/gcloud/reference/auth/activate-service-account)
  ✔️ Use the Example code.
  ⚠️ Value Error
  ✔️ This is a system error, It is just an initial throw put of streamlit library as we do not display the initial prompt in chat interface. Not to worry about it.


## Appreciation
  I wanna show my gratitude towards Talha Sabri and Mikhail Ocampo, for providing me this opportunity to complete this AI Mission. #RadicalXJourney.
  I also want to thank Shilpa Sivarajan for answering my doubts regarding the issues I have faced.
  ![image](https://github.com/AnikethRai/Gemini_Explorer/assets/95706188/7fec3346-20fe-4566-8a32-4ca49de2ea83)

## Socials
To join RadicalX follow this link. [RadicalX AI](https://www.community.radicalx.co/about)
LinkedIn [Aniketh Rai](https://www.linkedin.com/in/aniketh-rai/)


