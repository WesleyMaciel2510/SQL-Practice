# Prática de SQL 💾

## Para fins didáticos, foi utilizada a plataforma Oracle Live SQ (https://livesql.oracle.com). É um serviço online gratuito oferecido pela Oracle para aprendizado de SQL e PL/SQL. Ele é baseado em Apex e fornece aos usuários acesso a um banco de dados Oracle.

## ScreenShoot 📱

![Screenshot](https://github.com/user-attachments/assets/331e4ab3-e636-4d1a-8348-4c25da766f5d)

## Tabelas 🛠️

- **ALUNOS**: nome, e-mail, data de nascimento, endereço e se o pagamento está em dia.
- **PROFESSORES**: nome, e-mail, especialidade e salário.
- **DISCIPLINAS**: nome e o professor responsável.
- **RELACIONAMENTO_ALUNOS_DISCIPLINAS**: Tabela para relacionar alunos com disciplinas, incluindo a nota e se o aluno foi aprovado.

# Visualização de Dados 🔍

# Inserção de Dados 📝

# Atualização de Dados ✏️

# Exclusão de Dados 🗑️

## Joins 🔗

- **INNER JOIN**: Obtém alunos com as disciplinas nas quais estão matriculados.
- **LEFT JOIN**: Obtém todos os alunos e suas disciplinas, se disponíveis.
- **RIGHT JOIN**: Obtém todas as disciplinas e os alunos associados, se disponíveis.

## Drop Table 🧹

## 🚨 Obs.: É importamte Remover Constraints e Chaves Estrangeiras Antes do DROP TABLE 🚨
- Evita Erros: Remove erros ao tentar excluir tabelas referenciadas por outras.
- Mantém Integridade: Garante que a integridade referencial não seja comprometida.
- Facilita Reestruturação: Permite uma reestruturação mais fácil do banco de dados.

## Precaução com o Comando DROP TABLE ⚠️
- Perda de Dados: Remove permanentemente a tabela e seus dados; tenha backups.
- Impacto em Outras Tabelas: Pode afetar tabelas relacionadas e causar erros de integridade.
- Verificação Necessária: Confirme que a tabela não é mais necessária e que você tem backups.
