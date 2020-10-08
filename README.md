# Настройка сервака

### 1. Создание юзеров

sudo adduser sammy


#### Создание группы

sudo addgroup groupname

sudo adduser username groupname

### 2. Настройка putty

* Connection->Data autologin
* Connection keepalives [5]

#### Создание SSH ключа

* Puttygen сохраняем паблик и приват кей
* Создаем в корневой директории папку .ssh, в нем файл authorized_keys
* Вставляем паблик кей ssh-rsa ...
* В putty SSH->auth сохраняем приват кей

### 3. Создание репозитория

#### 1. Создаем репозиторий
#### 2. На гите в настройках профиля SSH and GPG keys -> New SSH Keys
#### 3. Командой ``` ssh-keygen -t rsa -b 4096 -C "your_email@example.com" ``` генерируем SSH ключ
#### 4. Переходим и копируем ключ из ~/.ssh/id_rsa.pub
#### 5. Вставляем его в git

### 4. 
