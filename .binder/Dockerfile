################################################################################
###                                                                          ###
### Created by Martin Genet                                                  ###
###                                                                          ###
### École Polytechnique, Palaiseau, France                                   ###
###                                                                          ###
################################################################################

# FROM registry.gitlab.inria.fr/aldabyse/nn-pgd-demos:latest
# FROM ghcr.io/alexandredabyseesaram/fenni-ii-pgd-paper-demo:latest

FROM ghcr.io/alexandredabyseesaram/OJ_internship

ARG NB_USER=jovyan
ARG NB_UID=1000
USER ${NB_USER}
ENV HOME /home/${NB_USER}
COPY --chown=${NB_UID} . ${HOME}
