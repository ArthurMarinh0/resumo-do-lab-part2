# resumo-do-lab-part2
Este repositório tem um resumo das lições estudadas na segunda parte do lab da DIO.

1 - Aqui aprendi sobre os três principais modelos de serviço da computação em nuvem, que são formas diferentes de consumir os recursos da nuvem. 

O IaaS(Infraestrutura como Serviço) é quando a nuvem oferece recursos básicos como servidores, rede e armazenamento. O usuário tem controle sobre o sistema operacional e os aplicativos.
Exemplo: Amazon EC2.
Esse modelo da mais liberdade para configurar o ambiente.

O PaaS(Plataforma como Serviço) fornece um ambiente pronto para desenvolver, testar e implantar aplicativos. Não preciso me preocupar com a infraestrutura por trás.
Exemplo: Google App Engine.
Esse modelo da tempo para focar no código e deixar o resto por conta da nuvem.

O SaaS(Software como Serviço) são os aplicativos prontos, acessados via internet. Não preciso instalar nada nem me preocupar com atualizações.
Exemplo: Gmail, Microsoft 365.
Esse modelo se usa quando e necessario apenas usar o software sem me preocupar com a parte técnica.

2 - Na parte de modelo de Responsabilidade Compartilhada, aprendi que, na nuvem, a responsabilidade pela segurança e gerenciamento dos recursos é dividida entre o provedor de nuvem e o cliente.

-O provedor é responsável pela segurança da nuvem (infraestrutura, data centers, rede).
-O cliente é responsável pelo que ele gerencia, como dados, usuários e configurações.
-Essa responsabilidade varia conforme o modelo de serviço:

Em IaaS, o cliente tem mais responsabilidade.
Em PaaS, responsabilidade média.
Em SaaS, o provedor assume quase tudo.

3 - Casos de Uso para IaaS, PaaS e SaaS. 
Aqui aprendi a identificar quando usar cada modelo de nuvem.

IaaS: bom para empresas que querem mais controle sobre o ambiente, como em testes avançados ou migração de sistemas legados.

PaaS: ideal para desenvolvedores que querem criar e lançar aplicações sem gerenciar servidores.

SaaS: ótimo para uso direto de aplicativos como e-mails, editores de texto, CRM e outros sistemas prontos.

Resumidamente, esses modelos mostram como a nuvem pode ser usada de formas diferentes, dependendo da necessidade de controle, praticidade e tipo de aplicação que se deseja utilizar. Se eu quiser mais liberdade, uso IaaS; se quiser focar no desenvolvimento, uso PaaS; e se quiser só usar um sistema pronto, uso SaaS.

4 - Criando um Banco de Dados no Azure
Aqui aprendi, na prática, como criar um banco de dados na nuvem usando o Microsoft Azure. Entendi que o Azure oferece serviços de banco de dados como parte do modelo PaaS, ou seja, não preciso me preocupar com a infraestrutura por trás.

O processo de criação foi simples e envolveu os seguintes passos:
Acessar o portal do Azure com minha conta.

No menu de serviços, escolhi a opção “SQL Database”.

Cliquei em “Criar” e preenchi as informações básicas, como:

Nome do banco de dados.

Nome do servidor (e criei um, caso não existisse).

Grupo de recursos.

Escolhi a camada de desempenho, dependendo da capacidade e custo desejado.

Após a criação, o banco de dados ficou disponível, e eu pude usar o Query Editor do próprio Azure para executar comandos SQL.

Com isso, entendi que é possível criar e gerenciar bancos de dados completos na nuvem, com alta disponibilidade, segurança e escalabilidade, sem precisar instalar nada no computador.

