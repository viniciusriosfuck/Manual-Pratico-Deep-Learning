Este repositório contém todo o código-fonte do curso __Manual Prático do Deep Learning__ na Udemy.

### [Link para o curso](https://www.udemy.com/course/redes-neurais/?referralCode=34C61CFBEACD87D2FD37)

### [Link para os slides](https://www.icloud.com/keynote/0LZvPsaugs7uCqr4TS-keRh-g#Manual)

# Instalação
1. Baixe ou clone o repositório.
2. Baixe e instale o [Miniconda](https://conda.io/miniconda.html). (__Windows__: marque a opção de adicionar o conda às variáveis de ambiente (_$PATH_))
3. Abra o terminal e digite o seguinte comando para instalar o ambiente:
    ```sh
    $ conda create -n mpdl python=3.8.2 numpy=1.18.1 pandas=1.0.3 matplotlib=3.1.3 scikit-learn=0.22.1 jupyter=1.0.0
    ```

# Uso do ambiente

> __Nota:  É obrigatório seguir as ordens da seção "Instalação" antes de utilizar o ambiente__.

Siga os passos abaixo sempre que quiser executar os códigos desse repositório.
1. Abra o terminal e digite:

    - __Windows__:
    ```sh
    $ activate mpdl
    ```
    - __Linux/Mac__:
    ```sh
    $ source activate mpdl
    ```

2. Instale extensões com widgets do notebook
    ```sh
	jupyter nbextension enable --py widgetsnbextension --sys-prefix
    ```

3. Instale autopep8 (guideline para códigos em Python)
    ```sh
	pip install autopep8
	```

4. Instale extensão para temas para jupyter-notebook
    ```sh
	conda install -c conda-forge jupyterthemes
	```

5. Sugestão de tema (dark mode)
    ```sh
	jt -t chesterish
	```

6. Execute o Jupyter Notebook:
    ```sh
    $ jupyter notebook
    ```

	
# Dúvidas ou sugestões?

Sinta-se à vontade para sanar qualquer dúvida diretamente com o professor do curso utilizando o contato mais abaixo. Porém, de preferência a fazer perguntas no fórum do curso ou aqui mesmo no Github. Se possível, siga as orientações abaixo de acordo com o tipo da sua dúvida:

- __Conteúdo teórico__: faça a pergunta dentro do próprio vídeo do udemy referente a pergunta ou utilize a seção FAQ do curso.
- __Código__: abra uma issue aqui no repositório.

> __Lembre-se que a sua dúvida pode acabar ajudando outras pessoas com a mesma dúvida!__

# Contato

:bust_in_silhouette: __Arnaldo Gualberto__:

* arnaldo.g12@gmail.com
* [Github](https://github.com/arnaldog12)
* [Site Pessoal](http://arnaldogualberto.com)
* [LinkedIn](https://www.linkedin.com/in/arnaldo-gualberto/)
