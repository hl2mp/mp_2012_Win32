Game: https://store.steampowered.com/app/320/HalfLife_2_Deathmatch/

Demo Server: 176.99.75.84:27400 (RU)

Demo Server: 185.169.234.121:27015 (UK, London)

Debian 13

apt-get install build-essential libstdc++-14-pic g++-multilib lib32gcc-s1

cd game/server/

make -j 4 -f server_linux32_hl2mp.mak
