# TASK-01: Cálculo de frete padrão e frete grátis por valor

## Escopo
- Implementar o cálculo de frete conforme REQ-01 e REQ-02 de specs/checkout_frete.md.
- Nada além disso (sem cupons, logs ou persistência).

## Critérios de aceite
- Subtotal < 200,00 -> total = subtotal + 15,00 (REQ-01)
- Subtotal >= 200,00 -> frete = 0,00 (REQ-02)
- O código deve citar REQ-01 e REQ-02 em comentários.