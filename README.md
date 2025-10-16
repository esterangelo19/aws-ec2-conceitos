# ☁️ Amazon EC2 - Conceitos e Anotações

Repositório criado para reunir **conceitos fundamentais**, **anotações práticas** e **exemplos de uso** sobre o serviço **Amazon EC2 (Elastic Compute Cloud)** da AWS.

---

## 📚 O que é o Amazon EC2?

O **Amazon EC2** é um serviço que permite **criar e gerenciar máquinas virtuais** (chamadas de instâncias) na nuvem da AWS.  
Com ele, é possível executar aplicações de forma escalável, configurando o sistema operacional, tipo de instância, armazenamento e rede.

---

## 🧩 Principais conceitos

| Conceito | Descrição |
|-----------|------------|
| **Instância** | Máquina virtual em execução na nuvem. |
| **AMI (Amazon Machine Image)** | Imagem usada para criar novas instâncias. |
| **Tipo de instância** | Define recursos como CPU, memória e rede. |
| **EBS (Elastic Block Store)** | Armazenamento persistente da instância. |
| **Key Pair** | Par de chaves para acesso seguro via SSH. |
| **Security Group** | Regras de firewall que controlam o tráfego. |

---

## 🧠 Boas práticas

- Crie instâncias em **regiões próximas** aos seus usuários.  
- **Use tags** para organizar seus recursos.  
- Sempre **configure o Security Group** corretamente.  
- Faça **backups (snapshots)** do seu EBS periodicamente.  
- Utilize **IAM Roles** para gerenciar permissões com segurança.

---

## 🖼️ Exemplo de Arquitetura EC2

![Diagrama EC2](images/ec2-diagrama.png)

---

## ✍️ Autor

**Ester Ângelo**  
Repositório criado como projeto de estudos sobre **Amazon EC2**.
