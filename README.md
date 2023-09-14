# 05-virt-iaac
iaac


# _**Задача 1**_

**Опишите основные преимущества применения на практике IaaC-паттернов.**

CI (continuous integration) - позволяет обнаружить ошибки на раннем этапе, ткм самым сократить затраты на ее устранение в дальнейшем.

CD (continuous delivery) - позволяет легко разворачивать и добавлять изменения, что делает процесс сборки более стабильным и оперативным.

CD (continuous deployment) - позволяет автоматизировать развертывание, что значительно упрощает процесс запуска в продакшн.

**Какой из принципов IaaC является основополагающим?**

Принцип создания/настройки инфраструктуры аналогично процессу разработки ПО.

# _**Задача 2**_

**Чем Ansible выгодно отличается от других систем управление конфигурациями?**

Отстутствие необходимости установки агентов на целевые хосты для управления и относительная простота использования.

**Какой, на ваш взгляд, метод работы систем конфигурации более надёжный — push или pull?**
Pull, так как отсутсвует единая точка хранения данных и риск полной потери данных ниже.

# _**Задача 3**_

Установите на личный компьютер:

VirtualBox,
Vagrant,
Terraform,
Ansible.
Приложите вывод команд установленных версий каждой из программ, оформленный в Markdown.

<img src= "https://github.com/yarkuliko3/05-virt-iaac/blob/main/Screenshot%20from%202023-09-14%2015-20-58.png"/>

```sh
ansible --version
ansible 2.10.8
  config file = None
  configured module search path = ['/home/yaroslav/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python3/dist-packages/ansible
  executable location = /usr/bin/ansible
  python version = 3.10.12 (main, Jun 11 2023, 05:26:28) [GCC 11.4.0]

vagrant -v
Vagrant 2.2.19
terraform -v
Terraform v1.5.7
on linux_amd64
vboxmanage -v
6.1.38_Ubuntur153438
```


# _**Задача 4**_
Воспроизведите практическую часть лекции самостоятельно.

Создайте виртуальную машину.
Зайдите внутрь ВМ, убедитесь, что Docker установлен с помощью команды

![Ответ](https://github.com/yarkuliko3/05-virt-iaac/blob/main/Screenshot%20from%202023-09-14%2012-14-01.png?raw=true)



