# 🛒 Lista de Compras - Aplicativo Web

Um aplicativo web simples e eficiente para gerenciar sua lista de compras do supermercado. Funciona completamente offline no navegador, com armazenamento local e funcionalidades de exportação/importação.

## ✨ Funcionalidades

### 🎯 Principais Recursos
- **Adicionar Itens**: Inclua produtos com preço, supermercado e data de compra
- **Editar Itens**: Modifique qualquer informação (produto, preço, supermercado, data)
- **Excluir Itens**: Remova itens da lista com confirmação
- **Estatísticas**: Visualize total de itens, valor gasto e quantidade de supermercados
- **Armazenamento Local**: Todos os dados são salvos no navegador (localStorage)
- **Funcionalidade Offline**: Funciona sem conexão com internet
- **Exportação/Importação**: Salve e carregue suas listas em arquivos JSON

### 📱 Design Responsivo
- **Mobile-First**: Interface otimizada para celulares e tablets
- **Acessível**: Componentes acessíveis com navegação por teclado
- **Modo Escuro/Claro**: Suporte a temas (se configurado)
- **Interface Intuitiva**: Design limpo e fácil de usar

## 🚀 Tecnologias Utilizadas

### 🎯 Framework e Linguagem
- **⚡ Next.js 15** - Framework React com App Router
- **📘 TypeScript 5** - JavaScript com tipagem estática
- **🎨 Tailwind CSS 4** - Framework CSS utilitário

### 🧩 Componentes UI
- **🧩 shadcn/ui** - Componentes acessíveis e de alta qualidade
- **🎯 Lucide React** - Biblioteca de ícones consistente
- **📅 date-fns** - Utilitários para manipulação de datas

### 💾 Armazenamento
- **🌐 localStorage** - Armazenamento no navegador do cliente
- **📄 JSON** - Formato para exportação/importação de dados

## 🎯 Por que usar este aplicativo?

- **🏎️ Rápido e Leve**: Não requer servidor ou banco de dados externo
- **💾 Sem Cadastro**: Funciona imediatamente sem necessidade de criar conta
- **📱 Totalmente Offline**: Use em qualquer lugar, mesmo sem internet
- **🔄 Portável**: Exporte suas listas e use em outros dispositivos
- **🎨 Interface Limpa**: Foco na usabilidade e simplicidade
- **🔒 Privacidade**: Seus dados ficam apenas no seu navegador

## 🚀 Como Usar

### 🌐 Acesso Direto
1. Abra o aplicativo no navegador
2. Comece a adicionar itens imediatamente
3. Seus dados são salvos automaticamente

### 📱 No Celular
1. Acesse o link do aplicativo
2. Adicione à tela inicial para acesso rápido (como um app nativo)
3. Use offline sem problemas

### 💾 Exportar/Importar Dados
1. **Exportar**: Clique em "Exportar" para baixar um arquivo JSON com seus dados
2. **Importar**: Clique em "Importar" e selecione um arquivo JSON previamente exportado
3. **Limpar Tudo**: Use "Limpar Tudo" para apagar todos os dados (com confirmação)

## 🛠️ Desenvolvimento

### 📋 Pré-requisitos
- Node.js 18+ 
- npm ou yarn

### 🚀 Configuração do Ambiente

```bash
# Clonar o repositório
git clone <url-do-repositorio>
cd lista-de-compras

# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev

# Construir para produção
npm run build

# Iniciar servidor de produção
npm start
```

### 📁 Estrutura do Projeto

```
src/
├── app/                    
│   ├── page.tsx            # Página principal do aplicativo
│   ├── layout.tsx          # Layout com metadados
│   └── globals.css         # Estilos globais
├── components/             
│   └── ui/                 # Componentes shadcn/ui
├── hooks/                  # Hooks personalizados
└── lib/                    # Utilitários e configurações
```

## 🎨 Componentes Disponíveis

### 🧩 Interface do Usuário
- **Card**: Exibição de estatísticas e conteúdo
- **Button**: Botões com diversos estilos
- **Input**: Campos de formulário
- **Table**: Tabela para exibição dos itens
- **Dialog**: Modal para adicionar/editar itens
- **Calendar**: Seleção de datas
- **Popover**: Componentes sobrepostos

### 📊 Funcionalidades
- **Formulários**: Validação e submissão
- **Tabela Responsiva**: Scroll horizontal em telas pequenas
- **Modal Dialog**: Interface para edição de itens
- **DatePicker**: Seleção intuitiva de datas

## 🌐 Deploy

### 🚀 Plataformas Sugeridas
O aplicativo é um site estático e pode ser implantado em qualquer plataforma:

#### Vercel (Recomendado)
```bash
# Instalar Vercel CLI
npm install -g vercel

# Fazer deploy
vercel
```

#### Netlify
```bash
# Construir projeto
npm run build

# Fazer upload da pasta out
# Ou conectar repositório GitHub no Netlify
```

#### GitHub Pages
```bash
# Construir projeto
npm run build

# Configurar GitHub Pages para servir a pasta out
```

### 📱 Configuração para Celular
Para melhor experiência em dispositivos móveis:
1. **Adicionar à Tela Inicial**: 
   - Chrome: Menu → "Adicionar à tela inicial"
   - Safari: Compartilhar → "Adicionar à tela inicial"
2. **Modo Offline**: Funciona automaticamente sem internet
3. **Ícone Personalizado**: O favicon será usado como ícone do app

## 🔧 Personalização

### 🎨 Cores e Temas
- Modifique as variáveis do Tailwind CSS em `tailwind.config.ts`
- Personalize cores no arquivo `globals.css`

### 📱 Layout Responsivo
- As classes responsivas já estão configuradas
- Use `sm:`, `md:`, `lg:` para diferentes breakpoints

### 🌐 Internacionalização
- O aplicativo está em português brasileiro
- Para outros idiomas, modifique os textos no componente principal

## 🤝 Contribuição

Este é um projeto simples e aberto a contribuições:

1. **Fork** o projeto
2. **Crie** uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. **Commit** suas mudanças (`git commit -am 'Adiciona nova funcionalidade'`)
4. **Push** para a branch (`git push origin feature/nova-funcionalidade`)
5. **Crie** um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar.

## 🎯 Roadmap Futuro

- [ ] Adicionar categorias de produtos
- [ ] Filtros por supermercado e período
- [ ] Gráficos de gastos por mês
- [ ] Notificações para lembrar compras
- [ ] Sincronização entre dispositivos
- [ ] Temas personalizados
- [ ] Exportação para PDF/Excel

---

Criado com ❤️ para facilitar a organização de compras do dia a dia.
