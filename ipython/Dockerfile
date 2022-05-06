FROM miniconda3
LABEL maintainer=@shahir
RUN conda update conda && \
    conda install --quiet --yes ipython && \
    conda clean -tipsy
CMD ["ipython"]
