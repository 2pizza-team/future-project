# pizzeria

#### 1. Зарегистрируйтесь на Гитхабе

Если у вас ещё нет аккаунта на [github.com](https://github.com/join), скорее зарегистрируйтесь.
Сообщите свою почту и аккаунт GitHub разработчикам. 

#### 2. Создайте форк

Откройте репозиторий и нажмите кнопку «Fork» в правом верхнем углу. Главный репозиторий будет скопирован в ваш аккаунт.

#### 3. Клонируйте репозиторий на свой компьютер

Будьте внимательны: нужно клонировать свой репозиторий (форк), а не главный репозиторий. Также обратите внимание, что клонировать репозиторий нужно через SSH, а не через HTTPS. Нажмите зелёную кнопку в правой части экрана, чтобы скопировать SSH-адрес вашего репозитория.

Клонировать репозиторий можно так:

```
git clone SSH-адрес_вашего_форка
```

Команда клонирует репозиторий на ваш компьютер и подготовит всё необходимое для старта работы.

#### 4. Создаете ветку с названием вашей фамилии

Создавать ветку нужно так:

```
git checkout -b "фамилия"
```

#### 5. После написания кода сделайте commit и push в вашу ветку.

```
git add . 
git commit -m "название коммита"
git push origin навазние вашей ветки
```

#### 6. Создайте пулл реквест в master-репозиторий в ветку под названием "test" и ждите ответа.

В случае если разрабочтики найдут ошибки они попросят вас исправить их и нужно будет повторить п.5. Разработчики ответственны за просмотр очереди pull-request'ов. Как правило, они отвечают в течение суток, в противном случае свяжитесь по почте: 2pizza.vdk@gmail.com


### 7. Так же для дальнейшей работы необходимо регулярно получать обновления с master-репризиторию в ваш форк, для этого необходимо добавить его в ваш локальный с помощью команды:

Делать
```
git remote add pizzeria git@github.com:2pizza-team/pizzeria.git
```

### 8. Поздравляем! Теперь вы можете получать обновления из master-репризитория!

Для этого нужно написать всего 3 команды:

```
git checkout master
git pull pizzeria master
git push origin master

```

### 9. Продолжайте свою работу! Вы прекрасно справляетесь


