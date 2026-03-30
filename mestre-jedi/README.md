# 🧙‍♂️ Mestre Jedi - Anti-Vibe Coding Framework

O **Mestre Jedi** é um agente focado em erradicar o caos no desenvolvimento de software assistido por IA. Ele atua como um Engenheiro de Software Sênior e Arquiteto, forçando o usuário a pensar, planejar e documentar antes de qualquer linha de código ser escrita.

## ⚙️ Principais Funcionalidades

Este agente opera com base em três fluxos de trabalho (`workflows`) selecionáveis:

1. 🚀 **Fast Track**: Para scripts rápidos. Exige validação de design arquitetural e imposição de testes automatizados.
2. 🏗️ **Spec-Driven Development**: O fluxo principal. Divide a criação do software em PRD (Requisitos), TechSpec (Arquitetura), Tasks (Macro) e Subtasks (Micro).
3. 🎓 **Professor Jedi**: Mentoria focada em fundamentos, utilizando método socrático (perguntas reflexivas) e negando respostas prontas ("TL;DR").

**Destaque:** O Mestre Jedi possui um `<clarification_loop>` rigoroso. Ele nunca fará suposições; se algo na sua solicitação for ambíguo, ele irá pausar e fazer perguntas até que tudo esteja 100% claro.

## 🛠️ Como Utilizar

### Passo 1: Configurar a IA
1. Abra o arquivo `AGENTS.md` localizado nesta mesma pasta.
2. Copie todo o seu conteúdo bruto (Raw).
3. Cole o texto no **System Prompt** (ou como primeira mensagem) no seu chat com a IA Generativa.

### Passo 2: Preparar o Ambiente Local
Para que o Mestre Jedi consiga organizar o seu projeto, crie uma pasta oculta na raiz do seu projeto local chamada `.mestre-jedi`. 

Você pode criar a estrutura rapidamente rodando o comando abaixo no seu terminal (Linux/Mac/WSL):
```bash
mkdir -p .mestre-jedi/{prd,tech_spec,tasks,subtasks,templates,artifacts,old_logs,regras}
```

### Passo 3: Iniciar a Interação
Faça sua primeira solicitação para a IA (ex: *"Quero criar uma API em Node.js para gerenciar tarefas"*). 
O Mestre Jedi irá te interromper imediatamente, apresentar o menu de fluxos e exigir que você escolha um caminho antes de prosseguir.

A partir daí, basta seguir as instruções do seu novo Mestre Jedi. Que a Força do Código Limpo esteja com você!
