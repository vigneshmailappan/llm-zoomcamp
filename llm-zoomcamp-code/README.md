# Step1: Connecting to Azure OpenAI 
This project uses Azure OpenAI as the LLM provider. 

## Prerequisites
Before running the project, set up Azure OpenAI access:
```text
Az account 
    -> Azure OpenAI 
        -> Create Resource 
            -> Foundry Portal 
                -> Deploy Model 
                    -> Grab endpoint, api_key
```
## Challenges Faced

1. Caching issue : Variable not refreshed with new values from .env. 

        replaced load_dotenv() to load_dotenv(override=True)