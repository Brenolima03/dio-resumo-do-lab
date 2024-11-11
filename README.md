# Resumo do Laboratório de Computação em Nuvem - DIO

No laboratório de computação em nuvem, foram explorados conceitos fundamentais e práticas com a plataforma **Microsoft Azure**, abrangendo desde a criação de contas até o uso de diversos serviços disponíveis. 

### CapEx vs. OpEx
Foram destacadas as diferenças entre **CapEx (Capital Expenditure)** e **OpEx (Operational Expenditure)**:
- **CapEx** envolve o investimento inicial em infraestrutura própria, como servidores e data centers.
- **OpEx** refere-se aos custos operacionais recorrentes, onde a empresa paga apenas pelos recursos que utiliza. A nuvem pública otimiza o OpEx ao reduzir custos iniciais e ao permitir a escalabilidade dos serviços conforme a demanda.

---

### Parte II: Modelos de Disponibilidade e Redundância no Armazenamento
Neste módulo, abordou-se a importância da alta disponibilidade e redundância no armazenamento em nuvem, destacando-se as opções de armazenamento na Azure:

- **LRS (Locally Redundant Storage)** – Armazenamento Localmente Redundante:
  - Replica dados três vezes dentro de um único data center em uma única região.
  - Oferece proteção contra falhas de hardware locais, mas não contra desastres regionais.

- **ZRS (Zone-Redundant Storage)** – Armazenamento com Redundância entre Zonas:
  - Replica dados em três zonas diferentes dentro da mesma região.
  - Protege contra falhas em zonas específicas, garantindo maior disponibilidade na região.

- **GRS (Geo-Redundant Storage)** – Armazenamento com Redundância Geográfica:
  - Replica dados em uma região secundária distante.
  - Proporciona recuperação de desastres em caso de falhas regionais, com replicação assíncrona.

- **GZRS (Geo-Zone-Redundant Storage)** – Armazenamento com Redundância Geo-Zonal:
  - Combina ZRS e GRS, replicando dados em várias zonas na região primária e em uma secundária.
  - Oferece o mais alto nível de resiliência contra falhas regionais e de zona.

---

### Modelos de Serviço em Nuvem: IaaS, PaaS e SaaS
Três principais modelos de serviço em nuvem foram abordados: **IaaS (Infrastructure as a Service)**, **PaaS (Platform as a Service)** e **SaaS (Software as a Service)**, cada um oferecendo diferentes níveis de controle e abstração.

- **IaaS (Infrastructure as a Service)**:
  - Fornece infraestrutura básica de TI, incluindo servidores virtuais, armazenamento e redes.
  - O cliente é responsável pelo gerenciamento do sistema operacional e aplicações.
  - **Ideal para**: Empresas que buscam flexibilidade e controle sobre seu ambiente, substituindo a infraestrutura física e agilizando a escalabilidade.
  - **Exemplo**: Máquinas virtuais no Azure para hospedar sistemas em ambientes personalizáveis.

- **PaaS (Platform as a Service)**:
  - O provedor gerencia a infraestrutura e o sistema operacional, oferecendo uma plataforma pronta para desenvolvimento, implantação e gestão de aplicativos.
  - **Ideal para**: Desenvolvedores, pois o PaaS permite criar e testar código com acesso a bancos de dados e ferramentas sem configurar a infraestrutura.
  - **Exemplo**: App Service do Azure, usado para criar e implantar aplicativos web sem a necessidade de gerenciar servidores.

- **SaaS (Software as a Service)**:
  - O provedor gerencia a infraestrutura, sistema operacional e software, fornecendo ao cliente acesso às aplicações pela internet.
  - **Ideal para**: Soluções padronizadas com fácil acesso e baixo custo de implementação, onde a empresa utiliza ferramentas completas sem precisar de infraestrutura própria.
  - **Exemplo**: Microsoft 365 e Salesforce, onde as empresas pagam por uma assinatura para acessar o software atualizado pelo provedor.

Esses modelos fornecem soluções adaptadas para diferentes necessidades empresariais, oferecendo escalabilidade, controle e economia de custos para diversas situações de uso.
