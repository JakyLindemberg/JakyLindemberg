<!-- GitHub Profile README — Jaky Lindemberg -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0B1622,55:0E3B43,100:117865&height=170&section=header&text=Jaky%20Lindemberg&fontSize=50&fontColor=FFFFFF&fontAlignY=42&desc=Senior%20Data%20Professional%20%C2%B7%20Microsoft%20Fabric%20%C2%B7%20Data%20and%20Analytics%20Engineering&descSize=17&descAlignY=68&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=3200&pause=900&color=2BD4A4&center=true&vCenter=true&width=720&lines=End-to-end+data+platforms+on+Microsoft+Fabric;Python+%C2%B7+PySpark+%C2%B7+SQL+%C2%B7+T-SQL+%C2%B7+DAX;Lakehouse+%E2%86%92+Warehouse+%E2%86%92+Semantic+Model+%E2%86%92+Power+BI;5x+Microsoft+Certified+%C2%B7+DP-700+%C2%B7+DP-600+%C2%B7+PL-300" alt="Typing SVG"/>

<a href="https://www.linkedin.com/in/jaky-lindemberg"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:jaky.lindemberg@gmail.com"><img src="https://img.shields.io/badge/Email-0E3B43?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="#microsoft-certifications"><img src="https://img.shields.io/badge/5x_Microsoft_Certified-Verified-0078D4?style=for-the-badge&logo=microsoft&logoColor=white"/></a>

<sub><b>English</b> · <a href="#português">Português</a></sub>

</div>

<br/>

I design and deliver **end-to-end data platforms on Microsoft Fabric** — from source ingestion to governed semantic models and executive reporting. With **9+ years in data** and **five Microsoft certifications**, including **DP-700 (Fabric Data Engineer)** and **DP-600 (Fabric Analytics Engineer)**, I combine engineering discipline with business context to build data products that leadership relies on to make decisions.

My work spans the full data lifecycle: **PySpark** and **Python** pipelines, **T-SQL** warehousing, **dimensional modelling**, **DAX** semantic layers and **Power BI** reporting — engineered for reliability, performance and governance.

<br/>

## Core Expertise

| Domain | What I deliver |
|---|---|
| **Data Engineering** | Batch ingestion with Fabric Data Pipelines and Dataflows Gen2; PySpark notebooks for transformation at scale; medallion architecture on Lakehouse with Delta Lake. |
| **Analytics Engineering** | Star-schema modelling, T-SQL Warehouse development, Direct Lake and Import semantic models, DAX measures and performance tuning. |
| **Business Intelligence** | Executive and operational Power BI solutions with KPI frameworks designed alongside directors and C-level stakeholders. |
| **Integration & Automation** | REST APIs, Microsoft Graph and Azure Management ingestion; Azure Functions, Logic Apps and Power Automate orchestration. |
| **Statistics & ML** | Exploratory analysis, correlation and distribution analysis, regression and classification models applied to business problems. |

<br/>

## Microsoft Certifications

<div align="center">

<table>
  <tr>
    <td align="center" width="190">
      <a href="https://learn.microsoft.com/api/credentials/share/en-us/JakyLindemberg-3618/B6E4441FD56396B1?sharingId=6EE237B93CB33367"><img src="https://learn.microsoft.com/en-us/media/learn/certification/badges/microsoft-certified-associate-badge.svg" width="105" alt="DP-700"/></a><br/>
      <b>DP-700</b><br/><sub>Fabric Data Engineer<br/>Associate</sub>
    </td>
    <td align="center" width="190">
      <a href="https://learn.microsoft.com/api/credentials/share/en-us/JakyLindemberg-3618/611184C1AAEE0A9B?sharingId=6EE237B93CB33367"><img src="https://learn.microsoft.com/en-us/media/learn/certification/badges/microsoft-certified-associate-badge.svg" width="105" alt="DP-600"/></a><br/>
      <b>DP-600</b><br/><sub>Fabric Analytics Engineer<br/>Associate</sub>
    </td>
    <td align="center" width="190">
      <a href="https://learn.microsoft.com/api/credentials/share/en-us/JakyLindemberg-3618/6E5891C4C7E1BDFD?sharingId=6EE237B93CB33367"><img src="https://learn.microsoft.com/en-us/media/learn/certification/badges/microsoft-certified-associate-badge.svg" width="105" alt="PL-300"/></a><br/>
      <b>PL-300</b><br/><sub>Power BI Data Analyst<br/>Associate</sub>
    </td>
    <td align="center" width="190">
      <a href="https://learn.microsoft.com/api/credentials/share/en-us/JakyLindemberg-3618/7E6A2769B50C6103?sharingId=6EE237B93CB33367"><img src="https://learn.microsoft.com/en-us/media/learn/certification/badges/microsoft-certified-fundamentals-badge.svg" width="105" alt="AI-900"/></a><br/>
      <b>AI-900</b><br/><sub>Azure AI<br/>Fundamentals</sub>
    </td>
    <td align="center" width="190">
      <a href="https://learn.microsoft.com/api/credentials/share/en-us/JakyLindemberg-3618/70F204735ECF5095?sharingId=6EE237B93CB33367"><img src="https://learn.microsoft.com/en-us/media/learn/certification/badges/microsoft-certified-fundamentals-badge.svg" width="105" alt="PL-900"/></a><br/>
      <b>PL-900</b><br/><sub>Power Platform<br/>Fundamentals</sub>
    </td>
  </tr>
</table>

<sub>All credentials are verifiable on Microsoft Learn — click any badge.</sub>

</div>

<br/>

## Reference Architecture

How I structure end-to-end solutions on Microsoft Fabric:

```mermaid
flowchart LR
    S["Sources<br/>REST APIs · Microsoft Graph<br/>SQL Server · Files"] --> I["Ingestion<br/>Data Pipelines<br/>Dataflows Gen2"]
    I --> B[("Bronze<br/>Lakehouse · raw Delta")]
    B --> SV[("Silver<br/>PySpark · cleansed<br/>and conformed")]
    SV --> G[("Gold<br/>Warehouse · T-SQL<br/>star schema")]
    G --> M["Semantic Model<br/>Direct Lake · DAX"]
    M --> R["Power BI<br/>Executive reporting"]

    classDef src fill:#0B1622,stroke:#2BD4A4,color:#fff
    classDef eng fill:#0E3B43,stroke:#2BD4A4,color:#fff
    classDef bi fill:#117865,stroke:#2BD4A4,color:#fff
    class S,I src
    class B,SV,G eng
    class M,R bi
```

<br/>

## Track Record

- **Hours to minutes.** Re-engineered data collection and transformation workflows with Python and Azure Functions, cutting processing time from hours to minutes.
- **Decision-grade reporting.** Power BI solutions used by directors and corporate clients to manage IT operations, security, service management and performance.
- **Data at scale.** Pipelines that process audit logs and telemetry from Microsoft cloud environments to support monitoring and governance.
- **Six years of operational analytics.** Built the reporting backbone of multiple contact-centre operations (SLA, AHT, abandonment, adherence), replacing manual spreadsheets with automated SQL-driven reports.

<br/>

## Technology Stack

<div align="center">

**Languages**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/T--SQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white"/>
<img src="https://img.shields.io/badge/DAX-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Power_Query_M-217346?style=flat-square&logo=microsoftexcel&logoColor=white"/>

**Data Platform**<br/>
<img src="https://img.shields.io/badge/Microsoft_Fabric-117865?style=flat-square&logo=microsoft&logoColor=white"/>
<img src="https://img.shields.io/badge/Lakehouse-0E3B43?style=flat-square&logo=databricks&logoColor=white"/>
<img src="https://img.shields.io/badge/Data_Warehouse-0B1622?style=flat-square&logo=microsoftsqlserver&logoColor=white"/>
<img src="https://img.shields.io/badge/Delta_Lake-00ADD4?style=flat-square&logo=delta&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white"/>

**Cloud & Integration**<br/>
<img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure_Functions-0062AD?style=flat-square&logo=azurefunctions&logoColor=white"/>
<img src="https://img.shields.io/badge/Logic_Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/Microsoft_Graph-0078D4?style=flat-square&logo=microsoft&logoColor=white"/>
<img src="https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square&logo=postman&logoColor=white"/>

**BI & Automation**<br/>
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white"/>
<img src="https://img.shields.io/badge/Power_Apps-742774?style=flat-square&logo=powerapps&logoColor=white"/>

**Data Science & Engineering Practices**<br/>
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white"/>

</div>

<br/>

## Experience

| Period | Role | Company |
|---|---|---|
| **2022 – Present** | Senior Data Analyst & RPA | Computécnica Tecnologia |
| **2016 – 2022** | Senior Business Intelligence Analyst | PARLA! Contact Center |

## Education

| Program | Institution | Year |
|---|---|---|
| Postgraduate Degree, Applied Statistics | Anhanguera | 2026 |
| Postgraduate Degree, Machine Learning Engineering | Anhanguera | 2025 |
| Technologist Degree, Data Science | Anhanguera | 2024 |

<br/>

## GitHub Activity

<div align="center">

<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=JakyLindemberg&theme=github_dark"/>

<img src="https://streak-stats.demolab.com?user=JakyLindemberg&hide_border=true&background=0B1622&ring=2BD4A4&fire=2BD4A4&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=2BD4A4&sideLabels=E6EDF3&dates=8B949E&stroke=0E3B43"/>

</div>

<br/>

---

<a id="português"></a>

## Português

Projeto e entrego **plataformas de dados end-to-end no Microsoft Fabric** — da ingestão das fontes até modelos semânticos governados e relatórios executivos. Com **mais de 9 anos em dados** e **cinco certificações Microsoft**, incluindo **DP-700 (Fabric Data Engineer)** e **DP-600 (Fabric Analytics Engineer)**, uno rigor de engenharia e visão de negócio para construir produtos de dados que sustentam as decisões da liderança.

Minha atuação cobre todo o ciclo de vida do dado: pipelines em **PySpark** e **Python**, data warehouse em **T-SQL**, **modelagem dimensional**, camadas semânticas em **DAX** e relatórios em **Power BI**, projetados para confiabilidade, performance e governança.

**Especialidades**

- **Engenharia de Dados:** ingestão com Data Pipelines e Dataflows Gen2, transformação em escala com notebooks PySpark e arquitetura medallion em Lakehouse com Delta Lake.
- **Analytics Engineering:** modelagem star schema, desenvolvimento de Warehouse em T-SQL, modelos semânticos Direct Lake e Import, DAX e otimização de performance.
- **Business Intelligence:** soluções executivas e operacionais em Power BI, com frameworks de KPIs definidos junto a diretores e executivos.
- **Integração e Automação:** ingestão via APIs REST, Microsoft Graph e Azure Management; orquestração com Azure Functions, Logic Apps e Power Automate.
- **Estatística e ML:** análise exploratória, correlação, distribuições e modelos de regressão e classificação aplicados a problemas de negócio.

**Resultados**

- Reestruturei fluxos de coleta e transformação de dados com Python e Azure Functions, **reduzindo o tempo de processamento de horas para minutos**.
- Soluções em Power BI utilizadas por diretores e clientes corporativos na gestão de operações de TI, segurança e serviços.
- Pipelines que processam logs de auditoria e telemetria de ambientes Microsoft em larga escala, apoiando monitoramento e governança.
- Seis anos construindo a base analítica de operações de contact center, substituindo planilhas manuais por relatórios automatizados em SQL.

**Certificações Microsoft:** DP-700 · DP-600 · PL-300 · AI-900 · PL-900

---

<div align="center">

**Open to opportunities in Data Engineering, Analytics Engineering and Microsoft Fabric.**<br/>
<sub>Aberto a oportunidades em Engenharia de Dados, Analytics Engineering e Microsoft Fabric.</sub>

<br/>

<a href="https://www.linkedin.com/in/jaky-lindemberg"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:117865,55:0E3B43,100:0B1622&height=6&section=footer" width="100%"/>

</div>
