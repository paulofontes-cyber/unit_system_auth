# Unit Authenticator

Sistema de autenticação de usuários implementado com Tabela Hash e tratamento de colisões por encadeamento.

## Estrutura do Projeto

\`\`\`
src/
├── No.java                          # Classe para nós da lista ligada
├── TabelaHash.java                  # Implementação da tabela hash
├── UnitAuthenticator.java           # Classe principal com menu interativo
└── TestesUnitAuthenticator.java     # Testes automatizados do sistema
\`\`\`

## Como Compilar e Executar

### Compilar todos os arquivos:
\`\`\`bash
javac src/*.java
\`\`\`

### Executar o sistema interativo:
\`\`\`bash
java -cp src UnitAuthenticator
\`\`\`

### Executar os testes automatizados:
\`\`\`bash
java -cp src TestesUnitAuthenticator
\`\`\`

## Funcionalidades

1. **Inserção**: Cadastrar novos usuários com nome e senha
2. **Remoção**: Remover usuários do sistema
3. **Busca**: Verificar se um usuário está cadastrado
4. **Login**: Autenticar usuário com nome e senha
5. **Sair**: Encerrar o sistema

## Características Técnicas

- **Estrutura de Dados**: Tabela Hash com encadeamento
- **Tratamento de Colisões**: Lista ligada (encadeamento)
- **Tamanho da Tabela**: 10 posições
- **Função Hash**: Soma dos valores ASCII dos caracteres módulo tamanho da tabela

## Testes Implementados

O arquivo `TestesUnitAuthenticator.java` contém 15 testes que demonstram:
- Inserção de usuários
- Detecção de usuários duplicados
- Busca de usuários existentes e inexistentes
- Autenticação com credenciais corretas e incorretas
- Remoção de usuários
- Tratamento de colisões por encadeamento
- Operações em listas com colisões

## Autor

Atividade da disciplina de Estrutura de Dados
