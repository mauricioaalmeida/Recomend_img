# Sistema de recomendação por imagens

<p align="left">
  <img src="https://img.shields.io/static/v1?label=&message=Python&color=blue&style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/static/v1?label=&message=PyTorch&color=blue&style=for-the-badge&logo=pytorch"/>
  <img src="https://img.shields.io/static/v1?label=&message=matplotlib&color=blue&style=for-the-badge&logo=matplotlib"/>
  <img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge"/>
</p>


Este Projeto foi realizado por Maurício André de Almeida como trabalho no curso de Treinamento de Redes Neurais com Transfer Learning na DIO.ME


### <b>Implementação:</b>

Neste projeto utilizei o pyTorch com o modelo RESNET18 pré-treinado com IMAGENET e retreinado com o dataset FashionMNIST

Realizei os seguintes passos para cumprir o desafio:

<ul>
<li>Carregar as bibliotecas necessárias</li>
<li>Verificar a disponibilidade da GPU com CUDA</li>
<li>Carregar o modelo ResNet18 pré-treinado</li>
<li>Modificar a camada final para 10 classes (FashionMNIST tem 10 classes)</li>
<li>Carregar e preparar o dataset FashionMNIST</li>
<li>Treinar o modelo com o novo dataset </li>
<li>Avaliar o modelo treinado</li>
<li>Salvar o modelo para futura utilização</li>
<li>Criar funções auxiliares para:</li>
<ul>
  <li>Carregar e pré-processar a imagem</li>
  <li>Prever a categoria da imagem</li>
  <li>Buscar itens semelhantes no Mercado Livre</li>
  <li>Realizar todo o processamento de uma imagem, reconhecendo o item e mostrando itens similares na WEB</li>
</ul>
<li>Realizar testes com algumas imagens encontradas na internet</li>
</ul>



<b>Citação do DATASET:</b>


Fashion-MNIST: a Novel Image Dataset for Benchmarking Machine Learning Algorithms. Han Xiao, Kashif Rasul, Roland Vollgraf. arXiv:1708.07747

Biblatex entry:

@online{xiao2017/online,
  author       = {Han Xiao and Kashif Rasul and Roland Vollgraf},
  title        = {Fashion-MNIST: a Novel Image Dataset for Benchmarking Machine Learning Algorithms},
  date         = {2017-08-28},
  year         = {2017},
  eprintclass  = {cs.LG},
  eprinttype   = {arXiv},
  eprint       = {cs.LG/1708.07747},
}
