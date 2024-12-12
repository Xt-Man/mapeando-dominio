# Mapeando o domínio
Desafio da seção DDD no Node.js do módulo [MBA] Desenvolvimento Back-end do curso MBA Rocketseat Full-Stack

## Entidades
- Produto
  - Deve possuir identificador único (obrigatório)
  - Deve possuir nome (obrigatório)
  - Pode possuir tamanho (opcional)
  - Pode possuir cor (opcional)

- Estoque
  -  Deve ser vinculado a um produto
  -  Deve possuir a quantidade atual
  -  Deve possuir um limite mínimo

- Alerta
  - Deve possuir identificador único
  - Deve possuir data de criação

- Notificação

- Venda
    - Deve possuir identificador único
    - Deve possuir data
    - Deve possuir lista de produtos vendidos
      - Produto
      - Quantidade
      - Valor unitário

- Compra
    - Identificador de Produto
    - Quantidade comprada
    - Valor unitário


## Casos de Uso

- Cadastrar produto com identificador único e informações extras
- Rastrear Produto pelo identificador único
- Obter histórico de vendas
- Obter estoque atual
- Definir limite mínimo para cada produto
- Gerar Alerta ao atingir quantidade mínima
- Enviar email de Alerta de estoque mínimo
- Enviar notificação de estoque mínimo
- Obter métricas do histórico de vendas por período
  - Lucro
  - Quantidade vendida
  - Tendência do estoque
- Gerar ordem de compra automática ao atingir limite mínimo
- Integrar com fornecedores para receber os prazos de entrega das ordens de compra
