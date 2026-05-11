# Introdução à Automação Web

## Sobre Mim

Especialista em Dados com 10+ anos de experiência em análise de dados e processos complexos. Com rigor metodológico e base científica, atuo como QA Trainee na Compass UOL, focando em AWS e IA. Unindo testes funcionais, automação e Data Quality, utilizo Engenharia de Prompt e Agentes de IA para otimizar o ciclo de testes. Meu foco é garantir a integridade técnica e a robustez estratégica de softwares e dados de alta complexidade.

---
## Dicionário Git do QA
Para um QA, o versionamento é a prova real da evolução do código. Aqui estão os conceitos fundamentais explicados sob a minha ótica:

| Termo | O que significa na prática? |
| :--- | :--- |
| **Commit** | É o "checkpoint". Salva as alterações feitas no código com uma mensagem explicativa. |
| **Push** | Envia as alterações locais para o servidor remoto (ex: GitHub). |
| **Pull** | Traz as alterações do servidor remoto para a sua máquina, mantendo tudo atualizado. |
| **Merge** | É quando unimos o código existente em uma branch em outra. |
| **Branch** | Uma linha do tempo paralela. Ideal para testar novas features sem quebrar a linha principal. |

---
## Comandos Favoritos
Estes são os comandos que têm sido essenciais no meu dia a dia de automação e controle de versão:

```bash
# Inicializar o repositório
git init

# Verificar o status das alterações
git status

# Adicionar todos os arquivos para o próximo commit
git add .

# Criar um ponto na história com uma mensagem clara
git commit -m "feat: estrutura inicial do projeto de automação"

# Criar e alternar para uma nova branch de testes
git checkout -b feature/cenarios-de-teste

# Enviar as alterações para o repositório remoto
git push origin main

# Busca as informações mais recentes do servidor (sem mesclar)
git fetch origin

# Força o código local a ser exatamente igual ao que está no remoto.
# Isso descarta TODAS as alterações locais e resolve conflitos de hash (Quando tudo deu errado e precisa começar do zero).
git reset --hard origin/main
