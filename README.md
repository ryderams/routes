# Keenetic, OpenVPN, VLESS, WG

## VPS Хостинг

- [AdminVPS](https://my.adminvps.ru/aff.php?aff=28722) (Промокод **GIT** — скидка 60%)
- [AEZA](https://aeza.net/?ref=537145) — оплата хостинга за UST
- [is*Hosting](https://ishosting.com/affiliate/NTAxNCM2) — если вам нужна определенная страна (36 стран)


## Маршруты для роутера Keenetic

[Глобальные маршруты](https://github.com/RockBlack-VPN/ip-address/tree/main/Global) | [YouTube (если тормозит)](https://github.com/RockBlack-VPN/ip-address/tree/main/Global/Youtube) | [Для российских сервисов](https://github.com/RockBlack-VPN/ip-address/tree/main/RU-RU)



### OpenVPN
```bash
wget -O openvpn.sh https://get.vpnsetup.net/ovpn
sudo bash openvpn.sh --auto
```

**Другие ключи для OpenVPN:**
- Создать нового клиента (например, client1):
	```bash
	sudo bash openvpn.sh --addclient client1
	```
- Удалить клиента (например, client1):
	```bash
	sudo bash openvpn.sh --delclient client1
	```


### 3X-UI
```bash
bash <(curl -Ls https://raw.githubusercontent.com/MHSanaei/3x-ui/refs/tags/v2.6.0/install.sh)
```

> В панели 3X-UI можно создавать клиентов WireGuard (WG) через удобный веб-интерфейс.

#### 3X-UI pro с панелью REALITY и входящими на 443 порту

[Инструкция по установке 3X-UI pro (панель REALITY, inbounds на 443)](https://scarce-hole-1e2.notion.site/3X-UI-pro-with-REALITY-panel-and-inbounds-3X-UI-pro-with-REALITY-panel-and-inbounds-on-port-443-on-10d1666462e48085be0fee4c136ce417)

> Этот скрипт устанавливает 3X-UI pro с поддержкой панели REALITY и входящими соединениями (inbounds) на порту 443. Подходит для продвинутой настройки и обхода блокировок.

