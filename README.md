## Azure Dev Containers

For a computer with Docker installed, this project should create a Docker image (using `.devcontainer/Dockerfile`) based on anaconda and vscode, and adding Microsoft's ODBC driver, pyodbc, and the faker packages.  Then at startup, it will add the vscode extensions docker, githistory, jupyter, python, pylance.  This folder's code will then be developed and debuged from within that container's controlled environment.
