# 👋 Hi, I’m **Kentaro Minegishi**

> AIエージェントと、それが動く基盤をつくる人。
>
> Azure で RAG チャットボットを本番運用経験有。最近は **AWS（Bedrock AgentCore / Strands）でのマルチエージェント開発**をメインにやりながら、**Roblox でのゲーム開発**に軸足を広げたりといろいろやってます。閉域網インフラの設計・構築も対応可能です。

---

## 🚀 Now working on

**🤖 マルチエージェント開発（AWS）**
Bedrock AgentCore / Strands Agents を使い、役割特化のエージェントを組み合わせた開発パイプラインを構築中。単発のLLM呼び出しではなく、設計・実装・検証を分担させ、検証役を読み取り専用にすることで品質を担保する構成を試しています。

**🎮 Roblox ゲーム開発**
Claude Code + MCP（Roblox Studio / Blender）で、ボードゲームを量産するためのエージェント基盤を開発。ルールロジックを Roblox API 非依存に保つことで、プレイせずに数百パターンを検証できる設計にしています。

---

## 🌟 About me

- 🇯🇵 Tokyo-based | Backend / AI Engineer
- 🤖 **マルチエージェント設計**（Bedrock AgentCore, Strands, MCP, Claude Code）
- 🎮 **Roblox 開発**（Luau, Roblox Studio, Blender 連携）
- 🧪 Python（Flask / Django）、LangChain で RAG チャットボットをプロトタイプ→本番運用まで
- ☁️ Azure 中心（OpenAI, Cosmos DB, AI Search, Blob Storage, VNet/閉域）
- ☁️ AWS: **SAA** / MGN によるオンプレ→クラウド移行の実務経験
- 🧠 RAG・ベクタDB（FAISS / PostgreSQL）での回答精度改善が得意
- 🎯 目的：**現場で使われるAI/内製ツールの高速立ち上げ**

---

## 🛠 Tech Stack

**AI Agents**

![Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-232F3E?logo=amazonaws&logoColor=white)
![AgentCore](https://img.shields.io/badge/Bedrock%20AgentCore-FF9900?logo=amazonaws&logoColor=white)
![Strands](https://img.shields.io/badge/Strands%20Agents-232F3E?logo=amazonaws&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?logo=anthropic&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20Code-D97757?logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-0E1117?logo=chainlink&logoColor=white)

**Game Development**

![Roblox](https://img.shields.io/badge/Roblox%20Studio-00A2FF?logo=roblox&logoColor=white)
![Luau](https://img.shields.io/badge/Luau-00A2FF?logo=lua&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-E87D0D?logo=blender&logoColor=white)

**Languages / Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)

**Cloud / AI**

![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?logo=microsoftazure&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-1F88E5?logo=openai&logoColor=white)
![Azure Cosmos DB](https://img.shields.io/badge/Cosmos%20DB-2E475D?logo=azurecosmosdb&logoColor=white)
![Azure AI Search](https://img.shields.io/badge/AI%20Search-0078D4?logo=microsoftazure&logoColor=white)
![Azure Blob Storage](https://img.shields.io/badge/Blob%20Storage-0078D4?logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![MGN](https://img.shields.io/badge/AWS%20MGN-FF9900?logo=amazonaws&logoColor=white)
![SAA](https://img.shields.io/badge/AWS%20SAA-Certified-232F3E?logo=amazonaws&logoColor=white)

**Data / Vector**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-005571?logo=facebook&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)

---

## 👨‍💻 What I build

- **マルチエージェント基盤**（Bedrock AgentCore / Strands / MCP）
  役割特化エージェント + 品質ゲートによる開発パイプライン
- **Roblox ゲーム開発基盤**（Claude Code + MCP）
  ルール層を Roblox API から分離し、プレイせずに検証できる設計
- **RAG チャットボット**（Azure OpenAI + AI Search + Cosmos DB + Blob）
- **閉域網で動作する Azure AI 基盤**（VNet, Private Endpoint, NSG 等）
- **ドキュメントOCR パイプライン**（Azure Document Intelligence）
- **RAGチャットボット用ドキュメント管理画面**（Flask + Cosmos DB + Blob）
- **Python API 開発**（Flask / FastAPI）

---

## 📌 Featured Projects

- **boardgame-factory** 🎮
  Roblox 向けボードゲームを量産する Claude Code テンプレート。専門エージェント11体と3つの品質ゲートで、仕様策定から実装・検証までを分担。
  `#Roblox` `#Luau` `#MCP` `#MultiAgent`
  **Repo:** `[coming soon]`

- **RAG Chatbot on Azure (Private Network)**
  Azure OpenAI + AI Search + Cosmos DB + Blob。VNet/PE/Private DNS により閉域で動作。LangChain/FAISS による精度改善。
  `#Python` `#Flask` `#Azure` `#RAG`
  **Repo:** `[coming soon]`

- **Python API Template**
  Flask/FastAPI ベースの API スケルトンと CI。
  **Repo:** [RAGチャットボットサンプルアプリ](https://github.com/kishika1sei/djangoapp-ragsample)

---

## 🔭 Now learning

- **エージェント設計パターン**（AI-DLC、品質ゲート、状態管理）
- **Luau / Roblox のサーバー権威設計**
- Retrieval 最適化（Chunking / Hybrid Search / リランキング）
- **Django**（API/管理画面の実務投入に向けて）

---

## 📫 Contact

- GitHub Issues or Discussions でお気軽にどうぞ
