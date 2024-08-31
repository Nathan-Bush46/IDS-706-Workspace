# IDS-706-Workspace

# Set up instructions using VS code + Docker: 
## Docker
1. For Windows, Mac, and maybe Linux, you download Docker Desktop. links can be found [here](https://docs.docker.com/engine/install/). Follow set up instructions and start the application.

2. In vs code add Dev Containers and Docker extensions 

3. clone repo, restart vs code, and open repo in vs code. 

4. should see a pop up to (re)open in devcontainer. Click it and let it run. It takes a bit of time for the first run but is much faster after that. Done.

### Alternatives to Docker
If you choose not to run docker, use a python virtual environment to prevent conflict with local packages and run the makefile.

 
# Testing

## makefile  
1. run makefile test to test all "\*test\*.py" files in src/test/ 
## VS code testing  
1. Can also use the VS-code testing menu in the same way.

## Things included are:

* `Makefile`

* `Pylint`

* `.devcontaner` with `Dockerfile`, `devcontaner.json`, and `postinstall.sh` 

*  vscode `settings.json` for testing

*  A base set of libraries in [text](requirements.txt)