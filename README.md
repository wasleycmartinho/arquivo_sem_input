# Gerando arquivo sem input no Jupyter Notebook

Para gerar arquivo em formato html ou pdf sem o input, caso queira enviar uma demonstração rápida dos dados.

Essa etapas foram realizadas no windows 10. 

**Pré-requisito**: Anaconda Navigator.

**Etapa 1**: Abrir o Anaconda Prompt.
Obs.: os próximos passos serão realizados no anaconda prompt

**Etapa 2**: Instalar `nbconvert`.
        
    conda install nbconvert
        
Obs.: só é necessário instalar apenas uma vez.

**Etapa 3**: Ir para o diretório que está o arquivo.

    cd "caminho diretório"
        
**Etapa 4**: digitar

_Para html_

    jupyter nbconvert --to html --no-input meu_notebook.ipynb
      
_Para pdf_

    jupyter nbconvert --to pdf --no-input meu_notebook.ipynb
        


