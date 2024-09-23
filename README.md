# resumo-do-lab3
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.


Visão geral

Sabemos que a segurança é o primeiro trabalho na nuvem e o quanto é importante que você encontre informações precisas e atualizadas sobre a segurança do Azure. Uma das melhores razões para usar o Azure para seus aplicativos e serviços é aproveitar sua ampla variedade de ferramentas e recursos de segurança. Essas ferramentas e recursos ajudam a tornar possível criar soluções seguras na plataforma segura do Azure. O Microsoft Azure fornece confidencialidade, integridade e disponibilidade dos dados do cliente, ao mesmo tempo que também permite uma responsabilidade transparente.

Este artigo fornece uma visão abrangente da segurança disponível com o Azure.
Plataforma do Azure

O Azure é uma plataforma de serviço de nuvem pública que dá suporte a uma ampla seleção de sistemas operacionais, linguagens de programação, estruturas, ferramentas, bancos de dados e dispositivos. Ele pode executar contêineres do Linux com a integração com o Docker, criar aplicativos com JavaScript, Python, .NET, PHP, Java e Node.js e criar back-ends para dispositivos iOS, Android e Windows.

Os serviços de nuvem pública do Azure dão suporte às mesmas tecnologias com as quais milhões de desenvolvedores e profissionais de TI já contam e nas quais confiam. Ao se basear ou migrar ativos de TI para um provedor de serviços de nuvem pública, você está confiando na capacidade dessa organização de proteger seus aplicativos e dados com os serviços e os controles que ela oferece para gerenciar a segurança de seus ativos baseados em nuvem.

A infraestrutura do Azure foi projetada desde a instalação até os aplicativos para hospedar milhões de clientes simultaneamente e fornece uma base confiável com a qual as empresas podem atender aos seus requisitos de segurança.

Além disso, o Azure oferece uma ampla variedade de opções de segurança configuráveis e a capacidade de controlá-las, de forma que você possa personalizar a segurança para atender aos requisitos exclusivos das implantações de sua organização. Este documento ajuda você a entender como as funcionalidades de segurança do Azure podem ajudá-lo a atender a esses requisitos.

Observação

O foco principal deste documento são os controles voltados para o cliente que você pode usar para personalizar e aumentar a segurança de seus aplicativos e serviços.

Para obter informações sobre como a Microsoft protege a plataforma do Azure, consulte Segurança de infraestrutura do Azure.
Resumo dos recursos de segurança do Azure

Dependendo do modelo de serviço de nuvem, a responsabilidade de quem gerencia a segurança do aplicativo ou serviço varia. Há recursos disponíveis na Plataforma Azure para ajudar você a cumprir essas responsabilidades por meio de recursos internos, e soluções de parceiros que podem ser implantadas em uma assinatura do Azure.

Os recursos internos são organizados em seis áreas funcionais: Operações, Aplicativos, Armazenamento, Rede, Computação e Identidade. Os detalhes adicionais sobre os recursos e funcionalidades disponíveis na Plataforma do Azure nessas seis áreas são fornecidos por meio de informações de resumo.
Operations

Esta seção fornece outras informações sobre os principais recursos em operações de segurança, e informações de resumo sobre esses recursos.
Microsoft Sentinel

O Microsoft Azure Sentinel é uma solução escalonável e nativa da nuvem que oferece SIEM (gerenciamento de eventos de informações de segurança) e SOAR (orquestração de segurança, automação e resposta). O Microsoft Sentinel oferece análise inteligente de segurança e inteligência contra ameaças em toda a empresa, com uma solução para detecção de ataques, visibilidade de ameaças, procura proativa e resposta a ameaças.
Microsoft Defender para Nuvem

O Microsoft Defender para Nuvem ajuda você a impedir, detectar e responder a ameaças com maior visibilidade e controle sobre a segurança dos seus recursos do Azure. Ela permite o gerenciamento de políticas e o monitoramento da segurança integrada entre suas assinaturas do Azure, ajuda a detectar ameaças que poderiam passar despercebidas e funciona com uma enorme variedade de soluções de segurança.

Além disso, o Defender para nuvem ajuda com operações de segurança, fornecendo um único painel que mostra alertas e recomendações que podem ser agidos imediatamente. Geralmente, você pode resolver problemas com um único clique no console do Defender para nuvem.
Azure Resource Manager

O Azure Resource Manager permite trabalhar com os recursos da sua solução como um grupo. Você pode implantar, atualizar ou excluir todos os recursos da sua solução em uma única operação coordenada. Use um modelo do Azure Resource Manager para a implantação, e esse modelo pode ser útil para diferentes ambientes, como teste, preparação e produção. O Gerenciador de Recursos fornece recursos de segurança, auditoria e marcação para ajudá-lo a gerenciar seus recursos após a implantação.

As implantações baseadas em modelos do Azure Resource Manager ajudam a melhorar a segurança das soluções implantadas no Azure devido às configurações de controle de segurança padrão, e podem ser integradas às implantações baseadas em modelo padronizadas. Isso reduz o risco de erros de configuração de segurança que podem ocorrer durante as implantações manuais.
Application Insights

O Application Insights é um serviço de Gerenciamento de Desempenho de Aplicativos (APM) extensível para desenvolvedores da Web. Com o Application Insights, você pode monitorar seus aplicativos Web ativos e detectar automaticamente as anomalias no desempenho. Ele inclui ferramentas de análise avançadas para ajudar você a diagnosticar problemas e entender o que os usuários realmente fazem com seu aplicativo. Ele monitora seus aplicativos em todo o tempo de execução, tanto durante o teste quanto depois de publicado ou implantado.

O Application Insights cria gráficos e tabelas que mostram, por exemplo, em que horas do dia você tem mais usuários, o nível de capacidade de resposta do aplicativo e quão bem ele é atendido por quaisquer serviços externos dos quais depende.

Se houver travamentos, falhas ou problemas de desempenho, você pode pesquisar os dados de telemetria em detalhes para diagnosticar a causa. E o serviço enviará a você emails se houver alterações na disponibilidade e no desempenho de seu aplicativo. Assim, o Application Insight torna-se uma ferramenta de segurança importante, pois ajuda com a disponibilidade na tríade de segurança de disponibilidade, integridade e confidencialidade.
Azure Monitor

O Azure Monitor oferece a visualização, consulta, roteamento, alertas, dimensionamento automático e automação nos dados da assinatura do Azure (Logs de Atividade) e de cada recurso individual do Azure( Logs de Recurso). Use o Azure Monitor para receber alertas sobre eventos relacionados à segurança que são gerados nos logs do Azure.
Logs do Azure Monitor

Logs do Azure Monitor – Fornece uma solução de gerenciamento de TI para infraestrutura local e em nuvem de terceiros (como AWS), além dos recursos do Azure. Os dados do Azure Monitor podem ser roteados diretamente para os logs do Azure Monitor para que você possa ver métricas e logs de todo o ambiente em um único lugar.

Os logs do Azure Monitor podem ser uma ferramenta útil na análise forense e em outras análises de segurança, pois a ferramenta permite que você pesquise rapidamente grandes quantidades de entradas relacionadas à segurança com uma abordagem de consulta flexível. Além disso, os logs de firewall e de proxy locais podem ser exportados para o Azure e disponibilizados para análise usando os logs do Azure Monitor.
Assistente do Azure

O Assistente do Azure é um consultor de nuvem personalizado que ajuda você a otimizar suas implantações do Azure. Ele analisa a configuração dos recursos e a telemetria do uso. Depois, recomenda soluções para ajudar a melhorar o desempenho, segurança e confiabilidade de seus recursos enquanto procura oportunidades para reduzir a despesa geral do Azure. O Assistente do Azure fornece recomendações de segurança, o que pode melhorar consideravelmente sua postura de segurança geral para soluções implantadas no Azure. Essas recomendações são obtidas da análise de segurança executada pelo Microsoft Defender para nuvem.
Aplicativos

A seção fornece outras informações sobre os principais recursos em segurança do aplicativo e informações de resumo sobre esses recursos.
Teste de penetração

Nós não fazemos teste de penetração do seu aplicativo para você, mas entendemos que você deseja e precisa executar testes nos seus próprios aplicativos. Isso é bom, porque quando você aumenta a segurança de seus aplicativos, você ajuda a tornar todo o ecossistema do Azure mais seguro. Embora a notificação à Microsoft das atividades de teste de penetração não seja mais necessária, os clientes ainda devem estar de acordo com as Regras de Participação em Testes de Penetração no Microsoft Cloud.
Firewall do aplicativo Web

O WAF (firewall de aplicativo Web) no Gateway de Aplicativo do Azure protege os aplicativos Web contra ataques comuns baseados na Web, como injeção de SQL, ataques de scripts entre sites e sequestros de sessão. Ele vem pré-configurado com proteção contra as ameaças identificadas pelo OWASP (Projeto Aberto de Segurança em Aplicativo Web) como as 10 vulnerabilidades mais comuns.
Autenticação e autorização no Serviço de Aplicativo do Azure

A Autenticação/Autorização do Serviço de Aplicativo é um recurso que oferece uma maneira para seu aplicativo conectar usuários de forma que você não precise alterar o código no back-end do aplicativo. Ele fornece uma maneira fácil de proteger o aplicativo e trabalhar com dados por usuário.
Arquitetura de segurança em camadas

Como os Ambientes do Serviço de Aplicativo fornecem um ambiente de runtime isolado implantado em uma Rede Virtual do Azure, os desenvolvedores podem criar uma arquitetura de segurança em camadas fornecendo níveis diferentes de acesso à rede para cada camada de aplicativo. Um desejo comum é ocultar os back-ends de API do acesso à Internet geral e só permitir que as APIs sejam chamadas por aplicativos Web upstream. Os NSGs (grupos de segurança de rede) podem ser usados em sub-redes da Rede Virtual do Azure contendo Ambientes do Serviço de Aplicativo para restringir o acesso público aos aplicativos da API.
Diagnóstico de servidor Web e diagnóstico de aplicativos

Os aplicativos da Web do Serviço de Aplicativo fornecem funcionalidade de diagnóstico para registrar em log informações tanto do servidor da Web quanto do aplicativo da Web. Estes estão logicamente separados em diagnóstico de servidor Web e diagnóstico de aplicativos. O servidor Web inclui dois grandes avanços em diagnóstico e solução de problemas de sites e aplicativos.

O primeiro são informações de estado em tempo real sobre pools de aplicativos, processos de trabalho, sites, domínios de aplicativo e solicitações em execução. O segundo são os eventos de rastreamento detalhados que rastreiam uma solicitação por todo o processo de solicitação e resposta.

Para habilitar a coleta desses eventos de rastreamento, o IIS 7 pode ser configurado para capturar automaticamente os logs de rastreamento completos, em formato XML, para qualquer solicitação específica com base no tempo decorrido ou em códigos de resposta do erro.
Armazenamento

A seção fornece outras informações sobre os principais recursos em segurança de armazenamento do Azure e informações de resumo sobre esses recursos.
RBAC do Azure (controle de acesso baseado em função do Azure)

Você pode proteger a conta de armazenamento com oAzure RBAC (controle de acesso baseado em função do Azure). Restringir o acesso com base nos princípios de segurança de divulgação restrita àqueles diretamente interessados e no privilégio mínimo é fundamental para as organizações que desejam impor políticas de segurança para acesso a dados. Esses direitos de acesso são concedidos atribuindo a função do Azure apropriada a grupos e aplicativos em determinado escopo. Você pode usar as funções internas do Azure, como Colaborador da Conta de Armazenamento, para atribuir privilégios aos usuários. O acesso às chaves de armazenamento para uma conta de armazenamento usando o modelo do Azure Resource Manager pode ser controlado por meio do Azure RBAC.
Assinatura de acesso compartilhado

Uma SAS (Assinatura de Acesso Compartilhado) fornece acesso delegado aos recursos da sua conta de armazenamento. A SAS significa que você pode conceder a um cliente permissões limitadas para objetos em sua conta de armazenamento por determinado período e com um conjunto específico de permissões. Você pode conceder essas permissões limitadas sem precisar compartilhar as chaves de acesso da conta.
Criptografia em trânsito

A criptografia em trânsito é um mecanismo de proteção de dados quando eles são transmitidos entre redes. Com o Armazenamento do Azure, você pode proteger dados usando:

    Criptografia de nível de transporte, como HTTPS ao transferir dados dentro ou fora do Armazenamento do Azure.

    Criptografia na transmissão, como a criptografia SMB 3.0 para compartilhamentos de Arquivo do Azure.

    Criptografia do cliente, que permite criptografar os dados antes que eles sejam transferidos para o armazenamento e descriptografá-los após serem transferidos para fora do armazenamento.

Criptografar em repouso

Para muitas organizações, a criptografia de dados em repouso é uma etapa obrigatória no sentido de garantir a soberania, a privacidade e a conformidade dos dados. Há três recursos de segurança de armazenamento do Azure que fornecem criptografia de dados que estão “em repouso”:

    Criptografia do Serviço de Armazenamento permite solicitar que o serviço de armazenamento criptografe automaticamente os dados ao gravá-los no Armazenamento do Azure.

    Client-side Encryption também fornece o recurso de criptografia em repouso.

    A Azure Disk Encryption para VMs do Linux e a Azure Disk Encryption para VMs do Windows permitem criptografar os discos do sistema operacional e discos de dados usados por uma máquina virtual IaaS.

Análise de Armazenamento

O Azure Storage Analytics executa o registro em log e fornece dados de métrica para uma conta de armazenamento. Você pode usar esses dados para rastrear solicitações, analisar tendências de uso e diagnosticar problemas com sua conta de armazenamento. A análise de armazenamento registra informações detalhadas sobre solicitações bem-sucedidas e com falha para um serviço de armazenamento. Essas informações podem ser usadas para monitorar solicitações individuais e diagnosticar problemas com um serviço de armazenamento. As solicitações são registradas em uma base de melhor esforço. Os seguintes tipos de solicitações autenticadas são registrados:

    Solicitações bem sucedidas.
    Solicitações com falha, incluindo o tempo limite, limitação, rede, autorização e outros erros.
    Solicitações que usam uma SAS (Assinatura de Acesso Compartilhado), incluindo solicitações bem-sucedidas e com falha.
    Solicitações para dados de análise.

Habilitar clientes com base no navegador usando CORS

CORS (Compartilhamento de recursos entre origens) é um mecanismo que permite que os domínios troquem permissões para acessar recursos uns dos outros. O Agente do Usuário envia cabeçalhos adicionais para garantir que o código JavaScript carregado de um determinado domínio tenha permissão para acessar os recursos localizados em outro domínio. Depois, o último domínio responde com cabeçalhos adicionais, permitindo ou negando o acesso do domínio original aos seus recursos.

Agora, os serviços de armazenamento do Azure oferecem suporte a CORS, para que depois de definir as regras de CORS para o serviço, uma solicitação autenticada corretamente feita no serviço de um domínio diferente será avaliada para determinar se é permitida de acordo com as regras que você especificou.
Rede

A seção fornece outras informações sobre os principais recursos em segurança de rede do Azure e informações de resumo sobre esses recursos.
Controles de camada de rede

O controle de acesso à rede é o ato de limitar a conectividade de entrada ou saída de sub-redes ou dispositivos específicos e representa o aspecto fundamental da segurança de rede. O objetivo do controle de acesso à rede é certificar-se de que suas máquinas virtuais e seus serviços são acessíveis apenas aos usuários e dispositivos para os quais você deseja que tenham esse acesso.
Grupos de segurança de rede

Um NSG (Grupo de Segurança de Rede) é um firewall básico de filtragem de pacotes com estado e permite o controle do acesso baseado em uma sequência de 5 tuplas. Os NSGs não fornecem inspeção da camada de aplicativo nem controles de acesso autenticado. Eles podem ser usados para controlar o tráfego entre sub-redes dentro de uma Rede Virtual do Azure e o tráfego entre uma Rede Virtual do Azure e a Internet.
Firewall do Azure

O Firewall do Azure é um serviço de segurança de firewall de rede inteligente e nativo de nuvem que fornece proteção contra ameaças para suas cargas de trabalho de nuvem em execução no Azure. É um firewall como serviço totalmente com estado com alta disponibilidade interna e escalabilidade de nuvem irrestrita. Ele fornece inspeção de tráfego de leste a oeste e de norte a sul.

O Firewall do Azure é oferecido em dois SKUs: Standard e Premium. O Firewall do Azure Standard fornece filtragem L3-L7 e feeds de inteligência contra ameaças diretamente da Segurança Cibernética da Microsoft. O Firewall do Azure Premium fornece funcionalidades avançadas que incluem IDPS baseado em assinatura para permitir a detecção rápida de ataques procurando padrões específicos.
Controle de rota e túnel forçado

A capacidade de controlar o comportamento de roteamento em suas Redes Virtuais do Azure é uma funcionalidade crítica de controle de acesso e segurança de rede. Por exemplo, se você quiser ter certeza de que todo o tráfego de entrada e saída da Rede Virtual do Azure passa por esse dispositivo de segurança virtual, será necessário conseguir controlar e personalizar o comportamento do roteamento. É possível fazer isso configurando as Rotas Definidas pelo Usuário no Azure.

As Rotas Definidas pelo Usuário permitem que você personalize os caminhos de entrada e saída de máquinas virtuais individuais ou sub-redes a fim de garantir a rota mais segura possível. túnel forçado é um mecanismo que pode ser usado para garantir que seus serviços não tenham permissão para iniciar uma conexão com dispositivos na Internet.

Isso é diferente de poder aceitar conexões de entrada e responder a elas. Os servidores Web front-end precisam responder à solicitação dos hosts da Internet e, portanto, o tráfego originado da Internet tem permissão de entrada nesses servidores Web, que, por sua vez, podem responder.

O túnel forçado é normalmente usado para forçar o tráfego de saída para a Internet a fim de passar por firewalls e proxies de segurança locais.
Dispositivos de segurança de rede virtual

Embora os Grupos de Segurança de Rede, as Rotas Definidas pelo Usuário e o túnel forçado forneçam um nível de segurança nas camadas de rede e de transporte do modelo OSI, em algumas ocasiões você pode querer habilitar a segurança em níveis superiores da pilha. É possível acessar esses recursos avançados de segurança de rede por meio de uma solução de dispositivo de segurança de rede de parceiro do Azure. Você pode encontrar as soluções mais atuais de segurança de rede de parceiros do Azure visitando o Azure Marketplace e pesquisando por “segurança” e “segurança de rede”.
Rede Virtual do Azure

Uma rede virtual do Azure (VNet) é uma representação da sua própria rede na nuvem. É um isolamento lógico da malha de rede do Azure dedicada à sua assinatura. Você pode controlar os blocos de endereços IP, as configurações de DNS, as políticas de segurança e as tabelas de rotas na rede. Você pode segmentar a VNet em sub-redes e colocar as VMs (máquinas virtuais) de IaaS do Azure e/ou os Serviços de nuvem (instâncias de função de PaaS) em Redes Virtuais do Azure.

Além disso, você pode conectar a rede virtual à sua rede local usando uma das opções de conectividade disponíveis no Azure. Em linhas gerais, você pode expandir sua rede no Azure, com controle total sobre os blocos de endereços IP, com benefícios de escala empresarial proporcionados pelo Azure.

A rede do Azure dá suporte a vários cenários de acesso remoto seguro. Entre eles estão:

    Conectar estações de trabalho individuais a uma Rede Virtual do Azure

    Conectar a rede local a uma Rede Virtual do Azure com uma VPN

    Conectar a rede local a uma Rede Virtual do Azure com uma conexão WAN dedicada

    Conectar Redes Virtuais do Azure entre si

Gerenciador de Rede Virtual do Azure

O Gerenciador de Rede Virtual do Azure fornece uma solução centralizada para proteger as suas redes virtuais em escala. Ele usa regras de administração de segurança para definir e aplicar centralmente políticas de segurança para suas redes virtuais em toda a organização. As regras de administração de segurança têm precedência sobre as regras do grupo de segurança de rede (NSGs) e são aplicadas na rede virtual. Isso permite que as organizações apliquem políticas básicas com regras de administração de segurança, ao mesmo tempo que permite que as equipes downstream adaptem os NSGs de acordo com suas necessidades específicas nos níveis de sub-rede e NIC. Dependendo das necessidades da sua organização, você pode usar ações de regra Permitir, Negar ou Sempre permitir para impor políticas de segurança.
