FROM gradiant/jenkins-slave-r-docker:master

MAINTAINER "Agustín Cañas" acanas@gradiant.org

USER root

# Install Packrat
RUN R -e "devtools::install_github('rstudio/packrat')"

USER jenkins