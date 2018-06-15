
#### How to setup the Anaconda environment:

- Make sure you have __Anaconda distribution__, if not then visit: [Miniconda Installation](https://conda.io/miniconda.html) to install it.
- For a faster installation, run command (on terminal): `curl -L mini.conda.ml | bash` (Courtesy: [@mikb0b](https://twitter.com/mikb0b))
- For any queries regarding conda environment, visit: [Managing Conda Environments](https://conda.io/docs/user-guide/tasks/manage-environments.html)
- Go to the folder `./flask_api`, you'll encounter `flask_api.yml` file.
- In the terminal run command: `conda env create -f flask_api.yml`
- Once done, run: `source activate flask_api`. Your virtual environment is setup successfully!

## How to run the model ::
1. conda create --name venv python=3.6
2. source activate venv
3. gunicorn --bind 0.0.0.0:8000 hello-world:app
4. gunicorn --bind 0.0.0.0:8000 server:app
5. https:0.0.0.0:8000/predict

