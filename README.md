<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,30&height=200&section=header&text=Said%20Sigala&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=IT%20Systems%20%7C%20Networking%20%C2%B7%20Cloud%20%C2%B7%20Security&descAlignY=58&descSize=16" width="100%" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=4C8BF5&center=true&vCenter=true&width=680&lines=Redes%2C+sistemas+y+cloud;Automatizaci%C3%B3n+con+Python%2C+Bash+y+Docker;Seguridad%2C+software+y+datos" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=SaidHoffman&label=Visitas&color=4c8bf5&style=flat-square&abbreviated=true" />
  <a href="https://said-sigala.netlify.app/"><img src="https://img.shields.io/badge/Portafolio-4c8bf5?style=flat-square&logo=netlify&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/saidsigala"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Disponible-para%20nuevas%20oportunidades-2D8C6E?style=flat-square" />
</p>

---

### Sobre mí

Egresado de Ingeniería en Sistemas Computacionales por el **Instituto Politécnico Nacional (ESCOM)**, promedio **9.02/10**, con un perfil orientado a **IT, sistemas, redes, cloud y seguridad**.

Me interesa construir y solucionar sistemas completos: APIs y automatización con Python, redes Cisco y GNS3, Linux, Docker, servicios cloud, seguridad defensiva, bases de datos y pipelines de datos. Trabajo con una mentalidad práctica: entender el problema, verificar el comportamiento y documentar una solución reproducible.

Busco mi primera oportunidad en **IT**, especialmente en infraestructura, redes, cloud, automatización, DevOps o seguridad.

---

### Áreas de interés

| Área | En qué trabajo |
|---|---|
| Sistemas y redes | TCP/IP, VLANs, routing, Cisco, GNS3, Linux y troubleshooting |
| Cloud y automatización | Docker, GCP, Azure, Python, Bash y GitHub Actions |
| Seguridad | SOC casero, Wazuh, Sysmon, MITRE ATT&CK, criptografía y hardening |
| Software y datos | APIs REST, Java, SQL, ETL/ELT, analítica y machine learning |

---

### Proyectos destacados

#### Proyecto destacado: Argon2Net

<table>
  <tr>
    <td>

**Mi Trabajo Terminal en la ESCOM-IPN (2025), propuesto a mención honorífica.**

¿Puede una red neuronal imitar a Argon2id, la función que convierte contraseñas en claves criptográficas? Para responderlo armamos un dataset de 2 millones de registros (contraseñas reales de SecLists, salts de 128 bits y la clave que da Argon2id) y entrenamos una BiLSTM en PyTorch para reproducirla.

| NIST SP 800-22 | Inferencia | Pruebas unitarias | Efecto avalancha |
|:---:|:---:|:---:|:---:|
| 13 de 15 aprobadas | ~5 ms | 21 de 21 | 4.30 % (lo ideal es 50 %) |

La red imita bien la distribución de las claves, pero no su efecto avalancha, así que no puede sustituir a Argon2. Medir ese límite con rigor fue lo más valioso del proyecto.

`Python` · `PyTorch` · `BiLSTM` · `pandas` · `NIST SP 800-22`

[→ Repo](https://github.com/SaidHoffman/RedNeuronalTT) · [→ Artículo (PDF)](https://github.com/SaidHoffman/portfolio/blob/main/assets/material/ArticuloTT_2025-B144%20%281%29.pdf)

  </td>
  </tr>
</table>

---

#### Redes, seguridad y sistemas

- [Home SOC Lab](https://github.com/SaidHoffman/home-soc-lab): laboratorio Blue Team con Wazuh y Sysmon, simulación de ataques, detecciones y respuesta mapeadas a MITRE ATT&CK.
- [Administración de Servicios en Red](https://github.com/SaidHoffman/Administracion-de-Servicios-en-Red): API REST en Python para administrar y monitorear routers Cisco emulados en GNS3 mediante SSH y SNMP.
- [Cripto](https://github.com/SaidHoffman/Cripto): aplicación Django de expedientes cifrados con AES-256, X25519, AES-GCM y firmas Ed25519.

#### Datos, automatización y analítica

<table>
  <tr>
    <td width="50%" valign="top">

#### LigaMX Intelligence
Quería ver qué tan predecible es la Liga MX. Bajo 2,813 partidos (2016-2024) de Kaggle a DuckDB, los modelo con dbt, calculo un ELO por equipo y entreno un XGBoost que alimenta una simulación Monte Carlo de 5,000 torneos. Todo corre con Prefect y se ve en Streamlit.

`dbt` · `DuckDB` · `Prefect` · `XGBoost` · `Streamlit`

[→ Repo](https://github.com/SaidHoffman/LIGAMX)

  </td>
    <td width="50%" valign="top">

#### Football Data Pipeline
Cada mañana Airflow baja la tabla y los partidos de La Liga y la Premier League desde una API, los guarda en Cloud Storage y los carga a BigQuery sin duplicar datos. dbt arma las capas silver y gold, y el resultado se ve en un dashboard de Looker Studio.

`Airflow` · `GCS` · `BigQuery` · `dbt` · `Docker`

[→ Repo](https://github.com/SaidHoffman/Pipeline-LaLiga---Premier-Ligue) · [→ Dashboard](https://datastudio.google.com/reporting/429d9a0c-fa02-4608-86a9-b8e1cd533fe0)

  </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

#### Weather Data Pipeline
Ingesta del clima de Nueva York desde la API de Weatherstack a PostgreSQL. dbt quita duplicados y saca promedios diarios, Airflow orquesta y Superset grafica. Todo levanta con Docker Compose.

`Airflow` · `dbt` · `PostgreSQL` · `Superset` · `Docker`

[→ Repo](https://github.com/SaidHoffman/weather-data-project)

  </td>
    <td width="50%" valign="top">

#### NYC Taxi: ETL a esquema estrella
ETL en Python que limpia viajes de taxi con reglas auditables (ninguna fila se borra sin registrarlo) y los carga a un esquema estrella en SQLite, con la integridad referencial revisada en Python y en la base.

`Python` · `pandas` · `SQL` · `Modelado dimensional`

[→ Repo](https://github.com/SaidHoffman/nyc-taxi-pipeline)

  </td>
  </tr>
</table>

Todo esto también está en mi [portafolio](https://said-sigala.netlify.app/) ([repo](https://github.com/SaidHoffman/portfolio)), un sitio estático en HTML, CSS y JavaScript.

---

### Stack

**Lenguajes**
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
</p>

**Automatización, datos y backend**
<p align="center">
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Prefect-070E10?style=flat-square&logo=prefect&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
</p>

**Cloud, bases de datos y almacenamiento**
<p align="center">
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloud%20Storage-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Dataflow-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
</p>

**Analítica y machine learning**
<p align="center">
  <img src="https://img.shields.io/badge/Apache%20Superset-20A6C9?style=flat-square&logo=apache&logoColor=white" />
  <img src="https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=looker&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-189FDD?style=flat-square" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
</p>

**Sistemas, redes y DevOps**
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,git,github,linux,windows,gcp,azure&theme=dark" />
</p>

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
