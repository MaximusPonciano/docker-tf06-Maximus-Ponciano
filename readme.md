# Docker Compose - TF06

## 📌 Descrição

Projeto utilizando Docker Compose para orquestrar:

* Servidor Nginx (build customizado)
* Cache Redis com persistência

---

## 🚀 Subindo o ambiente

```bash
docker compose up -d
```

---

### 📸 Evidência - Criação dos containers

![Evidência - Criação dos containers](https://github.com/user-attachments/assets/f76d3594-271d-45dd-90af-f828b94d6d2e)

### 📸 Evidência - Serviços ativos

![Evidência - Serviços ativos](https://github.com/user-attachments/assets/8f367ca3-ddd9-4819-b984-0514875c5655)

## 🔗 Teste de comunicação entre serviços

```bash
docker exec -it web_nginx sh
ping cache
```

✔️ Resultado esperado: comunicação funcionando via DNS interno do Docker

---

## 📁 Estrutura

```
lab_compose_tf06/
├── docker-compose.yml
├── nginx/
│   └── Dockerfile
└── README.md
```
