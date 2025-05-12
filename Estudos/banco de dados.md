# Criando Banco de Dados

## Objetivo
  Criar um banco de dados na plataforma Azure.

Ao acessar a tela inicial, já notamos a presença do serviço "Bando de Dados SQL". Usaremos esse atalho para acessá-lo. Em alguns casos, pode não aparecer esse serviço tão rapidamente, assim, para selecioná-lo, pode-se utilizar a barra de pesquisa na parte superior da tela.

![bd1](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/banco%20de%20dados/foto1.png)


Selecionamos o serviço e, em seguida, clicamos em "Criar".

![bd2](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/banco%20de%20dados/foto2.png)



## Iniciando a Configuração do Banco de Dados SQL

Inicia-se a configuração do banco de dados.
* Associamos à uma assinatura e a um grupo de recursos. No nosso caso, foi adicionado ao recurso "Máquinas1", onde está alocado a Máquina Virtual.
* Em seguida é necessário adicionar um Servidor e o Nome do banco de dados. Primeiro, vamos configurar o Servidor.
![bd3](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/banco%20de%20dados/foto3.png)


### Configurando o Servidor

Preenchemos os campos necessários e, como definimos como Método de Autenticação "Usar a autenticação somente do Microsoft Entra", é necessário associar a um Microsoft Entra ID Administrador. A escolha desse administrador é mostrado no lado direito da imagem abaixo. Por fim, clicamos em "ok".
![bd4](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/banco%20de%20dados/foto4.png)

### Terminando a configuração inicial do Banco de dados

Agora escolhemos o nome do servidor e selecionamos o Ambiente de carga de trabalho como "Desenvolvimento" e por fim a Redundância do armazenamento de backup. Lembrando que, a opção da Redundância afeta diretamente no SLA da aplicação.
![bd5](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/banco%20de%20dados/foto5.png)

### Configuração extras

A depender dos casos, é necessário configurar minuciosamente cada parte do banco de dados. Essas configuração irão variar de acordo com os requisitos que deverão ser atendidos. Para nosso caso, foi deixado padrão, por se tratar da criação de um banco de dados simples.


### Finalização

Após a configuração, fazemos a revisão e obtemos o cus estimado de armazenamento por mês. Após tudo está em conformidade, clica-se em "Criar" e é criado o banco de dados.
![bd6](https://github.com/psoares07/Concepts-Cloud-Azure/blob/main/images/banco%20de%20dados/foto6.png)
