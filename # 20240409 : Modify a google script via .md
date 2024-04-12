# 20240409 : Modify a google script via cli

Install clasp

``` bash
sudo npm install -g @google/clasp
```

Login through google api

``` bash
clasp login
```
Create src project to save your script
Access the google script

``` bash
clasp clone "{project_id}" --rootDir src
```

Push to google script

```bash
clasp -P src/ push
```