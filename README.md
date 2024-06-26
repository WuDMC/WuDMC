![Profile Header](./header.png)

<div align="center">
  <h1>Hi, I'm Denis!</h1>
</div>

🚀 Data Engineer specializing in building data pipelines for BI analytics! I transform data from any sources—databases/web scraping/parsing messengers/APIs—into valuable insights ✨📊 

**Is your startup ready to unlock data's potential?** Reach out to me on [Telegram](https://t.me/wudmc)! Together, we'll build scalable, cost-effective pipelines on Google Cloud's free tier, ensuring low costs and high-impact insights.
  
<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/wudmc/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>
  
---

### 💼 My non-NDA projects 

- **Telegram Jobs Parser**
  - **Description:** Parsing ~400 Telegram jobs channels to find the best 😎 offers: ELT pipeline loads the data into GCS => stages in BQ => DataMarts in BQ => simple Looker BI dashboard and AD HOCs to filter the results.
  - **Stack:** Python, Airflow, Google Cloud Storage, Google BigQuery, Looker.
  - **Repositories:** [ELT Airflow DAGs](https://github.com/WuDMC/ELT_DAGs_for_tg_jobs_parser) | [Telegram jobs parser module](https://github.com/WuDMC/tg_jobs_parser_module)
  - **Looker Dashboard:** [View Dashboard](https://lookerstudio.google.com/reporting/87cf00b3-86c9-4203-865b-54320c762bb6)
    <details>
      <summary>📊 Click here to view dashboard screenshot</summary>
      <img src="https://github.com/WuDMC/WuDMC/assets/65350779/42c84cdb-624e-4e3a-8c4c-940067c95c72" alt="Dashboard for Telegram Jobs Parser" width="800">
    </details>
    
    <details>
      <summary>📑 Todo list:</summary>
      <ul>
        <li>Add CI and auto tests (my bad ...it should have been done at the very first stage)</li>
        <li>Use Terraform and run the project with one button</li>
        <li>Simple ML model to classify vacancies from CHATS (not only dialogs like now)</li>
        <li>Create more useful dashboards</li>
        <li>Auto extraction to Google Sheets</li>
        <li>Deduplication</li>
        <li>Advanced ML model to parse vacancy parameters like region, salary</li>
      </ul>
    </details>

- **Media Processor Bot**
  - **Description:** Experiments with Computer Vision and FFmpeg: A web app (in Cloud Run container) processes media files (audio conversion with FFmpeg, face detection with Google Cloud Vision) and loads them to Google Drive via API. The interface is a simple Telegram bot. 😊 Full CI/CD workflow from scratch.
  - **Stack:** Python, Flask, Google Cloud Vision, Cloud Run & Cloud Build, FFmpeg, Docker, GitHub Actions.
  - **Bot Link:** [Gdrive Saver Bot](https://t.me/gdrive_saver_bot)
  - **Repositories:** [Data processing microservice](https://github.com/WuDMC/data-processing-web-app) | [Telegram Bot](https://github.com/WuDMC/simple-tg-bot)
    
    <details>
      <summary>😲 Click here to see face detection examples in Telegram</summary>
      <img src="https://github.com/WuDMC/WuDMC/assets/65350779/4a11e94f-9c29-4750-8a1c-881597fac733" alt="Gdrive Bot example" width="800">
    </details>

- **Startpoint APP**
  - **Description:** A web app generating travel routes from any place you are. If you don't know where to go during your holidays, try it.
  - **Stack:** Python, Django, Ruby, Sinatra, JS, Google Geocoding, Geonames API.
  - **App Link:** [Startpoint APP](https://wudmc.com/startpoint.html)
  - **Repositories:** [Geonames microservice](https://github.com/WuDMC/geonames) | [Django website](https://github.com/WuDMC/wudmc.com)
    
    <details>
      <summary>🚞 Click here to see route examples GIF</summary>
      <img src="https://wudmc.com/static/assets/img/maps.gif" alt="Startpoint app example" width="600">
    </details>

---

### 📈 My Stats

[![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=WuDMC&theme=dark&background=000000&hide_border=false&include_all_commits=true&count_private=true&layout=compact)](https://git.io/streak-stats)
