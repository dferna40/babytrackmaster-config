# BabyTrackMaster - Config Repo

Repo de configuración para Spring Cloud Config Server.

Convención de nombres:
- {app}.yml  → se sirve en `/{app}/default`
- {app}-{profile}.yml → se sirve en `/{app}/{profile}`

Apps:
- api-usuarios, api-cuidados, api-gastos, api-hitos, api-citas, api-diario, api-rutinas, api-gateway

Cómo probar:
1) Arranca config-server en localhost:8888.
2) Abre: http://localhost:8888/api-usuarios/default
