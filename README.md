# Pomodoro com Lista de Tarefas

Este projeto combina um temporizador Pomodoro com uma lista de tarefas, ajudando você a otimizar sua produtividade.

## Funcionalidades

* **Temporizador Pomodoro:**
    * Modos de foco, descanso curto e descanso longo.
    * Contagem regressiva com exibição do tempo formatado.
    * Reprodução de áudio para iniciar, pausar e finalizar o tempo.
    * Opção de ativar/desativar música de fundo.
* **Lista de Tarefas:**
    * Adicionar, editar e marcar tarefas como completas.
    * Persistência de tarefas usando `localStorage`.
    * Remover tarefas concluídas ou todas as tarefas.
    * Ao finalizar o tempo de foco, a tarefa selecionada é marcada como completa.
* **Interface de Usuário:**
    * Interface intuitiva e responsiva.
    * Alteração dinâmica do banner e título conforme o contexto do temporizador.
    * Marcação visual de tarefas ativas e completas.

## Como Usar

1.  **Clonar o repositório:**
    ```bash
    git clone [https://github.com/dolthub/dolt](https://github.com/dolthub/dolt)
    ```
2.  **Abrir o arquivo `index.html` no seu navegador.**
3.  **Temporizador Pomodoro:**
    * Selecione o modo desejado (foco, descanso curto ou descanso longo).
    * Clique em "Começar" para iniciar o temporizador.
    * Clique em "Pausar" para interromper o temporizador.
    * Use o botão de alternar música para ligar ou desligar a musica de fundo.
4.  **Lista de Tarefas:**
    * Clique no botão "+" para adicionar uma nova tarefa.
    * Digite a descrição da tarefa e pressione "Adicionar".
    * Clique em uma tarefa para selecioná-la.
    * Clique no ícone de edição para modificar a descrição da tarefa.
    * Ao finalizar o tempo de foco, a tarefa selecionada será marcada como completa.
    * Clique nos botões "Remover Concluídas" ou "Remover Todas" para limpar a lista de tarefas.

## Estrutura do Código

* **`index.html`:** Estrutura HTML da aplicação.
* **`script.js`:** Lógica JavaScript para o temporizador Pomodoro e a lista de tarefas.
* **`style.css`:** Estilos CSS da aplicação.
* **`imagens/`:** Diretório contendo imagens utilizadas na aplicação.
* **`sons/`:** Diretório contendo arquivos de áudio utilizados na aplicação.

## Tecnologias Utilizadas

* HTML
* CSS
* JavaScript
* `localStorage`

## Melhorias Futuras

* Adicionar configurações personalizadas para os tempos de foco e descanso.
* Implementar notificações para alertar sobre o fim do tempo.
* Melhorar a interface de usuário com animações e transições.
* Adicionar a opção de salvar as configurações do usuário.
* Adicionar testes unitários.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
