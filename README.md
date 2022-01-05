## Building the app
Requirements:
- python3
- pip3

```shell
python3 -m venv venv
. venv/bin/activate
pip3 install -r requirements.txt
```

## Linting the app
```shell
pylint main.py
```

## Testing the app
```shell
py.test --junitxml results.xml test.py
```

## Running the app
```shell
python3 main.py
```
## Screenshot from Jenkins
![Jenkins](https://github.com/ilnikolay/tap-ci/blob/main/jenkins.png "Jenkins")
## Screenshot from SonarQube
![SQ](https://github.com/ilnikolay/tap-ci/blob/main/sonarqube.png "SQ")
