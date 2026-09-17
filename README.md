# 🇧🇷 DEPLOY-GITHUB — Automação e Gerenciamento Git via Termux

Ferramenta em Shell Script desenvolvida para automatizar a criação, envio (deploy), configuração e limpeza de repositórios no GitHub diretamente do seu dispositivo Android via **Termux**.

## Imagem do DEPLOY-GITHUB
![Imagem do Repositório](icon.png)

## 🚀 Recursos
- **Setup Automático**: Configura permissão de armazenamento e instala dependências (`git`, `gh`, `python`) automaticamente.
- **Autenticação Facilitada**: Login via **GitHub CLI** com fluxo web prático.
- **Limpeza de Arquivos Grandes**: Remove automaticamente arquivos locais maiores que 25MB para evitar bloqueios de upload do GitHub.
- **Criação e Vincular Repositórios**: Lista seus projetos existentes e cria o repositório remoto automaticamente se ele ainda não existir.
- **Deploy em Tempo Real**: Mapeia, faz commit e envia novos arquivos/alterações com push forçado seguro.
- **Reset de Histórico Remoto**: Opção para apagar todo o histórico do repositório remoto, compactando tudo em um único *Commit Inicial* (ideal para economizar espaço e limpar rastros de commits antigos).

## 📥 Instalação e Execução

Execute o comando abaixo no Termux para iniciar a ferramenta:

```bash
bash <(curl -s https://raw.githubusercontent.com/AMHEEX/GITHUB/main/index.sh)
