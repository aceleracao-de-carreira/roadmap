# Computação em nuvem (Cloud Computing)

## Modelos de implantação de computação em nuvem

Se quisermos entender melhor como as tecnologias de nuvem funcionam, precisamos examinar três modelos de implantação.
Independentemente do modelo escolhido, os clientes procuram seu provedor de nuvem ideal e decidem quais serviços desejam usar (SaaS, IaaS, PaaS, ...).

### Nuvem Pública

Nuvens públicas são o tipo mais comum e popular. Este produto é oferecido aos clientes pelos provedores e os recursos são acessíveis pela internet. Os fornecedores cuidam de tudo que diz respeito à infraestrutura. Exemplos de provedores: Microsoft Azure, Amazon Web Services (AWS) e Google Cloud Platform.

### Nuvem Privada

A nuvem privada é como um data center interno. A organização paga e gerencia a infraestrutura e a equipe desfruta dos benefícios usuais da computação em nuvem, como escalabilidade e compartilhamento de recursos, aproveitando a virtualização.

### Nuvem Híbrida

A nuvem híbrida combina os modelos público e privado, conectando-os via internet e redes virtuais privadas. O modelo híbrido é ideal para empresas que desejam ter um backup virtual externo para mitigação de desastres ou se a organização usou todos os seus recursos internos e requer poder de computação adicional. O Híbrido funciona particularmente bem se uma organização tiver dados armazenados em uma nuvem pública, liberando espaço de armazenamento na nuvem privada para dados privados e confidenciais.

### [Bônus] Multicloud

Multicloud se baseia na utilização de pelo menos dois ambientes distintos na nuvem de maneira simultânea. Sua abordagem é formada pela utilização de mais de um fornecedor de nuvem pública. Ela também pode ser definida como uma forma de implementação e administração da computação em nuvem.

É comum a comparação entre nuvem híbrida e multicloud. A nuvem híbrida se enquadra como uma combinação de serviços entre nuvem privada e pública, ambas sendo integradas por uma camada de software ou plataforma de orquestração. Deste modo, o serviço consegue funcionar corretamente de maneira transparente. Já a multicloud envolve dois ambientes de nuvem pública, podendo ter também, ou não, mais um ambiente de nuvem privada.

## Modelos de computação em nuvem

Existem basicamente três modelos de negócio e tecnologias, embora alguns fornecedores possam listar mais modelos, que são variações dos principais modelos: SaaS, PaaS e IaaS.

![Infografico](https://azurecomcdn.azureedge.net/cvt-40a2e09beb1091376af315aecd7f952555711812a53ac824c5c44e46e572906b/images/page/overview/what-is-saas/what-is-saas.png)

|||||||
|-|-|-|-|-|-|
|Apps/aplicativos hospedados|Ferramentas de desenvolvimento, gerenciamento de banco de dados, análise de negócios|Sistemas operacionais|Servidores e armazenamento|Segurança/firewalls de rede|Construção/planta física do datacenter|
|||||||

Créditos: [https://azure.microsoft.com/pt-br/overview/what-is-saas/](https://azure.microsoft.com/pt-br/overview/what-is-saas/)

### SaaS (Software as a Service) - Software como serviço

O SaaS é um modelo de software vendido como um serviço e não está ligado à aquisição de licenças. O pagamento pode ser feito por meio de assinaturas ou de acordo com os serviços que são realmente utilizados.

Com esse modelo não é necessário instalar, manter e atualizar hardwares ou softwares.

O provedor do serviço, assume toda a responsabilidade pelas atualizações e gerenciamento de acessos, incluindo a segurança da informação, disponibilidade e desempenho.

Os aplicativos SaaS também são chamados de softwares baseados na Web, softwares sob demanda ou softwares hospedados.

Principais exemplos de SaaS disponíveis:
- Dropbox
- Google Drive
- Google Analytics
- Netflix
- Paypal
- DocuSign
- Slack
- Zendesk
- Outlook
- Gmail

### PaaS (Platform as a Service) - Plataforma como Serviço

Fornece um ambiente na nuvem que possibilita o desenvolvimento e implantação de aplicativos mais simples até softwares empresariais mais complexos. Os recursos necessários podem ser adquiridos por meio de um provedor de serviços hospedado na nuvem e o acesso é feito por meio da internet.

Como é o caso do IaaS, a Plataforma como Serviço fornece infraestrutura, como servidores, rede e armazenamento, mas também proporciona ferramentas voltadas para o desenvolvimento, BI (Business Intelligence), sistemas de gerenciamento de banco de dados, entre outros.

Principais exemplos de PaaS disponíveis:
- AWS Elastic Beanstalk
- Windows Azure
- Heroku
- Tsuru
- Read Hat OpenShift

### IaaS (Infrastructure as a Service) - Infraestrutura como serviço

Ao invés de precisar investir na aquisição de itens de infraestrutura, como roteadores, servidores, racks, entre outros, a contratação é feita por meio de serviços, com servidores virtuais.

O provedor de IaaS também fornece uma variedade de ferramentas e serviços para o gerenciamento da infraestrutura, facilitando os processos de monitoramento e controle de acessos, balanceamento de cargas de trabalho e implementações de políticas de segurança, como backups, replicações e planos de recuperação.

Principais exemplos de IaaS disponíveis:
- AWS EC2
- Digital Ocean
- Microsoft Azure
- Oracle Cloud Infrastructure
- Google Compute Engine (GCE)

## [Bônus] XaaS - Tudo como Serviço

O XaaS reflete como as empresas em todo o mundo estão adotando o método de que qualquer coisa no setor de TI pode ser entregue como um serviço pela Internet.

O principal objetivo das ofertas XaaS é aumentar o valor para o cliente. Em um modelo XaaS, você deseja converter compradores ocasionais em assinantes de serviço que recebem benefícios contínuos do produto.

No conceito do que é XaaS, tudo pode ser oferecido: 

- por intermédio da tecnologia cloud computing;
- com acesso por diferentes dispositivos permitido;
- de acordo com a demanda do cliente.

O XaaS se originou com o modelo SaaS e inclui IaaS, PaaS e modelos ainda mais específicos de funcionalidade, como banco de dados como serviço (DBaas), Desktop como um serviço (DaaS) e mais.

## Serverless Computing - Computação sem servidor

Com o modelo serverless, o provedor de nuvem executa servidores físicos e aloca dinamicamente os recursos deles em nome dos usuários, que podem implantar código diretamente na produção.

As soluções de computação serverless costumam ser divididas em duas categorias: back-end como serviço (BaaS) e função como serviço (FaaS).  

Com o BaaS, os desenvolvedores têm acesso a vários serviços e aplicações de terceiros. Por exemplo, talvez um provedor de nuvem ofereça serviços de autenticação, criptografia extra, bancos de dados acessíveis pela nuvem e dados de uso de alta fidelidade. Normalmente, você chama as funções serverless por meio de interfaces de programação de aplicações (APIs).

Na verdade, quando os desenvolvedores se referem ao serverless, é mais provável que eles estejam falando do modelo FaaS. Com esse modelo, os desenvolvedores ainda gravam uma lógica personalizada no lado do servidor, mas ela é executada em containers totalmente gerenciados por um provedor de serviços de nuvem. 

## [Extra] Alguns outros tipos de XaaS

### Baas (Backend as a Service) - Backend como serviço

Baas é um middleware para seu aplicativo. Ele fornece APIs para seus aplicativos web e móveis, prontos para serem integrados online.

Imagine que você seja um desenvolvedor com recursos limitados e pouco tempo para desenvolver sua solução.
Usando um provedor BaaS, você pode executar algumas tarefas repetitivas entre seus aplicativos da web e móveis, como fazer login e armazenar arquivos. Você não precisa se preocupar com a infraestrutura envolvida e com a implementação da regra de autenticação; você terceirizará esse trabalho para o BaaS.

Principais exemplos de Baas disponíveis:
- Firebase
- RapidAPI
- Back4App
- Backendless
- AWS Amplify
- Couchbase
- 

### DBaaS (Database as a Service) - Banco de dados como serviço

DBaas é um serviço de banco de dados executado em uma plataforma de computação em nuvem, provê escalabilidade e alta disponibilidade através de uma camada de softwares e hardwares que são transparentes para o usuário, trazendo assim acesso direto às bases de dados, sem a necessidade de manutenção da camada sistema do banco de dados ou do hardware físico e suas configurações.

Principais exemplos de DBaaS disponíveis:
- Bancos de dados (Amazon RDS)
- API Gateways (Mulesoft)
- Autenticação (Google OAuth)
- Blockchain (Ethereum)

## DaaS (Desktop as a Service) - Desktop como um serviço

DaaS é uma oferta de computação em nuvem em que um provedor fornece desktops virtuais (VDI) para os colaboradores. Tudo isso é feito pela internet e licenciado com uma assinatura por usuário.

Os sistemas operacionais de desktop são executados em máquinas virtuais em servidores em um data center de provedor de nuvem. Toda a infraestrutura de suporte necessária, incluindo recursos de armazenamento e rede, também reside na nuvem.

Assim como acontece com o VDI local, um provedor de DaaS transmite desktops virtuais através de uma rede para os dispositivos de um cliente, onde os usuários finais podem acessá-los por meio de software cliente ou um navegador da web.

**VDI** (Virtual Desktop Infrastructure). Caso não conheça o termo, se refere à virtualização do sistema operacional do computador, permitindo que sejam criadas várias máquinas virtuais dentro do sistema.

Principais exemplos de DaaS disponíveis:
- Amazon WorkSpaces
- Citrix DaaS
- Windows Virtual Desktop
- VMWare Horizon Cloud

## FaaS (Function as a Service) - Função como serviço

É uma parte da computação sem servidor e se concentra principalmente em gateways, armazenamento, API e competições. Estas são categorias de serviço FaaS. É uma assistência mais simples e permite ao desenvolvedor economizar tempo na codificação.

Principais exemplos de FaaS disponíveis:
- AWS Lambda
- Google Cloud Functions
- Azure Cloud Functions
- Cloudflare Workers
- IBM Cloud Functions

## Links Úteis

- [O que é cloud computing?](https://www.mandic.com.br/cloud/)
- [Computação em nuvem: tudo que você precisa saber sobre](https://blog.ecoit.com.br/computacao-em-nuvem/)
- [Computação em nuvem: o que é e como funciona?](https://www.voitto.com.br/blog/artigo/computacao-em-nuvem)
- [O que é computação em nuvem?](https://www.cisco.com/c/pt_br/solutions/cloud/what-is-cloud-computing.html)
- [Computação em Nuvem (Cloud Computing)](https://www.youtube.com/watch?v=e3rQ373LnC0)
- [Cloud Computing (Computação em Nuvem) // Dicionário do Programador](https://www.youtube.com/watch?v=97l0Ahu2efE)
- [Modelos de Implantação | Introdução](https://www.gta.ufrj.br/grad/15_1/openstack/nuvem/implantacao.html)
- [Computação em nuvem: pública, privada ou híbrida?](https://teltecsolutions.com.br/mundo/computacao-em-nuvem)
- [Armazenamento na nuvem: 4 tipos diferentes de cloud](https://www.copeltelecom.com/site/blog/armazenamento-na-nuvem-4-tipos-de-cloud/)
- [Passo a passo: aprenda como implementar sistema na nuvem](https://blog.ccmtecnologia.com.br/post/como-implementar-sistema-na-nuvem)
- [Nuvem privada](https://www.vmware.com/br/topics/glossary/content/private-cloud.html)
- [Nuvem pública](https://www.vmware.com/br/topics/glossary/content/public-cloud.html)
- [Nuvem híbrida](https://www.vmware.com/br/topics/glossary/content/hybrid-cloud.html)
- [Multi-cloud](https://www.vmware.com/br/topics/glossary/content/multi-cloud.html)
- [SaaS: entenda como funciona o modelo de software como serviço](https://blog.vindi.com.br/saas/)
- [SaaS: O Que É, Como Funciona, Exemplos e Benefícios](https://neilpatel.com/br/blog/saas/)
- [SaaS: o que é, benefícios e exemplos práticos](https://conteudo.movidesk.com/o-que-e-saas/)
- [IaaS, PaaS e SaaS: entenda os modelos de nuvem e suas finalidades](https://brasil.softlinegroup.com/sobre-a-empresa/blog/iaas-paas-saas-nuvem)
- [SaaS, PaaS, IaaS, XaaS, DaaS: entenda de uma vez por todas as diferenciações](https://inova.globalweb.com.br/post/saas-paas-iaas-xaas-daas-entenda-de-uma-vez-por-todas-as-diferenciacoes)
- [O que é IaaS?](https://4linux.com.br/o-que-e-iaas/)
- [O que é PaaS (Platform as a Service)](https://solvimm.com/blog/o-que-e-paas/)
- [Tipos de Computação em Nuvem – Um Guia Extenso de Soluções e Tecnologias em Nuvem em 2021](https://kinsta.com/pt/blog/tipos-de-computacao-em-nuvem/)
- [Conheça o XaaS, o modelo de negócio baseado na oferta ampla de serviços](https://rockcontent.com/br/blog/xaas/)

## Considerações finais

Fica mais fácil usar o termo Xaas. haha
Acredito que ficou claro que tudo na área de TI, pode ser um serviço.

Finalizo com algumas vantagens da computação na nuvem:

- Redução de custos
- Segurança
- Flexibilidade
- Mobilidade
- Controle de qualidade
- Recuperação de Desastres
- Prevenção de perdas
- Atualizações Automáticas de Software
- Vantagem Competitiva
- Sustentabilidade

Qualquer dúvida, estou à disposição.
Provavelmente este texto terá novas atualizações para ficar mais didático.
