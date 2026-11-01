# Origem e licenças dos pacotes

Os pacotes deste repositório são binários para o PlayStation 2 (R5900,
little-endian, o32, soft-float, musl), compilados pelo projeto Emotion Linux
a partir das versões fixadas abaixo, com patches e configurações do projeto.

| Pacote | Versão | Repositório | Licença | Origem do código |
|---|---|---|---|---|
| apk-tools | 3.0.8-r3 | main | GPL-2.0-only | https://gitlab.alpinelinux.org/alpine/apk-tools |
| busybox | 1.36.1-r1 | main | GPL-2.0-only | https://busybox.net |
| ca-certificates | 2026.7.22-r1 | main | MPL-2.0 | https://github.com/certifi/python-certifi |
| curl | 8.22.0-r0 | main | curl | https://curl.se |
| doas | 6.8.2-r0 | main | ISC | https://github.com/Duncaen/OpenDoas |
| dosfstools | 4.2-r0 | community | GPL-3.0-or-later | https://github.com/dosfstools/dosfstools |
| dropbear | 2026.94-r0 | main | MIT | https://matt.ucc.asn.au/dropbear/dropbear.html |
| e2fsprogs | 1.47.4-r0 | main | GPL-2.0-only | https://e2fsprogs.sourceforge.net |
| emotion-browser | 0.1.0-r0 | community | custom AND Bitstream-Vera AND Apache-2.0 | https://github.com/acostadanilo23 |
| emotion-desktop | 0.1.0-r12 | experimental | GPL-2.0-or-later AND MIT AND LGPL-2.1-or-later AND custom | https://github.com/acostadanilo23/Emotion-Linux |
| emotion-doom | 2026.10.11-r5 | experimental | GPL-2.0-or-later | https://github.com/ozkl/doomgeneric |
| emotion-gb | 0.1.0-r1 | community | MIT | https://github.com/deltabeard/Peanut-GB |
| emotion-kernel | 5.4.221-r2 | experimental | GPL-2.0-only | https://github.com/acostadanilo23/Emotion-Linux |
| emotion-md | 0.1.0-r1 | community | custom | https://github.com/libretro/Genesis-Plus-GX |
| emotion-nes | 0.1.0-r1 | community | GPL-2.0-only | https://github.com/libretro/libretro-fceumm |
| emotion-play | 0.1.0-r0 | community | GPL-2.0-or-later | https://github.com/acostadanilo23/Emotion-Linux |
| emotion-rss | 0.1.0-r0 | community | custom | https://github.com/acostadanilo23 |
| emotion-sdk-tools | 0.9.0-r0 | community | custom | https://github.com/acostadanilo23 |
| emotion-snes | 0.1.0-r1 | community | custom | https://github.com/libretro/snes9x2002 |
| emotion-weather | 0.1.0-r0 | community | custom | https://github.com/acostadanilo23 |
| fastfetch | 2.54.0-r0 | community | MIT | https://github.com/fastfetch-cli/fastfetch |
| file | 5.47-r0 | community | BSD-2-Clause | https://www.darwinsys.com/file/ |
| freedoom | 0.13.0-r0 | experimental | BSD-3-Clause | https://freedoom.github.io |
| frotz | 2.55-r0 | community | GPL-2.0-or-later | https://davidgriffith.gitlab.io/frotz/ |
| git | 2.47.1-r0 | community | GPL-2.0-only | https://git-scm.com |
| gzip | 1.14-r0 | main | GPL-3.0-or-later | https://www.gnu.org/software/gzip/ |
| htop | 3.3.0-r0 | community | GPL-2.0-or-later | https://htop.dev/ |
| jq | 1.7.1-r0 | community | MIT | https://jqlang.github.io/jq/ |
| less | 668-r0 | main | GPL-3.0-or-later OR BSD-2-Clause | https://www.greenwoodsoftware.com/less/ |
| links | 2.30-r0 | community | GPL-2.0-or-later | http://links.twibright.com |
| linux-modules | 5.4.221-r3 | main | GPL-2.0-only | https://github.com/frno7/linux |
| lua | 5.4.9-r0 | community | MIT | https://www.lua.org |
| nano | 9.2-r0 | main | GPL-3.0-or-later | https://www.nano-editor.org |
| ncdu | 1.20-r0 | community | MIT | https://dev.yorhel.nl/ncdu |
| ncurses-terminfo | 6.6_p20260608-r0 | main | MIT | https://invisible-island.net/ncurses/ |
| ps2-firmware | 0.2-r3 | main | GPL-2.0-only | https://github.com/frno7/iopmod |
| ps2linux-base | 0.2-r13 | main | GPL-2.0-only | https://github.com/acostadanilo23/Emotion-Linux |
| rsync | 3.4.4-r0 | community | GPL-3.0-or-later | https://rsync.samba.org |
| sqlite | 3.53.4-r0 | community | blessing | https://sqlite.org |
| tmux | 3.5a-r0 | community | ISC | https://github.com/tmux/tmux |
| tzdata-belem | 2026.10.30-r0 | community | LicenseRef-Public-Domain | https://www.iana.org/time-zones |
| tzdata-extra | 2026.10.31-r0 | community | LicenseRef-Public-Domain | https://www.iana.org/time-zones |
| xz | 5.8.3-r0 | main | 0BSD AND GPL-2.0-or-later | https://tukaani.org/xz/ |
| zapc | 0.1.0-r0 | community | MIT AND Apache-2.0 | https://github.com/acostadanilo23 |
| zstd | 1.5.6-r0 | community | BSD-3-Clause | https://facebook.github.io/zstd/ |

## Componentes e commits fixados

- binutils 2.39: `b51c2fec1da205ea3e7354cbb3e253018d64873c` em https://sourceware.org/git/binutils-gdb.git
- gcc 12.4.0: `2bada4bc59bed4be34fab463bdb3c3ebfd2b41bb` em https://gcc.gnu.org/git/gcc.git
- musl 1.2.5: `0784374d561435f7c787a555aeab8ede699ed298` em https://git.musl-libc.org/git/musl
- busybox 1.36.1: `1a64f6a20aaf6ea4dbba68bbfa8cc1ab7e5c57c4` em https://git.busybox.net/busybox
- linux 5.4.221-ps2: `77174dd4c8958a91aa5b76fb064a60eb68119e70` em https://github.com/frno7/linux.git
- iopmod main-20241229: `12cdf14b78ed5e648ffe1d52e6754f00b3b69001` em https://github.com/frno7/iopmod.git
- qemu 10.1.2: `ccaea6b2656ec6eab966585f7b16438208f98de7` em https://gitlab.com/qemu-project/qemu.git
- mbedtls 3.6.7: `068ff080b369adfac81509f9b57b2afabaf82dc5` em https://github.com/Mbed-TLS/mbedtls.git
- wolfssl 5.9.4: `3c5eead44904df64e6a5a1f4ebdce377d35a849a` em https://github.com/wolfSSL/wolfssl.git
- curl 8.22.0: `01346829096c61b372692f6dc43ffa778c6caccd` em https://github.com/curl/curl.git
- dropbear 2026.94: `28216cd9af822732a1549b78621c2ea9a76a0fe5` em https://github.com/mkj/dropbear.git
- e2fsprogs 1.47.4: `7ee1d505ef3b37831215f490411f346fe57e9053` em https://git.kernel.org/pub/scm/fs/ext2/e2fsprogs.git
- zlib 1.3.2: `da607da739fa6047df13e66a2af6b8bec7c2a498` em https://github.com/madler/zlib.git
- apktools 3.0.8: `44dcdfc255c26a4e19a4a27f66a54169cce5ca72` em https://gitlab.alpinelinux.org/alpine/apk-tools.git
- opkg lede-20251105: `80503d94e356476250adaf1f669ee955ec26de76` em https://git.openwrt.org/project/opkg-lede.git
- jsonc 0.19: `aa716cd8d663c976b99b0f30f102ee1d8ef63146` em https://github.com/json-c/json-c.git
- libubox master-da2d205: `da2d205a5cf3e877c45a2eec488218cbaf452e7d` em https://git.openwrt.org/project/libubox.git
- usign master-c4c72b1: `c4c72b1b07945ee192361dc751291a7c98d6adcd` em https://git.openwrt.org/project/usign.git

## Fontes dos pacotes (arquivo e SHA-256 usados no build)

- doas 6.8.2: https://github.com/Duncaen/OpenDoas/releases/download/v6.8.2/opendoas-6.8.2.tar.xz (sha256 `4e98828056d6266bd8f2c93e6ecf12a63a71dbfd70a5ea99ccd4ab6d0745adf0`)
- dosfstools 4.2: https://github.com/dosfstools/dosfstools/releases/download/v4.2/dosfstools-4.2.tar.gz (sha256 `64926eebf90092dca21b14259a5301b7b98e7b1943e8a201c7d726084809b527`)
- emotion-doom 2026.10.11: https://github.com/ozkl/doomgeneric/archive/e257a09527062bfb986b6e5e0780839b6cbd5b71.tar.gz (sha256 `26f8f60daa6c6e4d3c01e5eac9fb700d592dede803d13ac848154ff356b2a2e7`)
- emotion-gb 0.1.0: https://github.com/deltabeard/Peanut-GB/archive/d0bcca771c83a2638c93a9ae61f3d51f226dc905.tar.gz (sha256 `f021361201be1abce25f1a4351e73ffbbf07070f54005fa64cd8320a8ececb84`)
- emotion-md 0.1.0: https://github.com/libretro/Genesis-Plus-GX/archive/f27655b592ef43f317272d79883bcaa10d3ac8ad.tar.gz (sha256 `4720dce8f219994951fe5d021e433f3b107ad7c3c64b6295a6a12928f31a73ea`)
- emotion-nes 0.1.0: https://github.com/libretro/libretro-fceumm/archive/ac0d00a7fc01166f84c7bac01d1084ebfd2b865e.tar.gz (sha256 `364affeeea3d91ab8de4ef2a333cb0ca4d7d8e8992e94366a270b32e309485ca`)
- emotion-snes 0.1.0: https://github.com/libretro/snes9x2002/archive/6ffbf9ef4f0063e1f1b78a40d10c50fc52f2524c.tar.gz (sha256 `01c733054f8d02b26c53ab3f89ae0698e1f4edb55999dfa63c9a522fccb6382d`)
- fastfetch 2.54.0: https://codeload.github.com/fastfetch-cli/fastfetch/tar.gz/refs/tags/2.54.0 (sha256 `e6a0516364bc0a4991a588537ee2abb538b86db41f7d9dff795d49baec990529`)
- file 5.47: https://astron.com/pub/file/file-5.47.tar.gz (sha256 `45672fec165cb4cc1358a2d76b5d57d22876dcb97ab169427ac385cbe1d5597a`)
- frotz 2.55: https://gitlab.com/DavidGriffith/frotz/-/archive/2.55/frotz-2.55.tar.gz (sha256 `a8c4c4d79a2aa9b39e0efbbd3e0803f1dc5ef36f75f2c2945e295d190575eb09`)
- git 2.47.1: https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.47.1.tar.xz (sha256 `f3d8f9bb23ae392374e91cd9d395970dabc5b9c5ee72f39884613cd84a6ed310`)
- gzip 1.14: https://ftp.gnu.org/gnu/gzip/gzip-1.14.tar.xz (sha256 `01a7b881bd220bfdf615f97b8718f80bdfd3f6add385b993dcf6efd14e8c0ac6`)
- htop 3.3.0: https://github.com/htop-dev/htop/releases/download/3.3.0/htop-3.3.0.tar.xz (sha256 `a69acf9b42ff592c4861010fce7d8006805f0d6ef0e8ee647a6ee6e59b743d5c`)
- jq 1.7.1: https://github.com/jqlang/jq/releases/download/jq-1.7.1/jq-1.7.1.tar.gz (sha256 `478c9ca129fd2e3443fe27314b455e211e0d8c60bc8ff7df703873deeee580c2`)
- less 668: https://www.greenwoodsoftware.com/less/less-668.tar.gz (sha256 `2819f55564d86d542abbecafd82ff61e819a3eec967faa36cd3e68f1596a44b8`)
- links 2.30: http://links.twibright.com/download/links-2.30.tar.bz2 (sha256 `c4631c6b5a11527cdc3cb7872fc23b7f2b25c2b021d596be410dadb40315f166`)
- lua 5.4.9: https://www.lua.org/ftp/lua-5.4.9.tar.gz (sha256 `2335b6c582a52654f94612bf10d2f4672805d05329aa6568b1d8cd9e5c6fb8e6`)
- nano 9.2: https://www.nano-editor.org/dist/v9/nano-9.2.tar.xz (sha256 `05ecb99247b782e8a5b3a25ed4101dd034b0236902f7449bc9795b717642f7e9`)
- ncdu 1.20: https://dev.yorhel.nl/download/ncdu-1.20.tar.gz (sha256 `5fe2bb841abe72374bb242dbb93293c4ae053078432d896a7481b2ff10be9572`)
- ncurses-terminfo 6.6_p20260608: https://invisible-island.net/archives/ncurses/current/ncurses-6.6-20260608.tgz (sha256 `3b91eb714ba61b9ebfcfe09cf8e7c1c45cf2e8a6282f5887fb942db514ae93bd`)
- rsync 3.4.4: https://github.com/RsyncProject/rsync/releases/download/v3.4.4/rsync-3.4.4.tar.gz (sha256 `bd88cf82fa653da32314fb229136407c5c90f80d1758d8f4b091767877d8fa96`)
- sqlite 3.53.4: http://archive.ubuntu.com/ubuntu/pool/main/s/sqlite3/sqlite3_3.53.4.orig.tar.xz (sha256 `05366adc8ee80c6b1faa71285b49d133c2121238ca58934b077fdeb95934abd4`)
- tmux 3.5a: https://github.com/tmux/tmux/releases/download/3.5a/tmux-3.5a.tar.gz (sha256 `16216bd0877170dfcc64157085ba9013610b12b082548c7c9542cc0103198951`)
- xz 5.8.3: https://github.com/tukaani-project/xz/releases/download/v5.8.3/xz-5.8.3.tar.xz (sha256 `fff1ffcf2b0da84d308a14de513a1aa23d4e9aa3464d17e64b9714bfdd0bbfb6`)
- zstd 1.5.6: https://github.com/facebook/zstd/releases/download/v1.5.6/zstd-1.5.6.tar.gz (sha256 `8c29e06cf42aacc1eafc4077ae2ec6c6fcb96a626157e0593d5e82a34fd403c1`)
- util-macros 1.20.2: https://www.x.org/archive/individual/util/util-macros-1.20.2.tar.gz (sha256 `f642f8964d81acdf06653fdf9dbc210c43ce4bd308bd644a8d573148d0ced76b`)
- xorgproto 2021.5: https://www.x.org/archive/individual/proto/xorgproto-2021.5.tar.bz2 (sha256 `aa2f663b8dbd632960b24f7477aa07d901210057f6ab1a1db5158732569ca015`)
- xtrans 1.5.0: https://www.x.org/archive/individual/lib/xtrans-1.5.0.tar.gz (sha256 `a806f8a92f879dcd0146f3f1153fdffe845f2fc0df9b1a26c19312b7b0a29c86`)
- libfontenc 1.1.8: https://www.x.org/archive/individual/lib/libfontenc-1.1.8.tar.gz (sha256 `b55039f70959a1b2f02f4ec8db071e5170528d2c9180b30575dccf7510d7fb9f`)
- libXfont 1.5.4: https://www.x.org/archive/individual/lib/libXfont-1.5.4.tar.gz (sha256 `59be6eab53f7b0feb6b7933c11d67d076ae2c0fd8921229c703fc7a4e9a80d6e`)
- libXau 1.0.12: https://www.x.org/archive/individual/lib/libXau-1.0.12.tar.gz (sha256 `2402dd938da4d0a332349ab3d3586606175e19cb32cb9fe013c19f1dc922dcee`)
- xcb-proto 1.17.0: https://xcb.freedesktop.org/dist/xcb-proto-1.17.0.tar.gz (sha256 `392d3c9690f8c8202a68fdb89c16fd55159ab8d65000a6da213f4a1576e97a16`)
- libxcb 1.17.0: https://xcb.freedesktop.org/dist/libxcb-1.17.0.tar.gz (sha256 `2c69287424c9e2128cb47ffe92171e10417041ec2963bceafb65cb3fcf8f0b85`)
- libX11 1.8.12: https://www.x.org/archive/individual/lib/libX11-1.8.12.tar.gz (sha256 `220fbcf54b6e4d8dc40076ff4ab87954358019982490b33c7802190b62d89ce1`)
- libXext 1.3.6: https://www.x.org/archive/individual/lib/libXext-1.3.6.tar.gz (sha256 `1a0ac5cd792a55d5d465ced8dbf403ed016c8e6d14380c0ea3646c4415496e3d`)
- rxvt 2.6.4: https://archive.debian.org/debian/pool/main/r/rxvt/rxvt_2.6.4.orig.tar.gz (sha256 `e830b6a8aff1036ef9641a400b1e0e0fba43b9330ecb6bb91fd8b9255d65f448`)
- jwm 2.4.6: https://codeload.github.com/joewing/jwm/tar.gz/3e4518efdbc3b89c710a20d672b392608fbc8f3c (sha256 `591e5827c49fd7faae7069497bfafe54a25aa2189e8e2c5d60776d8ce478e142`)
- libXdmcp 1.1.5: https://www.x.org/archive/individual/lib/libXdmcp-1.1.5.tar.gz (sha256 `31a7abc4f129dcf6f27ae912c3eedcb94d25ad2e8f317f69df6eda0bc4e4f2f3`)
- tinyx feab72c: https://codeload.github.com/tinycorelinux/tinyx/tar.gz/feab72ca891bc04b18763763e15ee4e532369cdf (sha256 `82f69bbd7a979d30a25a80082ba6fdcb975740ba36836795a3763814aff0adca`)
- libICE 1.1.2: https://www.x.org/archive/individual/lib/libICE-1.1.2.tar.gz (sha256 `1da62f732f8679c20045708a29372b82dff9e7eceee543ed488b845002b3b0ff`)
- libSM 1.2.6: https://www.x.org/archive/individual/lib/libSM-1.2.6.tar.gz (sha256 `166b4b50d606cdd83f1ddc61b5b9162600034f848b3e32ccbb0e63536b7d6cdd`)
- libXt 1.3.1: https://www.x.org/archive/individual/lib/libXt-1.3.1.tar.gz (sha256 `cf2212189869adb94ffd58c7d9a545a369b83d2274930bfbe148da354030b355`)
- libXmu 1.2.1: https://www.x.org/archive/individual/lib/libXmu-1.2.1.tar.gz (sha256 `bf0902583dd1123856c11e0a5085bd3c6e9886fbbd44954464975fd7d52eb599`)
- libXpm 3.5.17: https://www.x.org/archive/individual/lib/libXpm-3.5.17.tar.gz (sha256 `959466c7dfcfcaa8a65055bfc311f74d4c43d9257900f85ab042604d286df0c6`)
- libXaw 1.0.16: https://www.x.org/archive/individual/lib/libXaw-1.0.16.tar.gz (sha256 `012f90adf8739f2f023d63a5fee1528949cf2aba92ef7ac1abcfc2ae9cf28798`)
- libXaw3d 1.6.6: https://www.x.org/archive/individual/lib/libXaw3d-1.6.6.tar.gz (sha256 `0cdb8f51c390b0f9f5bec74454e53b15b6b815bc280f6b7c969400c9ef595803`)
- SDL2 2.32.10: https://www.libsdl.org/release/SDL2-2.32.10.tar.gz (sha256 `5f5993c530f084535c65a6879e9b26ad441169b3e25d789d83287040a9ca5165`)
- xfm 1.5.4: https://archive.debian.org/debian/pool/main/x/xfm/xfm_1.5.4.orig.tar.gz (sha256 `2c4c3f7c4c0473963a1d434303c0cd743f7c6bcb8a153d3aca74303c05f56cc2`)
- xsysinfo 1.7: https://deb.debian.org/debian/pool/main/x/xsysinfo/xsysinfo_1.7.orig.tar.gz (sha256 `cc392b55de781fcffb6916e1d76e0deda13d711173a480e975537069b5642ab6`)
- mutt 2.4.1: https://deb.debian.org/debian/pool/main/m/mutt/mutt_2.4.1.orig.tar.gz (sha256 `5624321f0b1cc1eff6cab9ef08f25954ff64c51b33d4bf3b99484cf1edd8cfff`)
- terminus-font 4.49.1: https://downloads.sourceforge.net/project/terminus-font/terminus-font-4.49/terminus-font-4.49.1.tar.gz (sha256 `d961c1b781627bf417f9b340693d64fc219e0113ad3a3af1a3424c7aa373ef79`)

## Código-fonte correspondente

Para os componentes sob GPL/LGPL, o código-fonte correspondente é o
upstream no commit fixado acima mais os patches, configurações e scripts de
build do Emotion Linux usados para gerar cada pacote.

**Oferta por escrito:** por no mínimo três anos a partir da publicação de
cada pacote, qualquer pessoa pode pedir o código-fonte completo
correspondente a um pacote deste repositório abrindo uma issue em
<https://github.com/acostadanilo23/emotion-linux-packages/issues>; ele será
fornecido sem custo além do de distribuição.
