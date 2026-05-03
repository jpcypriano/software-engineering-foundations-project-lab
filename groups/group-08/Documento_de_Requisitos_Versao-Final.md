#  Documento de Requisitos e Projeto de Software

---

##  1. Introdução

### 1.1 Objetivo
Descrever o objetivo deste documento e do sistema.

### 1.2 Escopo
Descrever o que o sistema faz, seus limites e o que está fora do escopo.

### 1.3 Definições, Acrônimos e Abreviações
Liste termos importantes utilizados no documento.

---

##  2. Product Vision

### 2.1 Problema
O Brasil registra mais de 30 mil acidentes com serpentes por ano, além de milhares de casos envolvendo escorpiões e aranhas. Muitos desses acidentes são agravados pela falta de informação da população sobre identificação dos animais e procedimentos corretos em situações de emergência.

Além disso, trabalhadores rurais, profissionais da linha de frente (bombeiros, policiais) e moradores de áreas próximas à vegetação estão constantemente expostos a esses riscos, especialmente em regiões como Mato Grosso. A ausência de ferramentas acessíveis que unam educação, prevenção e monitoramento torna o problema ainda mais crítico.

### 2.2 Público-Alvo
O sistema é voltado para:

- Trabalhadores rurais
- Profissionais como bombeiros, policiais e agentes ambientais
- Moradores de áreas urbanas próximas à vegetação
- Estudantes e população em geral
O foco principal está nos usuários mais expostos ao risco, mas a solução é acessível para qualquer pessoa.

### 2.3 Proposta de Valor
O nosso projeto será uma plataforma digital (aplicativo) que oferece:

- Catálogo de animais peçonhentos (cobras, escorpiões e aranhas)
- Orientações de primeiros socorros e modo emergência
- Registro e visualização de ocorrências em mapa
- Conteúdos educativos e cursos
- Sistema de gamificação com quizzes, pontos e conquistas
A proposta é unir educação, prevenção e tecnologia, criando uma solução útil tanto no dia a dia quanto em situações críticas.

### 2.4 Diferencial
Atualmente, existem poucas soluções completas no mercado com esse foco integrado. Entre os concorrentes indiretos, destacam-se:

- Sites informativos sobre animais peçonhentos
- Aplicativos educativos genéricos
- Conteúdos isolados em redes sociais e plataformas de vídeo
No entanto, esses concorrentes não oferecem integração entre educação, geolocalização, emergência e engajamento, o que diferencia o projeto em si.

---

##  3. Visão Geral do Sistema

### 3.1 Descrição Geral
Explique o sistema de forma resumida.

### 3.2 Stakeholders
Liste os principais envolvidos:
- Usuários
- Clientes
- Desenvolvedores
- Outros

---

##  4. Requisitos Funcionais

### RF01 - Nome do requisito
**Descrição:**  
Descreva a funcionalidade.

**Prioridade:** Alta / Média / Baixa  
**Entradas:**  
**Saídas:**  
**Regras de negócio:**  

---

### RF02 - Nome do requisito
(repita o padrão)

---

##  5. Requisitos Não Funcionais

### 5.1 Performance (Desempenho)
- O sistema deve responder requisições em até **2 segundos** em condições normais.
- O sistema deve suportar no mínimo **1.000 usuários simultâneos**.
- O carregamento de imagens deve ocorrer em até **3 segundos**.
- O sistema deve possuir disponibilidade mínima de **99% (uptime)**.
- As consultas ao banco de dados devem ser otimizadas para evitar lentidão.

### 5.2 Security (Segurança)
- O sistema deve criptografar senhas utilizando **hash seguro**.
- O sistema deve implementar **autenticação de usuários (login)**.
- O sistema deve possuir **controle de acesso por níveis**:
  - Usuário comum
  - Profissional
  - Administrador
- O sistema deve utilizar **HTTPS** para comunicação segura.
- O sistema deve seguir diretrizes da **LGPD** para proteção de dados.

### 5.2 Usability (Usabilidade)
- O sistema deve ser **intuitivo e fácil de navegar**.
- O sistema deve ser **responsivo** (adaptável a celular e desktop).
- O sistema deve fornecer **feedback visual** (ex: carregamento, confirmação).
- O sistema deve utilizar linguagem clara e acessível.
- O sistema deve possuir acesso rápido a **instruções de emergência**.
---

##  6. Requisitos Organizacionais

### 6.1 Ambientais
- O sistema deverá ser acessado via navegador web, sendo compatível com os principais navegadores, como Google Chrome, Mozilla Firefox e Microsoft Edge, em suas versões atualizadas.
- O sistema deverá ser compatível com sistemas operacionais Windows 10 ou superior, garantindo funcionamento adequado em desktops e notebooks.
- O sistema deverá ser acessível por dispositivos móveis (smartphones e tablets), sendo compatível com sistemas Android e iOS, por meio de navegadores web.
- A interface do sistema deverá ser responsiva, adaptando-se automaticamente a diferentes tamanhos de tela, garantindo usabilidade tanto em computadores quanto em dispositivos móveis.
- Por se tratar de um sistema baseado na web, deverá ser possível acessá-lo em qualquer ambiente que possua conexão com a internet, sem necessidade de instalação local.

- O sistema deverá ser hospedado em ambiente de servidor, podendo ser em infraestrutura local (on-premise) ou em nuvem.
- O sistema deverá exigir conexão com a internet para seu funcionamento, sendo recomendado o uso de conexão estável e de boa velocidade.
- O acesso ao sistema deverá ocorrer por meio de navegadores web, permitindo sua utilização em diferentes dispositivos conectados à rede.
- O sistema deverá utilizar protocolos seguros de comuni

### 6.2 Operacionais
- Logs  
- Monitoramento  

### 6.3 Desenvolvimento
- Versionamento (Git)  
- Padrões de código  
- Testes automatizados  

---
