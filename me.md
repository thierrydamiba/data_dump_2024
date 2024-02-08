# About me

## Resume

● Built and deployed 5 classification models in Databricks notebooks using sklearn, regex, and n-grams saving adjudicators over 8 hours a week. 

● Conceptualized and deployed 5 dashboards to Tableau via Jenkins to provide actionable insights and help the company transition to a data driven approach. 

● Drove business value analysis for major tool in the company which helped capture the value of the application. 

● Created a forecasting model using Prophet and built a dashboard in Tableau to predict the effect of Covid on the business. 

● Performed big data analysis on Databricks using Python and SQL to provide metrics. 

## Currently working on

#### Learning Laptops

First we install an open source llm on the laptop using (text-generation-webui) llamma cpp

Then we install data science libraries, datasets, and educational materials and assessments 

Then we send the laptops out to a student who will have a semester to learn

At the end of the semester they send the laptop back and we "upgrade it for them" and send back

Goal is to expose students to LLMs, Data Science, and ai world


### Hotel Semantic Search
Popuar travel websites allow you to search for hotels in an area, but there is no way to directly find specific amenities or search through reviews. For example, if you are looking for a hotel with a rooftop pool and bar, the travel site will mention 

#### Key Libraries and Technologies Used

- **`sentence_transformers`**: A library for state-of-the-art sentence, text, and image embeddings. Its use suggests the project involves transforming sentences into embeddings for semantic comparison or search tasks.
- **`gradio`**: Create the interactive UI to display content in a user friendly manner
- **`spacy` and `nltk`**: NLP libraries for text processing or natural language understanding tasks
- **`numpy`, `pandas`**: Data manipulation, proccessing and numerical operations
- **`torch`**: PyTorch for generating or processing text embeddings
- **`re`**: Regular expressions for text cleaning or processing
- **`openai.embeddings_utils`**: Utilized for embedding generation or manipulation and interfacing with OpenAI's API for advanced semantic analysis.
- **`gzip`, `json`, `os`, `time`**: File management, data serialization, and timing operations.

#### Major Steps or Sections

0. **Data Extraction Method**: Hotel Data scraped from Tripadvisor. Tripadvisor is a dynamic website and retains its information within concealed JSON documents. These documents are then transformed into the visible HTML through JavaScript. Consequently, it's feasible to directly access and extract the review data from these JSON files.
1. **Data Preparation**:  Loading and cleaning text data, removing stop words, chunking, punctuation for cleaner semantic analysis, etc.
2. **Embedding Generation**: Using `sentence_transformers` to transform text data into embeddings that capture semantic meaning.
3. **Semantic Search Implementation**: Utilizing embeddings for semantic search tasks. This could involve comparing embeddings for similarity (using cosine similarity from `openai.embeddings_utils`) to find the most relevant text entries given a query.
4. **Interface Creation**: Using `gradio` to build an interactive interface, allowing users to input queries and displaying the most semantically relevant results.
5. **Optimization and Testing**: Employing various libraries for performance tuning (e.g., `tqdm` for progress bars) and possibly refining the model or search algorithm based on test results.

#### Significant Findings or Results

While specific findings or results were not extracted in this step, the project's focus on semantic search likely aims to demonstrate effective retrieval of information based on query meaning rather than keyword matching. The use of advanced NLP models and embeddings is key to achieving high relevance in search results.

For your call with the recruiter, emphasize the project's application of cutting-edge NLP techniques for semantic search, your ability to implement interactive tools for model demonstration, and the technical skills demonstrated through the use of these libraries. Highlight any specific challenges you overcame, such as optimizing search algorithms or embedding models, and any innovative features of your project's interface.

