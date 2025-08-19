1. Добавить ssh-ключ на сервер для установки openldap
2. В файле host.txt прописать корректный ip адрес и имя пользователя
3. Запустить ansible-playbook openldap.yml

4. Проверить на сервере с openldap
   ldapsearch -x -b "dc=unosoft" -D "cn=admin,dc=unosoft" -w adminpassword
5. Результат на скриншоте (images/snapshot.png)
