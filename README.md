# AI-QuizPro - Python Implementation.
# AI-QuizPro aims to empower students and learners by offering them a convenient and efficient way to strengthen their grasp of diverse subjects. Leveraging AI technology, the tool generates quizzes in real-time from documents provided by users, providing immediate feedback and comprehensive explanations. This approach facilitates a deeper understanding and better retention of knowledge, thereby enriching the learning journey.
# Starting with Google Cloud Platform, setup a project, enabling Vertex AI APIs & manage service account with owner permisssion. Authenticate using the service account key(authentication.json) and configure with the project name helps to use all the necessary APIs. (SDK authentication).
# Install all the packages from requirements.txt (streamlit, chromadb, langchain, langchain-google-vertexai, pypdf).
# The entire project is implemented in tasks from task3 to task10. The python files with the documentation and the respective outputs are in the respository.
# Task3 - Document Ingestion focuses on handling files with streamlit. Uploading PDFs and process the files using PyPDFLoader from Langchain framework. Handles multiple pdf files.
# Task4 - This is embedding with VertexAI & Langchain, initializing VertexAI embeddings and test it by inputing with "Hello World".
# Task5 - Creation of Data Pipeline with Chroma DB. Document processing, split the text into the chunks and creation of Chroma collection in memory from the document.
# Task6 - Creation of Streamlit UserInterface for DataIngestion, quiz creation with AI integration. Leverages Chroma collection for quiz question generation.
# Task7 - Boosting up the quiz question creativity using google "gemini-pro" model. Configuring the parameters for controlled outputs, integrate with the vectorstore from the previous tasks to get the context-driven generation.
# Task8 - Generation of Quiz Algorithm.
# Task9 - Generate Quiz UserInterface. Also allowing seamless movement between the questions and displaying questions via. streamlit.
# Task10 - Session State Handling. Streamlit quiz setup and navigation. Initialize the question bank, set topic (given as a prompt), question quantity using streamlit widgets,managing with the quiz generation and display. Finally, testing with the application.

