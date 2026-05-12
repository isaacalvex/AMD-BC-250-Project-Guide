# 🎮 AMD BC-250 - Console Project Guide

## 📋 Sobre o Projeto
O **BC-250** utiliza um hardware derivado da unidade de processamento (APU) do PlayStation 5, adaptado para o ambiente de desktop. Este projeto transforma essa placa em uma **Steam Machine** personalizada, utilizando o **Bazzite OS** para oferecer uma interface de console otimizada para jogos e emulação.

### Especificações Base
*   **Arquitetura:** Zen 2 (8 núcleos / 16 threads).
*   **Gráficos:** RDNA 2 Integrado.
*   **Sistema Operacional:** [Bazzite OS (Linux)](https://bazzite.gg/).

---

## 📚 Documentação Técnica e Modificações
Para informações detalhadas sobre hardware, pinagem e software, consulte os repositórios da comunidade:

*   **[Pinagem e Hardware](https://github.com/mothenjoyer69/bc250-documentation)** – Documentação oficial por *mothenjoyer69*.
*   **[Ajustes de BIOS](https://github.com/dannybastos/bc-250-archlinux)** – BIOS Mod para Linux por *dannybastos*.
*   **[Compatibilidade de Vídeo](https://github.com/isaacalves/AMD-BC250-hdmi-displayport-compatibility)** – Banco de dados de cabos e adaptadores testados.

---

## 🛠️ Itens Obrigatórios para a Montagem

| Prévia | Item | Qtd | Link de Compra |
| :---: | :--- | :---: | :--- |
| <img src="https://github.com/user-attachments/assets/0bcfc120-fb4b-447e-b11e-1ddc9428bbba" width="60"> | **Parafusos M3x6** | 1 un. | [AliExpress](https://pt.aliexpress.com/item/1005005467831636.html) |
| <img src="https://github.com/user-attachments/assets/a6fd68c5-4355-4bf2-a7e8-1bff6de87501" width="60"> | **Hub USB 4 Portas** | 1 un. | [Mercado Livre](https://www.mercadolivre.com.br/hub-usb-4-portas-multiplicador-entrada-pc-cabo-extensor-50cm-usb-20-30/p/MLB25726861) |
| <img src="https://github.com/user-attachments/assets/da5829c4-ba4a-48ee-b524-d3092116ec5f" width="60"> | **Extensão RJ-45 (Painel)** | 1 un. | [Mercado Livre](https://www.mercadolivre.com.br/cabo-extensao-rj-45-macho-e-femea-50-cm--pacht-painel-rack/up/MLBU783975495) |
| <img src="https://github.com/user-attachments/assets/556de085-e7b4-4533-8dd0-0ac9ea5fb09b" width="60"> | **Splitter PWM para Fans** | 1 un. | [Mercado Livre](https://www.mercadolivre.com.br/cabo-extensor-splitter-multi-fan-pwm-para-3-fans/up/MLBU777411727) |
| <img src="https://github.com/user-attachments/assets/816bbb9b-8f24-46cd-b51f-0cb6de8cd58b" width="60"> | **NodeMCU ESP32** | 1 un. | [Mercado Livre](https://www.mercadolivre.com.br/lote-de-baixa-energia-bluetooth-nodemcu-esp32-vroom-wifi/p/MLB46869037) |
| <img src="https://github.com/user-attachments/assets/649c0974-3cb6-449f-b9a6-2dc50f5ad4fb" width="60"> | **Display IPS 1.28 GC9A01** | 1 un. | [Mercado Livre](https://www.mercadolivre.com.br/display-ips-128-gc9a01-redondo/p/MLB2066163968) |
| <img src="https://github.com/user-attachments/assets/c40e5315-4f34-4147-92ad-4567b3fc52fd" width="60"> | **Conector JST SM 4 Pinos** | 1 un. | [Mercado Livre](https://www.mercadolivre.com.br/5-pares-conector-engate-rapido-jst-sm-4-pinos-4-fios/up/MLBU1985452711) |
| <img alt="D_Q_NP_853295-MLB87399952660_072025-F" src="https://github.com/user-attachments/assets/8713c870-0761-49a7-8fc4-c38574a04b45" width="60"> | **Extensor PCI-E 6 Pinos** | 1 un. | [AliExpress](https://pt.aliexpress.com/item/1005008976362329.html) |
| <img src="https://github.com/user-attachments/assets/71c7976a-94d8-4e65-bcad-7493228c3612" width="60"> | **Fans Arctic P12 Pro** | 2 un. | [WAZ](https://www.waz.com.br/ventoinha-cooler-12cm-arctic-cooling-p12-pro-preto-acfan00305a-131823-html/p) |
| <img src="https://github.com/user-attachments/assets/387d97d1-b84a-49b6-aeb2-f927af8289b7" width="60"> | **Botão com trava (Azul)** | 1 un. | [Mercado Livre](https://mercadolivre.com/sec/2JBbnZW) |
| <img src="https://http2.mlstatic.com/D_NQ_NP_806506-MLB44249098754_122020-O.webp" width="60"> | **Botão sem trava (Amarelo)** | 1 un. | [Mercado Livre](https://mercadolivre.com/sec/223wKj9) |
| <img src="https://cf.shopee.com.br/file/4094e9f76c5b967a57a1b94b7e80a041" width="60"> | **Adaptador DP para HDMI** | 1 un. | [Shopee](https://shopee.com.br/Adaptador-DisplayPort-para-HDMI-Benfei-(4K-60Hz)) |
| <img src="https://github.com/user-attachments/assets/f9619f11-af14-481a-95fa-221b7c407e0f" width="60"> | **Tomada de Força C14** | 1 un. | [Mercado Livre](https://produto.mercadolivre.com.br/MLB-1167597495-10-tomada-de-forca-tripolar-as-02-c14-preta-_JM) |
| <img src="https://http2.mlstatic.com/D_NQ_NP_824522-MLB48011283307_102021-O.webp" width="60"> | **Cabo PCI-E 8 pinos** | 1 un. | [Mercado Livre](https://mercadolivre.com/sec/2PYv3qZ) |

---

## 🚀 Próximos Passos

1.  **Modelagem 3D:** Baixe e imprima as peças no repositório **CubeLAB**.
2.  **Software:** Realize a instalação do **Bazzite OS** para garantir compatibilidade nativa com os sensores e a GPU RDNA 2.
3.  **Conectividade:** Utilize o banco de dados de cabos para garantir que a saída de vídeo funcione corretamente na sua TV ou monitor.
