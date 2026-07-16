<!-- # EasyNetwork [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@EasyNetworkVPN) [![Telegram](https://img.shields.io/badge/Telegram-0088cc?style=flat&logo=telegram&logoColor=white)](https://t.me/easynetpro) -->

> [!TIP]
> **Рекомендуемые VPS-хостинги**
>
> - **AdminVPS** — https://vk.cc/cRBFB3  
>   🎁 Промокод **`GIT`** — скидка **60% на первый месяц**.
>
> - **TWCloud** — https://vk.cc/cZiTCl  
>   🎁 Промокод **`EASY2X`** — удвоение первого пополнения баланса (активируйте промокод **до первого пополнения**). Максимальная сумма удвоения — **50 000 ₽**.
>
> - **Fornex** — https://vk.cc/cWMNwQ  
>   🎁 Скидка уже **встроена в ссылку**, промокод вводить не нужно.

## Маршруты для роутера Keenetic

| Тип | Ссылка |
|-----|--------|
| **Глобальные маршруты** | [GitHub](https://github.com/RockBlack-VPN/ip-address/tree/main/Global) |
| **YouTube** (если тормозит) | [GitHub](https://github.com/RockBlack-VPN/ip-address/tree/main/Global/Youtube) |
| **Российские сервисы** | [GitHub](https://github.com/RockBlack-VPN/ip-address/tree/main/RU-RU) |
| **Доменные маршруты** | [GitHub](https://github.com/v2fly/domain-list-community/tree/master/data) |

---

## OpenVPN

📖 **[Полная инструкция по OpenVPN](https://github.com/ryderams/OpenVPN-ru)**

### Установка

```bash
wget -O openvpn.sh https://get.vpnsetup.net/ovpn
sudo bash openvpn.sh --auto
```

### Управление клиентами

**Создать нового клиента** (например, `client1`):
```bash
sudo bash openvpn.sh --addclient client1
```

**Удалить клиента** (например, `client1`):
```bash
sudo bash openvpn.sh --revokeclient client1
```

---

## 3X-UI

### 1. Базовый скрипт

```bash
bash <(curl -Ls https://raw.githubusercontent.com/MHSanaei/3x-ui/refs/tags/v2.6.0/install.sh)
```

### 2. 3X-UI Pro с панелью REALITY Требуется домен + sub домен.

```bash
sudo su -c "bash <(wget -qO- https://raw.githubusercontent.com/mozaroc/x-ui-pro/refs/heads/master/x-ui-pro.sh) -install yes"
```
🔧 **[Полная инструкция по установке 3X-UI Pro(сайт может быть ограничен в вашем регионе)](https://vk.cc/cRG1KM)**

> Этот скрипт устанавливает **3X-UI Pro** с поддержкой:
> - 📡 Панель REALITY
> - 🌐 WebSocket
> - 🔌 Входящие соединения (inbounds) на порту 443

---

**Все скрипты взяты из официальных GitHub репозиториев.**


