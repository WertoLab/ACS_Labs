# Лабораторная работа №1

### Выполнение:

1. После создания учетной записи в nextcloud, проверил nextcloud.log
![](screenshots/nextcloud_logs.png)
2. Проверил promtail подсоединился к nextcloud и собирает логи
![](screenshots/promtail_logs.png)
3. Связал nextcloud и zabbix для получения логов о состоянии nextcloud (health)
![](screenshots/zabbix_health_logs.png)
4. Добавил в grafana Loki data source
![](screenshots/loki_connection.png)
5. Добавил в grafana Zabbix data source (для этого установил соответствующий plugin)
![](screenshots/zabbix_connection.png)
6. Создал два dashboard для логирования zabbix и  nextcloud  
![](screenshots/grafana_dashboards.png)

### Ответы на вопросы:

1) Основное различие заключается в том, что SLA является официальным соглашением с клиентом, тогда как SLO — это внутренние цели, которые помогают обеспечить выполнение условий SLA
 
2) Различие в том, что инкрементальный бэкап - сохраняет изменения с последнего бэкапа (полного или инкрементального),
   а дифференциальный бэкап - сохраняет изменения с последнего полного бэкапа.

3) Разница в том, что monitoring - фокусируется на сборе метрик для оценки производительности, а
   observability - охватывает более широкий спектр данных (логи, трассировки) для понимания состояния системы и выявления причин проблем.
