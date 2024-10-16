# portainer-autoinstall

<img src="https://i.postimg.cc/4dh7HRpq/autoinstall.png"> 

## ⚠️ Pré-requisitos

Você deve criar 6 subdominios do tipo 'A' na Cloudflare
*Status do Proxy deve esta desligado

<p>portainer</p>
<p>www.portainer</p>
<p>traefik</p>
<p>www.traefik</p>
<p>edge</p>
<p>www.edge</p>

<img src="https://packtypebot.com.br/wp-content/uploads/2023/12/apontamentos.png"> 

<a href="https://packtypebot.com.br/gerador/htpasswd.php">Gerador de Senha htpasswd</a>

## 🎥 Tutorial

https://www.youtube.com/watch?v=GuT92GXosTw

## 💽 Instalação

<p>Copie e cole no Terminal da sua VPS:</p>

```
sudo apt update && sudo apt install -y git && git clone https://github.com/Maicon-Bartoski/portainer-autoinstall.git && cd portainer-packtypebot && sudo chmod +x install.sh && ./install.sh
```

## Caso  instância do Portainer expire
<img class="alignnone wp-image-2222 size-full" src="https://packtypebot.com.br/wp-content/uploads/2023/12/erro-port.jpg" alt="" width="950" height="385" />

Abra o terminal e rode os seguintes comandos:

<p>cd Portainer

<p>docker compose down --remove-orphans
<p>docker compose pull portainer
<p>docker compose up -d

## ❤️ Creditos

<p>Creditos do arquivo docker-compose.yml @Andre Almeida</p>
<br>
