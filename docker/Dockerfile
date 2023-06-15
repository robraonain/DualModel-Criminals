FROM rocker/verse:4.2.2

RUN apt-get update -qq
RUN apt-get -y install cmake
RUN apt-get -y --no-install-recommends install libglu1-mesa-dev
RUN apt-get -y install libxml2-dev
RUN apt-get -y install ghostscript
RUN apt-get -y install libxt-dev
RUN apt-get -y install git

RUN install2.r –error \
--deps TRUE \
rmarkdown \
pwr \
tidyselect \
bookdown \
rstatix \
ggpubr \
RColorBrewer \
jtools \
interactions \
lm.beta \
sandwich \
lmerTest \
robustlmm \
car \
stargazer \
effects \
gvlma \
gridExtra \
cowplot \
ggsci \
ez \
afex \
magick \
broman
