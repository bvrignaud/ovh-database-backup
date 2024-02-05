# OVH Database Backup

Sauvegarde une base de données sur l'infra ovh, puis download en local le dump précédemment généré.

Ce script est très largement inspiré de clui-ci : https://github.com/illuin-tech/ovh-db-backup.

## Usage
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python -m ovh_db_backup
```
