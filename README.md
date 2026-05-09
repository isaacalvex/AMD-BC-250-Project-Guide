# AMD BC-250 - Console Project Guide

## Sobre o Projeto

O **BC-250** utiliza um hardware derivado da unidade de processamento (APU) do PlayStation 5, adaptado para o ambiente de desktop. Este projeto transforma essa placa em uma **Steam Machine** personalizada, utilizando o **Bazzite OS** para oferecer uma interface de console otimizada para jogos e emulação.

A placa conta com arquitetura **Zen 2** (8 núcleos e 16 threads) e gráficos integrados **RDNA 2**.

---

## Documentacao Tecnica e Modificacoes

Para informações detalhadas sobre hardware e software:

* **Pinagem e Hardware**: [Documentação BC-250 (mothenjoyer69)](https://github.com/mothenjoyer69/bc250-documentation).
* **Ajustes de BIOS**: [BIOS Mod para Linux (dannybastos)](https://github.com/dannybastos/bc-250-archlinux).
* **Compatibilidade de Video**: [Banco de Dados de Cabos Testados](https://github.com/isaacalves/AMD-BC250-hdmi-displayport-compatibility).

---

## Itens obrigatorios para a montagem

| Foto | Item | Qtd | Link de Compra |
| :---: | :--- | :---: | :--- |
| <img src="https://m.media-amazon.com/images/I/51f98I9-pBL._AC_SL1000_.jpg" width="50"> | Parafusos M3x6 | 20 | [AliExpress](https://pt.aliexpress.com/item/1005007345768217.html) |
| <img src="https://m.media-amazon.com/images/I/5176A6y-P0L._AC_SL1000_.jpg" width="50"> | Insertos M3x6 | 15 | [AliExpress](https://pt.aliexpress.com/item/1005008301352294.html) |
| <img src="https://http2.mlstatic.com/D_NQ_NP_956743-MLA50346399432_062022-O.webp" width="50"> | Hub USB (4 portas) | 1 | [Mercado Livre](https://www.mercadolivre.com.br/hub-usb-4-portas-multiplicador-entrada-pc-cabo-extensor-50cm-usb-20-30/p/MLB25726861) |
| <img src="https://http2.mlstatic.com/D_NQ_NP_664188-MLB49435491913_032022-O.webp" width="50"> | Extensão RJ-45 (Painel) | 1 | [Mercado Livre](https://www.mercadolivre.com.br/cabo-extensao-rj-45-macho-e-femea-50-cm--pacht-painel-rack/up/MLBU783975495) |
| <img src="https://http2.mlstatic.com/D_NQ_NP_777411-MLBU777411727_072024-O.webp" width="50"> | Splitter PWM para fans | 1 | [Mercado Livre](https://www.mercadolivre.com.br/cabo-extensor-splitter-multi-fan-pwm-para-3-fans/up/MLBU777411727) |
| <img src="https://http2.mlstatic.com/D_NQ_NP_675344-MLB44140024925_112020-O.webp" width="50"> | NodeMCU ESP32 | 1 | [Mercado Livre](https://www.mercadolivre.com.br/lote-de-baixa-energia-bluetooth-nodemcu-esp32-vroom-wifi/p/MLB46869037) |
|<img width="100" height="100" alt="gc9a01-128-zoll-rundes-lcd-tft-display-fur-arduino-602642" src="https://github.com/user-attachments/assets/649c0974-3cb6-449f-b9a6-2dc50f5ad4fb" /> | Display IPS 1.28 GC9A01 | 1 | [Mercado Livre](https://www.mercadolivre.com.br/display-ips-128-gc9a01-redondo/p/MLB2066163968) |
| <img width="100" height="100" alt="jst" src="https://github.com/user-attachments/assets/c40e5315-4f34-4147-92ad-4567b3fc52fd" />| Conector JST SM 4 Pinos | 1 | [Mercado Livre](https://www.mercadolivre.com.br/5-pares-conector-engate-rapido-jst-sm-4-pinos-4-fios/up/MLBU1985452711) |
| <img src="https://ae01.alicdn.com/kf/S5584852c00214878a2e7240f2e008608p.jpg" width="50"> | Extensor PCI-E 6 Pinos | 1 | [AliExpress](https://pt.aliexpress.com/item/1005008976362329.html) |
| <img src="https://www.waz.com.br/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/a/r/arctic-p12-pro-1.jpg" width="50"> | Fans Arctic P12 Pro | 2 | [WAZ](https://www.waz.com.br/ventoinha-cooler-12cm-arctic-cooling-p12-pro-preto-acfan00305a-131823-html/p) |
| <img src="https://http2.mlstatic.com/D_NQ_NP_868351-MLB44249156095_122020-O.webp" width="50"> | Botao com trava (Azul) | 1 | [Mercado Livre](https://mercadolivre.com/sec/2JBbnZW) |
| <img src="https://http2.mlstatic.com/D_NQ_NP_806506-MLB44249098754_122020-O.webp" width="50"> | Botao sem trava (Amarelo) | 1 | [Mercado Livre](https://mercadolivre.com/sec/223wKj9) |
| <img src="https://cf.shopee.com.br/file/4094e9f76c5b967a57a1b94b7e80a041" width="50"> | Adaptador DP para HDMI | 1 | [Shopee](https://shopee.com.br/Adaptador-DisplayPort-para-HDMI-Benfei-\(4K-60Hz\)-compat%C3%ADvel-HP-ThinkPad-AMD-NVIDIA-Desktop-B07JFTK8YV-i.1590082224.58250184593) |
| <img width="100" height="100" alt="fita" src="https://github.com/user-attachments/assets/18b22687-02f9-4d31-adac-f4fb338e0e38" />| Fita Metalizada Termoisolante | 1 | [Mercado Livre](https://www.mercadolivre.com.br/fita-ultra-fitas-metalizada-50m-x-48mm-termoisolante/p/MLB36521923) |
| <img src="https://http2.mlstatic.com/D_NQ_NP_727914-MLB29202868285_012019-O.webp" width="50"> | Tomada de Forca C14 | 1 | [Mercado Livre](https://produto.mercadolivre.com.br/MLB-1167597495-10-tomada-de-forca-tripolar-as-02-c14-preta-_JM) |
| <img src="https://http2.mlstatic.com/D_NQ_NP_824522-MLB48011283307_102021-O.webp" width="50"> | Cabo PCI-E 8 pinos | 1 | [Mercado Livre](https://mercadolivre.com/sec/2PYv3qZ) |

---

---

## Proximos Passos

1. Consulte os arquivos de modelagem 3D no repositório **CubeLAB**.
2. Realize a instalação do **Bazzite OS** para garantir a compatibilidade com sensores e GPU.
3. Utilize o banco de dados de cabos para garantir a saída de vídeo correta em sua TV ou monitor.
