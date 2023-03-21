# Monitoramento e observabilidade usando Prometheus, Grafana e Alertmanager

Neste projeto foram desenvolvidos códigos para realizar o acompanhamento de métricas de uma Rest API de exemplo via dashboards utilizando o Prometheus e o Grafana, além da configuração do Alertmanager para enviar avisos à um canal do Slack quando necessário.

| Nome | Descrição |
| -- | --|
| [Script docker-compose](https://github.com/lucasbalponti/Observabilidade-e-Monitoramento---Prometheus-Grafana-e-Alertmanager/blob/main/docker-compose.yaml) | Script onde foi configurada a criação dos containers tanto da aplicação em si quanto do Prometheus, Grafana e Alertmanager |
| [Script prometheus.yml](https://github.com/lucasbalponti/Observabilidade-e-Monitoramento---Prometheus-Grafana-e-Alertmanager/blob/main/prometheus/prometheus.yml) | Script onde foram feitas as configurações específicas do prometheus |
| [Script prometheus.yml](https://github.com/lucasbalponti/Observabilidade-e-Monitoramento---Prometheus-Grafana-e-Alertmanager/blob/main/prometheus/prometheus.yml) | Script onde foram feitas as configurações específicas do prometheus |
| [Arquivo JSON de configuração da dashboard](https://github.com/lucasbalponti/Observabilidade-e-Monitoramento---Prometheus-Grafana-e-Alertmanager/blob/main/dash-forum-api-1679360158685.json) | Arquivo que contém as configurações da dashboard desenvolvida no grafana |
| [Script alertmanager.yml](https://github.com/lucasbalponti/Observabilidade-e-Monitoramento---Prometheus-Grafana-e-Alertmanager/blob/main/alertmanager/alertmanager.yml) | Script onde foi feita a configuração dos alertas no Alertmanager, assim como a vinculação do mesmo com o canal do slack |