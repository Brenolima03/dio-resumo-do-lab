# dio-resumo-do-lab
Durante o laboratório, aprendi sobre computação em nuvem, incluindo como criar uma conta na Microsoft Azure e usar os serviços disponíveis. Também entendi a diferença entre CapEx e OpEx: CapEx refere-se ao investimento inicial de uma empresa para adquirir e manter sua própria infraestrutura de TI, como servidores e data centers, enquanto OpEx trata dos custos operacionais contínuos, nos quais a empresa paga apenas pelos recursos que usa. Na nuvem pública, isso permite reduzir os custos iniciais e escalonar os serviços conforme necessário.

Na parte II do laboratório, vimos sobre os preços de alguns modelos de nuvem e suas qualidades, alguns que ficam inativos até por alguns dias durante o ano e outros que ficam apenas minutos. Vimos sobre as zonas de disponibilidade e sobre redundânia de armazenamento.

LRS (Locally Redundant Storage) – Armazenamento Localmente Redundante: Replica os dados três vezes dentro de um único data center em uma única região. Protege contra falhas de hardware local, mas não contra desastres que afetem toda a região.

ZRS (Zone-Redundant Storage) – Armazenamento com Redundância entre Zonas: Replica os dados em três zonas diferentes dentro da mesma região. Protege contra falhas em uma zona específica, garantindo alta disponibilidade na mesma região.

GRS (Geo-Redundant Storage) – Armazenamento com Redundância Geográfica: Replica os dados em uma região secundária distante. Protege contra desastres regionais, replicando dados de forma assíncrona em outra região para recuperação de desastres.

GZRS (Geo-Zone-Redundant Storage) – Armazenamento com Redundância Geo-Zonal: Combina ZRS e GRS, replicando dados em várias zonas de uma região primária e também em uma região secundária. Proporciona o mais alto nível de resiliência contra falhas de zona e de região.
