# 📝 Lista de Tarefas - To-Do List

Aplicativo web simples e funcional para gerenciamento de tarefas desenvolvido como trabalho acadêmico.

## 🚀 Demonstração

O aplicativo permite gerenciar tarefas de forma intuitiva com interface moderna e responsiva.

## ✨ Funcionalidades

### Requisitos Obrigatórios ✅
- **Adicionar tarefas:** Digite a tarefa e clique em "Adicionar" ou pressione Enter
- **Marcar como concluída:** Clique no checkbox ao lado de cada tarefa
- **Remover tarefas:** Clique no botão "Remover" de cada item

### Funcionalidades Extras 🎁
- Persistência de dados com localStorage
- Contador de estatísticas (total, pendentes, concluídas)
- Timestamps relativos ("Há 2 horas", "Há 3 dias")
- Interface responsiva para mobile e desktop
- Animações suaves e feedback visual
- Estado vazio ilustrado

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização moderna com gradientes e animações
- **JavaScript Vanilla** - Lógica da aplicação com ES6+
- **localStorage** - Persistência de dados no navegador

## 📦 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/todo-list.git
```

2. Abra o arquivo `index.html` em qualquer navegador moderno

3. Pronto! O aplicativo está funcionando localmente

## 🏗️ Estrutura do Projeto

```
todo-list/
│
├── index.html          # Arquivo único com toda a aplicação
└── README.md          # Este arquivo
```

## 💻 Arquitetura

O código está organizado em uma classe `TodoManager` que gerencia:
- **Estado:** Array de objetos tarefa com id, texto, status e timestamp
- **Persistência:** Sincronização automática com localStorage
- **Renderização:** Atualização dinâmica do DOM
- **Eventos:** Delegação eficiente de eventos

### Estrutura de Dados
```javascript
{
    id: 1694567890123,           // Timestamp único
    text: "Estudar JavaScript",   // Texto da tarefa
    completed: false,             // Status de conclusão
    createdAt: "2024-09-17..."   // Data de criação ISO
}
```

## 🎨 Design

- **Cores:** Gradiente roxo/azul moderno
- **Tipografia:** System fonts para melhor performance
- **Layout:** Flexbox responsivo
- **Animações:** Transições CSS suaves
- **UX:** Feedback visual imediato em todas as ações

## 📱 Compatibilidade

- ✅ Chrome/Edge (Chromium)
- ✅ Firefox
- ✅ Safari
- ✅ Opera
- ✅ Dispositivos móveis

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos.

---

Desenvolvido com ❤️ para o trabalho de Programação
