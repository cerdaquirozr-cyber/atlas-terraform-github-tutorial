# Tutorial de Terraform con GitHub (Fork del Atlas Terraform GitHub Tutorial)

![Terraform Logo](https://www.hashicorp.com/_next/image?url=https%3A%2F%2Fwww.datocms-assets.com%2F2885%2F1629941242-terraform-primary.svg&w=384&q=75)  
*(Fork actualizado de un repo antiguo de HashiCorp)*

Este repositorio es un **fork** del antiguo tutorial `hashicorp/atlas-terraform-github-tutorial` (de hace +10 años).  
El original mostraba cómo usar **Terraform** junto con **HashiCorp Atlas** (la plataforma predecesora de **Terraform Cloud**) y GitHub para versionar y aplicar infraestructura como código (IaC).

**Atlas ya no existe** (fue reemplazado por Terraform Cloud / HCP Terraform en 2019), por lo que este repo está **archivado y desactualizado**, pero sirve como ejemplo básico de configuración Terraform.

## ¿Qué contiene?

Archivos principales:
- `providers.tf` → Configuración de proveedores (probablemente AWS u otro cloud de la época)
- `example.tf` → Recursos de ejemplo (quizá una instancia EC2 o similar)
- `outputs.tf` → Outputs para ver resultados después del `terraform apply`
- `.gitignore` → Ignora archivos típicos de Terraform

## Advertencia importante

Este código es de **2015 aprox.** → No lo uses en producción sin actualizarlo.  
Las versiones antiguas de Terraform y providers pueden tener vulnerabilidades o sintaxis obsoleta.

Recomendación 2026:  
Usa la versión más reciente de Terraform (≥ 1.14 o superior) y migra a **Terraform Cloud** o **OpenTofu** si quieres algo open source.

## Cómo usarlo hoy (pasos actualizados)

1. Clona tu fork:
   ```bash
   git clone https://github.com/cerdaquirozrz-cyber/atlas-terraform-github-tutorial.git
   cd atlas-terraform-github-tutorial
