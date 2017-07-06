FROM dookie23/jenkins-slave-r-docker

MAINTAINER "Agustín Cañas" acanas@gradiant.org

RUN R -e "install.packages(c('dplyr'), repos='http://cloud.r-project.org/')"

RUN R -e "install.packages(c('RJSONIO', 'rjson'), repos='http://cloud.r-project.org/')"

RUN R -e "install.packages(c('plumber), repos='http://cloud.r-project.org/')"