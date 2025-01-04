# Установка Linux

!!! warning "Вы разделили свою microSD карту?"
    Этот гайд предполагает, что вы следовали гайду NH-Server до этого момента, и ваша microSD карта должна быть разделена соответствующим образом. Если вы этого не сделали, ознакомьтесь с [этой страницей](../user_guide/all/partitioning_sd_syscfw.md) нашего руководства.

Linux 4 Switch — это дочерний проект Switchroot Android, использующий схожее ядро, но предоставляющий различные дистрибутивы Linux. На данный момент доступны следующие дистрибутивы:

- Ubuntu Bionic (поддерживается CTCaer, основным разработчиком как ядра L4S, так и Hekate — это самый стабильный и поддерживаемый дистрибутив)

- Ubuntu Jammy (поддерживается theofficialgman, одним из главных разработчиков программы установки L4T Megascript)

- Fedora 39 (поддерживается azkali, разработчиком ядра L4S)

- Lakka 5.x (поддерживается gavin_darkglider, разработчиком ядра L4S и поддержкой Lakka)

!!! info "Ищете Arch?"
    К сожалению, L4S Arch Linux устарел после изменения xorg ABI, которое нарушает совместимость с BSP Tegra210.

### **Установка**
Чтобы установить дистрибутив L4S, следуйте официальному руководству, начиная с [0. Дистрибутивы Linux](https://wiki.switchroot.org/wiki/linux/linux-distributions).

- **Примечание:** Вы можете пропустить раздел о выполнение раздела microSD карты, так как вы уже разделили карту в ходе руководства NH-Server. Начните с шага 4 в разделе [Установка](https://wiki.switchroot.org/wiki/linux/linux-install-update-guide#installation).

-----

Эта страница была создана в сотрудничестве с `makinbacon21` на Discord. См. сворачиваемый раздел ниже для поддерживающих команду L4S.

??? note "Сотрудники проекта L4S (Android / Linux)"
    Если хотите, вы можете поддержать людей, которые сделали этот проект возможным, используя следующие ссылки.

    - CTCaer (разработчик Linux и низкоуровневых систем, поддержка Hekate)
    [https://www.patreon.com/ctcaer](https://www.patreon.com/ctcaer)

    - Azkali (разработчик Linux и низкоуровневых систем)
    [https://www.patreon.com/azkali](https://www.patreon.com/azkali)

    - gavin_darkglider (разработчик Linux и Lakka)
    [https://paypal.me/gavindarkglider](https://paypal.me/gavindarkglider)

    - ave (инфраструктура и хостинг)
    [https://patreon.com/aveao](https://patreon.com/aveao)
