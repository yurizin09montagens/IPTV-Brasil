# 🇧🇷 IPTV Brasil

> 📺 Playlist IPTV em formato **M3U** para reprodução de transmissões ao vivo em players compatíveis, como **VLC Media Player**.

O **IPTV Brasil** é um projeto para organizar e disponibilizar uma playlist IPTV de forma simples, permitindo acessar transmissões através de uma única lista `.m3u`.

---

## 📺 Sobre o projeto

Este projeto utiliza o formato **M3U**, compatível com diversos players de mídia e aplicativos de IPTV.

A playlist pode ser utilizada em:

- 🖥️ VLC Media Player
- 📱 Aplicativos compatíveis com M3U
- 📺 Smart TVs com suporte a playlists IPTV
- 💻 Outros players compatíveis com streams HLS/M3U8

---

## 🚀 Como usar

### VLC Media Player

1. Abra o **VLC Media Player**.
2. Acesse **Mídia → Abrir fluxo de rede**.
3. Cole a URL da playlist:

```text
https://raw.githubusercontent.com/yurizin09montagens/IPTV-Brasil/refs/heads/main/playlist.m3u
```

4. Clique em **Reproduzir**.

---

## 📋 Formato da playlist

```m3u
#EXTM3U

#EXTINF:-1 tvg-name="Canal Exemplo" group-title="Brasil",Canal Exemplo
https://exemplo.com/stream/canal.m3u8
```

---

## 📂 Estrutura do projeto

```text
IPTV-Brasil/
├── playlist.m3u
├── epg.xml
├── logos/
└── README.md
```

---

## 🛠️ Tecnologias

- **M3U** — formato da playlist
- **M3U8 / HLS** — transmissão de vídeo
- **GitHub** — hospedagem da playlist
- **VLC Media Player** — reprodução

---

## 🎯 Objetivos

- Organizar canais em uma playlist M3U.
- Facilitar a reprodução através do VLC.
- Aprender sobre playlists IPTV e streaming.
- Manter o projeto simples e fácil de atualizar.
- Permitir futuras integrações com EPG e logos.

---

## ⚠️ Aviso

Este projeto é destinado a **fins educacionais e de organização de fontes autorizadas**.

Não são fornecidos, incentivados ou distribuídos conteúdos protegidos por direitos autorais sem autorização. Utilize somente transmissões que você possui, criou ou tem permissão para redistribuir.

A disponibilidade e legalidade de cada transmissão são de responsabilidade da respectiva fonte.

---

## 🤝 Contribuição

Contribuições são bem-vindas!

1. Faça um **Fork** do projeto.
2. Crie uma nova branch.
3. Faça suas alterações.
4. Envie um **Pull Request**.

---

## ⭐ Apoie o projeto

Se este projeto foi útil para você, considere deixar uma ⭐ no repositório!

**IPTV Brasil — simples, organizado e feito para aprender. 🇧🇷📺**
