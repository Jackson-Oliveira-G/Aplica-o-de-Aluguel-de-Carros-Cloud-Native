# Aplica-o-de-Aluguel-de-Carros-Cloud-Native
Aplicação de Aluguel de Carros Cloud-Native

# 🚗 Aplicação de Aluguel de Carros - Cloud Native

## 📦 Sobre o Projeto

Este projeto é uma aplicação de **aluguel de carros**, totalmente **Cloud-Native**, construída durante o curso. Ela é composta por uma arquitetura moderna baseada em microserviços, escalável e pronta para execução em ambientes de nuvem como AWS, Azure ou GCP.

---

## 🛠️ Tecnologias Utilizadas

- Docker e Docker Compose
- Kubernetes (Minikube ou EKS/GKE/AKS)
- Node.js / Java / Python (ajuste conforme sua stack)
- MongoDB / PostgreSQL
- GitHub Actions (CI/CD)
- AWS S3 / EC2 / RDS (ou outros serviços em nuvem)
- Terraform (para IaC)

---

## ⚙️ Etapas do Desenvolvimento

1. **Criação do repositório no GitHub**

   - Nome do repositório: `car-rental-cloud-native`
   - Inicialização com um `README.md`

   ![Print - Repositório GitHub](./prints/github-repositorio.png)

2. **Desenvolvimento da aplicação**

   - Separação dos módulos (ex: usuários, carros, reservas, pagamentos);
   - Criação de microserviços com APIs RESTful.

   ![Print - Estrutura de Pastas](./prints/estrutura-pastas.png)

3. **Containerização com Docker**

   - Cada serviço com seu próprio `Dockerfile`;
   - Docker Compose para ambiente de desenvolvimento local.

   ![Print - Docker Compose](./prints/docker-compose.png)

4. **Orquestração com Kubernetes**

   - Criação de arquivos YAML (`deployment`, `service`, `ingress`);
   - Testes locais com Minikube.

   ![Print - Kubernetes Pods](./prints/k8s-pods.png)

5. **Provisionamento em Nuvem**

   - Deploy automatizado com GitHub Actions;
   - Uso do Terraform para infraestrutura como código.

   ![Print - Terraform Apply](./prints/terraform.png)

---

## 💡 Insights do Curso

- **Cloud-Native** não é só "rodar na nuvem", mas projetar pensando em resiliência, escalabilidade e automação desde o início.
- A separação de serviços facilita a manutenção e a evolução do sistema.
- Utilizar ferramentas como Docker e Kubernetes simplifica a implantação e aumenta a portabilidade.
- GitHub Actions facilita CI/CD com pipelines automatizados.

---

## 🌐 Possibilidades Futuras

- Adicionar autenticação com OAuth (Google/Facebook/Login do Gov);
- Dashboard administrativo com visualização em tempo real de reservas e veículos;
- Uso de mensageria (ex: Kafka ou RabbitMQ) para eventos assíncronos;
- Monitoramento com Prometheus e Grafana.

---

## 📎 Link do Repositório

[🔗 Acesse aqui o repositório no GitHub](https://github.com/seu-usuario/car-rental-cloud-native)

---

## ✅ Conclusão

Este projeto mostrou como construir uma aplicação robusta, escalável e orientada a serviços, seguindo os princípios de Cloud-Native. A experiência trouxe conhecimento técnico e prático sobre DevOps, infraestrutura e desenvolvimento moderno.

