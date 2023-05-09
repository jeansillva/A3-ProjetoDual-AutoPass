# Projeto Dual Auto Pass

# Índice/Sumário

* [Sumário](#índice/sumário)
* [Sobre](#sobre-o-projeto)
* [Requisitos Funcionais](#requisitos-funcionais)
* [Tecnologias Usadas](#tecnologias-usadas)
* [Contribuição](#contribuição)
* [Autores](#autores)
* [Licença](#licença)
* [Agradecimentos](#agradecimentos)


# Sobre o Projeto

O projeto de reconstrução e desenvolvimento de novas telas para os ATMs da AutoPass tem como objetivo aprimorar a usabilidade e a experiência do usuário, oferecendo uma interface mais amigável e intuitiva.

O projeto incluirá o redesenho das telas existentes, bem como a criação de novas telas para funcionalidades adicionais, como a recarga de cartões de transporte e a compra de bilhetes de transporte.

A identidade visual do produto será mantida, seguindo as diretrizes da AutoPass, mas com um visual moderno e atraente. Será dada atenção especial à escolha de cores, fontes e elementos gráficos, para que o design seja visualmente agradável e coerente com a marca.   

# Tecnologias Usadas

- [HTML5](https://html.spec.whatwg.org/)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

# 1 - Estudo da Aplicação Características e Requisitos 

A empresa AutoPass é a principal empresa privada no Brasil que oferece as melhores soluções referente a bilhetagem eletrônica e mobilidade. Dentro desse mercado a mais de 12 anos, a empresa tem como principal objetivo implementar uma solução e plataforma digital que possibilite o usuário a utilizar seus serviços de forma satisfatória e simplificar a experiencia em seus produtos.  
  
Visando alcançar esse objetivo e sempre evoluir continuamente em seus serviços e produtos ofertados, foi constatado a necessidade de realizar o redesign da interface gráfica de software dos ATMs (máquinas de autoatendimento) que pertencem a empresa.  
  
O projeto se resume em reconstruir totalmente e até mesmo construir novas telas melhorando a usabilidade e a experiência do usuário. Além de criar e manter a identidade visual do produto ATMs seguindo as diretrizes da AutoPass.  
  
Esse projeto deve garantir que os usuários tenham a acessibilidade e consigam usufruir dos seguintes serviços/produtos: 
  
Bilhete Digital QR Code: é um bilhete digital que utiliza o QR Code e é destinado ao embarque nas mais de 180 estações da CPTM e Metrô de São Paulo.  
  
Cartão Transporte TOP: cartão de transporte exclusivo para embarque no transporte público – estações da CPTM e Metrô, assim como as linhas de ônibus intermunicipais da EMTU. 
  
Bilhete Único: É um cartão que armazena créditos eletrônicos monetários e temporais para pagamento de tarifas no Serviço de Transporte Coletivo Público de Passageiros na Cidade de São Paulo, gerenciado pela SPTrans, e o Sistema Estadual de Transporte Público Metropolitano Metroferroviário (Metrô e CPTM). 
  
Informações retiradas do site oficial da [AutoPass.](https://www.autopass.com.br/produtos/) 
  
# Requisitos Funcionais 

- [x] **Cadastrar Usuário**
- [x] **Fazer Login**
- [ ] Vender Bilhete Digital QR Code via Cartão de Débito 
- [ ] Recarregar Cartão TOP em Dinheiro
- [ ] Recarregar Cartão TOP via Cartão de Débito
- [ ] Recarregar Bilhete Único em Dinheiro
- [ ] Recarregar Bilhete Único via Cartão de Débito
- [ ] Consultar o saldo

# Fluxo de Usuário: 
<div align="center">
  <h3> Fluxo do QR CODE: </h3> <img src="https://user-images.githubusercontent.com/111095599/236970966-4b8d532f-b7db-499e-b611-5fc664eec814.png"width="200rem"/>
  <h3> Fluxo do Cartão TOP: </h3><img src="https://user-images.githubusercontent.com/111095599/236970967-62472937-a0a3-4f85-919e-60e81105b0a8.png"width="1000rem"/>
  <h3> Fluxo do Bilhete único: </h3><img src="https://user-images.githubusercontent.com/111095599/236970961-d509b2d5-0fa3-4f7b-828a-607a79e6725b.png"width="1000rem"/>
</div>

# 2 - Personas

<div align="center">
<img src="https://user-images.githubusercontent.com/111095599/236958158-27ce32d3-d711-40f7-8ae7-c81640b3671f.jpg"width="800rem"/>
<img src="https://user-images.githubusercontent.com/111095599/236958165-93b89914-e365-4b20-b811-d2e6fd7657c9.jpg"width="800rem"/>
<img src="https://user-images.githubusercontent.com/111095599/236958166-a4d697ec-bda6-4529-87e5-da4243a8d71d.jpg" width="800rem"/>
<img src="https://user-images.githubusercontent.com/111095599/236958169-13561c78-fcb4-422b-8a5b-30e513e7c5e4.jpg"width="800rem"/>
<img src="https://user-images.githubusercontent.com/111095599/236958170-4eeab3db-39b0-4f82-b850-a1631fcd113b.jpg"width="800px"/>
<img src="https://user-images.githubusercontent.com/111095599/236958172-fed0daa5-df40-49b8-8ef5-9b7d2ecd0f3f.jpg"width="800px"/>
<img src="https://user-images.githubusercontent.com/111095599/236958173-76f08151-d59d-4a4e-89fe-944670eac3ec.jpg"width="800px"/>
</div>

# 3 - Cenários
<div align="center">
<img src="https://user-images.githubusercontent.com/111095599/236974270-8bacff71-f1d3-4312-a2a6-7dfeb049d945.png"width="700rem"/>
<img src="https://user-images.githubusercontent.com/111095599/236974276-1f30de76-197c-4ed5-aefc-9b712863c84e.png"width="700rem"/>
<img src="https://user-images.githubusercontent.com/111095599/236974279-07bc0831-ed7d-44a9-84e9-4ee65dbcfda7.png"width="700rem"/>
<img src="https://user-images.githubusercontent.com/111095599/236974281-e03c0b39-2e64-432d-b01a-b924f6ef7279.png"width="700rem"/>
<img src="https://user-images.githubusercontent.com/111095599/236974283-a452d868-cfcc-4b08-98a1-5c0afc1a526b.png"width="700rem"/>
<img src="https://user-images.githubusercontent.com/111095599/236974285-86c5a5b7-0810-4918-b209-1ed962952314.png"width="700rem"/>
<img src="https://user-images.githubusercontent.com/111095599/236974290-d3dad188-f9e9-4526-9f5f-72d35d3bd74f.png"width="700rem"/>
</div>
# Contribuição


# Autores



# Licença



# Agradecimentos


