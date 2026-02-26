Use Azure AI to Discover Intelligence in the Data 1 hour

In this part of the hackathon, you’ll use Azure AI to uncover insights, patterns, or predictions from the data you ingested and transformed.
You can approach this however you want — the goal is simply to add intelligence to your dataset using any Azure AI capability.

Ways You Can Add Intelligence
Here are some easy, hackathon‑friendly ideas participants can pick from
:
    • Run text analytics
Use Azure AI Language to extract key phrases, detect sentiment, or identify named entities (people, places, products, etc.).
    • Classify or tag data
Use a pre‑built model to categorize text, label documents, or assign topics.
    • Summarize content
Feed your dataset into Azure OpenAI (or the Fabric Prompt Flow experience) to generate summaries of reports, logs, or long text fields.
    • Build a quick prediction model
Use AutoML in Fabric or Azure ML to predict something simple — churn, demand, volumes, or yes/no outcomes.
    • Generate insights with natural language
Use Azure OpenAI models to let users ask questions about the data and get an answer back in plain English.
    • Detect anomalies
Use Azure AI Anomaly Detector to spot unusual spikes, drops, or outliers in your time‑series data.
    • Enrich your structured data
Let an LLM rewrite messy text fields, normalize categories, or create new derived columns.
    • Create embeddings + similarity search
Generate embeddings with Azure OpenAI and find similar items, documents, or records inside your dataset.
    • Sentiment or customer feedback analysis
If your data has comments or notes, use Azure AI Language to measure positive/negative/neutral trends.
    • Build a simple chatbot using Data Agent
Use your ingested dataset as context, then build a data agent in the Fabric
    • Enhance with AI Foundry
    Connect the data agent in Azure Foundry `as part of agentic solution 
    
    
    1) Natural-language Q&A over your data (Data Agent / Chat with data)
    Option	What to use	Learn link
    Fabric	Data Agent on Lakehouse/Warehouse	https://learn.microsoft.com/fabric/data-science/how-to-create-data-agent
    Azure AI	RAG with embeddings + chat using Azure OpenAI Service	https://learn.microsoft.com/azure/ai-services/openai/use-your-data
    

    2) Summarize, classify, sentiment, entities (text enrichment)
    Option	What to use	Learn link
    Fabric	AI Functions in notebooks / Prompt Flow	https://learn.microsoft.com/fabric/data-science/ai-functions/overview
    Azure AI	Azure AI Language (Text Analytics)	https://learn.microsoft.com/azure/ai-services/language-service/overview
    

    3) Embeddings + similarity search
    Option	What to use	Learn link
    Fabric	AI Functions + Vector index in Lakehouse	https://learn.microsoft.com/fabric/data-science/ai-functions/overview
    Azure AI	Embeddings with Azure OpenAI	https://learn.microsoft.com/azure/ai-services/openai/how-to/embeddings
    

    4) Build prediction model (AutoML)
    Option	What to use	Learn link
    Fabric	AutoML experiment on Lakehouse tables	https://learn.microsoft.com/fabric/data-science/automl-overview
    Azure AI	AutoML in Azure ML	https://learn.microsoft.com/azure/machine-learning/automl/overview
    

    5) Detect anomalies in time-series
    Option	What to use	Learn link
    Fabric	Notebook with Python/Spark anomaly logic	https://learn.microsoft.com/fabric/data-engineering/how-to-use-notebook
    Azure AI	Azure AI Anomaly Detector	https://learn.microsoft.com/azure/ai-services/anomaly-detector/overview
    

    6) Enrich / normalize messy text fields with LLM
    Option	What to use	Learn link
    Fabric	Prompt Flow / AI Functions	https://learn.microsoft.com/fabric/data-science/ai-functions/overview
    Azure AI	Azure OpenAI completions	https://learn.microsoft.com/azure/ai-services/openai/how-to/chatgpt
    

    7) Agentic extension (advanced / bonus)
    Option	What to use	Learn link
    Fabric	Data Agent as your data tool	https://learn.microsoft.com/fabric/data-science/concept-data-agent
    Azure AI	Connect to Azure AI Foundry for orchestration	https://learn.microsoft.com/fabric/data-science/data-agent-foundry
    

    In the hackathon
    “You can do this entirely in Fabric or call Azure AI services directly. Both are valid. Fabric is faster; Azure AI gives more control.”
    
