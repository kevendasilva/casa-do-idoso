# Sistema de Gestão Interna - Casa do Idoso

Este sistema web foi desenvolvido para auxiliar na gestão interna da Casa do Idoso em Limoeiro do Norte, proporcionando uma administração mais eficiente e integrada das informações referentes a residentes e funcionários.

## Funcionalidades

- **Gerenciamento de Informações:**  
  Cadastro e atualização de dados dos residentes e funcionários, garantindo um controle completo das informações.

- **Relatórios Avançados:**  
  Geração de diversos relatórios filtráveis, incluindo análises detalhadas do acompanhamento de saúde dos residentes.

- **Acompanhamento Médico:**  
  Registro automático das movimentações dos residentes, como alterações de medicamentos, com a opção de adicionar registros manualmente. Essa funcionalidade foi desenvolvida para oferecer um monitoramento preciso e seguro da saúde dos residentes.

- **Automação de Processos:**  
  Diversas automações que simplificam tarefas rotineiras e contribuem para uma gestão mais eficaz.

- **Controle de Acesso:**  
  Sistema dividido por níveis de autorização, garantindo que cada usuário tenha acesso apenas às funcionalidades pertinentes ao seu perfil.

## Tecnologias Utilizadas

- **Ruby on Rails:**  
  Framework principal utilizado no desenvolvimento da aplicação.

- **AWS:**  
  - Utilizado como bucket para armazenamento de imagens e arquivos.
  - Responsável pelo serviço de API de e-mails para o envio de notificações e comunicações.

- **Heroku:**  
  Plataforma utilizada para a hospedagem da aplicação.

## Desafios Técnicos

Um dos principais desafios enfrentados durante o desenvolvimento foi a implementação da área de acompanhamento médico dos residentes. A criação de um sistema que registra automaticamente as mudanças de medicamentos — além de permitir a inserção manual de registros — exigiu uma integração robusta de tecnologias e o desenvolvimento de automações precisas, representando um desafio técnico e funcional significativo.
