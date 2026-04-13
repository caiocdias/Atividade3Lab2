# Laboratório 2 - Atividade 3 - Dispositivos Móveis

Aplicativo Android desenvolvido para a disciplina de Dispositivos Móveis que realiza a reprodução de áudio em segundo plano utilizando um ForegroundService com MediaPlayer. O serviço é iniciado pela Activity, reproduz um arquivo de música local (armazenado em raw) e exibe uma notificação persistente com o título "Tocando Música" durante toda a execução. O serviço utiliza START_STICKY para manter a execução mesmo em situações de encerramento pelo sistema e realiza a liberação adequada dos recursos do MediaPlayer no onDestroy().

## Alunos

- Caio Cezar Dias
- Isabely Toledo de Melo

## Instituição

Universidade do Estado de Minas Gerais (UEMG)

