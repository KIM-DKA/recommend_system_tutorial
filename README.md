
---

# Python 을 이용한 개인화 추천 시스템 2판

## Environment

- **Language**: Python (3.8.19)
- **Database**: PostgreSQL
- **Development Tools**: Visual Studio Code, Git, DBeaver, Drawio, Docker, Airflow

## Development Standard

- **Code Style**: PEP 8, SQL Style Guide (Download pylint plugin)
- **Code Review**: GitHub Pull Requests
- **Git Convention**: Git Convention for Data Intelligence Team
- **Branched**: main(maintain), develop(maintain), feature(temporary), hotfix(temporary)
- **Merge Style**:
  - Push `feature` branch to the `develop` branch as `Rebase and Merge`
  - Push `hotfix` branch to the `develop` branch as `Rebase and Merge`
  - Push `develop` branch to the `main` branch as `Merge and Commit`

- **CI/CD**: GitHub Actions

## Installation

- **git repository**

```
git clone https://github.com/KIM-DKA/recommend_system_tutorial.git
```

---
## Virtual Enviroment Setting

- conda env list 출력

```
conda env list
```

- Create virtual Enviroments
```
conda create -n $ENV_NAME python=3.8.19
```

- activate virtual env
```
conda activate $ENV_NAME
```

- Export Env yaml Setttings

```
 conda env export> environments.yaml
```

- Import Env yaml Setttings
```
conda env create -f environments.yaml
```

- Project Packages Install
```
pip install -r requirements.txt
```
