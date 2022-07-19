**#Установка**

Замените YOUR_ALCHEMY_HTTP_ADDRESS
```
ALCHEMY=YOUR_ALCHEMY_HTTP_ADDRESS
echo 'export ALCHEMY='$ALCHEMY >> $HOME/.bash_profile
```

Для установки ноды выполните однострочный скрипт установки:
```
wget -O starknet.sh https://raw.githubusercontent.com/MannanovIN/Nodes/main/StarkNet/starknet.sh && chmod +x starknet.sh && ./starknet.sh
```


**#Обновление(сразу после установки не нужно выполнять)**
```
curl -s https://raw.githubusercontent.com/MannanovIN/Nodes/main/StarkNet/update_starknet.sh | bash
```
