# Explorando o portal Azure

## Criação de Máquinas Virtuais

O Objetivo dessa primeira parte é registrar a criação de uma Máquina Virtual no portal Azure. Foi focado em montar uma máquina teste, portanto não foi realizado grandes personalizações da máquina.

### Tela inicial

Primeiramente, abre-se o ambiente inicial da plataforma, como mostrado abaixo.

![tela-inicial](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/1.png)

### Selecionando o serviço de Máquina Virtual
Ao selecionar as três barras no canto superior direito e clicarmos e "Todos os serviços" acessamos aos serviços do portal.

![imagem2](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/3.png)

Na barra de busca, escrevemos "Máquinas Virtuais" e selecionamos o serviço.

![imagem-maq](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/2.png)


Clica-se em "Criar" para entrar no ambiente de criação.

![imagem4](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/4.png)

### Configurando a Máquina Virtual

Entra-se no ambiente de configuração como mostrado abaixo. Podemos resumir as configurações da seguinte forma:
* Define-se a qual assinatura e grupo que a máquina irá se vincular. No nosso caso, não havia grupos, portanto foi criado o grupo "Máquinas1"
![imagem5](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/5.png)

* Define-se o nome, região e zona (ou zonas) da VM. Nessa parte é importante ressaltar que, ao avaliar uma VM que será utilizada na organização, é necessário avaliar atentamente essas configurações para garantir disponibilidade do serviço que estiver em execução. Para nosso caso, como é uma máquina de testes a configuração mais simples foi utilizada.
![imagem6](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/6.png)

* Define-se o Sistema Operacional. Nesse caso foi escolhido "Ubuntu Server 24.04 LTS – Gen2".
![imagem7](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/7.png)

* Por se tratar de uma máquina de testes, foi escolhida uma VM de tamanho menor, como pode ser visto na imagem abaixo.
![imagem9](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/9.png)

No mais, foi deixado padrão todas as outras configurações. Após a revisão e validação da configuração, foi criado a Máquina Virtual.

![imagem10](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/10.png)



