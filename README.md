# Projeto Dual Auto Pass

[Capa do Projeto](https://picsum.photos/850/280

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
  
Informações retiradas do site oficial da AutoPass (https://www.autopass.com.br/produtos/) 
  
# Requisitos Funcionais 

- [x] **Cadastrar Usuário**
- [x] **Fazer Login**
- [ ] Vender Bilhete Digital QR Code via Cartão de Débito 
- [ ] Recarregar Cartão TOP em Dinheiro
- [ ] Recarregar Cartão TOP via Cartão de Débito
- [ ] Recarregar Bilhete Único em Dinheiro
- [ ] Recarregar Bilhete Único via Cartão de Débito
- [ ] Consultar o saldo

# 2 - Personas

![Persona1](https://user-images.githubusercontent.com/111095599/236958158-27ce32d3-d711-40f7-8ae7-c81640b3671f.jpg)
![Persona2](https://user-images.githubusercontent.com/111095599/236958165-93b89914-e365-4b20-b811-d2e6fd7657c9.jpg)
![Persona3](https://user-images.githubusercontent.com/111095599/236958166-a4d697ec-bda6-4529-87e5-da4243a8d71d.jpg)
![Persona4](https://user-images.githubusercontent.com/111095599/236958169-13561c78-fcb4-422b-8a5b-30e513e7c5e4.jpg)
![Persona5](https://user-images.githubusercontent.com/111095599/236958170-4eeab3db-39b0-4f82-b850-a1631fcd113b.jpg)
![Persona6](https://user-images.githubusercontent.com/111095599/236958172-fed0daa5-df40-49b8-8ef5-9b7d2ecd0f3f.jpg)
![Persona7](https://user-images.githubusercontent.com/111095599/236958173-76f08151-d59d-4a4e-89fe-944670eac3ec.jpg)

# 3 - Cenários

Cenário para a Persona Alberto:
Alberto acabou de chegar em casa depois de um dia cansativo de trabalho no centro de São Paulo. Ele está sentindo a tensão do dia ainda em seus ombros e pensa no que precisa fazer para se preparar para o dia seguinte. Ele se lembra que precisa recarregar o cartão de bilhetes para a passagem de ônibus da semana. Como ele não quer sair de casa novamente, decide usar o aplicativo da TOP, que oferece uma opção de recarga de crédito por Pix. Ele pega o telefone e abre o aplicativo. Ele é direcionado para a página de login, onde ele coloca suas credenciais de usuário. Ao entrar no aplicativo, ele vai até a opção de recarga de crédito do cartão de ônibus e seleciona a opção de Pix. Ele então insere o valor que deseja recarregar e confirma a transação. A página do aplicativo mostra a confirmação da transação e o valor total que ele acabou de recarregar. Alberto se sente aliviado e agradece pela facilidade e rapidez do aplicativo. Ele decide então passar o restante da noite com a família, assistindo televisão e jogando jogos de tabuleiro com seus filhos. Ele se sente grato por ter encontrado uma maneira fácil de lidar com uma das muitas tarefas que tem em sua rotina diária.

Cenário para a Persona Sophia:
Sophia está caminhando em direção à parada de ônibus quando percebe que esqueceu seu celular em casa. Ela se sente frustrada porque precisa recarregar seu cartão de bilhetes de ônibus e não tem certeza se pode fazer isso sem o celular. Ela verifica o tempo e percebe que o ônibus que ela precisa pegar passará em 15 minutos. Ela se lembra que seu pai deixou um cartão de crédito com ela para emergências. Ela decide tentar recarregar seu cartão de ônibus em um ATM que fica perto da parada de ônibus. Quando chega ao ATM, ela insere o cartão de crédito e seleciona a opção de recarga de bilhetes de ônibus. Sophia seleciona o valor que deseja recarregar e confirma a transação. Ela se sente aliviada quando a tela do ATM mostra que a recarga foi bem-sucedida. Ela pega o comprovante e corre de volta para a parada de ônibus, sabendo que tem apenas alguns minutos para chegar a tempo. Ela finalmente chega à parada de ônibus e percebe que o ônibus que ela precisa pegar ainda não chegou. Ela aproveita o tempo para ler o novo romance que acabou de pegar na biblioteca e se perde na história. Quando o ônibus chega, ela sobe a bordo e se sente grata por ter encontrado uma solução rápida e eficaz para seu problema.

# Contribuição

Leia o arquivo [CONTRIBUTING.md](CONTRIBUTING.md) para saber detalhes sobre o nosso código de conduta e o processo de envio de solicitações *pull* (*Pull Request*) para nós.

# Autores

[Exemplo](https://github.com/testing-library/react-testing-library#contributors)

# Licença

Este projeto está licenciado sob a Licença MIT,  consulte o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.

# Agradecimentos

Seção livre para você agradecer a todos que contribuiram para a execução do seu projeto.
