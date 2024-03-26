
# End-to-end-Medical-Chatbot-using-Llama2

[](https://github.com/entbappy/End-to-end-Medical-Chatbot-using-Llama2/tree/main#end-to-end-medical-chatbot-using-llama2)

# How to run?

[](https://github.com/entbappy/End-to-end-Medical-Chatbot-using-Llama2/tree/main#how-to-run)

### STEPS:

[](https://github.com/entbappy/End-to-end-Medical-Chatbot-using-Llama2/tree/main#steps)

Clone the repository
```
Project repo: https://github.com/
```
### STEP 01- Create a conda environment after opening the repository

[](https://github.com/entbappy/End-to-end-Medical-Chatbot-using-Llama2/tree/main#step-01--create-a-conda-environment-after-opening-the-repository)
```
conda create -n mchatbot python=3.8 -y
```
```
conda activate mchatbot
```
### STEP 02- install the requirements

[](https://github.com/entbappy/End-to-end-Medical-Chatbot-using-Llama2/tree/main#step-02--install-the-requirements)
```
pip install -r requirements.txt
```
### Create a  `.env`  file in the root directory and add your Pinecone credentials as follows:

[](https://github.com/entbappy/End-to-end-Medical-Chatbot-using-Llama2/tree/main#create-a-env-file-in-the-root-directory-and-add-your-pinecone-credentials-as-follows)
```
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
### Download the quantize model from the link provided in model folder & keep the model in the model directory:

[](https://github.com/entbappy/End-to-end-Medical-Chatbot-using-Llama2/tree/main#download-the-quantize-model-from-the-link-provided-in-model-folder--keep-the-model-in-the-model-directory)
```
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin

## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```
```
# run the following command
python store_index.py
```
```
# Finally run the following command
python app.py
```
Now,
```
open up localhost:
```
### Techstack Used:

[](https://github.com/entbappy/End-to-end-Medical-Chatbot-using-Llama2/tree/main#techstack-used)

-   Python
-   LangChain
-   Flask
-   Meta Llama2
-   Pinecone
