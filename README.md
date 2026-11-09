# 🎙️ Voice Reminder – Piper TTS Edition

Versión personalizada de Voice Reminder para Super Productivity, con integración de síntesis de voz local mediante Piper TTS.

## ✨ Características

- Síntesis de voz local mediante Piper TTS.
- Compatibilidad con diferentes modelos de voz.
- Personalización de voces e idiomas.
- Mensajes de recordatorio aleatorios.
- Recordatorios de descanso configurables.
- Integración mediante un puente local.
- Mejoras progresivas de funcionalidades y experiencia de usuario.

## 🛠️ Tecnologías utilizadas

- Python 3.13
- Piper TTS 1.8.0
- ONNX Runtime 1.31.1
- PowerShell
- Super Productivity
- Modelos de voz ONNX

## ⚙️ Requisitos

- Windows 10/11.
- Super Productivity.
- Python 3.13.
- Piper TTS.
- Modelos de voz compatibles con Piper.
- Archivos `.onnx` y `.onnx.json` de cada voz.

## 🚀 Configuración

### 1. Preparar Piper TTS

Instalar y configurar Piper TTS en un entorno virtual de Python 3.13.

### 2. Añadir voces

Guardar los modelos de voz y sus archivos de configuración `.onnx.json` en la carpeta de voces de Piper.

Cada voz necesita sus dos archivos correspondientes.

### 3. Iniciar el puente local

Utilizar los scripts incluidos:

- `Start-Piper-Bridge.ps1`: inicia el servicio local.
- `Stop-Piper-Bridge.ps1`: detiene el servicio local.

El puente utiliza la dirección local:

`127.0.0.1:8712`

### 4. Configurar el plugin

En Voice Reminder:

1. Seleccionar el motor `Piper local`.
2. Elegir el modelo de voz deseado.
3. Iniciar el puente local de Piper.
4. Probar la reproducción de voz.

## 📦 Descargas

En este repositorio encontrarás:

- Código fuente personalizado.
- Paquete instalable del plugin.
- Versiones y actualizaciones.

## 🎯 Sobre el proyecto

Proyecto personal desarrollado de forma iterativa con ayuda de OpenAI Codex.

El objetivo es personalizar Voice Reminder, integrar síntesis de voz local y añadir funcionalidades adaptadas a mi flujo de trabajo.

## 📌 Versión

**v2.0.0**

## ⚠️ Aviso

Proyecto independiente y no oficial de Super Productivity.

El proyecto original pertenece a sus respectivos desarrolladores:

https://github.com/johannesjo/super-productivity
