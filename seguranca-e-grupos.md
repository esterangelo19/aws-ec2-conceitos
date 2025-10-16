# Segurança e Grupos no EC2

O **Security Group** funciona como um firewall virtual para controlar o tráfego das instâncias.

- **Inbound Rules**: tráfego que entra na instância.  
- **Outbound Rules**: tráfego que sai da instância.

Exemplo de regra para permitir acesso SSH:
- Protocolo: TCP
- Porta: 22
- Origem: Seu IP público

**Dica:** nunca abra portas para “0.0.0.0/0” em produção.
