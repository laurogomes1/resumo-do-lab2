Resumo do Lab sobre Criação de Máquinas Virtuais e Localizações no Microsoft Azure

O que eu aprendi:

Criação de Máquinas Virtuais (VMs):
Aprendi a criar Máquinas Virtuais (VMs) diretamente no portal do Azure. As VMs são servidores virtuais que podem ser configurados com diferentes sistemas operacionais, como Windows ou Linux, e são usadas para hospedar aplicações, bancos de dados, e realizar outras funções de servidor.
Durante o processo de criação, configurei a máquina virtual com parâmetros como:
Tipo de instância (CPU, memória, etc.)
Armazenamento (SSD, HDD)
Rede e segurança (grupos de segurança, firewall)
Localização geográfica
Benefícios de Criar Máquinas em Múltiplas Localizações:
Redundância e Alta Disponibilidade: A criação de máquinas virtuais em diferentes regiões geográficas melhora a disponibilidade e garante que, mesmo que uma região sofra uma falha ou interrupção, as máquinas em outras regiões continuam operando. Isso é essencial para manter os serviços disponíveis para os usuários.
Desempenho Global: Ao distribuir máquinas em várias regiões, é possível reduzir a latência para usuários que estão em diferentes partes do mundo, pois o conteúdo e os serviços podem ser fornecidos a partir do servidor mais próximo geograficamente.
Disaster Recovery: Ter servidores em várias regiões também facilita a implementação de um plano de recuperação de desastres, garantindo que os dados e serviços sejam rapidamente restaurados caso uma região inteira seja afetada.
Escalabilidade: Utilizando múltiplas máquinas em diferentes locais, é mais fácil escalar os recursos conforme necessário, distribuindo a carga de trabalho entre várias regiões e atendendo à demanda de usuários em picos de acesso.
Configuração Regional no Azure:
O Microsoft Azure oferece datacenters distribuídos globalmente, permitindo que você escolha a região de hospedagem de sua máquina virtual. Cada região pode ter características e recursos diferentes, como tipos de VM disponíveis, preços e regulamentações específicas.
Aprendi a importância de escolher a localização geográfica com base na proximidade dos usuários e também nos custos envolvidos, pois diferentes regiões podem ter custos distintos para os mesmos serviços.
Azure Load Balancer:
Utilizei o Azure Load Balancer para distribuir o tráfego de rede entre múltiplas VMs em diferentes regiões. Isso ajuda a equilibrar a carga, evitar sobrecarga de um único servidor e melhorar a resiliência do sistema.
Benefícios Gerais do Microsoft Azure:

Ao longo do lab, pude perceber como o Microsoft Azure facilita a criação de uma infraestrutura global, oferecendo ferramentas que permitem configurar e gerenciar máquinas virtuais de forma eficiente e segura. A possibilidade de distribuir máquinas em diferentes regiões oferece flexibilidade e segurança para projetos de qualquer escala.
