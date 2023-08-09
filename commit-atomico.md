# Commits Atômicos

Commits atômicos referem-se à prática de fazer commits individuais para cada mudança lógica ou funcional no código. Em vez de combinar várias alterações em um único commit, cada alteração é isolada em seu próprio commit. Esta abordagem mantém o histórico do Git limpo, facilita a revisão de código e permite reverter facilmente mudanças específicas se necessário.

# Tamanho apropriado do commit
Em resumo, um commit atômico é focado, isolado e facilmente compreensível. A chave é garantir que cada commit represente uma unidade lógica de trabalho que possa ser entendida, testada e, se necessário, revertida de forma independente.

### Propósito Único
Um commit atômico deve ter um único propósito. Se você pode descrever o commit com uma única frase concisa, provavelmente é atômico. Por exemplo, "Adiciona método de busca de usuário" ou "Corrige bug no cálculo de impostos".

### Revertível
Um dos grandes benefícios dos commits atômicos é a capacidade de reverter facilmente uma mudança específica sem afetar outras partes do código. Se o commit for muito grande, com múltiplas alterações, reverter uma mudança específica pode se tornar complicado.

### Revisão Simplificada
Commits menores e mais focados são mais fáceis de revisar. Se um commit tem centenas de linhas de mudanças em vários arquivos, a revisão torna-se mais desafiadora. É mais difícil para um revisor entender todas as implicações e possíveis efeitos colaterais.

### Testável
Cada commit atômico deve ser testável por si só. Se um commit introduz uma nova funcionalidade ou corrige um bug, deve ser possível testar essa mudança específica e garantir que ela funciona como esperado.

### Evitar Commits "Frankenstein"
Às vezes, os desenvolvedores têm a tendência de incluir várias alterações não relacionadas no mesmo commit, como corrigir um bug, refatorar um método e adicionar comentários. Isso cria commits "Frankenstein", que são misturas de diferentes tipos de alterações. É melhor dividir essas mudanças em commits separados.

### Tamanho Não É Necessariamente Medido em Linhas
Um commit atômico não significa necessariamente que seja um commit pequeno em termos de linhas de código. Pode ser uma mudança significativa, mas ainda assim focada em uma única funcionalidade ou correção.

### Contexto da Equipe e do Projeto
A definição de "atômico" pode variar dependendo da equipe ou do projeto. Em alguns projetos, pode ser apropriado ter commits um pouco maiores se as mudanças estiverem todas relacionadas. Converse com sua equipe para definir o que faz sentido no contexto específico de vocês.


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
