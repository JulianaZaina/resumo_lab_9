# resumo_lab_9
Resumo de aprendizagem do Lab 9: Governança e Conformidade - módulo 3
## Bootcamp DIO Microsoft Azure Essentials AZ-900
Lab 9: Gerenciando Políticas em Acesso Azure
Portal de Confiança do Serviço: como a Microsoft serviço em nuvem protege seus dados e como você pode gerenciar segurança e conformidade de dados em nuvem para sua organiuzação. 
  - http://servicetrust.microsoft.com
  - Certificações, regulamentos e padrões:
  - ISO / IEC - International Organization for Standardization (ISO) e International Electrotechnical Commission (IEC)
  - SOC - Controles de Sistema e Organização - Relatórios 1, 2 e 3
  - RGPD - Regulamento Geral sobre Proteção de Dados
  - FedRamp - Programa Federal de Gerenciamento de Risco e Autorização
  - Pci - Padrões de Segurança de dados (DDS) do PCI (Payment Card Industry)
  - Estrela CSA/ STAR CSA - Registro de segurança, confiança e garantia da CSA (Cloud security Alliance) STAR
  - Regulamentos referentes à países - recursos para o Brasil Docs aplicáveis ( BACEN Resolution e Check List). Ter ideia das regulações disponíveis para avaliar regulamentos.
  - Geralmente consultados para apresentar à auditorias.
Bloqueio de Recursos (Portal Azure): Policy gerenciar políticas, personalizar, avaliar. Adicionar um bloqueio no grupo de recursos criado AZ_900_DIO_Lab.
  - Todos os componentes desse recurso vão herdar sua política de bloqueio.
  - Observar as inferências no contexto do ambiente e suas possíveis consequências.
  - Alguns componentes podem ser movidos para não herdarem o bloqueio em outro grupo de recurso, (ex. VNET).
Microsoft Purview (Portal): criar um usuário para acessar o portal. Suite de aplicações
  - Open Microsoft Purview Governance Portal (nova versão e antiga versão) - abrir novo portal - Monitoramento dashboard.
  - Gerencia de usuário
  - Documentação
  - Propósito funciona para todos, não é personalizável a permissão isolada.
  - Funcionalidade: aplicar políticas independentes, gerenciamento de recursos fora do Azure
      - Recursos: Data Map, Data Catalog, Information Protection, Audit, Settings, View all solutions.
      - Riscos e complaince, comunicação, capturar mensagens impróprias, restringir comunicações com conflito, automatizar retenção, gravações de carácter crítico (records management)
  Policy: gerenciar e exibir políticas. Adicionar, alterar políticas. Verificar as já existentes para estar em conformidade. Políticas são uma forma de padronização.
    - Política sobre Regiões permitidas: sua assinatura exibe (complaint), 4 relacionadas a região do Brasil e 2 nos US, 1 fora do compaint (non).
    - Remediação: pode se criar uma entidade gerenciada para assinalar quando for criado um recurso em outra região. Veificar se não causa outros problemas com a aplicação ou ambiente.
    - Definição de políticas (modelos), podem ser criados como base para montar sua política, e pode ser personalizado, com alterações.
    - Observar na criação de políticas, o botão enable (habilitada) se está marcado.
    - Recomensações menos críticas, criação de Tags, com poucas influências em aplicações e que ajudam a identificar o centro de custos e cobrança.
