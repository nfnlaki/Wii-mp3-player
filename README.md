# Wii mp3 player

wiiで動くmp3プレーヤーです

<img src="https://github.com/user-attachments/assets/fa3052a2-f0da-4a0f-ae1f-023a21b5affe" width="500">

<img src="https://github.com/user-attachments/assets/658e47a8-0b35-4345-b339-d6b990afde01" width="500">

## Forwarder Channel

このプロジェクトには、Dolphinでの使用を想定したカスタムForwarder Channelがあります。
このチャンネルを起動すると、SDカード上の以下のファイルを読み込んで実行します。


```text
sd:/apps/wii-mp3-player/boot.dol
```

## Dolphinでの構成

```text
WiiSDSync/
├─ apps/
│  └─ wii-mp3-player/
│     ├─ boot.dol
│     ├─ meta.xml
│     └─ icon.png
└─ music/
   ├─ song1.mp3
   └─ song2.mp3
```
