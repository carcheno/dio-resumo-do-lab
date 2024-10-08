## Criar máquinas Virtuais:

O SLA (Acordo de Nível de Serviço) define o tempo máximo de indisponibilidade de um serviço. Ao contratar um serviço, o cliente recebe créditos caso o SLA seja violado, na Azure. A disponibilidade e o custo estão diretamente relacionados: maior disponibilidade implica em custos mais elevados. É essencial avaliar as necessidades específicas para cada projeto para escolher o SLA mais adequado.

Para criar uma máquina virtual:

1. Acesse _Categories_ -> _Compute_ -> _Virtual Machines_.

![](../img/azure_essentials/provisioning-virtual-machines/azure_01.png)  
2. Clique em _Create_.

![](../img/azure_essentials/provisioning-virtual-machines/azure_02.png)  
3. Configure as opções de acordo com as necessidades do projeto. Por exemplo, para garantir alta disponibilidade, escolha a opção _Availability Options_. Embora isso possa aumentar o custo, o SLA será melhor, reduzindo o tempo de indisponibilidade da máquina.

![](../img/azure_essentials/provisioning-virtual-machines/azure_03.png)  

#### Links

[Opções de disponibilidade para Máquinas Virtuais](https://learn.microsoft.com/pt-br/azure/virtual-machines/availability)
