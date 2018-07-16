FROM gradiant/jenkins-slave-r-docker:master

MAINTAINER "Agustín Cañas" acanas@gradiant.org

USER root

# Install Packrat
RUN R -e "devtools::install_github('rstudio/packrat')"
RUN chmod -R 777 /usr/local/lib/R/site-library

USER jenkins