# Trabalho 03 de IOT
Este painel foi desenvolvido em Node-RED para monitoramento e controle de uma célula/dispositivo via MQTT. O ambiente é executado através de Docker Compose, permitindo iniciar rapidamente o serviço de Node-RED e o broker MQTT.

## 1. Baixando o Projeto
Clone este repositório:

```bash
git clone https://github.com/aagablm/trabalho03-iot.git
cd trabalho03-iot
```

## 2. Subindo o Ambiente (Docker Compose)
```bash
docker compose up -d
```
Isso criará os containers necessários. Aguarde até que estejam ativos.

## 3. Acessando o Node-RED
No navegador, acesse:
```bash
http://localhost:1880
```

## 4. Importando o Flow
- No Node-RED, clique no menu ≡ (canto superior direito).
- Selecione **Import**.
- Cole ou carregue o arquivo **flow.json**.
