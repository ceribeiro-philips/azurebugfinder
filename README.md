# 🐞 Azure Bug Finder

**Azure Bug Finder** é uma extensão para desenvolvida para facilitar a consulta de bugs no Azure DevOps, com filtros avançados, exportação para Excel e suporte a múltiplas plataformas Tasy.
📌 Veja o [Changelog completo](CHANGELOG.md)

---

## 🚀 Funcionalidades

- 🔍 Consulta rápida de bugs por versão e aplicação
- 🧠 Filtros avançados dinâmicos (Customer, Function, Problem Task, etc.)
- 📦 Exportação dos resultados para Excel
- 🕵️‍♂️ Suporte a busca por versões superiores (SP)
- 🧩 Compatível com Tasy HTML5, Java e Delphi
- 🛡️ Validação automática do token PAT
- 🌙 Tema escuro com persistência
- 📌 Histórico de versões buscadas
- 📋 Menu de copiar resultado com clique direito
- 🔄 Verificação automática de versão do plugin (com alerta de atualização)

---

## 🛠️ Como usar

1. **Configure seu token PAT** clicando no ícone de engrenagem.
2. **Preencha a versão** desejada e selecione a(s) aplicação(ões).
3. (Opcional) Ative a busca por versões superiores (SP).
4. (Opcional) Adicione filtros avançados clicando em "Filtro Avançado".
5. Clique em **Consultar** para buscar os bugs.
6. Clique em **Exportar** para salvar os resultados em Excel.

---

## 📁 Estrutura dos arquivos

| Arquivo             | Função principal                          |
|---------------------|-------------------------------------------|
| `consulta.js`       | Lógica de consulta WIQL e tratamento dos dados |
| `filtros.js`        | Filtros dinâmicos e persistência local    |
| `modalPat.js`       | Configuração e validação do token PAT     |
| `autocomplete.js`   | Autocompletar campos de filtro            |
| `exportacao.js`     | Exportação dos dados para Excel           |
| `ui.js`             | Comportamento visual e interações         |
| `background.js`     | Verificação de versão                     |
| `main.js`           | Inicialização e controle da interface     |

---

## 🔒 Segurança

- O plugin **não armazena dados sensíveis** fora do navegador.
- O token PAT é salvo localmente via `chrome.storage.local`.
- A verificação de versão é feita via arquivo público no GitHub, sem expor credenciais.

---

## 📦 Atualizações

O plugin verifica automaticamente se há uma nova versão disponível. Se houver, o usuário será alertado e poderá optar por continuar ou fechar o plugin.

---

## 🧪 Requisitos

- Navegador Chrome ou Edge
- Acesso ao Azure DevOps com token PAT válido
- Permissões para consultar Work Items no projeto EMR

---

## 📄 Créditos

Criado por Carlos Eduardo Ribeiro
