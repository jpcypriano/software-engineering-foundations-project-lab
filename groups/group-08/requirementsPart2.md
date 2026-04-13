 ## Performance (Desempenho)

### O que é:
Define velocidade, tempo de resposta e capacidade do sistema.

### Requisitos:
- O sistema deve responder requisições em até **2 segundos** em condições normais.
- O sistema deve suportar no mínimo **1.000 usuários simultâneos**.
- O carregamento de imagens deve ocorrer em até **3 segundos**.
- O sistema deve possuir disponibilidade mínima de **99% (uptime)**.
- As consultas ao banco de dados devem ser otimizadas para evitar lentidão.

---

## Security (Segurança)

### O que é:
Define como os dados e acessos são protegidos.

### Requisitos:
- O sistema deve criptografar senhas utilizando **hash seguro**.
- O sistema deve implementar **autenticação de usuários (login)**.
- O sistema deve possuir **controle de acesso por níveis**:
  - Usuário comum
  - Profissional
  - Administrador
- O sistema deve utilizar **HTTPS** para comunicação segura.
- O sistema deve seguir diretrizes da **LGPD** para proteção de dados.

---

## Usability (Usabilidade)
- O sistema deve possuir interface intuitiva e responsiva, adaptável a smartphones, tablets e desktops, priorizando a experiência mobile para o público-alvo.
- O sistema deve minimizar o número de ações para acessar funções críticas, como o botão de emergência e instruções de primeiros socorros, acessíveis em no máximo 2 toques a partir da tela inicial.
- O sistema deve fornecer feedback visual e auditivo em todas as interações, incluindo sons de confirmação, alertas sonoros em situações de emergência e notificações auditivas para áreas de risco, tornando a experiência mais imersiva e responsiva.
- O sistema deve utilizar linguagem simples e acessível, apresentando informações sobre animais com imagens, ícones de nível de risco e descrições objetivas para facilitar a identificação rápida.
- O sistema deve possuir modo emergência com alto contraste, fontes legíveis e suporte auditivo, garantindo que as instruções de primeiros socorros sejam compreendidas mesmo em situações de estresse.
- O sistema deve garantir acessibilidade básica com suporte a fontes ajustáveis, compatibilidade com leitores de tela e interações auditivas, atendendo usuários com diferentes necessidades.

### O que é:
Define a facilidade de uso do sistema.

### Requisitos:
- O sistema deve ser **intuitivo e fácil de navegar**.
- O sistema deve ser **responsivo** (adaptável a celular e desktop).
- O sistema deve fornecer **feedback visual** (ex: carregamento, confirmação).
- O sistema deve utilizar linguagem clara e acessível.
- O sistema deve possuir acesso rápido a **instruções de emergência**.

---

## User Stories (Histórias de Usuário)
- US01 - Como usuário comum, quero me cadastrar no sistema para acessar as
funcionalidades disponíveis.
- US02 - Como usuário, quero fazer login para acessar minha conta com segurança.
- US03 - Como usuário, quero identificar um animal peçonhento para saber se ele
representa perigo.
- US04 - Como usuário, quero visualizar informações detalhadas sobre um animal para
aprender sobre ele.
- US05 - Como usuário, quero acessar instruções de primeiros socorros para agir
corretamente em caso de acidente.
- US06 - Como usuário, quero registrar uma ocorrência para contribuir com dados sobre
acidentes.
- US07 - Como usuário, quero visualizar ocorrências em um mapa para entender áreas de
risco.
- US08 - Como usuário, quero receber alertas sobre áreas de risco para evitar acidentes.
- US09 - Como usuário, quero acessar conteúdos educativos para aprender mais.
- US10 - Como usuário, quero realizar quizzes para testar meu conhecimento.

## Profissional
- US11 - Como profissional de saúde, quero consultar informações confiáveis para auxiliar no atendimento.
- US12 - Como um profissional, eu quero acessar dados de ocorrências, para analisar áreas de risco.
- US13 - Como um profissional, eu quero visualizar relatórios, para apoiar a tomada de decisões.
- US14 - Como um profissional, eu quero atualizar informações sobre animais, para manter o sistema preciso.


## Sistema (Automático)
- US15 - Como sistema, quero integrar dados de fontes públicas para manter as informações atualizadas.

## Administrador
- US16 - Como administrador, quero gerenciar usuários para manter o sistema organizado.
- US17 - Como administrador, quero gerenciar conteúdos para garantir informações atualizadas.
- US18 - Como administrador, quero visualizar estatísticas para analisar o uso do sistema.
