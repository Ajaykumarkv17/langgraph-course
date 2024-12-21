# langgraph-course

## To Access the OpenAI LLM 

### Get the API key from github

[Link to get your own github token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens)

```python
llm = ChatOpenAI(model="gpt-4o", temperature=0,api_key=os.getenv("GITHUB_TOKEN"),base_url="https://models.inference.ai.azure.com")
```


this is readme file


A Lang graph course in which you will learn how to use and build langraph to build Agentic Applications and deploy scalable
