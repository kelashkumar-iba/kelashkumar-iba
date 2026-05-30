<div align="center">
  <img src="https://github.com/kelashkumar-iba/kelashkumar-iba/blob/main/newcover.png" width="100%" />
</div>

<br/>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=720&lines=Data+Engineer+%7C+Pipeline+Builder;Kafka+%7C+Debezium+%7C+dbt+%7C+Airflow+%7C+DuckDB;Production+pipelines+at+%240%2Fmonth+infra+cost;90s+push-to-live+%7C+OCI+ARM+%7C+Docker;Open+to+Internships+%26+Junior+DE+Roles" alt="typing" />
</div>

<br/>

<div align="center">

[![Portfolio](https://img.shields.io/badge/kelash.me-38BDF8?style=for-the-badge&logo=googlechrome&logoColor=0D1117&labelColor=38BDF8)](https://kelash.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kelashkumar-iba)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kelash.iba22@gmail.com)
![Views](https://komarev.com/ghpvc/?username=kelashkumar-iba&style=for-the-badge&color=0D1117&label=VIEWS&labelColor=38BDF8)

</div>

---

<br/>

```python
kelash = {
    "role"     : "Data Engineer",
    "school"   : "BS CS — Sukkur IBA University (May 2026)",
    "stack"    : ["Kafka/Redpanda", "dbt", "Airflow", "Debezium", "DuckDB", "Docker"],
    "infra"    : "OCI ARM VM · 4 OCPU / 24 GB · Ubuntu 22.04 · $0/month",
    "projects" : "3 end-to-end pipelines · streaming · CDC · lakehouse",
    "live_at"  : "https://streaming-pipeline.kelash.me",
    "open_to"  : ["Internships", "Junior DE Roles", "Remote"],
}
```

<br/>

---

## ⚙️ Projects

<div align="center">
<table>
<tr>

<td align="center" width="330" valign="top">

<br/>

**⚡ &nbsp; Real-Time Crypto Pipeline**

---

<img src="https://img.shields.io/badge/🟢_LIVE-OCI_ARM_·_$0%2Fmonth-22C55E?style=flat-square"/>

<br/><br/>

9-service Docker Compose stack.<br/>
Redpanda → Python consumer → PostgreSQL.<br/>
Airflow orchestrates 3-layer dbt transforms.<br/>
4-job CI/CD · safety-gated SSH deploy.

<br/>

| Metric | Value |
|:---|:---:|
| Updates/day | ~14,400 |
| E2E freshness | < 5 min |
| Push-to-live | ~90s |
| Test suite | 8 pytest |

<br/>

[![Live](https://img.shields.io/badge/LIVE-streaming--pipeline.kelash.me-22C55E?style=flat-square&logo=googlechrome&logoColor=white)](https://streaming-pipeline.kelash.me)
[![Repo](https://img.shields.io/badge/GitHub-View-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/kelashkumar-iba)

<br/>

![Redpanda](https://img.shields.io/badge/Redpanda-FF3E00?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![OCI](https://img.shields.io/badge/OCI-F80000?style=flat-square&logo=oracle&logoColor=white)

<br/>

</td>

<td align="center" width="330" valign="top">

<br/>

**🔄 &nbsp; CDC Pipeline**

---

<img src="https://img.shields.io/badge/⚙️_LOCAL-Deploy_Pending-FB923C?style=flat-square"/>

<br/><br/>

PostgreSQL WAL → Debezium → Redpanda.<br/>
Idempotent Python consumer · PK upserts.<br/>
dbt SCD Type 2 for full change history.<br/>
Dead-letter queue for malformed events.

<br/>

| Metric | Value |
|:---|:---:|
| Replication lag | < 10s |
| Previous lag | ~60 min |
| Delivery | at-least-once |
| Duplicates | eliminated |

<br/>

[![Repo](https://img.shields.io/badge/GitHub-View-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/kelashkumar-iba)

<br/><br/>

![Debezium](https://img.shields.io/badge/Debezium-FF1F1F?style=flat-square)
![Redpanda](https://img.shields.io/badge/Redpanda-FF3E00?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<br/>

</td>

<td align="center" width="330" valign="top">

<br/>

**🏛️ &nbsp; Medallion Lakehouse**

---

<img src="https://img.shields.io/badge/⚙️_LOCAL-Deploy_Pending-FB923C?style=flat-square"/>

<br/><br/>

Bronze → Silver → Gold on MinIO + Parquet.<br/>
DuckDB as zero-cost SQL compute engine.<br/>
31 Great Expectations checks per layer.<br/>
Partition-aware DAGs for safe backfills.

<br/>

| Metric | Value |
|:---|:---:|
| GX checks | 31 total |
| Bronze | 11 checks |
| Silver | 20 checks |
| Infra cost | $0/month |

<br/>

[![Repo](https://img.shields.io/badge/GitHub-View-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/kelashkumar-iba)

<br/><br/>

![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Great Expectations](https://img.shields.io/badge/Great_Expectations-FF6B35?style=flat-square)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<br/>

</td>

</tr>
</table>
</div>

<br/>

---

## 🛠️ Stack

<div align="center">

**⬡ &nbsp; Data Engineering**

![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka_/_Redpanda-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium-FF1F1F?style=for-the-badge)
![Great Expectations](https://img.shields.io/badge/Great_Expectations-FF6B35?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![ETL/ELT](https://img.shields.io/badge/ETL_%2F_ELT-0F172A?style=for-the-badge&labelColor=38BDF8&color=0F172A)
![CDC](https://img.shields.io/badge/CDC-0F172A?style=for-the-badge&labelColor=38BDF8&color=0F172A)
![SCD Type 2](https://img.shields.io/badge/SCD_Type_2-0F172A?style=for-the-badge&labelColor=38BDF8&color=0F172A)
![Data Modeling](https://img.shields.io/badge/Data_Modeling-0F172A?style=for-the-badge&labelColor=38BDF8&color=0F172A)
![Medallion](https://img.shields.io/badge/Medallion_Architecture-0F172A?style=for-the-badge&labelColor=38BDF8&color=0F172A)
![Metabase](https://img.shields.io/badge/Metabase-509EE3?style=for-the-badge)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

<br/>

**🗄️ &nbsp; Languages & Databases**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=for-the-badge)

<br/>

**⚙️ &nbsp; Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![OCI](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-00ADD8?style=for-the-badge)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![pre-commit](https://img.shields.io/badge/pre--commit-FAB040?style=for-the-badge&logo=precommit&logoColor=black)
![Makefile](https://img.shields.io/badge/Makefile-6D4C41?style=for-the-badge&logo=gnu&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-0F172A?style=for-the-badge&labelColor=38BDF8&color=0F172A)
![SSH](https://img.shields.io/badge/SSH-0F172A?style=for-the-badge&labelColor=38BDF8&color=0F172A)
![iptables](https://img.shields.io/badge/iptables-0F172A?style=for-the-badge&labelColor=38BDF8&color=0F172A)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="assets/stats.svg" width="49%" alt="GitHub Stats"/>
<img src="assets/streak.svg" width="49%" alt="Streak Stats"/>

</div>

<br/>

<div align="center">
  <img src="assets/activity.svg" width="97%" alt="Contribution Activity"/>
</div>

---

<div align="center">

<br/>

*Three end-to-end pipelines. Real infra. Real numbers. No fluff.*

**[streaming-pipeline.kelash.me](https://streaming-pipeline.kelash.me) — live right now.**

<br/>

[![Portfolio](https://img.shields.io/badge/kelash.me-38BDF8?style=for-the-badge&logo=googlechrome&logoColor=0D1117&labelColor=38BDF8)](https://kelash.me)
&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kelashkumar-iba)
&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kelash.iba22@gmail.com)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0D1117,38BDF8&height=120&section=footer" width="100%"/>

</div>
