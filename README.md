# Instalación de ACCAIS-BD

Instalar el certificado ACCAIS (obligatorio)

Antes de instalar la aplicación, Windows debe confiar en el publicador.
Siga estos pasos:
  1. Abrir el archivo ACCAISCert.cer
  2. Seleccionar Instalar certificado
  3. Elegir Equipo local
    (Si no tiene permisos, seleccione Usuario actual)
  4. Seleccionar Colocar todos los certificados en el siguiente almacén
  5. Hacer clic en Examinar…
  6. Elegir Entidades de certificación raíz de confianza
  7. Aceptar la advertencia y finalizar la instalación del certificado

Instalar la aplicación ACCAIS-BD

  1. Abrir ACCAIS-BD.msix
  2. Hacer clic en Instalar

Problemas comunes
1. Error 0x800B0109 — El certificado no es de confianza

    El certificado no se instaló correctamente. Debe colocarse en el almacén: Entidades de certificación raíz de confianza (Preferentemente en Equipo local).

2. El instalador no se abre

    Activar "Sideload apps" o "Modo de desarrollador"
