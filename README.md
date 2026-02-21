# 🚀 Instalacion de PNETLABv6

Instalador automatizado para configurar Ubuntu Server con PNETLab v6 e iShare2 CLI, optimizado para laboratorios técnicos.

## 📦 Características:
- Instalacion de Ubuntu 20.04.6 LTS (Focal Fossa)
- Instalación de PNETLab v6.0.0-103

## 🧰 Requisitos

- Ubuntu Server Ubuntu 20.04.6 LTS (Focal Fossa) [Link](https://releases.ubuntu.com/focal/)
- Creacion de VM en VMware Workstation Pro:
  * Espacion Disco Duro 100GB o Superior
  * Configuracion de Tarjeta de red modo NAT.
  * Capacidad de RAM 8GB o Superior
  * Activacion de Caracteristica Procesador:
    - Virtualize Intel VT-x/EPT or AMD-V/RVI
 <img width="736" height="204" alt="{DF384D60-B86D-4515-8443-568AD67964E4}" src="https://github.com/user-attachments/assets/502d5f8e-2f66-485e-a339-7cd2bb9bb9c7" />

## ⚙️ Configuracion de VM y OS

- Instalacion de Ubuntu 20.04.6 LTS (Focal Fossa):
  * Instalar OS y no Actualizar.
  * Configurarion de Segmento de Red
    - DHCP o Estatico
  * Creacion de Usuario:
    - Usuario: pnet
    - Password: pnet
    - Hostname: pnetlab 

# 🚀 Instalacion de PNETLABv6

```shell
git clone https://github.com/CASMITPro/PNETLABv6.git
cd PNETLABv6
ls -la

```
#### Descargar estas dependencias:
una vez clonado el repositorio, favor descargar este archivo, descomprimir y copia todo en la carpeta del proyecto PNETLABv6, esto trae dependencias de binarios offline, lo cual agiliza el proceso de instalacion:
<img width="882" height="364" alt="image" src="https://github.com/user-attachments/assets/8eafdcc4-5c75-46db-b647-9d7b0f6d9238" />
<img width="787" height="830" alt="image" src="https://github.com/user-attachments/assets/819f265c-164a-404d-b087-1743ae53d8b5" />
https://bit.ly/pnetlab-ajustado

## Una vez copiada la informacion, proceder con brindar los permisos de ejecucion al scritp y ejecutar el mismo:
```shell
sudo chmod +x install_pnetlab_v6.sh
sudo ./install_pnetlab_v6.sh

```
### Luego de esto realizar un reinicio de la VM.
```shell
sudo reboot

```

<img width="1176" height="743" alt="image" src="https://github.com/user-attachments/assets/ce44c920-b78c-4336-ab5f-f0ebd5f08b35" />

## Descargas de Imagenes para Router, Switch, Servidores, etc:
<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/5d95cd70-778b-4e79-aa3b-e1261b7b1340" />

https://cios.dhitechnical.com/EVE-NG_IMAGE_PACK/

- Usuario: cios
- Contraseña: SuperSecretPassword

# 🚀 A Disfrutar PNETLab version 6.0.0-103!!!!!
