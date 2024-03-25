# Chat with document
In this repository we are created an interface of an chat application where user can upload any type of docuemt from this type : .doc,.docx,.pdf,.ppt,.pptx,.tex .
User can found any query related to the scientific document.

The main highlighted features of our software is : User can upload and found any query from this uploaded document type. 
The user also get the picture/ graphs related information if it their in the document, document summarization, if any equation is their in the scientific paper than also it will find and return. Also we are mainting the spell errors which is there in the questions.

Goal: Develop a solution to parse multiple document types and connect with LLMs for interaction
Building a Multimodal Document Parsing and LLM Chat Interface
Document Types: .PDF, .PPT, .PPTX, .DOCX, .DOC, .TEX
Input: Various document types 
Parsing Module: Convert documents into a unified format (e.g., plain text or structured data)
Handling user queries and generating responses based on document context
Document upload section, Chat interface with LLM, Query input field, Response display area
Asking questions related to the uploaded documents and receiving LLM-generated responses

**Objective :**
In the age of LLMs and multimodality, we have seen the rise of input not just as simple plain text 
but as documents in entirety. Many solutions out there work out of the box for taking PDF as 
input. Well, researchers and scientists use lots of different document types to create their research 
on beyond pdf - .docx, latex (.tex), .ppt (infographics/research slides). This also controls 
hallucinations in LLMs since it is extracting and presenting information only from documents 
provided by end user.
We want you to create a solution which can take input as atleast 2 or more doc types including 
pdf and making it ready to parse/send to any LLM. Bonus points for building a chat interface by

**main technology which we are used here is :**

Frontend technologies : HTML,CSS, Js
Backend technologies : Python
Framework : DJango
Used technologies : Natural language processing, Natural language generation, RAG-langchain
Database : FAISS (for storing the vector space) 
LLM: OpenAI

**the django project file flows :**
![WhatsApp Image 2024-03-02 at 11 05 40_b58105b9](https://github.com/Rushali2012/minedhackathon2024/assets/131957409/2e583c62-5555-4b93-92d8-57b93df6cc24)

**Requirement to set up django :**
Step 1 :
**first create an environment of your django folder**
Create virtual environment first:
Py -m venv nameofyourproject

Activate the environment:
nameofyourproject\Scripts\activate.bat

Step 2:
Install all these necessary libraries in your virtual environment 
# Installing neccessary libraries
pip install langchain
pip install openai
pip install PyPDF2
pip install faiss-cpu
pip install tiktoken
pip install langchain-openai
pip install python-pptx
pip install python-docx

Step 3:
Once you download all the necessary stuff. 
Just type **Python manage.py runserver**

Step 4:
You found a chatinterface where you can just upload your file (any type of from mentioned here). and get the answer of your query from the document.

**Upload file section :**
(From any doc type :  .doc,.docx,.pdf,.ppt,.pptx,.tex)
![WhatsApp Image 2024-03-02 at 10 15 12_8124f172](https://github.com/Rushali2012/minedhackathon2024/assets/131957409/ece92d03-c291-4be8-b8db-44310e2e8eb3)

![WhatsApp Image 2024-03-02 at 10 36 48_d817be4c](https://github.com/Rushali2012/minedhackathon2024/assets/131957409/e3cecee9-877d-453e-b784-c74f4869bb74)

**User can ask any questions:**
![WhatsApp Image 2024-03-02 at 10 19 16_c095d5e1](https://github.com/Rushali2012/minedhackathon2024/assets/131957409/cddaa326-b83c-4c5d-9544-8d1235072daa)

**about the figures and maintaing the spelling checks error :**
![WhatsApp Image 2024-03-02 at 10 45 11_36632c03](https://github.com/Rushali2012/minedhackathon2024/assets/131957409/5ef887a5-578a-486f-bfdc-abaa4d1ea872)

**User Interface:**
![image](https://github.com/Rushali2012/minedhackathon2024/assets/131957409/394f9829-896b-4ac1-abe7-607bba516f88)

