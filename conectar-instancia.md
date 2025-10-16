# Conectar à Instância EC2 via SSH

1. Localize o arquivo `.pem` baixado ao criar o Key Pair.  
2. No terminal, use o comando:

```bash
ssh -i "chave.pem" ec2-user@IP_PUBLICO
```

3. Caso use Windows, você pode utilizar o **PuTTY** ou o **Windows Terminal** com OpenSSH.
