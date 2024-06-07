# DISRUPTIVE ARCHITECTURES: IOT, IOB & GENERATIVE IA


##  Modelos: 

https://app.roboflow.com/gutodidonato/fishes-troublemakers-polution/deploy

https://app.roboflow.com/espao-mzqoc/sujeira-e-oleo-sobre-o-mar/deploy

https://app.roboflow.com/espao-mzqoc/lixo-na-praiaa/deploy

##  Sobre os modelos: 

1. fishes-troublemakers-polution
    1. classes
        1. aquatic animals
        2. human
        3. lionfish
        4. thrash
2. sujeira-e-oleo-sobre-o-mar
    1. classes
        1. garbage
        2. oilspill
3. lixo-na-praiaa
    1. classes
        1. lixo

##  Justificativa dos modelos: 

O primeiro modelo foi proposto como desafio fundamental, escolhemos espécies marinhas em imagens
subaquáticas, querendo distinguir vida marinha comum, entre humanos, poluentes e um tipo de peixe que vem causando grande problema na vida marinha brasileira que é o peixe leão, a escolha dele foi por causa da falta de predadores deste peixe, por causa do seu veneno, e a capacidade predatória dele de peixes menores, sendo necessária a mão do homem no controle populacional de peixes leão.

O segundo modelo ele participa do nosso projeto principal como tecnologia embarcada em drones, para detecção de óleo e lixo sobre o mar, para futuramente ongs fazerem a captura e redirecionamento dessa carga de material.

O terceiro modelo já está embarcado no nosso app mobile, o **Water2Save**, onde a foto tirada pelo usuário ira ser validada pela api disponibilizada pelo roboflow, conforme a resposta será criado um foco para as empresas próximas fazerem o redirecionamento. Este modelo é capaz de detectar sujeira superficial nas praias 


##  Metodologia:

Para equilibrar o viés e a variância, utilizamos um grande volume de imagens rotuladas de forma eficiente. Nosso objetivo é criar um modelo capaz de reconhecer uma ampla diversidade de imagens, abrangendo diferentes cenários e condições. Para isso, empregamos diversos modelos pré-treinados, aproveitando seus valiosos datasets de imagens para melhorar a robustez e a precisão do nosso modelo.

Reconhecemos que o modelo ainda não está perfeito. Devido à captura de imagens de diferentes fontes, com variadas resoluções e estados da água, seria necessário um volume ainda maior de imagens para alcançar uma precisão ideal. No entanto, para um MVP (Produto Mínimo Viável), o desempenho obtido foi satisfatório, permitindo-nos seguir adiante com o projeto.

Para aumentar a precisão das avaliações, optamos por destinar 15% dos dados para os conjuntos de validação e teste, respectivamente. Mesmo com 70% dos dados destinados ao treinamento, os modelos atingiram índices aceitáveis de mAP (mean Average Precision), precisão (precision) e recall, demonstrando boa capacidade de generalização.

O treinamento dos modelos foi realizado utilizando a plataforma **Roboflow**, que nos proporcionou um ambiente eficiente e eficaz para a preparação e treinamento dos nossos modelos. Os resultados obtidos foram bastante satisfatórios, confirmando a viabilidade do nosso approach para este MVP.


##  App:
link para o app Water2Save: https://github.com/gutodidonato/Global-mobile

para utilizar o backend do app mobile é necessário entrar em contato comigo