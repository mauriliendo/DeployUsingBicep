# 🚀 Despliegue de Infraestructura en Azure con Azure DevOps

Este proyecto fue creado utilizando **Azure** para automatizar el despliegue de una **máquina virtual** y su infraestructura asociada. El pipeline en **Azure DevOps** despliega recursos clave como discos, NICs, NSG, IP pública, y VNet, todo a través de **Bicep**.

## 🔧 Descripción del Proyecto

Este proyecto consta de un pipeline de **Azure DevOps** que automatiza tres etapas principales:

1. **Validación de Infraestructura**: Se valida la plantilla Bicep antes de realizar el despliegue.
2. **Despliegue de Infraestructura**: Se despliegan los recursos necesarios en Azure (VM, discos, NIC, NSG, IP pública, y VNet).
3. **Instalación de Herramientas Base**: Después de desplegar la infraestructura, se ejecuta un script para instalar herramientas esenciales como **Git**, **Visual Studio Code** y **7-Zip** en la máquina virtual.

### Recursos Desplegados

- **Máquina Virtual** (VM)
- **Disco** (para la VM)
- **Interfaz de Red** (NIC)
- **Grupo de Seguridad de Red** (NSG)
- **IP Pública** (para acceso a la VM)
- **Red Virtual** (VNet)
