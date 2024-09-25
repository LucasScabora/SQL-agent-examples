# SQL Agent Examples

Examples of SQL Agents using Langchain over an Chinook Public Database. In the examples, we explored the SQL Toolkit using both [OpenAI](./SQL_agent_openai.ipynb) and [IBM Generative AI Python SDK](./SQL_agent_ibmgen.ipynb) to answer some questions about the data stored in the database.

## Setup Virtual Python Environment

Prepare Python Virtual Environment:
```
python3.11 -m venv venv
```

Install required Python Libraries:

```
pip install -r requirements.txt
```

Prepare a `.env` file based on the [OpenAI](./.env-example) with the required credentials.


## Setup Dataset

Downloaded de SQL script [Chinook_Sqlite.sql](https://raw.githubusercontent.com/lerocha/chinook-database/master/ChinookDatabase/DataSources/Chinook_Sqlite.sql) referring to the `Chinook Database - Version 1.4.5`.
