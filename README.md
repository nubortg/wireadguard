## Описание:
WireHole — это комбинация докер контейнеров WireGuard, Adguard Home и Unbound с целью предоставления пользователям возможности
быстро и легко создавать и развертывать лично управляемые полные или разделенные туннели WireGuard VPN
с возможностями блокировки рекламы (через Adguard Home) и Кэширование DNS с дополнительными параметрами конфиденциальности (через Unbound).

## Быстрый запуск
```shell
git clone https://github.com/nubortg/wireadguard.git &
cd wireadguard &
docker-compose up -d &
cat wireguard/peer1/peer1.conf
```
