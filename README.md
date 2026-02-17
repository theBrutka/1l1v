Аспект А1-1 – не выполнен

  <img width="639" height="136" alt="image" src="https://github.com/user-attachments/assets/333f6bd9-7ab6-435c-8afb-2c8b62554efb" />

Комментарий: на ISP доменное имя не совпадает с текстом задания

Аспект А1-2 – выполнен

<img width="974" height="475" alt="image" src="https://github.com/user-attachments/assets/81dd576c-bece-4c4f-82c9-ca612b4077be" />

<img width="974" height="787" alt="image" src="https://github.com/user-attachments/assets/ed272a14-dc85-46ad-90c5-40600cf611e4" />

<img width="974" height="223" alt="image" src="https://github.com/user-attachments/assets/56e249fe-6a27-44d3-b77b-c4ddc7ef92db" />

<img width="974" height="249" alt="image" src="https://github.com/user-attachments/assets/c7ad503d-d386-4a3c-a0b8-2256f8076b87" />

<img width="974" height="528" alt="image" src="https://github.com/user-attachments/assets/1ffa10f9-e15e-4b1f-b2bc-5c7088e44dca" />

<img width="974" height="486" alt="image" src="https://github.com/user-attachments/assets/64656c33-a49f-445a-8775-8a8dcbd9f142" />

Комментарий: расчет ip адресов был произведен верно

 

Аспект А1-3 – не выполнен

<img width="738" height="209" alt="image" src="https://github.com/user-attachments/assets/d4440103-64c1-44c1-8634-bce9f69132c3" />

Комментарий: интерфейс vlan200 имеет id vlan2000


Аспект А1-4 – выполнен
 
<img width="974" height="718" alt="image" src="https://github.com/user-attachments/assets/53385ff2-a1c6-4c25-9510-270c8b965e80" />

Комментарий: на HQ-RTR и BR-RTR корректно настроен nftables, в nat настроено правило masquerade,что подтверждает использование технологии PAT для выхода в интернет


Аспект А1-5 – выполнен

 <img width="974" height="721" alt="image" src="https://github.com/user-attachments/assets/f9097266-5ac3-4bac-b577-451705094a16" />

Комментарий: устройства офиса branc не используют PAT для выхода в Интернет





Аспект А1-6 –  выполнен nmcli HQ-RTR

 <img width="894" height="598" alt="image" src="https://github.com/user-attachments/assets/d5a1a76f-c745-424d-8248-ba7916d9ce0b" />

Комментарий: есть туннель gretap добавленный в bridge с именем gre-tun











Аспект А1-7 –  не выполнен

 <img width="974" height="1183" alt="image" src="https://github.com/user-attachments/assets/f505a379-3ea6-4b7b-93d8-7672b5233aab" />

Комментарий: установлено соседство не только по туннелю но и по другим интерфейсам  
Аспект 

А1-8 –  не выполнен

 <img width="618" height="1115" alt="image" src="https://github.com/user-attachments/assets/e7fa55b2-0ab4-417d-97ef-3fe79c40ce06" />

Комментарий: на HQ-RTR не правильно настроен passive-interface enp7sl вместо enp7s1







Аспект А1-9 –  выполнен

 <img width="554" height="1046" alt="image" src="https://github.com/user-attachments/assets/9d76b994-de0e-4a81-a746-ba6d261833d2" />

Комментарий: аутентификация настроена верно по ключам  


Аспект А1-11 – выполнен

 <img width="974" height="406" alt="image" src="https://github.com/user-attachments/assets/9ca244b1-f001-4777-8666-396eb3fdcc86" />

Комментарий: DHCP установлен и функционирует 


Аспект А1-12 – не выполнен
 
 <img width="864" height="138" alt="image" src="https://github.com/user-attachments/assets/3beb7cbf-03f4-458b-bb2b-01c5bba7e6a7" />

<img width="409" height="59" alt="image" src="https://github.com/user-attachments/assets/17605fbc-28ae-41d6-8cd4-4687cf020ddf" />

Комментарий: не правильное доменное имя, на HQ-CLI домен настроен вручную 

Аспект А1-13 – выполнен

 <img width="974" height="354" alt="image" src="https://github.com/user-attachments/assets/4c4a136b-0298-4238-8b01-4d58ae24fc8a" />

Комментарий: в качестве dns используется dnsmasq


Аспект А1-14 – выполнен cat /etc/dnsmasq.conf
 
 <img width="974" height="45" alt="image" src="https://github.com/user-attachments/assets/f1dd48ef-c0ac-4013-a124-25bb1e7aad15" />

<img width="714" height="178" alt="image" src="https://github.com/user-attachments/assets/163c176d-3415-4183-9710-c57d1be9772e" />

Комментарий: записи прямых зон разрешены и хранятся на HQ-SRV


Аспект А1-15– не выполнен
 
 <img width="974" height="54" alt="image" src="https://github.com/user-attachments/assets/a98546d8-3479-4a96-9e1e-40158f012c29" />

<img width="802" height="142" alt="image" src="https://github.com/user-attachments/assets/3b803699-9d57-452d-8ecc-8c734441a4fb" />

Комментарий: обратные записи разрешаются но хранятся на HQ-SRV


Аспект А2-1 

 <img width="974" height="103" alt="image" src="https://github.com/user-attachments/assets/6022da64-987d-42a7-a3a5-4638c9104d35" />

<img width="974" height="110" alt="image" src="https://github.com/user-attachments/assets/34a607f8-4521-4ae4-9d6e-7e5cac23b659" />

Комментарий: присутствуют пользователи, имеющие права на исполнение sudo без пароля на BR-SRV и HQ-SRV


Аспект А2-2  – выполнен
 
 <img width="974" height="216" alt="image" src="https://github.com/user-attachments/assets/87c95c0d-e016-4c9d-8188-11092e48a33d" />

<img width="974" height="183" alt="image" src="https://github.com/user-attachments/assets/29393857-ef6a-4705-9d9a-21bdfd069708" />

Комментарий: на машинах созданы пользователи net_admin и у них есть права на исполнение sudo без пароля.


Аспект А2-3 – не выполнен

 <img width="974" height="427" alt="image" src="https://github.com/user-attachments/assets/2be094d0-0fa5-4d47-8da3-b6ce1eb82808" />

Комментарий: нет, параметр MaxAuthTries равен 1, хотя в конфиге установлено 2, но даже если в конфиге 2, то ssh применяет первый найденный параметр, после первой отбросит. Также разрешен вход для root.


Аспект А2-4 – не выполнен

 <img width="555" height="230" alt="image" src="https://github.com/user-attachments/assets/abdcf9fe-d992-4620-883b-f9468a76c5f1" />

Комментарий: не активирован ntp пакет, поэтому systemctl его не видит. 


Аспект А2-5 – выполнен

<img width="773" height="233" alt="image" src="https://github.com/user-attachments/assets/2ad15fb2-8227-4a9f-8095-7174a69b0ca4" />
 
Комментарий: Развертывание домена на BR-SRV осуществлено в соответствии с заданием 


Аспект А2-6 – выполнен

 <img width="974" height="401" alt="image" src="https://github.com/user-attachments/assets/014845a0-3e3b-4eeb-9758-7b877eb2998f" />

Комментарий: машина введена в домен пользователи аутентифицируются 


Аспект А2-7 – не выполнен

 <img width="856" height="64" alt="image" src="https://github.com/user-attachments/assets/766f38d1-71df-453d-b95c-3a7de358840d" />

Комментарий: настройка sudo не настроено, поэтому команды cat grep id не работают


Аспект А2-8 – не выполнен

 <img width="974" height="297" alt="image" src="https://github.com/user-attachments/assets/4aa18c64-9741-4e43-81e5-ad64f2ec1414" />

Комментарий: docker активен, не корректное название контейнера testappp вместо testapp


Аспект А2-9 – выполнен

 <img width="652" height="664" alt="image" src="https://github.com/user-attachments/assets/08af87d6-2c43-4d9c-9477-1f2d8d7dbdb8" />

Комментарий: все необходимые хосты перечисленны, инвентарь сформирован верно


Аспект А2-10 – выполнен

 <img width="974" height="276" alt="image" src="https://github.com/user-attachments/assets/5f0aa4d8-dc31-4f91-8d04-b6c37746e545" />

Комментарий: pong без ошибок кроме предупреждения о хосте вне задания


Аспект А2-12 – выполнен

 <img width="647" height="192" alt="image" src="https://github.com/user-attachments/assets/5e4e3a99-ae14-4639-b6e4-5a8a1315169b" />

Комментарий: Web приложение доступно и функционирует  веб аутентификацией в соответствии с заданием


Аспект А2-13 – не выполнен

 <img width="974" height="330" alt="image" src="https://github.com/user-attachments/assets/68df6c6a-f759-413f-839c-6f7a6df59e4b" />

Комментарий: проброс портов выполнен только для docker приложений


Аспект А2-14 – выполнен
grep -r "HQ-SRV" /etc/ - HQ-SRV

Аспект А2-15 – не выполнен

 <img width="658" height="142" alt="image" src="https://github.com/user-attachments/assets/f87a1ea2-4f1f-4ab2-9915-539fc325cc6b" />

Комментарий: вместо RAID0 создан RAID1




Аспект А2-16 – не выполнен

 <img width="974" height="236" alt="image" src="https://github.com/user-attachments/assets/f8ac3654-1b7a-4b3c-ad93-12c3f051d02b" />

Комментарий: монтирование осуществляется в /mnt/raid и создана ссылка на каталог, располагающаяся по пути /mnt/nfs, функционально отрабатывает как да
