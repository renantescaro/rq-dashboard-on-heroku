# rq-dashboard-on-heroku
A version of [RQ Dashboard][] that can be deployed to Heroku.

[rq dashboard]: https://github.com/eoranged/rq-dashboard


## Python version
Python 3.10.5


## Deployment
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


## Configuration deploy
Three settings must be configured:
- `RQ_DASHBOARD_REDIS_URL=rediss://redis:6379`
- `RQ_DASHBOARD_USERNAME=user`
- `RQ_DASHBOARD_PASSWORD=pass`


## Local in Windows
In file run_windows.bat, change values `RQ_DASHBOARD_REDIS_URL`, `RQ_DASHBOARD_USERNAME` and `RQ_DASHBOARD_PASSWORD`.

In CMD, run:
```cmd
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
run_windows.bat
```

## License

This project is licensed under the 2-clause BSD license.
