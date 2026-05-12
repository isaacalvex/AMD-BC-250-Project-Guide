#  AMD BC-250 - Console Project Guide

##  Sobre o Projeto
O **BC-250** utiliza um hardware derivado da unidade de processamento (APU) do PlayStation 5, adaptado para o ambiente de desktop. Este projeto transforma essa placa em uma **Steam Machine** personalizada, utilizando o **Bazzite OS** para oferecer uma interface de console otimizada para jogos e emulação.

### Especificações Base
*   **Arquitetura:** Zen 2 (8 núcleos / 16 threads).
*   **Gráficos:** RDNA 2 Integrado.
*   **Sistema Operacional:** [Bazzite OS (Linux)](https://bazzite.gg/).

---

##  Documentação Técnica e Modificações
Para informações detalhadas sobre hardware, pinagem e software, consulte os repositórios da comunidade:

*   **[Pinagem e Hardware](https://github.com/mothenjoyer69/bc250-documentation)** – Documentação oficial por *mothenjoyer69*.
*   **[Ajustes de BIOS](https://github.com/dannybastos/bc-250-archlinux)** – BIOS Mod para Linux por *dannybastos*.
*   **[Compatibilidade de Vídeo](https://github.com/isaacalves/AMD-BC250-hdmi-displayport-compatibility)** – Banco de dados de cabos e adaptadores testados.

---

##  Itens Obrigatórios para a Montagem

| Prévia | Item | Qtd | Link de Compra |
| :---: | :--- | :---: | :--- |
| <img src="https://github.com/user-attachments/assets/0bcfc120-fb4b-447e-b11e-1ddc9428bbba" width="60"> | **Parafusos M3x6** | 1 un. | [AliExpress](https://pt.aliexpress.com/item/1005005467831636.html) |
| <img src="https://github.com/user-attachments/assets/a6fd68c5-4355-4bf2-a7e8-1bff6de87501" width="60"> | **Hub USB 4 Portas** | 1 un. | [Mercado Livre](https://www.mercadolivre.com.br/hub-usb-4-portas-multiplicador-entrada-pc-cabo-extensor-50cm-usb-20-30/p/MLB25726861) |
| <img src="https://github.com/user-attachments/assets/da5829c4-ba4a-48ee-b524-d3092116ec5f" width="60"> | **Extensão RJ-45 (Painel)** | 1 un. | [Mercado Livre](https://www.mercadolivre.com.br/cabo-extensao-rj-45-macho-e-femea-50-cm--pacht-painel-rack/up/MLBU783975495) |
| <img src="https://github.com/user-attachments/assets/556de085-e7b4-4533-8dd0-0ac9ea5fb09b" width="60"> | **Splitter PWM para Fans** | 1 un. | [Mercado Livre](https://www.mercadolivre.com.br/cabo-extensor-splitter-multi-fan-pwm-para-3-fans/up/MLBU777411727) |
| <img src="https://github.com/user-attachments/assets/816bbb9b-8f24-46cd-b51f-0cb6de8cd58b" width="60"> | **NodeMCU ESP32** | 1 un. | [Mercado Livre](https://www.mercadolivre.com.br/lote-de-baixa-energia-bluetooth-nodemcu-esp32-vroom-wifi/p/MLB46869037) |
| <img src="https://github.com/user-attachments/assets/649c0974-3cb6-449f-b9a6-2dc50f5ad4fb" width="60"> | **Display IPS 1.28 GC9A01** | 1 un. | [Mercado Livre](https://www.mercadolivre.com.br/display-ips-128-gc9a01-redondo/p/MLB2066163968) |
| <img src="https://github.com/user-attachments/assets/c40e5315-4f34-4147-92ad-4567b3fc52fd" width="60"> | **Conector JST SM 4 Pinos** | 1 un. | [Mercado Livre](https://www.mercadolivre.com.br/5-pares-conector-engate-rapido-jst-sm-4-pinos-4-fios/up/MLBU1985452711) |
| <img src="https://github.com/user-attachments/assets/71c7976a-94d8-4e65-bcad-7493228c3612" width="60"> | **Fans Arctic P12 Pro** | 2 un. | [WAZ](https://www.waz.com.br/ventoinha-cooler-12cm-arctic-cooling-p12-pro-preto-acfan00305a-131823-html/p) |
| <img src="https://github.com/user-attachments/assets/387d97d1-b84a-49b6-aeb2-f927af8289b7" width="60"> | **Botão com trava (Azul)** | 1 un. | [Mercado Livre](https://mercadolivre.com/sec/2JBbnZW) |
| <img alt="br-11134207-81z1k-mggv7m1gtrev70@resize_w450_nl (1)" src="https://github.com/user-attachments/assets/b916ef9e-04dd-43ba-89dc-bade941c0bde" width="60"/> | **Adaptador DP para HDMI** | 1 un. | [Shopee](https://shopee.com.br/Adaptador-DisplayPort-para-HDMI-Benfei-(4K-60Hz)) |
| <img src="https://github.com/user-attachments/assets/f9619f11-af14-481a-95fa-221b7c407e0f" width="60"> | **Tomada de Força C14** | 1 un. | [Mercado Livre](https://produto.mercadolivre.com.br/MLB-1167597495-10-tomada-de-forca-tripolar-as-02-c14-preta-_JM) |
| <img alt="Captura de tela 2026-05-12 202456" src="https://github.com/user-attachments/assets/32877123-1926-4e75-8c4c-217f38825ab3" width="60"> | **Fonte Metalfish 500W** | 1 un. | [Aliexpress]([https://mercadolivre.com/sec/2PYv3qZ](https://pt.aliexpress.com/item/1005009635167985.html?spm=a2g0o.productlist.main.2.296feccbc8nD1F&algo_pvid=f028510b-1c00-4f64-b97e-4d7d0e9811e4&algo_exp_id=f028510b-1c00-4f64-b97e-4d7d0e9811e4-1&pdp_ext_f=%7B%22order%22%3A%22217%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21BRL%21417.33%21384.99%21%21%2178.90%2172.79%21%40210328c017786281878564673e6d28%2112000049711330740%21sea%21BR%211742837610%21X%211%210%21n_tag%3A-29919%3Bd%3Aaeb01396%3Bm03_new_user%3A-29895&curPageLogUid=cHW9sizj8lc2&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009635167985%7C_p_origin_prod%3A)) |

---

##  Próximos Passos

1.  **Modelagem 3D:** Baixe e imprima as peças no repositório **CubeLAB**.
2.  **Software:** Realize a instalação do **Bazzite OS** para garantir compatibilidade nativa com os sensores e a GPU RDNA 2.
3.  **Conectividade:** Utilize o banco de dados de cabos para garantir que a saída de vídeo funcione corretamente na sua TV ou monitor.
