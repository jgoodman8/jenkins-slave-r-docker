FROM gradiant/jenkins-slave-r-docker

MAINTAINER "Agustín Cañas" acanas@gradiant.org

USER root

# Install JSON packages
RUN R -e "install.packages(c('RJSONIO', 'rjson'), repos='http://cloud.r-project.org/')"

# Install DPLYR
RUN R -e "install.packages(c('dplyr'), repos='http://cloud.r-project.org/')"

# Install Plumber (REST services)
RUN R -e "install.packages(c('plumber'), repos='http://cloud.r-project.org/')"

# Install packages ('Other packages')
RUN R -e "install.packages(c('fitdistrplus', 'arules'), repos='http://cloud.r-project.org/')"

USER jenkins