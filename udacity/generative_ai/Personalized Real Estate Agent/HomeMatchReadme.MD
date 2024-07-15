First it is needed to install the libraries in requirements.txt to run the code.

To run the code, either you need to add your own OpenAI_Key into or add your key to your environment.

llm = ChatOpenAI(model_name=model_name, openai_api_key=os.environ.get('openai_key'))
embeddings_model  = OpenAIEmbeddings( openai_api_key=os.environ.get('openai_key'))

