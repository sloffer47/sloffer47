<!-- README de profil GitHub pour @sloffer47 -->
<h1 align="center">🚀 Salut moi c'est <span style="color:#00BFFF;">Yorick MBANDOU</span></h1>

<p align="center">
  <em>Data Engineer •Analysis•MLOps • Cloud • Streaming • Automatisation</em><br/>
  <small>Python 🐍 | Docker 🐳 | SQL 💾 | Kafka ⚙️ | Databricks 🔥 | Jenkins ⚡ | MLflow 📈 | Kubernetes ☸️ | AWS ☁️ | GCP 🌍</small>
</p>

---

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bannière Data Engineer</title>
    <style>
        body {
            margin: 0;
            padding: 20px;
            background: #0a0a0a;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
            font-family: Arial, sans-serif;
        }
        
        #banner {
            width: 1200px;
            height: 400px;
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 50%, #0f172a 100%);
            position: relative;
            overflow: hidden;
            border-radius: 10px;
            box-shadow: 0 20px 60px rgba(59, 130, 246, 0.3);
        }
        
        .grid-bg {
            position: absolute;
            width: 100%;
            height: 100%;
            opacity: 0.05;
            background-image: 
                linear-gradient(0deg, transparent 24%, rgba(59, 130, 246, 0.3) 25%, rgba(59, 130, 246, 0.3) 26%, transparent 27%, transparent 74%, rgba(59, 130, 246, 0.3) 75%, rgba(59, 130, 246, 0.3) 76%, transparent 77%, transparent),
                linear-gradient(90deg, transparent 24%, rgba(59, 130, 246, 0.3) 25%, rgba(59, 130, 246, 0.3) 26%, transparent 27%, transparent 74%, rgba(59, 130, 246, 0.3) 75%, rgba(59, 130, 246, 0.3) 76%, transparent 77%, transparent);
            background-size: 50px 50px;
        }
        
        .particle {
            position: absolute;
            width: 4px;
            height: 4px;
            background: #3b82f6;
            border-radius: 50%;
            opacity: 0.6;
            animation: float 8s infinite ease-in-out;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0) translateX(0); opacity: 0.6; }
            50% { transform: translateY(-300px) translateX(20px); opacity: 0.2; }
        }
        
        .data-flow {
            position: absolute;
            left: 50px;
            top: 50%;
            width: 200px;
            height: 200px;
            transform: translateY(-50%);
        }
        
        .flow-line {
            position: absolute;
            height: 2px;
            background: linear-gradient(90deg, transparent, #3b82f6, transparent);
            width: 150px;
            animation: pulse 3s infinite;
        }
        
        @keyframes pulse {
            0%, 100% { opacity: 0.3; transform: scaleX(1); }
            50% { opacity: 0.8; transform: scaleX(1.1); }
        }
        
        .center-content {
            position: absolute;
            left: 50%;
            top: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            z-index: 10;
        }
        
        .main-title {
            font-size: 56px;
            font-weight: 900;
            background: linear-gradient(135deg, #3b82f6 0%, #8b5cf6 50%, #06b6d4 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin: 0;
            letter-spacing: 2px;
            text-transform: uppercase;
            filter: drop-shadow(0 0 20px rgba(59, 130, 246, 0.5));
            animation: glow 3s ease-in-out infinite;
        }
        
        @keyframes glow {
            0%, 100% { filter: drop-shadow(0 0 20px rgba(59, 130, 246, 0.5)); }
            50% { filter: drop-shadow(0 0 30px rgba(139, 92, 246, 0.8)); }
        }
        
        .subtitle {
            font-size: 24px;
            color: #94a3b8;
            margin: 15px 0 0 0;
            letter-spacing: 3px;
            font-weight: 300;
        }
        
        .skills-bar {
            position: absolute;
            bottom: 80px;
            left: 50%;
            transform: translateX(-50%);
            width: 800px;
            height: 6px;
            background: rgba(30, 41, 59, 0.6);
            border-radius: 3px;
            overflow: hidden;
        }
        
        .skills-progress {
            height: 100%;
            background: linear-gradient(90deg, #3b82f6, #8b5cf6, #10b981);
            width: 0%;
            animation: fillBar 2s ease-out forwards;
            box-shadow: 0 0 20px rgba(59, 130, 246, 0.6);
        }
        
        @keyframes fillBar {
            to { width: 85%; }
        }
        
        .tech-badges {
            position: absolute;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 12px;
            flex-wrap: wrap;
            justify-content: center;
            max-width: 900px;
        }
        
        .badge {
            padding: 8px 20px;
            border-radius: 20px;
            font-size: 13px;
            font-weight: 600;
            letter-spacing: 0.5px;
            backdrop-filter: blur(10px);
            border: 1px solid;
            animation: fadeInUp 0.6s ease-out backwards;
            transition: all 0.3s ease;
        }
        
        .badge:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.3);
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .badge-blue {
            background: rgba(59, 130, 246, 0.15);
            border-color: #3b82f6;
            color: #60a5fa;
        }
        
        .badge-green {
            background: rgba(16, 185, 129, 0.15);
            border-color: #10b981;
            color: #34d399;
        }
        
        .badge-purple {
            background: rgba(139, 92, 246, 0.15);
            border-color: #8b5cf6;
            color: #a78bfa;
        }
        
        .badge-orange {
            background: rgba(245, 158, 11, 0.15);
            border-color: #f59e0b;
            color: #fbbf24;
        }
        
        .badge-red {
            background: rgba(239, 68, 68, 0.15);
            border-color: #ef4444;
            color: #f87171;
        }
        
        .badge-cyan {
            background: rgba(6, 182, 212, 0.15);
            border-color: #06b6d4;
            color: #22d3ee;
        }
        
        .icon-container {
            position: absolute;
            width: 100%;
            height: 100%;
            pointer-events: none;
        }
        
        .icon {
            position: absolute;
            font-size: 40px;
            opacity: 0.1;
            animation: float-icon 6s infinite ease-in-out;
        }
        
        @keyframes float-icon {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(10deg); }
        }
        
        .gear {
            position: absolute;
            right: 150px;
            top: 50%;
            transform: translateY(-50%);
            width: 80px;
            height: 80px;
            border: 4px solid #10b981;
            border-radius: 50%;
            animation: rotate 10s linear infinite;
            opacity: 0.3;
        }
        
        .gear::before,
        .gear::after {
            content: '';
            position: absolute;
            background: #10b981;
            border-radius: 50%;
        }
        
        .gear::before {
            width: 8px;
            height: 8px;
            top: -4px;
            left: 50%;
            transform: translateX(-50%);
        }
        
        .gear::after {
            width: 8px;
            height: 8px;
            bottom: -4px;
            left: 50%;
            transform: translateX(-50%);
        }
        
        @keyframes rotate {
            from { transform: translateY(-50%) rotate(0deg); }
            to { transform: translateY(-50%) rotate(360deg); }
        }
        
        .download-btn {
            padding: 15px 40px;
            background: linear-gradient(135deg, #3b82f6, #8b5cf6);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(59, 130, 246, 0.3);
        }
        
        .download-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 15px 40px rgba(59, 130, 246, 0.5);
        }
        
        .info {
            color: #64748b;
            font-size: 14px;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div id="banner">
        <div class="grid-bg"></div>
        
        <!-- Particules animées -->
        <div class="particle" style="left: 15%; top: 20%; animation-delay: 0s;"></div>
        <div class="particle" style="left: 25%; top: 60%; animation-delay: 1s; background: #10b981;"></div>
        <div class="particle" style="left: 35%; top: 30%; animation-delay: 2s; background: #8b5cf6;"></div>
        <div class="particle" style="left: 85%; top: 40%; animation-delay: 0.5s; background: #f59e0b;"></div>
        <div class="particle" style="left: 75%; top: 70%; animation-delay: 1.5s; background: #06b6d4;"></div>
        <div class="particle" style="left: 65%; top: 25%; animation-delay: 2.5s; background: #ef4444;"></div>
        
        <!-- Flux de données -->
        <div class="data-flow">
            <div class="flow-line" style="top: 40px; animation-delay: 0s;"></div>
            <div class="flow-line" style="top: 80px; animation-delay: 1s; background: linear-gradient(90deg, transparent, #10b981, transparent);"></div>
            <div class="flow-line" style="top: 120px; animation-delay: 2s; background: linear-gradient(90deg, transparent, #8b5cf6, transparent);"></div>
        </div>
        
        <!-- Engrenage DevOps -->
        <div class="gear"></div>
        <div class="gear" style="right: 200px; top: 30%; width: 60px; height: 60px; border-color: #8b5cf6; animation-duration: 8s; animation-direction: reverse;"></div>
        
        <!-- Icônes flottantes -->
        <div class="icon-container">
            <div class="icon" style="left: 100px; top: 80px; animation-delay: 0s;">⚡</div>
            <div class="icon" style="right: 100px; top: 100px; animation-delay: 1s;">📊</div>
            <div class="icon" style="left: 120px; bottom: 100px; animation-delay: 2s;">🚀</div>
            <div class="icon" style="right: 120px; bottom: 120px; animation-delay: 1.5s;">🔧</div>
        </div>
        
        <!-- Contenu principal -->
        <div class="center-content">
            <h1 class="main-title">DATA ENGINEER</h1>
            <p class="subtitle">ANALYTICS • DEVOPS • CLOUD ARCHITECT</p>
        </div>
        
        <!-- Barre de compétences -->
        <div class="skills-bar">
            <div class="skills-progress"></div>
        </div>
        
        <!-- Badges de technologies -->
        <div class="tech-badges">
            <span class="badge badge-blue" style="animation-delay: 0.1s;">Python</span>
            <span class="badge badge-blue" style="animation-delay: 0.2s;">SQL</span>
            <span class="badge badge-green" style="animation-delay: 0.3s;">Apache Spark</span>
            <span class="badge badge-purple" style="animation-delay: 0.4s;">Docker</span>
            <span class="badge badge-purple" style="animation-delay: 0.5s;">Kubernetes</span>
            <span class="badge badge-cyan" style="animation-delay: 0.6s;">AWS</span>
            <span class="badge badge-cyan" style="animation-delay: 0.7s;">Azure</span>
            <span class="badge badge-orange" style="animation-delay: 0.8s;">Airflow</span>
            <span class="badge badge-red" style="animation-delay: 0.9s;">CI/CD</span>
            <span class="badge badge-green" style="animation-delay: 1s;">Terraform</span>
            <span class="badge badge-blue" style="animation-delay: 1.1s;">ETL/ELT</span>
        </div>
    </div>
    
    <button class="download-btn" onclick="downloadBanner()">📥 Télécharger la bannière (PNG)</button>
    <p class="info">Cliquez sur le bouton pour télécharger votre bannière professionnelle</p>
    
    <script>
        function downloadBanner() {
            const banner = document.getElementById('banner');
            
            // Utiliser html2canvas pour convertir en image
            const canvas = document.createElement('canvas');
            canvas.width = 1200;
            canvas.height = 400;
            const ctx = canvas.getContext('2d');
            
            // Alternative: Utiliser une capture d'écran SVG
            const data = new XMLSerializer().serializeToString(banner);
            const svg = `
                <svg xmlns="http://www.w3.org/2000/svg" width="1200" height="400">
                    <foreignObject width="100%" height="100%">
                        <div xmlns="http://www.w3.org/1999/xhtml" style="width: 1200px; height: 400px;">
                            ${banner.outerHTML}
                        </div>
                    </foreignObject>
                </svg>
            `;
            
            const blob = new Blob([svg], {type: 'image/svg+xml'});
            const url = URL.createObjectURL(blob);
            const img = new Image();
            
            img.onload = function() {
                ctx.drawImage(img, 0, 0);
                canvas.toBlob(function(blob) {
                    const link = document.createElement('a');
                    link.download = 'data-engineer-banner.png';
                    link.href = URL.createObjectURL(blob);
                    link.click();
                    URL.revokeObjectURL(url);
                });
            };
            
            img.src = url;
        }
    </script>
</body>
</html>

## 🧠 À propos de moi

| Domaine | Description |
|----------|--------------|
| 💼 **Profession** | Data Engineer & MLOps Enthusiast |
| 🧰 **Stack technique** | Python, SQL, Spark, Kafka, Airflow, Jenkins, MLflow, Docker, Kubernetes |
| ☁️ **Clouds** | AWS, GCP, Databricks |
| 🧱 **Spécialités** | CI/CD, orchestrations ML, data pipeline, cloud architecture |
| 🎯 **Objectif** | Construire des systèmes data robustes, scalables et automatisés |

---

## 📂 Projets phares

| Projet | Description | Stack principale |
|--------|--------------|------------------|
| 🚗 **[MLops_vehicule_price](https://github.com/sloffer47/MLops_vehicule_price)** | Pipeline complet MLOps pour la prédiction du prix des véhicules : Airflow, MLflow, API FastAPI, Docker, retrain & déploiement auto. | `Python`, `Airflow`, `MLflow`, `FastAPI`, `Docker` |
| 🧱 **[Lakehouse_kubernetes_Project](https://github.com/sloffer47/Lakehouse_kubernetes_Project)** | Architecture Lakehouse sur Kubernetes avec ingestion, stockage et transformation scalable. | `Databricks`, `Kubernetes`, `Spark`, `AWS` |
| 🛰️ **[vehicle-gps-pipeline](https://github.com/sloffer47/vehicle-gps-pipeline)** | Pipeline streaming de données GPS véhicules : ingestion Kafka → traitement Spark → stockage. | `Kafka`, `Spark`, `Databricks` |
| ⚙️ **[Projet_jenkins](https://github.com/sloffer47/Projet_jenkins)** | Intégration et déploiement continu pour modèles ML avec Jenkins et Docker. | `Jenkins`, `Docker`, `CI/CD` |
| 🔄 **[Projet_kafka_pipeline_sparkjob](https://github.com/sloffer47/Projet_kafka_pipeline_sparkjob)** | Traitement temps réel de flux Kafka avec Spark Structured Streaming. | `Kafka`, `Spark`, `Python` |
| 🧠 **[ETL_Databricks](https://github.com/sloffer47/ETL_Databricks)** | Conception d’un pipeline ETL complet sur Databricks : ingestion brute, nettoyage, transformation PySpark et stockage Delta Lake, entièrement versionné avec Git. | `Databricks`, `PySpark`, `Delta Lake`, `Git`, `ETL` |


---

## 🧩 Stack technique & outils

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,docker,airflow,kafka,aws,gcp,databricks,mlflow,kubernetes,jenkins,fastapi,postgres" />
</p>

| Catégorie | Technologies |
|------------|---------------|
| 💻 Langages | Python, SQL, Bash |
| ⚙️ Orchestration | Airflow, Jenkins |
| 🧠 Machine Learning | MLflow, Scikit-learn |
| ☸️ Conteneurisation | Docker, Kubernetes |
| ☁️ Cloud | AWS, GCP, Databricks |
| 📊 Base de données | PostgreSQL, BigQuery, Delta Lake |

---

## 🔬 Ce que je construis
- 🚀 Pipelines de données **end-to-end** (ingestion → transformation → analyse → monitoring)
- 📊 Analyses exploratoires et création de **dashboards interactifs** avec Power BI et Looker Studio
- 🧮 Nettoyage, feature engineering et **data storytelling** pour valoriser la donnée avant le ML
- 🤖 Déploiement automatique de modèles ML avec **Airflow + FastAPI**
- ⚡ Orchestration CI/CD avec **Jenkins**
- ☸️ Mise à l’échelle des jobs via **Kubernetes**
- 🧠 Tracking des expériences avec **MLflow**
- ☁️ Intégration cloud hybride (**AWS / GCP / Databricks**)


---

## 📈 Statistiques GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sloffer47&show_icons=true&theme=tokyonight&hide_border=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sloffer47&layout=compact&theme=tokyonight&hide_border=true" height="160" />
</p>

---

## 🧭 Vision
> “Je transforme les flux de données bruts en systèmes intelligents, orchestrés et observables — du pipeline à la production.”

---

## 📫 Me contacter
- ✉️ **Email** : mbandouyorick@gmail.com 


---

<p align="center">
  <img src="https://github.com/sloffer47/MLops_vehicule_price/assets/illustration_mlops.gif" width="500px" alt="MLOps pipeline illustration"/>
</p>

<p align="center"><i>« Data Engineering n’est pas juste de la tech, c’est de la précision, de la vision et beaucoup de passion. »</i></p>
<p align="center">
  <i>“Les données ne dorment jamais — moi non plus, tant que les pipelines tournent.” 😄</i>
</p>
