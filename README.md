# <img width="50" height="50" alt="icon" src="https://github.com/user-attachments/assets/2c23f8d7-cdc4-4150-9ca8-f6cf3a5d4035" /> Azure Bug Finder

**Azure Bug Finder** é uma extensão para facilitar a consulta de bugs no Azure DevOps, com filtros avançados e exportação para Excel.

<div align="center">
  <img width="485" height="385" alt="Tela principal do plugin" src="https://github.com/user-attachments/assets/3cac043a-0217-470e-8b42-cf6a6681360c" />
</div>

📌 Veja o [Changelog completo](CHANGELOG.md)

---

## 📦 Instalação

Para instalar o plugin, siga o vídeo abaixo:

🔗 [Assistir vídeo tutorial](https://github.com/user-attachments/assets/b0dc151c-0dc2-4dbf-ba82-333e025359fd)


## 🔐 Configuração do Token PAT

Após a instalação, é necessário inserir seu **token PAT** para que o plugin possa validar suas permissões e autorizar as consultas ao Azure DevOps.

### ✅ Passo a passo:

1. Clique no ícone de **engrenagem** no canto inferior esquerdo do plugin
2. Insira seu token na tela exibida
3. Clique em **Salvar Token** para ativar o acesso

<div align="center">
  <img width="485" height="385" alt="Tela de configuração do token PAT" src="https://github.com/user-attachments/assets/53a32966-da97-4566-a33c-c038a0e3f135" />
</div>

---


## 🚀 Funcionalidades

- 🔍 Consulta rápida de bugs por versão e aplicação
- 🧠 Filtros avançados dinâmicos (Customer, Function, Problem Task)
- 📦 Exportação dos resultados para Excel
- 🕵️‍♂️ Suporte a busca por service packs 
- 🧩 Busca plataformas Tasy HTML5, Java e Delphi
- 🛡️ Validação automática do token PAT
- 🌙 Tema escuro com persistência
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

## 🔒 Segurança

- O plugin **não armazena dados sensíveis** fora do navegador.
- O token PAT é salvo localmente via `chrome.storage.local`.
- A verificação de versão é feita via arquivo público no GitHub, sem expor credenciais.

---

## 📦 Atualizações

O plugin verifica automaticamente se há uma nova versão disponível. Se houver, o usuário será alertado e poderá optar por continuar ou fechar o plugin.

Clique sobre a versão para ser direcionado ao repositório do GitHub.

---

## 🧪 Requisitos

- Navegador Chrome ou Edge
- Acesso ao Azure DevOps-EMR com token PAT válido
- Permissões para consultar Work Items no projeto EMR

---

## 📄 Créditos

Criado por Carlos Eduardo Ribeiro
