# lab02-azure-
**Beneficios da Nuvem**
- **Alta disponibilidade.**
    SLA - Service Level Agreement (Contrato de Nível de Serviço)
    Quanto maior a disponibilidade de horas em funcionamento, maior os custos.
    Este serviço pode ***SIM*** ficar fora de funcionamento sendo especificado em contrato.
    - *99% - $*
    - *99.9% - $$*
    - *99.95% - $$$*
    - *99.99% - $$$$*
    A alta disponibilidade se concentra em garantir a disponibilidade máxima, independente de interrupções ou eventos que possam ocorrer.
    **Se o serviço ficar fora de funcionamento por um período maior do que o especificado em contrato, a Microsoft (provedora do serviço) fica responsável por disponibilizar um valor em créditos (”voucher”) respectivo ao     tempo fora que ultrapasse o permitido por contrato.**

- **Escalabilidade - VERTICAL.**
    A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda.
    A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento de demanda.
    - Outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços.
    - Como a nuvem é um modelo baseado em consumo você paga apenas pelo que usa.
    - Se a demanda cair, você poderá reduzir seus recursos e assim reduzir seus custos.
    *Com a escala vertical, se você estiver desenvolvendo um aplicativo e precise de mais capacidade de processamento, poderia assim escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual.*
  
- **Elasticidade - HORIZONTAL.**
    Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente).
    ***Ex.** BLACK FRIDAY.*
    - Você pode adicionar máquinas virtuais ou contêineres por meio da expansão.
    - Se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente ( de maneira automática ou manual).
 
- **Confiabilidade.**
    Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. A nuvem permite que você tenha recursos implantados em várias regiões do mundo.
    Com a escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.
    
- **Previsibilidade.**  
    A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo *Microsoft Azure Well-Architected Framework*. 
    
- **Segurança.**
    A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.
    Se você quiser o controle máximo da segurança, a infraestrutura como serviços (IaaS) fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção.
    Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço (PaaS) ou software como serviço (SaaS) podem ser as melhores estratégias de nuvem para você.

  - **Governança.**
    
    A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação (resolução).
    
    Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.
    

- **Gerenciabilidade.**
    Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento.
    Escalar automaticamente a implantação de recursos com base na necessidade.
    Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
    1. Por meio de um portal da Web.
    2. Usando uma interface de linha de comando.
    3. Usando APIs
    4. Usando o PowerShell.
