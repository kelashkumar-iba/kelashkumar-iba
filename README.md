<div align="center">
  <img src="https://github.com/kelashkumar-iba/kelashkumar-iba/blob/main/githubcover.png" width="100%" />
</div>

<br/>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=22&duration=2500&pause=800&color=38BDF8&center=true&vCenter=true&width=750&lines=Hi+%F0%9F%91%8B+I'm+Kelash+Kumar;Data+Engineer+%7C+Pipeline+Builder;Kafka+%7C+Debezium+%7C+dbt+%7C+DuckDB+%7C+OCI;~90s+push-to-live+on+real+ARM+infrastructure;Open+to+Internships+%26+Junior+DE+Roles" alt="typing" />
</div>

<br/>

<div align="center">

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-kelash.me-0F172A?style=for-the-badge&labelColor=38BDF8&color=0F172A)](https://kelash.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kelashkumar-iba)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kelash.iba22@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/kelashkumar)
![Views](https://komarev.com/ghpvc/?username=kelashkumar-iba&style=for-the-badge&color=38BDF8&label=PROFILE+VIEWS)

</div>

---

## `$ whoami`

```yaml
name        : Kelash Kumar
role        : Data Engineer  ·  Fresh Graduate (BS CS, May 2026)
university  : Sukkur IBA University — CGPA 3.1  ·  NSCT 92.2nd percentile
location    : Mithi, Tharparkar, Pakistan 🇵🇰
portfolio   : https://kelash.me
open_to     : [Internships, Junior DE Roles, Remote]
focus       : Streaming · CDC · Lakehouse · CI/CD
infra       : OCI ARM VM  ·  4 OCPU / 24 GB  ·  Ubuntu 22.04
```

---

## `$ ls ./projects`

<table>
<tr>
<td width="33%" valign="top">

### ⚡ Real-Time Crypto Pipeline

Kafka producers ingest live crypto market data. Consumers write to PostgreSQL. Metabase serves live dashboards. Deployed on OCI ARM with Caddy + Let's Encrypt HTTPS. 4-job GitHub Actions CI/CD pipeline.

```
latency : ~90s push-to-live
infra   : OCI ARM · Docker · Caddy
status  : 🟢 LIVE
```

[![LIVE DEMO](https://img.shields.io/badge/LIVE-streaming--pipeline.kelash.me-22C55E?style=flat-square&logo=googlechrome&logoColor=white)](https://streaming-pipeline.kelash.me)
[![Repo](https://img.shields.io/badge/GitHub-View-0D1117?style=flat-square&logo=github)](https://github.com/kelashkumar-iba)

![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Metabase](https://img.shields.io/badge/Metabase-509EE3?style=flat-square)

</td>
<td width="33%" valign="top">

### 🔄 CDC Pipeline

PostgreSQL Write-Ahead Logging captured by Debezium and streamed via Kafka. dbt materializes SCD Type 2 tables — full insert/update/delete history with zero data loss.

```
pattern : Debezium → Kafka → dbt
scd     : Type 2 (full lineage)
status  : 🟡 Local · Deploy pending
```

[![Repo](https://img.shields.io/badge/GitHub-View-0D1117?style=flat-square&logo=github)](https://github.com/kelashkumar-iba)

![Debezium](https://img.shields.io/badge/Debezium-FF1F1F?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_WAL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

</td>
<td width="33%" valign="top">

### 🏛️ Medallion Lakehouse

Three-layer architecture (Bronze → Silver → Gold) on MinIO object storage. DuckDB powers analytical queries. Great Expectations enforces schema contracts at every layer boundary automatically.

```
layers  : Bronze → Silver → Gold
storage : MinIO (S3-compatible)
quality : Great Expectations gates
```

[![Repo](https://img.shields.io/badge/GitHub-View-0D1117?style=flat-square&logo=github)](https://github.com/kelashkumar-iba)

![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
</table>

---

## `$ cat ./stack.yml`

**Data Engineering**

![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium-FF1F1F?style=for-the-badge)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Great Expectations](https://img.shields.io/badge/Great_Expectations-FF6B35?style=for-the-badge)

**Languages & Databases**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=for-the-badge&logo=scala&logoColor=white)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/OCI_ARM_VM-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_Ubuntu_22.04-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Caddy](https://img.shields.io/badge/Caddy_+_HTTPS-00ADD8?style=for-the-badge)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white)

---

## `$ github --stats`

<div align="center">

<img src="assets/stats.svg" width="49%" alt="GitHub Stats" />
<img src="assets/streak.svg" width="49%" alt="Streak Stats" />

</div>

<br/>

<div align="center">
  <img src="assets/top-langs.svg" width="40%" alt="Top Languages" />
</div>

<br/>

<div align="center">
  <img src="assets/activity.svg" width="97%" alt="Contribution Activity" />
</div>

---

## `$ git log --oneline`

```
2026  ██████████████████  BS CS — Sukkur IBA University (May 2026)
2026  ████████████        Crypto Pipeline live on OCI ARM · kelash.me
2026  ████████            CDC Pipeline — Debezium + WAL + dbt SCD Type 2
2026  ██████              Medallion Lakehouse — MinIO + DuckDB + GX
2026  ████████████████    Custom domain · CI/CD · Caddy HTTPS · Let's Encrypt
2026  ██████████          92.2nd percentile — National Standardised Testing
```

---

<div align="center">

**Not a tutorial project collector. Every pipeline runs on real infrastructure.**

The Crypto Pipeline is live right now → **[streaming-pipeline.kelash.me](https://streaming-pipeline.kelash.me)**

<br/>

[![Portfolio](https://img.shields.io/badge/kelash.me-38BDF8?style=for-the-badge&logo=google-chrome&logoColor=0D1117)](https://kelash.me)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kelashkumar-iba)
&nbsp;
[![Email](https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kelash.iba22@gmail.com)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,16&height=100&section=footer" width="100%"/>

</div>
