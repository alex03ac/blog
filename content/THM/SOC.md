### Tareas de un Analista de Seguridad Junior

#### Resumen

- **Objetivos**: 
	- Monitorear utilizando un dashboard SIEM.
	- Analizar direcciones IP sospechosas de las alertas (confirmar reputación y ubicación).
	- Escalar incidentes.
	- Aplicar respuesta rápida para contención o ralentización del ataque.
- **Plataformas Open-Souce**: [AbuseIPDB](https://www.abuseipdb.com/), [Cisco Talos Intelligence](https://www.talosintelligence.com/),
- **Recomendaciones**: 
	- En caso de encontrar una dirección IP maliciosa, para una Internet más segura se recomienda realizar un reporte de la dirección IP maliciosa en estas plataformas.
	- Escalar el incidente al personal adecuado (De acuerdo con las políticas se escala el problema o dar solución en caso sea parte de tus responsabilidades).
- **Acciones Posteriores**: Una vez escalado el incidente se espera una orden de acción para detener o ralentizar el ataque.

#### Escenario

**Fase 1: Monitoreo**

>En nuestras actividades de monitoreo en el dashboard del SIEM atenderemos las alertas de seguridad que vallan surgiendo. De acuerdo a su criticidad y las políticas de la empresa iremos escalando incidentes de peso. 

En este caso el escenario plantea un acceso exitoso por SSH de una dirección IP desconocida. Ademas de una alerta previa de múltiples intentos de sesión no autorizados por parte de la misma dirección IP. Correlacionando los eventos el escenario dejo de ser un incidente menor y necesita de un análisis mas detallado ante un acceso no autorizado.


![[Pasted image 20260728115746.png]]

**Fase 2: Investigación**

Como analistas de seguridad tenemos que realizar un adecuado reporte de la situación por ello es bueno revisar la reputación de las direcciones IP sospechosas en listas negras de Internet. Ademas de recolectar información como la ubicación así descartando que el acceso no sea legitimo desde un dispositivo no mapeado en la empresa.

![[Pasted image 20260728115813.png]]

**Fase 3: Escalado**

Ante un incidente de acceso no autorizado de una dirección IP maliciosa desde China, la situación requiere un escalado hacia el líder del equipo SOC.

![[Pasted image 20260728115834.png]]

**Fase 4: Respuesta rápida**
Una respuesta rápida, ya sea para la contención o ralentización del ataque, es bloquear la dirección IP maliciosa con el Firewall.


![[Pasted image 20260728115925.png]]


---

