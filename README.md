<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,30&height=200&section=header&text=Said%20Sigala&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Data%20Engineer%20|%20ETL%2FELT%20·%20Airflow%20·%20dbt%20·%20GCP&descAlignY=58&descSize=16" width="100%" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=4C8BF5&center=true&vCenter=true&width=680&lines=Pipelines+de+datos+de+extremo+a+extremo;Airflow+%C2%B7+dbt+%C2%B7+BigQuery+%C2%B7+Docker;Datos+confiables%2C+documentados+y+observables" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=SaidHoffman&label=Visitas&color=4c8bf5&style=flat-square&abbreviated=true" />
  <a href="https://said-sigala.netlify.app/"><img src="https://img.shields.io/badge/Portafolio-4c8bf5?style=flat-square&logo=netlify&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/saidsigala"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Disponible-para%20nuevas%20oportunidades-2D8C6E?style=flat-square" />
</p>

---

### Sobre mí

Egresado de Ingeniería en Sistemas Computacionales por el **Instituto Politécnico Nacional (ESCOM)**, promedio **9.02/10**, enfocado en **ingeniería de datos**.

Construyo **pipelines ETL/ELT de extremo a extremo**: ingesta desde APIs y archivos, orquestación con **Airflow** y **Prefect**, transformaciones con **dbt** y **SQL** (CTEs, funciones de ventana), modelado dimensional y despliegue en **Google Cloud** (BigQuery, Dataflow, Cloud Storage). Me importa que los datos sean confiables: pruebas de calidad, cargas idempotentes y documentación clara.

Busco mi primera oportunidad como **Data Engineer** o **Analytics Engineer**.

---

### Stack

**Lenguajes**
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
</p>

**Orquestación y transformación**
<p align="center">
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Prefect-070E10?style=flat-square&logo=prefect&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
</p>

**Almacenamiento y nube**
<p align="center">
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloud%20Storage-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Dataflow-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
</p>

**Visualización y ML**
<p align="center">
  <img src="https://img.shields.io/badge/Apache%20Superset-20A6C9?style=flat-square&logo=apache&logoColor=white" />
  <img src="https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=looker&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-189FDD?style=flat-square" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
</p>

**Infraestructura**
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,git,github,linux,gcp&theme=dark" />
</p>

---

### Proyectos destacados

<table>
  <tr>
    <td width="50%" valign="top">

#### LigaMX Intelligence
Plataforma de analytics sobre **2,813 partidos** de Liga MX (2016–2024). Ingesta desde Kaggle a **DuckDB**, transformación en capas con **dbt** (staging → intermediate → marts) y tests de calidad, orquestada con **Prefect**. Rating **ELO dinámico**, clasificador **XGBoost** y simulador **Monte Carlo** en un dashboard **Streamlit**.

`dbt` · `DuckDB` · `Prefect` · `XGBoost` · `Streamlit`

[→ Repo](https://github.com/SaidHoffman/LIGAMX)

  </td>
    <td width="50%" valign="top">

#### Football Data Pipeline
Pipeline en **GCP** con arquitectura **medallion**: la API de football-data.org aterriza en **Cloud Storage** (Bronze), se carga de forma **idempotente** a **BigQuery** y **dbt** construye Silver y Gold con 7 tests de calidad. **Airflow** extrae La Liga y Premier League en paralelo. Dashboard en **Looker Studio**.

`Airflow` · `GCS` · `BigQuery` · `dbt` · `Docker`

[→ Repo](https://github.com/SaidHoffman/Pipeline-LaLiga---Premier-Ligue)

  </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

#### Weather Data Pipeline
Pipeline **ELT** 100 % contenedorizado: ingesta de clima en tiempo real desde la API de Weatherstack a **PostgreSQL**, modelos **dbt** con deduplicación por funciones de ventana y marts de promedios diarios, orquestado con **Airflow** y visualizado en **Apache Superset**.

`Airflow` · `dbt` · `PostgreSQL` · `Superset` · `Docker`

[→ Repo](https://github.com/SaidHoffman/weather-data-project)

  </td>
    <td width="50%" valign="top">

#### NYC Taxi — ETL a esquema estrella
Pipeline **ETL** en Python con capa de *landing* inmutable, **reglas de limpieza auditables**, **esquema estrella** (dimensión de rol y llaves sustitutas) e **integridad referencial** validada en Python y en la base. Cargas idempotentes a **SQLite**.

`Python` · `pandas` · `SQL` · `Modelado dimensional`

[→ Repo](https://github.com/SaidHoffman/nyc-taxi-pipeline)

  </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

#### Argon2Net — Trabajo Terminal
Pipeline **ETL modular** que procesó **2 millones de registros** para entrenar una red **BiLSTM** en **PyTorch**. Aprobó 13/15 pruebas **NIST SP 800-22** (86.67 %) con 5 ms de inferencia. Empaquetada como librería con 21 pruebas unitarias. *Propuesto a Mención Honorífica.*

`Python` · `ETL` · `PyTorch` · `pandas`

[→ Repo](https://github.com/SaidHoffman/RedNeuronalTT)

  </td>
    <td width="50%" valign="top">

#### Portafolio
Sitio personal con mis proyectos, experiencia y certificaciones. Estático, sin *frameworks* y basado en archivos JSON, desplegado en **Netlify**.

`HTML` · `CSS` · `JavaScript` · `Netlify`

[→ Ver sitio](https://said-sigala.netlify.app/) · [→ Repo](https://github.com/SaidHoffman/portfolio)

  </td>
  </tr>
</table>

---

### Certificaciones

| Certificación | Emisor |
|---------------|--------|
| [ETL Processing on Google Cloud Using Dataflow and BigQuery](https://coursera.org/verify/8CBYXPT9INU8) | Google Cloud |
| [Introduction to Data Engineering on Google Cloud](https://coursera.org/verify/6MKNVOG12MHE) | Google Cloud |
| [Supervised Machine Learning: Regression and Classification](https://coursera.org/verify/LMUVE5KYYQL2) | DeepLearning.AI / Stanford |
| [SQL (Intermediate)](https://www.hackerrank.com/certificates/b1bcd547cd78) · [Python](https://www.hackerrank.com/certificates/334aaaa99db5) · [Problem Solving (Gold)](https://www.hackerrank.com/certificates/37bee920e4f8) | HackerRank |

---

### Estadísticas

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=SaidHoffman&show_icons=true&include_all_commits=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=4c8bf5&icon_color=4c8bf5" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SaidHoffman&layout=compact&langs_count=8&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=4c8bf5" />
</p>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=SaidHoffman&theme=react-dark&hide_border=true&bg_color=0d1117&color=4c8bf5&line=4c8bf5&point=ffffff&area=true&height=300" width="100%" />

---

<p align="center">
  <a href="mailto:saidsigala14@gmail.com"><img src="https://img.shields.io/badge/Correo-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://said-sigala.netlify.app/"><img src="https://img.shields.io/badge/Portafolio-4c8bf5?style=for-the-badge&logo=netlify&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/saidsigala"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4c8bf5,100:0d1117&height=120&section=footer" width="100%" />
