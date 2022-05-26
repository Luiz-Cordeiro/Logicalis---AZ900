# Simulado AZ900

## 1: Planos de suporte
- Todos os planos além do Basic oferecem a abertura de requisições de suporte técnico 24/7 por telefone ou email.

## 2: Regiões e armazenamento
- Regiões podem possuir múltiplos datacenters, isso provê zonas de disponibilidade para os recursos hospedados no Azure. Os dados dentro de uma região são replicados entre as zonas de disponibilidade de forma síncrona, devido a rede de baixa latência que conecta cada um dos datacenters de uma mesma região. Além disso, é possível replicar os dados entre regiões distintas de modo assíncrono.
- Todos os recursos agregados dentro de uma mesma conta de armazenamento estão sujeitas as mesmas configurações de redundância

### Tipos de redundância:
- Armazenamento com redundância local (LRS): copia os dados de forma síncrona três vezes em um único local físico da região primária.
- Armazenamento com redundância de zona (ZRS): copia os dados de forma síncrona em três zonas de disponibilidade.
- Armazenamento com redundância geográfica (GRS): copia os dados em um único local físico na região primária e, em seguida, copia os dados em um único local físico de uma região secundária
- Armazenamento com redundãncia de zona geográfica (GZRS): copia os dados em um três zonas de disponibilidade na região primária e, em seguida, copia os dados em um único local físico de uma região secundária
- Por padrão, a região secundária não está disponível para leitura. É necessário configurar o acesso de forma pontual.
- Se houver comprometimento da região primária, a secundária assume o papel desta última até que a região primária fique novamente dispónível.

## 3: Planos de suporte
- Azure App Consult: disponibiliza consultorias para a arquitetura cloud do cliente Azure. Está disponível (orientação geral) a partir do plano Programador, porém possui privilégios exclusivos no plano de Suporte Direto Profissional.

## 4: Modelos de serviço
- O ponto de partida para a migração de serviços para nuvem consiste nas máquinas virtuais, logo trata-se de uma infraestrutura como serviço.

## 5: Modelo de serviço 
- O ponto de partida para a migração de serviços para nuvem consiste nas máquinas virtuais, logo trata-se de uma infraestrutura como serviço.

## 6: Modelo de serviço 
- O ponto de partida para a migração de serviços para nuvem consiste nas máquinas virtuais, logo trata-se de uma infraestrutura como serviço.

## 7: Azure Web Tier Plan
- Serviços de web sites:

    - Free: Gratuito e para fins de avaliação. Não possui SLA.
      - 10 sites - 1GB
    - Shared Web Sites: Permite a hospedagem do site 24/7. Capacidade limitada e sem SLA também.
      - 100 sites - 1GB
    - Basic Web Sites: Voltados para a produção de pequenos a médios websites.
      - Sites ilimitados - 10GB - Até 3 instâncias - Computação dedicada
    - Standard Web Sites: Voltados para a produção de médios e grandes websites com alta disponibilidade e operações de desenvolvimento.
      - Sites ilimitados - 50GB - Até 10 instâncias - Computação dedicada

## 8: Azure AD
- É mais viável usar diferentes assinaturas ao invés de usar o Azure Active Directory.

## 9: Azure Web Tier Plan
- O plano Standard oferece 50GB e até 3 instâncias

## 10: Azure expenditure model
- Os modelo de custo aplicável é o operacional

## 11: Azure expenditure model
- Os modelo de custo aplicável é o operacional

## 12: Azure expenditure model
- Os modelo de custo aplicável é o operacional

## 13: Serviços IA
- Cosmos DB é o serviço de banco de dados não relacional do Azure, é compatível com MongoDB e CassandraDB

## 14: Azure AD
- É possível usar o serviço de sincronização entre o Azure AD e o AD on-premises.

## 15: Azure AD
- Azure Machine Learning Studio é a aplicação correta para análise de dados para fins preditivos

## 16: Gerenciamento de API do Azure
- É uma plataforma de gerenciamento de APIs híbrida e multicloud

## 17: Grupos de gerenciamento
- Grupos de gerenciamento permitem controlar permissões de várias assinaturas

## 18: Azure Resource Manager templates
- Trata-se de Infraestrutura como Código (IaC). Permite provisionar recursos cloud do Azure com um script JSON

## 19: SLA da distribuição de carga
- 99,9% - máquina virtual isolada
- 99,95% - datacenter - carga distribuída entre vários racks
- 99,99% - zonas de disponibilidade - carga distribuída entre vários datacenters da região

## 20: SLA da distribuição de carga
- 99,9% - máquina virtual isolada
- 99,95% - datacenter - carga distribuída entre vários racks
- 99,99% - zonas de disponibilidade - carga distribuída entre vários datacenters da região
- A questão colocar apenas 2 zonas de disponibilidade, enquanto o correto seria 3 para  o SLA de 99,99%

## 21: SLA da distribuição de carga
- Para todas as Máquinas Virtuais com duas ou mais instâncias implantadas em duas ou mais Zonas de Disponibilidade na mesma região, garantimos que você terá Conectividade de Máquinas Virtuais, no mínimo, a uma instância, pelo menos, 99,99% do tempo.
- Para todas as Máquinas Virtuais com duas ou mais instâncias implantadas no mesmo Conjunto de Disponibilidade ou no mesmo Grupo de Hosts Dedicados garantimos que você terá Conexão com Máquinas Virtuais, no mínimo, a uma instância, pelo menos, 99,95% do tempo.
- Para qualquer Máquina Virtual de Única Instância que usa SSD Premium ou Disco Ultra para todos os Discos de Sistema Operacional e Discos de Dados, garantimos que você terá Conectividade de Máquinas Virtuais pelo menos 99,9% do tempo.
- Para qualquer Máquina Virtual de Única Instância que usa Discos Gerenciados por SSD Padrão para o Disco de Sistema Operacional e Discos de Dados, garantimos que você terá Conectividade de Máquinas Virtuais pelo menos 99,5% do tempo.
- Para qualquer Máquina Virtual de Única Instância que usa Discos Gerenciados por HDD Padrão para os Discos de Sistema Operacional e Discos de Dados, garantimos que você terá Conectividade de Máquinas Virtuais pelo menos 95% do tempo.

## 22: Azure DevLabs
- Permite provisionar máquinas para ambientes de teste
  - Rápida provisão
  - Pouco desperdício de tempo com políticas e cotas dos recursos
  - Desligamentos automáticos para redução de custos
  - Criação de ambientes Windows e Linux

## 25: Conexões de rede
- Site para site: usada para conexão entre o ambiente on-premises e o Azure network sobre o túnel VPN IPsec/IKE (IKEv1 ou IKEv2)
- VNet para VNet: conexão entre duas ou mais redes virtuais Azure com túnel VPN IPsec/IKE S2S
- Ponto para site (P2S): conexão entre uma rede virtual e um computador cliente individual

## 26: Azure Information Protection
- É uma solução baseada em cloud que permite a organização descobrir, classificar, e proteger documentos e emails, aplicando tags ao conteúdo.

## 27: Azure Multi Factor Authenticator
- É o serviço de autenticação multinível do Azure, baseado nos seguintes princípios:
  - O que você sabe - senha
  - O que você tem - dispositivo móvel, celular
  - O que você é - biometria

## 28: Azure Government
- A Microsoft dispõe de datacenter dedicados, com instalações e redes isoladas (localizadas apenas no território norte-americano) para entidades do governo estadunidense e associados.
- Esse serviço oferece uma camada adicional de segurança através de cláusulas adicionais contratuais que limitam o armazenamento de dados de clientes nos EUA e também limita o acesso de dados de clientes a pessoas com checagem de histórico e idoneidade

## 29: Azure Identity Protection
- Automatizar a detecção e a correção de riscos baseados em identidade.
- Investigar os riscos usando os dados no portal.
- Exportar dados de detecção de riscos para o SIEM.
- Os sinais de risco podem disparar esforços de remediação, como exigir que os usuários: executem a Autenticação Multifator do Azure AD, redefinam sua senha usando a redefinição de senha por autoatendimento ou bloqueiem até que um administrador executa uma ação.

## 30: Azure AD Privileged Identity Management
- É um serviço do Azure AD que permite gerenciar, controlar, e monitorar acesso a recursos importantes na sua organização
- É possível reduzir a concessão de privilégios de acesso e fornecer acesso sob demanda a recursos sensíveis

 










