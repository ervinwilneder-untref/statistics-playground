FROM rocker/tidyverse
WORKDIR /home/rstudio
COPY . /home/rstudio

RUN apt-get update
RUN R -e 'install.packages("requiRements")'
RUN R -e 'requiRements::install(path_to_requirements = "requirements.txt")'