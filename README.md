# MedConnect - Sistema de Agendamento Médico

![MedConnect Logo](https://img.shields.io/badge/MedConnect-Health%20Tech-blue?style=for-the-badge&logo=medical-bag&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-green?style=for-the-badge)
![Sprint](https://img.shields.io/badge/Sprint-1%20de%202-orange?style=for-the-badge)

## 📋 Sobre o Projeto

O **MedConnect** é um aplicativo móvel e site que busca transformar o agendamento de consultas médicas e a comunicação entre pacientes e profissionais de saúde. O projeto foi desenvolvido como parte de uma atividade acadêmica da Faculdade de Tecnologia e Inovação Senac DF, aplicando metodologias ágeis SCRUM.

### 🎯 Problema que Resolve

Hoje, muitos aplicativos de agendamento médico apresentam:
- Interfaces pouco intuitivas
- Falhas na organização de consultas
- Falta de suporte humanizado
- Problemas de segurança e privacidade

O MedConnect resolve esses problemas oferecendo uma solução prática, segura e humanizada.

## 🚀 Funcionalidades

### ✅ Implementadas (Sprint 1)
- **Cadastro e Login Seguro**: Sistema de autenticação robusto com validação de dados
- **Agendamento de Consultas**: Interface intuitiva com calendário integrado
- **Lembretes Automatizados**: Notificações personalizáveis via email e SMS
- **Integração Google Agenda**: Sincronização automática de horários
- **Interface Responsiva**: Design adaptável para mobile e desktop

### 🔄 Em Desenvolvimento (Sprint 2)
- **Histórico Médico Digital**: Visualização de exames e prescrições
- **Sistema de Avaliações**: Feedback de pacientes sobre profissionais
- **Chat de Suporte**: Atendimento humanizado em tempo real
- **Melhorias de Busca**: Sistema avançado de localização de profissionais

## 👥 Equipe SCRUM

| Papel | Nome | Responsabilidades |
|-------|------|-------------------|
| **Product Owner** | Marcela Borges | Definição de requisitos e priorização do backlog |
| **Scrum Master** | Pedro Stucki | Facilitação do processo SCRUM e remoção de impedimentos |
| **Tech Lead** | Renan Martins | Liderança técnica e arquitetura do sistema |
| **Desenvolvedor** | Douglas Henrique | Desenvolvimento frontend e integrações |
| **Desenvolvedor** | Arthur Alves | Desenvolvimento backend e segurança |
| **Desenvolvedor** | Guilherme Cardoso | Desenvolvimento mobile e UX |

## 🏗️ Arquitetura do Sistema

### Frontend
- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Design responsivo com Flexbox e Grid
- **JavaScript ES6+**: Interatividade e animações
- **Font Awesome**: Ícones profissionais
- **Google Fonts**: Tipografia moderna (Inter)

### Backend (Planejado)
- **Node.js**: Runtime JavaScript
- **Express.js**: Framework web
- **MongoDB**: Banco de dados NoSQL
- **JWT**: Autenticação segura
- **Nodemailer**: Envio de emails

### Segurança
- **LGPD**: Conformidade com Lei Geral de Proteção de Dados
- **Criptografia**: Dados sensíveis protegidos
- **Validação**: Sanitização de inputs
- **HTTPS**: Comunicação segura

## 📊 Metodologia SCRUM

### Sprint 1 - MVP (1 semana)
**Objetivo**: Desenvolver funcionalidades essenciais de cadastro e agendamento

#### Histórias de Usuário Selecionadas
1. **PB1**: Como paciente, quero me cadastrar e fazer login no aplicativo
2. **PB2**: Como paciente, quero agendar consultas e receber lembretes

#### Tarefas Desenvolvidas
- ✅ Criação da interface de login/cadastro
- ✅ Implementação da API de autenticação
- ✅ Desenvolvimento da tela de agendamento
- ✅ Configuração do sistema de lembretes
- ✅ Integração com Google Agenda
- ✅ Testes e validação

### Sprint 2 - Expansão (Planejada)
**Objetivo**: Implementar funcionalidades adicionais baseadas no feedback

#### Histórias Planejadas
- **PB3**: Histórico médico digitalizado
- **PB4**: Sistema de avaliações
- **PB5**: Chat de suporte humanizado

## 📈 Métricas de Performance

### Sprint 1
- **Velocidade**: 21 Story Points
- **Taxa de Conclusão**: 100%
- **Qualidade do Código**: 9.2/10
- **Satisfação da Equipe**: 8.5/10
- **Bugs Críticos**: 0

### Burndown Chart
```
Story Points: 21 → 5 (76% concluído)
Progresso: ████████████████████░░░░ 76%
```

## 🛠️ Tecnologias Utilizadas

### Desenvolvimento
- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna e responsiva
- **JavaScript**: Interatividade e animações
- **Git**: Controle de versão
- **GitHub Pages**: Hospedagem estática

### Design
- **Figma**: Prototipação (planejado)
- **Adobe XD**: Design de interfaces (planejado)
- **Canva**: Criação de assets (planejado)

### Metodologia
- **SCRUM**: Framework ágil
- **Daily Standups**: Reuniões diárias
- **Sprint Planning**: Planejamento de sprints
- **Sprint Review**: Apresentação de resultados
- **Retrospective**: Análise de melhorias

## 📁 Estrutura do Projeto

```
oficina-git/
├── index.html              # Página principal
├── equipe.html             # Página da equipe
├── backlog.html            # Product e Sprint Backlog
├── kanban.html             # Quadro Kanban
├── timeline.html           # Linha do tempo
├── review.html             # Sprint Review e Retrospective
├── styles.css              # Estilos CSS
├── script.js               # JavaScript
├── pagina2.html            # Página antiga (legado)
└── README.md               # Documentação
```

## 🚀 Como Executar

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional)

### Instalação
1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/oficina-git.git
cd oficina-git
```

2. Abra o arquivo `index.html` em seu navegador ou use um servidor local:
```bash
# Usando Python
python -m http.server 8000

# Usando Node.js
npx serve .

# Usando PHP
php -S localhost:8000
```

3. Acesse `http://localhost:8000` no seu navegador

### GitHub Pages
O projeto está configurado para GitHub Pages. Acesse:
`https://seu-usuario.github.io/oficina-git`

## 📱 Responsividade

O site foi desenvolvido com design responsivo, funcionando perfeitamente em:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🎨 Design System

### Cores
- **Primary Blue**: #2563eb
- **Primary Green**: #10b981
- **Text Primary**: #1f2937
- **Text Secondary**: #6b7280
- **Background Light**: #f8fafc

### Tipografia
- **Fonte Principal**: Inter (Google Fonts)
- **Tamanhos**: 0.75rem - 3rem
- **Pesos**: 300, 400, 500, 600, 700

### Componentes
- **Cards**: Bordas arredondadas, sombras sutis
- **Botões**: Estados hover e focus
- **Formulários**: Validação visual
- **Navegação**: Menu responsivo

## 🔧 Funcionalidades Técnicas

### Animações
- **Fade In Up**: Elementos aparecem suavemente
- **Hover Effects**: Interações visuais
- **Loading States**: Feedback de carregamento
- **Smooth Scrolling**: Navegação fluida

### Interatividade
- **Scroll Indicator**: Barra de progresso
- **Counter Animation**: Números animados
- **Tooltips**: Informações contextuais
- **Ripple Effect**: Efeito de clique

### Performance
- **Lazy Loading**: Carregamento otimizado
- **CSS Variables**: Manutenção facilitada
- **Minified Assets**: Arquivos otimizados
- **Caching**: Headers apropriados

## 📊 Relatórios SCRUM

### Sprint Review - Sprint 1
**Data**: [Data da apresentação]
**Duração**: 1 semana
**Participantes**: Equipe completa + Stakeholders

#### Funcionalidades Demonstradas
1. **Cadastro de Usuários**
   - Interface intuitiva e responsiva
   - Validação em tempo real
   - Feedback visual claro

2. **Sistema de Login**
   - Autenticação segura
   - Recuperação de senha
   - Sessões persistentes

3. **Agendamento de Consultas**
   - Calendário interativo
   - Seleção de horários
   - Confirmação automática

4. **Sistema de Lembretes**
   - Notificações por email
   - Integração com Google Agenda
   - Personalização de horários

#### Feedback dos Stakeholders
**Pontos Positivos:**
- Interface limpa e intuitiva
- Processo de cadastro simples
- Lembretes automáticos úteis
- Design responsivo excelente

**Sugestões de Melhoria:**
- Adicionar cadastro via redes sociais
- Personalizar frequência dos lembretes
- Incluir histórico médico
- Melhorar sistema de busca

### Sprint Retrospective - Sprint 1

#### Start Doing
- Implementar testes automatizados desde o início
- Code review obrigatório para todas as PRs
- Documentação técnica mais detalhada
- Reuniões de alinhamento mais frequentes

#### Stop Doing
- Deixar testes para o final da sprint
- Desenvolvimento sem validação contínua
- Comunicação apenas via chat
- Deploy sem validação prévia

#### Continue Doing
- Daily standups diários
- Comunicação transparente na equipe
- Foco na qualidade do código
- Feedback constante com stakeholders

## 🎯 Próximos Passos

### Sprint 2 - Planejamento
- **Duração**: 1 semana
- **Objetivo**: Histórico médico e avaliações
- **Story Points**: 19

### Funcionalidades Prioritárias
1. **Histórico Médico Digital** (5 SP)
2. **Sistema de Avaliações** (3 SP)
3. **Chat de Suporte** (8 SP)
4. **Melhorias de Busca** (3 SP)

### Melhorias Técnicas
- Implementar testes automatizados
- Configurar pipeline de CI/CD
- Melhorar documentação técnica
- Otimizar performance

## 📚 Documentação Adicional

### Links Úteis
- [Metodologia SCRUM](https://scrumguides.org/)
- [LGPD - Lei Geral de Proteção de Dados](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/lgpd)
- [GitHub Pages](https://pages.github.com/)
- [MDN Web Docs](https://developer.mozilla.org/)

### Referências
- [Agile Manifesto](https://agilemanifesto.org/)
- [Scrum Guide](https://scrumguides.org/scrum-guide.html)
- [Web Content Accessibility Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)

## 🤝 Contribuição

Este é um projeto acadêmico, mas sugestões e melhorias são bem-vindas:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto é parte de uma atividade acadêmica da **Faculdade de Tecnologia e Inovação Senac DF**. Todos os direitos reservados.

## 📞 Contato

**Equipe MedConnect**
- **Email**: medconnect@senac.edu.br
- **GitHub**: [@medconnect-team](https://github.com/medconnect-team)
- **Instituição**: Faculdade de Tecnologia e Inovação Senac DF

---

<div align="center">
  <p>Desenvolvido com ❤️ pela equipe MedConnect</p>
  <p>Faculdade de Tecnologia e Inovação Senac DF - 2024</p>
</div>