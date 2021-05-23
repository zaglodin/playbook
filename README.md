# Что делает playbook
Playbook скачивает диструбитивы нужных версий для JDK, Elastiksearch и Kibana, распаковывает, устанавливает их и задаёт переменные окружения.

# Параметры
java_jdk_version: 11.0.11  
elastic_version: "7.10.1"  
kibana_version: "7.12.1"  

# Теги
java  
elastik  
kibana  
skip_ansible_lint