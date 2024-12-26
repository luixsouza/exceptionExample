# Tratamento de Exceções em Java

Este projeto foi desenvolvido para demonstrar o uso de **tratamento de exceções** em Java. Ele simula um sistema de reservas de quartos, lidando com entradas inválidas e regras de domínio.

## Funcionalidades

- Criar uma reserva informando número do quarto, check-in e check-out.
- Atualizar as datas de uma reserva existente.
- Tratar os seguintes erros:
  - Formato de data inválido (`ParseException`).
  - Regras de domínio violadas, como datas inconsistentes (`DomainException`).
  - Erros inesperados (`RuntimeException`).

## Tecnologias

- Java
- SimpleDateFormat
- Scanner
- Exceções personalizadas (`DomainException`)

## Objetivo
Este projeto foi criado para fins de aprendizado, destacando:

- Uso de exceções personalizadas.
- Validação de regras de negócio.
- Tratamento de erros comuns em aplicações Java.
