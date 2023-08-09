# Mensagens de Commit Claras e Detalhadas

As mensagens de commit representam a documentação em tempo real do progresso do seu projeto. Quando escritas de forma eficaz, oferecem uma compreensão clara do que foi feito, permitindo que desenvolvedores, revisores e futuros colaboradores compreendam a história do projeto. As mensagens bem elaboradas são essenciais para manter a base de código sustentável e colaborativa.

### Importância das Mensagens de Commit:

- **Histórico Legível:**
Ao revisar a história de um projeto, é vital que as mensagens de commit forneçam um contexto claro sobre o que, por que e como mudanças foram feitas.

- **Facilitar a Revisão:**
Durante revisões de código, as mensagens de commit ajudam os revisores a entender as intenções do autor, facilitando feedbacks construtivos e precisos.

- **Documentação Instantânea:**
Em muitos casos, antes de consultar a documentação oficial ou a Wiki do projeto, os desenvolvedores procuram commits relacionados para entender as mudanças ou resolver bugs.

- **Facilita a Rastreabilidade:**
Em situações onde um bug é identificado, mensagens de commit claras ajudam a rastrear quando e por que uma determinada mudança foi feita, auxiliando na resolução do problema.

### Características de uma Boa Mensagem de Commit:

- **Concisa e Informativa:**
A primeira linha do commit deve ser um resumo conciso (geralmente até 50 caracteres) do que foi feito. Detalhes adicionais podem ser fornecidos após uma linha em branco.

- **Uso do Imperativo:**
Escreva suas mensagens no modo imperativo, como "Adiciona", "Corrige", "Refatora", em vez de "Adicionado", "Corrigido" ou "Refatorado".

- **Fornecer Contexto:**
Quando aplicável, explique por que a mudança é necessária. Por exemplo: "Corrige bug onde o carrinho de compras não atualizava corretamente".

- **Evitar Ambiguidade:**
Evite mensagens genéricas como "Correções" ou "Atualizações". Seja específico sobre o que foi alterado.

- **Referência a Recursos Externos:**
Se a mudança estiver relacionada a uma discussão externa, como um ticket de bug ou um pedido de recurso, referencie esse recurso na mensagem.

Ao seguir estas diretrizes, você não apenas melhora a clareza e a utilidade de suas mensagens de commit, mas também promove uma cultura de colaboração e transparência dentro de sua equipe.

# Exemplos

### Adiciona Nova Funcionalidade:
- Adiciona função de busca de usuário
- Implementa autenticação via OAuth
- Integra API de pagamentos
- Cria componente de galeria de imagens
- Adiciona suporte a múltiplos idiomas

### Corrige um Bug:
- Corrige erro de cálculo no módulo financeiro
- Resolve vazamento de memória na página de perfil
- Ajusta falha de carregamento de imagens em dispositivos iOS
- Corrige erro de roteamento em URLs específicas
- Resolve incompatibilidade entre plugins

### Refatora Código (Alteração Lógica):
- Refatora lógica de ordenação para melhor desempenho
- Simplifica função de filtro com uso de higher-order function
- Organiza imports seguindo padrão do projeto
- Separa lógica de negócios de componentes de UI
- Consolida funções duplicadas

### Atualiza Documentação:
- Atualiza README com instruções de instalação
- Adiciona comentários no módulo de sincronização
- Documenta processo de migração de banco de dados
- Detalha propósito e uso de hooks personalizados
- Elabora FAQ para problemas comuns

### Melhora UI:
- Ajusta estilos do cabeçalho para melhor visualização em mobile
- Modifica paleta de cores para ser mais acessível
- Otimiza layout da página de checkout
- Adiciona animações de transição entre páginas
- Introduz modo escuro

### Muda Nome de Variável (Alteração Lógica):
- Renomeia variável 'lst' para 'listaUsuarios'
- Modifica 'qtd' para 'quantidade' nas funções de carrinho
- Altera nome da constante 'MAX_LMT' para 'MAX_LIMIT'
- Substitui 'usr' por 'user' no contexto de autenticação
- Muda 'cfg' para 'config' em módulo de configurações

### Remove Código Obsoleto:
- Remove funções antigas de autenticação
- Descarta biblioteca de animações não utilizada
- Elimina código comentado na classe principal
- Despreza módulo antigo de notificações
- Exclui assets desatualizados

### Adiciona Testes:
- Adiciona testes unitários para a função de login
- Implementa testes de integração para API de produtos
- Cria mock de serviços externos para testes
- Adiciona testes para componentes de frontend
- Elabora testes de stress para ambiente de produção

### Muda Biblioteca/Dependência:
- Migra de lodash para underscore
- Atualiza versão do React de 16 para 17
- Substitui biblioteca de gráficos por uma mais leve
- Implementa TypeScript no lugar de JavaScript puro
- Transiciona de Jest para Mocha para testes

### Modifica Configurações:
- Atualiza configurações de build para nova versão do Node
- Ajusta parâmetros de linting para padrão de código atual
- Modifica ambiente de desenvolvimento para usar Docker
- Configura nova ferramenta de CI/CD
- Ajusta configurações de cache para otimização de performance
