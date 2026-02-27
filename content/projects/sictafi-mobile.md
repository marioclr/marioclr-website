---
title: "SICTAFI Mobile"
date: 2014-01-01
summary: "Aplicación móvil Android para inventario y geolocalización de bienes públicos con sincronización segura hacia sistema central en ASP.NET."
organization: "Jibda & Asociados"
role: "Lider técnico - Web & Mobile"
period: "2016–2017"
tags: ["Android", "Java", "ASP.NET", "SQL Server", "Arquitectura Distribuida"]
featured: false
---

## Executive Summary

SICTAFI Mobile fue una iniciativa tecnológica desarrollada para habilitar levantamientos de inventario de bienes públicos directamente en campo, mediante dispositivos móviles Android tipo Toughbook.

El sistema permitió digitalizar procesos censales que anteriormente dependían de formatos manuales, habilitando captura georreferenciada, registro fotográfico y sincronización segura hacia el sistema central SICTAFI.

Este proyecto fortaleció la capacidad operativa de gobiernos estatales y municipales para mantener padrones actualizados de activos públicos destinados a procesos de aseguramiento institucional.

---

## Stack Tecnológico

- Android nativo (Java)
- SQLite (persistencia local offline)
- Servicios Web en .NET (C#)
- ASP.NET (Sistema Central)
- Microsoft SQL Server
- Infraestructura Windows Server + IIS

---

## Contexto Tecnológico y Operacional

El ecosistema existente incluía un sistema central robusto (SICTAFI Central) operando en infraestructura Microsoft.

El reto principal consistía en:

- Operación en zonas sin conectividad
- Sincronización de información de más de 200 dispositivos
- Integridad de datos geográficos y fotográficos
- Seguridad en transmisión de información sensible

El sistema debía operar en múltiples entornos estatales con diferentes condiciones de conectividad y logística.

---

## Arquitectura y Decisiones Técnicas Clave

El modelo arquitectónico se diseñó bajo un enfoque **offline-first**, priorizando resiliencia operativa en campo.

Principios implementados:

- Persistencia local completa mediante SQLite.
- Sincronización diferida con control de integridad.
- Servicios web seguros desarrollados en .NET (C#).
- Validación estructural de datos antes de transmisión.
- Manejo de archivos multimedia (fotografías) integrados al flujo de sincronización.

Arquitectura general:

Dispositivo Android (SQLite)  
↓  
Servicios Web Seguros (.NET C#)  
↓  
SICTAFI Central (ASP.NET + SQL Server)

Participé directamente en:

- Diseño de arquitectura móvil.
- Desarrollo nativo Android.
- Diseño y desarrollo de servicios web.
- Modelado de sincronización de datos.
- Integración con base de datos central.

---

## Modelo Operativo del Sistema

1. Levantamiento en campo mediante tabletas.
2. Captura de datos técnicos del activo.
3. Registro fotográfico y geolocalización.
4. Persistencia local sin necesidad de conectividad.
5. Sincronización posterior al detectar red disponible.
6. Validación y consolidación en sistema central.

El sistema soportó operaciones simultáneas en distintos estados de la república.

---

## Impacto Institucional

- Digitalización del inventario de bienes públicos.
- Reducción de errores manuales.
- Mejora en trazabilidad de activos.
- Base sólida para procesos de aseguramiento mediante pólizas.
- Operación estable de cientos de dispositivos concurrentes.

---

## Evolución Profesional

Este proyecto consolidó mi experiencia en:

- Arquitectura distribuida.
- Diseño de sistemas offline-first.
- Integración entre plataformas heterogéneas.
- Desarrollo móvil empresarial.
- Implementación de soluciones tecnológicas en sector público.