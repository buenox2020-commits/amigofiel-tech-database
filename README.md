***# amigofiel-tech-database
# 🐾 AmigoFiel Tech - Modelagem e Implementação de Banco de Dados Relacional

Projeto acadêmico de modelagem e implementação de banco de dados relacional desenvolvido para otimizar a gestão operacional, prontuário sanitário e controle de adoções de uma ONG de proteção animal.

## 🛠️ Tecnologias e Conceitos Aplicados
- **SQL (DDL, DML, DQL)**: Criação de tabelas, inserção de dados e consultas avançadas.
- **Modelagem de Dados**: Diagrama EER e normalização até a 3ª Forma Normal (3NF).
- **Engenharia de Requisitos**: Mapeamento de regras de negócio, RFs e RNFs.
- **Integridade Referencial**: Chaves primárias, estrangeiras e restrições UNIQUE/ENUM.

## 🗂️ Estrutura do Banco de Dados
O sistema é composto por 9 tabelas interligadas:
`unidades`, `especies`, `racas`, `colaboradores`, `animais`, `adotantes`, `vacinas`, `historico_vacinas` e `processos_adocao`.

## 🚀 Como Executar
1. Execute o script `schema.sql` no seu SGDB (MySQL / MariaDB).
2. O script criará o banco `AmigoFielDB`, as tabelas com suas restrições e fará o povoamento inicial.
