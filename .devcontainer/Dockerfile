# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.209.6/containers/python-3-miniconda/.devcontainer/base.Dockerfile
FROM mcr.microsoft.com/vscode/devcontainers/miniconda:0.202.1-3

# Install dependencies of OpenCV that don't come with it.
RUN sudo apt-get update
RUN sudo apt-get install libgl1 -y

# Update the conda environment according to the environment.yml file in the project.
# COPY environment.yml /tmp/conda-tmp/
# RUN /opt/conda/bin/conda env update -n base -f /tmp/conda-tmp/environment.yml && rm -rf /tmp/conda-tmp