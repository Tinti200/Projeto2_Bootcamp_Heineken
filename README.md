# Projeto2_Bootcamp_Heineken

Repositório destinado ao projeto 2 do Bootcamp Heineken - Construindo um Esquema Conceitual para Banco De dados

Resumo Visual do Diagrama: (Entidades x Relacionamentos)
- Cliente -> Veículo (1:N)
- Veículo -> Ordem de Serviço (OS) (1:N)
- Ordem de Serviço (OS) -> Serviço (1:N)
- Ordem de Serviço (OS) -> Peça (1:N)
- Ordem de Serviço (OS) -> Mecânico (N:M)
- Mecânico -> Equipe (N:1)
- Serviço -> Tabela de Referência de Mão de Obra (N:1)
