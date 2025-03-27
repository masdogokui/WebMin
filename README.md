# WebMin
![image](https://github.com/user-attachments/assets/d8fb6075-6898-4514-a974-2940ee68c934)
# 1.- Crear i modificar usuaris
## Has de crear dos usuaris bakalao_X i techno_X on (X és el vostre cognom).

![Captura desde 2025-03-25 14-22-01](https://github.com/user-attachments/assets/56bae59b-5011-4e35-a384-cfe7a2ee0bb1)
![Captura desde 2025-03-25 14-26-43](https://github.com/user-attachments/assets/b5b44b4c-9727-4997-aff4-a296a639afc5)
![Captura desde 2025-03-25 14-28-55](https://github.com/user-attachments/assets/53dbf72a-46c9-4044-bf5c-f98157cfeeb5)
![Captura desde 2025-03-25 14-29-56](https://github.com/user-attachments/assets/146dbbfc-9a79-4681-8a75-c2f7909ff59f)
![image](https://github.com/user-attachments/assets/a36149f5-40cc-490d-a8dd-5c7ef0482219)


## Els usuaris et passaran el hash de la seva contrasenya, no la contrasenya real. (podeu fer servir openssl).
![image](https://github.com/user-attachments/assets/ab68b7ab-b196-4e37-b0da-d3beb295ce21)

## Cada usuari tindrà un directori a home igual al seu nom d'usuari.
![image](https://github.com/user-attachments/assets/bf920e85-3ad0-427d-8844-cd42bc708052)

![Captura desde 2025-03-25 14-42-34](https://github.com/user-attachments/assets/48dc89ad-a5aa-443e-9515-818d6ecfa494)

## Utilitzaran bash com a shell.
![image](https://github.com/user-attachments/assets/36ea6e77-fb9a-4c33-85d5-e181f0ef08b5)

## Els usuaris estaran dins del grup que tingui el seu mateix nom i dins del grup usuaris_empresa.
![image](https://github.com/user-attachments/assets/427834ef-6bdf-4c2d-a5f0-ad4bf6fc4d14)
![image](https://github.com/user-attachments/assets/5fab7ed5-d0b1-4062-a70b-1f9900420036)
![image](https://github.com/user-attachments/assets/e46c00bb-639b-4fea-918d-876ccce32a95)


## L'usuari techno no podrà fer login després del dia 31-03-2025.
![image](https://github.com/user-attachments/assets/99564a40-baa5-456b-b7f3-d6fc22ab3f09)

## Comproveu que els usuaris poden iniciar sessió.
![image](https://github.com/user-attachments/assets/f3137af2-cc68-411a-9bb8-eaca405bdcb9)
![image](https://github.com/user-attachments/assets/2ec0ac51-0767-43ee-90a8-ac4a5aa0e688)

## Canvia la data del sistema (utilitzant webmin) i comprova que techno no pot iniciar sessió si estem a dia 01-04-2025.
![image](https://github.com/user-attachments/assets/ce4e7ac8-d525-4fa1-adfe-1c7d737fe104)
![image](https://github.com/user-attachments/assets/45c04cc8-f75c-4782-bf14-6b82e8016caa)

## 2.- Programar tasques

- Programa una tasca que neteja els paquets de Linux que ja no s'utilitzen una vegada al mes.
  ![image](https://github.com/user-attachments/assets/1c958ad4-0321-44b7-a83b-0b0fa953f27f)

- Programa una tasca diaria que apaga l'ordinador a les 14:00.
![image](https://github.com/user-attachments/assets/2ed3ca42-296d-4962-8bd9-9d5261b42287)

- Comprova que funcionen (canvia dia i hora del sistema mitjançant webmin).
![image](https://github.com/user-attachments/assets/ae08ddd5-3196-4a6d-a807-680f1a6568e2)

  
## 3.- Instal·lació de software

- Utilitza webmin per mostrar quins paquets de software es podrien actualitzar.
- Des de webmin actualitza un paquet.
- Utilitza webmin per instal·lar un joc de apt.
- Utilitza webmin per instal·lar gimp de apt.
- Utilitza webmin per desinatl·lar el joc que heu instal·lat abans.

## 4.- Serveis

- Utilitza webmin per mostrar els serveis que s'inicien amb el sistema.
- Utilitza webmin per mostrar els serveis que estan actius.
- Utilitza webmin per mostrar l'estat del servidor Apache.
- Utilitza webmin per aturar Apache.
- Utilitza webmin per mostrar l'estat del servidor Apache apagat.
- Utilitza webmin per reiniciar Apache.
- Utilitza webmin per mostrar l'estat del servidor Apache reiniciat.

## 5.- Quotes de disc

Activa les quotes de disc pels usuaris amb la comanda: 

```
sudo apt install quota quotatool
```

- Utilitza webmin perquè l'usuari bakalao_X no pugui tenir més de 2 MB d'informació al disc.
- Comprova que el límit de la quota funciona.
- Utilitza webmin perquè l'usuari techno no pugui tenir més de 10 fitxers al disc.
- Comprova que el límit de la quota funciona.

## 6.- Còpies de seguretat

- Utilitzant el mòdul de Webmin Filesystem Backup fes una còpia de seguretat del directori /home al directori /backups (l'haureu de crear si no existeix).
- Modifica alguns fitxers de /home.
- Recupera la còpia de seguretat.
- Comprova que els fitxers de /home són els correctes.
- Programa una còpia de seguretat de /home/bakalao_X per els divendres a les 21:00.
- Esborra la còpia de seguretat programada anteriorment.

## 7.- Compartició

- Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "area_public_X" per a usuaris sense autenticar en forma de lectura i escriptura.
- Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "pontaeri_privat_X" per a usuaris _X i techno només de lectura.
- Comprovar des de Windows que aquests recursos funcionen.

