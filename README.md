## Make any repo deployable for web app deploy. like koyeb and render.

## How Make Any Repo Healthy Deployable In Koyeb?

- Step 1: Add All Above Files in your repo.
  
- Step 2: In koyeb Enter Run command
> gunicorn app:app & your_main_file_name (See in Procfile)

Example:
```
gunicorn app:app & python3 bot.py
```
