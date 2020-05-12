# azure-webapps-python-aiohttp
Hello world aiohttp for Github Actions and Oryx

## To run in Azure Web App, you will need to use this custom startup command: 

```python
gunicorn --bind=0.0.0.0 --timeout 600 --worker-class aiohttp.worker.GunicornWebWorker index:app
```

