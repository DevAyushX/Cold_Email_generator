# Cold Mail Generator
This tool helps service-based companies generate personalized cold emails using Groq, Langchain, and Streamlit. Users can input the careers page URL of a target company, and the tool will automatically extract job openings. Based on each job description, it crafts customized cold emails and attaches relevant portfolio links retrieved from a vector database. 

**Use Case Scenario::**

- Suppose Nike is looking to hire a Principal Software Engineer. The company will invest considerable time and resources in recruiting, onboarding, and training.
- Atliq, a software development firm, can offer a skilled engineer on a dedicated basis to fulfill this need.
- Mohan, a business development executive at Atliq, plans to reach out to Nike through a cold email to propose this solution



## Set-up
1. First, obtain an API key from: https://console.groq.com/keys.
Then, open app/.env and update the GROQ_API_KEY field with your generated API key. 


2. Install the required dependencies by running:

    ```commandline
     pip install -r requirements.txt
    ```
   
3. Launch the Streamlit application with:


   ```commandline
   streamlit run app/main.py
   ```
   

Copyright (C) Codebasics Inc. All rights reserved.

**Additional Terms:**
This software is licensed under the MIT License. However, commercial use of this software is strictly prohibited without prior written permission from the author. Attribution must be given in all copies or substantial portions of the software.
