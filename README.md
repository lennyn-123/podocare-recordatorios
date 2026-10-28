# Reloj de recordatorios PodoCare

Este repositorio contiene unicamente la programacion cada cinco minutos que llama a una tarea autenticada del servidor. No contiene codigo de la aplicacion, pacientes, claves de Firebase ni credenciales de la base. El token de ejecucion esta cifrado en GitHub Actions Secrets y solo permite disparar los avisos pendientes.

La ejecucion depende de GitHub Actions y puede retrasarse. El servidor evita duplicados y recupera avisos pendientes mientras la cita siga siendo futura.
