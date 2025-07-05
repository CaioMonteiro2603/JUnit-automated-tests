##  Nome das pastas

### As pastas com os nomes `ws01`, `ws02` etc foram seguidos de acordo com os nomes dos sites presentes em nossa documentação do overleaf. 
---
## 🤖 Como os testes foram gerados

### Os casos de teste presentes nas pastas foram gerados automaticamente com a IA **Suna**, uma plataforma que orquestra múltiplos agentes de IA para automação de tarefas complexas.
---

A geração foi realizada com a seguinte infraestrutura:
- 🐍 **Python** – linguagem principal utilizada
- 🐳 **Docker + Docker Compose** – para isolar e gerenciar os serviços
- 🐇 **RabbitMQ** – mensageria entre os agentes
- 🛑 **Redis** – para cache e controle de estado
- ⚙️ **Vários workers e serviços backend/frontend**

> Todo o setup foi configurado e executado localmente para garantir controle total sobre a geração dos testes.

---
## 💻 Onde rodar esses casos de teste?
Cada pasta contém um conjunto de arquivos de teste automatizados, prontos para serem analisados, executados e expandidos. Os casos de testes foram executados no **Eclipse IDE** com JUnit.

