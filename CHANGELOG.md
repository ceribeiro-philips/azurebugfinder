# 📜 Changelog – Azure Bug Finder

---

## v1.0.3-Alpha – Melhorias de controle e integração com GitHub (20/10/2025)

- 🔄 Verificação automática de versão com controle de tempo (10 minutos entre alertas)
- ❌ Bloqueio de uso caso o usuário recuse continuar com versão desatualizada
- 🔗 Link direto para o repositório do GitHub ao clicar na versão (substitui modal de changelog)
- 🧠 Ajuste no `main.js` para encapsular inicialização e evitar execução indevida
- 🧹 Remoção segura de eventos e modais obsoletos para evitar erros de execução
- 🔗 Estilização do número da versão como hiperlink visível (azul, sublinhado, cursor de mão)
- 📄 Criação do arquivo `CHANGELOG.md` para histórico de versões separado do `README.md`

---

## v1.0.2-Alpha – Atualizações de usabilidade

- 🧩 Campo **Function** adicionado aos filtros avançados com autocompletar baseado em lista externa

---

## v1.0.1-Alpha – Usabilidade e experiência visual

- 🧹 **Limpar Resultados:** botão que remove apenas os resultados da consulta, mantendo filtros e configurações intactos
- 🕵️‍♂️ **Busca por SP:** checkbox que ativa campos de intervalo para filtrar versões por Service Pack
- 🧩 Campo **Customer** adicionado aos filtros avançados com autocompletar baseado em lista externa
- 🌙 **Modo Escuro:** alternância de tema com botão dedicado no rodapé. Preferência salva automaticamente
- 🎯 **Ícone de Filtro Dinâmico:** aparece ao lado de "Filtro Avançado" apenas quando há filtros preenchidos
- 💾 **Persistência de Filtros:** filtros avançados são salvos e restaurados automaticamente via `localStorage`
- ⚠️ **Validação Visual:** campos incompletos nos filtros são destacados com borda vermelha
- 📐 **Layout Refinado:** espaçamento ajustado entre botão de limpeza e rodapé para visual mais compacto
- 🔤 **Contraste Aprimorado:** textos como "Version Found" e "Version Fixed" com melhor legibilidade no modo escuro
