# Deep Learning para reconhecimento de imagens
## [Semana da Engenharia 2018 - Facens](https://www3.facens.br/seat/)

Estes são os arquivos de aula do workshop de deep learning da Semana de Engenharia da Facens de 2018.


# Instalação
Para rodar esses códigos, você precisa primeiramente  **[instalar o Anaconda](https://conda.io/docs/installation.html)** para Python 3.6.

Após ter instalado o Anaconda, rode o seguinte comando:
```
source ~/.bashrc
```

Então, crie o enrivonment do anaconda com o comando
```
conda env create -f environment.yml
```
Esse processo será demorado, pois o conda fará o download de vários pacotes.

# Como rodar o notebook
Para rodar os exemplos é necessário inicializar o servidor jupyter notebook. Para isso, acesse o ambiente criado com o conda
```
source activate dp-facens
```
E depois inicie o jupyter notebook
```
jupyter notebook
```
Pronto! Seu servidor jupyter deve estar rodando. Agora, acesse http://localhost:8888/ e comece a usar!
