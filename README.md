<<<<<<< HEAD
# streamlit-agent

#### 介绍
{**以下是 Gitee 平台说明，您可以替换此简介**
Gitee 是 OSCHINA 推出的基于 Git 的代码托管平台（同时支持 SVN）。专为开发者提供稳定、高效、安全的云端软件开发协作平台
无论是个人、团队、或是企业，都能够用 Gitee 实现代码托管、项目管理、协作开发。企业项目请看 [https://gitee.com/enterprises](https://gitee.com/enterprises)}

#### 软件架构
软件架构说明


#### 安装教程

1.  xxxx
2.  xxxx
3.  xxxx

#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
=======
<<<<<<< HEAD
# 🦜️🔗 LangChain 🤝 Streamlit agent examples

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/langchain-ai/streamlit-agent?quickstart=1)

This repository contains reference implementations of various LangChain agents as Streamlit apps including:

- `basic_streaming.py`: Simple streaming app with `langchain.chat_models.ChatOpenAI` ([View the app](https://langchain-streaming-example.streamlit.app/))
- `basic_memory.py`: Simple app using `StreamlitChatMessageHistory` for LLM conversation memory ([View the app](https://langchain-st-memory.streamlit.app/))
- `mrkl_demo.py`: An agent that replicates the [MRKL demo](https://python.langchain.com/docs/modules/agents/how_to/mrkl) ([View the app](https://langchain-mrkl.streamlit.app))
- `minimal_agent.py`: A minimal agent with search (requires setting `OPENAI_API_KEY` env to run)
- `search_and_chat.py`: A search-enabled chatbot that remembers chat history ([View the app](https://langchain-chat-search.streamlit.app/))
- `simple_feedback.py`: A chat app that allows the user to add feedback on responses using [streamlit-feedback](https://github.com/trubrics/streamlit-feedback), and link to the traces in [LangSmith](https://docs.smith.langchain.com/) ([View the app](https://langsmith-simple-feedback.streamlit.app/))
- `chat_with_documents.py`: Chatbot capable of answering queries by referring custom documents ([View the app](https://langchain-document-chat.streamlit.app/))
- `chat_with_sql_db.py`: Chatbot which can communicate with your database ([View the app](https://langchain-chat-sql.streamlit.app/))
- `chat_pandas_df.py`: Chatbot to ask questions about a pandas DF (Note: uses `PythonAstREPLTool` which is vulnerable to arbitrary code execution,
  see [langchain #7700](https://github.com/langchain-ai/langchain/issues/7700))

Apps feature LangChain 🤝 Streamlit integrations such as the
[Callback integration](https://python.langchain.com/docs/modules/callbacks/integrations/streamlit) and
[StreamlitChatMessageHistory](https://python.langchain.com/docs/integrations/memory/streamlit_chat_message_history).

## More great app examples

Check out some other full examples of apps that utilize LangChain + Streamlit:

- [Auto-graph](https://auto-graph.streamlit.app/) - Build knowledge graphs from user-input text ([Source code](https://github.com/langchain-ai/langchain-benchmarks/blob/main/extraction/streamlit_app.py))
- [Web Explorer](https://web-explorer.streamlit.app/) - Retrieve and summarize insights from the web ([Source code](https://github.com/langchain-ai/web-explorer))
- [LangChain Teacher](https://lang-teacher.streamlit.app/) - Learn LangChain from an LLM tutor ([Source code](https://github.com/langchain-ai/langchain-teacher))
- [Text Splitter Playground](https://langchain-text-splitter.streamlit.app/) - Play with various types of text splitting for RAG ([Source code](https://github.com/langchain-ai/text-split-explorer))
- [Tweet Generator](https://elon-twitter-clone.streamlit.app/) - Fine tune GPT-3.5 on tweets ([Source code](https://github.com/langchain-ai/twitter-finetune))

## Setup

This project uses [Poetry](https://python-poetry.org/) for dependency management.

```shell
# Create Python environment
$ poetry install

# Install git pre-commit hooks
$ poetry shell
$ pre-commit install
```

## Running

```shell
# Run mrkl_demo.py or another app the same way
$ streamlit run streamlit_agent/mrkl_demo.py
```

# Running with Docker

This project includes `Dockerfile` to run the app in Docker container. In order to optimise the Docker Image is optimised for size and building time with cache techniques.

To generate Image with `DOCKER_BUILDKIT`, follow below command

```DOCKER_BUILDKIT=1 docker build --target=runtime . -t langchain-streamlit-agent:latest```

1. Run the docker container directly

``docker run -d --name langchain-streamlit-agent -p 8051:8051 langchain-streamlit-agent:latest ``

2. Run the docker container using docker-compose (Recommended)

Edit the Command in `docker-compose` with target streamlit app

``docker-compose up``

## Contributing

We plan to add more agent and chain examples over time and improve the existing ones - PRs welcome! 🚀
=======
# my_streamlit_example2.py
>>>>>>> ddc033ce98d50121594c89b072c31e2cd6df2d10
>>>>>>> a432c1e (test)
