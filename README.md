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
![image](https://github.com/user-attachments/assets/6f6aaa9b-e837-47ac-ad66-d916ae2ca62f)
![image](https://github.com/user-attachments/assets/4bc13bc5-3e8c-4f10-a2ba-d5b1548e8167)


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
  ![image](https://github.com/user-attachments/assets/e7eb8235-a107-4bd8-b525-1266797e790c)

- Des de webmin actualitza un paquet.
  ![image](https://github.com/user-attachments/assets/3ce7a5ed-ed9b-43bd-840b-39098a9d71b8)
![image](https://github.com/user-attachments/assets/c267395f-f19e-4101-ae76-9bbed4e6c488)

- Utilitza webmin per instal·lar un joc de apt.
 ![image](https://github.com/user-attachments/assets/866bd7cc-049f-41cb-ba7b-6d412d0a76e5)
![image](https://github.com/user-attachments/assets/a3d350cd-2ab7-413f-bd9b-408dbb0c7370)

- Utilitza webmin per instal·lar gimp de apt
  ![image](https://github.com/user-attachments/assets/1836b0b8-0628-41dc-a2b5-747e52f240a1)
![image](https://github.com/user-attachments/assets/2617f761-cd58-4528-8144-8d590dd5f068)

- Utilitza webmin per desinatl·lar el joc que heu instal·lat abans.
![image](https://github.com/user-attachments/assets/01bea73d-b629-4006-9661-9e1acc5caa30)

![image](https://github.com/user-attachments/assets/d87aa613-35fd-40bb-850f-0be8a5555d60)


## 4.- Serveis

- Utilitza webmin per mostrar els serveis que s'inicien amb el sistema.
  ![image](https://github.com/user-attachments/assets/46982741-de42-424d-b0b1-a08e6608b9c8)

- Utilitza webmin per mostrar els serveis que estan actius.
  ![image](https://github.com/user-attachments/assets/300cdf75-cf8b-4a23-9a58-7eece390b968)

- Utilitza webmin per mostrar l'estat del servidor Apache.
  ![image](https://github.com/user-attachments/assets/0492411d-95b9-4e01-8f28-421ca910a4ef)

- Utilitza webmin per aturar Apache.
![image](https://github.com/user-attachments/assets/ea3c5249-5198-40ec-b71f-dd17022b6b42)


  ![image](https://github.com/user-attachments/assets/f3cf3bf5-361e-4b50-a72a-b63fd1de4c3d)

- Utilitza webmin per mostrar l'estat del servidor Apache apagat.
![image](https://github.com/user-attachments/assets/c45356bf-e4e8-4345-9625-700eea0ab4d6)

- Utilitza webmin per reiniciar Apache
  ![image](https://github.com/user-attachments/assets/934cdc03-d92b-4887-97c5-074dcd37b598)

- Utilitza webmin per mostrar l'estat del servidor Apache reiniciat.
 ![image](https://github.com/user-attachments/assets/934cdc03-d92b-4887-97c5-074dcd37b598)

## 5.- Quotes de disc
![image](https://github.com/user-attachments/assets/21bc5ef0-9afa-431c-aa54-4bef639b3329)
![image](https://github.com/user-attachments/assets/32208d77-8c6a-42c3-9d07-89bfe40e23b2)
![image](https://github.com/user-attachments/assets/02d17ace-25cc-4036-a9a3-2f08dddf45f2)
![image](https://github.com/user-attachments/assets/c5d541cb-5448-432e-ab8b-1c4361314c67)
![image](https://github.com/user-attachments/assets/6ed62dfd-70c7-4e76-8896-4518abaa9b28)
![image](https://github.com/user-attachments/assets/ef337b66-c909-441b-8ba9-b77b0a618cab)
![image](https://github.com/user-attachments/assets/00957074-946b-4b6a-b227-e3143984f9de)
![image](https://github.com/user-attachments/assets/41788981-0315-4b89-b720-b1bd5583fef1)


## 6.- Còpies de seguretat

![image](https://github.com/user-attachments/assets/a7e8270d-fc43-4562-8ca8-152e92ce2a55)
![image](https://github.com/user-attachments/assets/c7ce1290-e66e-49e0-af4c-e4883fff9a6f)
![image](https://github.com/user-attachments/assets/18644c13-0817-4d95-86bd-669166f1e3d5)
![image](https://github.com/user-attachments/assets/0ca5190d-7fe6-4cfa-b32b-86779b2b83a7)


## 7.- Compartició

- Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "area_public_X" per a usuaris sense autenticar en forma de lectura i escriptura
![image](https://github.com/user-attachments/assets/814a527e-c0e4-4772-a501-aecd9ae9f1e8)
  ![image](https://github.com/user-attachments/assets/d1a57295-87e0-468e-8999-441ded5c04eb)
![image](https://github.com/user-attachments/assets/1d92ca5d-dcbb-4159-b0b0-614ed8569a1d)
![image](https://github.com/user-attachments/assets/cddf018d-adfd-4d6b-abf8-e37ec9bb0308)
![image](https://github.com/user-attachments/assets/26ad28fb-d13d-4097-85f5-295ce8ee74b9)
![image](https://github.com/user-attachments/assets/c0b37270-4592-44ae-9c96-d654a9bfcbfe)
![image](https://github.com/user-attachments/assets/5865476d-1fb7-4cf1-955e-acfe4c397b2a)


- Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "pontaeri_privat_X" per a usuaris _X i techno només de lectura.
  ![image](https://github.com/user-attachments/assets/33231843-9fb6-468e-bab8-fcb012855dd4)
![image](https://github.com/user-attachments/assets/34a11bae-a0db-4fb3-bd54-18b220c8d7a4)
![image](https://github.com/user-attachments/assets/697b0c39-b115-424c-a860-dc677e37b5c8)
![image](https://github.com/user-attachments/assets/3f3bc1ae-1b62-43fc-944c-df22fc1dcd16)
![image](https://github.com/user-attachments/assets/c6df4650-074f-44f9-8b35-3d07146d4e32)

- Comprovar des de Windows que aquests recursos funcionen.
![image](https://github.com/user-attachments/assets/cdf05273-e158-4040-b9cc-b36a1c57662c)
![image](https://github.com/user-attachments/assets/aebb7e31-ee57-445b-b1c1-e0a152c7ebf1)
![image](https://github.com/user-attachments/assets/c6e0a7c8-5b8f-4168-b8ba-c0f34d86de05)
![image](https://github.com/user-attachments/assets/0e050843-ff4d-49c6-99e1-589ba0a04a76)
![image](https://github.com/user-attachments/assets/41e30533-2028-468a-9048-77c64d70a491)

![image](https://github.com/user-attachments/assets/979954ca-f4af-4308-a163-a35bd81f14ee)
![image](https://github.com/user-attachments/assets/db317c31-f1eb-419b-8f56-091e580f8b54)
![image](https://github.com/user-attachments/assets/f19793c8-e316-485a-b41d-c21808e89bbd)
![Captura desde 2025-04-03 12-31-25](https://github.com/user-attachments/assets/1eb2a364-a0ed-4129-9f99-59290a58a961)
![Captura desde 2025-04-03 12-31-29](https://github.com/user-attachments/assets/44a0d10d-b558-4139-88fb-d45e03d79acc)

![image](https://github.com/user-attachments/assets/284ae8c4-2dcd-43bc-a8ee-b0dff0a6da44)
![image](https://github.com/user-attachments/assets/c499c1c8-bb79-41c1-ae27-b6288ed79b48)
![image](https://github.com/user-attachments/assets/a996e385-04c1-43cf-9527-de90bbe92a74)

![image](https://github.com/user-attachments/assets/26ae2de8-3267-49d6-8944-d03b98410fd0)

![image](https://github.com/user-attachments/assets/c499c1c8-bb79-41c1-ae27-b6288ed79b48)
![image](https://github.com/user-attachments/assets/a996e385-04c1-43cf-9527-de90bbe92a74)

![image](https://github.com/user-attachments/assets/26ae2de8-3267-49d6-8944-d03b98410fd0)


