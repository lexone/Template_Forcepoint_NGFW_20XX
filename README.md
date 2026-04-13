Template para monitoramento de firewalls Forcepoint (StoneGate) via SNMP, compatível com Zabbix 7.0.

🔍 Visão Geral

Este template coleta métricas essenciais do firewall, permitindo visibilidade operacional e geração de alertas sobre desempenho e estado do equipamento.

📡 Tipo de Coleta
SNMP (Simple Network Management Protocol)
Baseado na MIB: FORCEPOINT-NGFW-ENGINE-MIB
📈 Métricas Monitoradas
🔹 Performance
Carga de CPU
Memória física total e utilizada
Memória swap total e utilizada
🔹 Rede e Tráfego
Número de conexões ativas
Pacotes aceitos
Pacotes descartados
Pacotes rejeitados
🔹 Sistema
Versão do software
Nome da política de segurança ativa
Status operacional do nó (com Value Map)
🚨 Triggers Inclusas
Alto número de conexões (> 12.000)
Uso de CPU acima de 90%
📊 Gráficos
Uso de CPU
Uso de memória
Conexões ativas
Pacotes trafegados
⚙️ Requisitos
Zabbix 7.0 ou superior
SNMP habilitado no firewall
Comunidade SNMP configurada corretamente
Acesso do Zabbix Server ao dispositivo
📥 Instalação
Acesse Configuration → Templates
Clique em Import
Selecione o arquivo .yaml
Confirme a importação
🧠 Observações
Template ajustado para compatibilidade com Zabbix 7.0
Não requer customizações adicionais para uso básico
Pode ser expandido com novos OIDs conforme necessidade
👤 Autor

Everton Silva
