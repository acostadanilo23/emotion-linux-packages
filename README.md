# Emotion Linux — pacotes

Repositório de pacotes `apk` do Emotion Linux, uma distribuição Linux para
o PlayStation 2 (R5900, 32 MB de RAM). Servido pelo GitHub Pages em
<https://acostadanilo23.github.io/emotion-linux-packages/>.

## Usar no PS2

```sh
pkg repo https://acostadanilo23.github.io/emotion-linux-packages/v0
pkg update
pkg upgrade
```

O repositório offline do pendrive continua configurado e é usado quando não
há rede. `pkg repo local` volta a usar só o offline.

## Segurança

Pacotes e índices são assinados. O PS2 confia apenas em
`/etc/apk/keys/ps2linux.rsa.pub` (cópia em [ps2linux.rsa.pub](ps2linux.rsa.pub))
e recusa pacote alterado ou assinado por outra chave. O download é por HTTPS
com validação de certificado.

## Conteúdo

- `v0/main`: sistema base (BusyBox, apk, curl, Dropbear, kernel...).
- `v0/community`: programas extras.
- `v0/experimental`: desktop gráfico opcional.

Cada diretório tem `SHA256SUMS`. Origem, versões e licenças: [SOURCES.md](SOURCES.md).

Gerado por `build/scripts/stage-packages-repo.sh` do projeto Emotion Linux.
