# AMD BC-250 Project Guide

![AMD BC-250 Custom Steam Machine](https://github.com/user-attachments/assets/054dce06-1e0c-4125-b9cd-1b2700f88108)

## Sobre o Projeto

O **BC-250** utiliza um hardware derivado da unidade de processamento (APU) do PlayStation 5, adaptado para o ambiente de desktop. Este projeto transforma essa placa em uma **Steam Machine** personalizada, utilizando o **Bazzite OS** para oferecer uma interface de console otimizada para jogos e emulação.

A placa conta com arquitetura **Zen 2** (8 núcleos e 16 threads) e gráficos integrados **RDNA 2**.

---

## Documentacao Tecnica e Modificacoes

Para informações detalhadas sobre hardware e software:

*   **Pinagem e Hardware**: [Documentação BC-250 (mothenjoyer69)](https://github.com/mothenjoyer69/bc250-documentation).
*   **Ajustes de BIOS**: [BIOS Mod para Linux (dannybastos)](https://github.com/dannybastos/bc-250-archlinux).
*   **Compatibilidade de Video**: [Banco de Dados de Cabos Testados](https://github.com/isaacalves/AMD-BC250-hdmi-displayport-compatibility).

---

## Itens obrigatorios para a montagem

| Categoria | Item | Quantidade | Link de Compra |
| :--- | :--- | :--- | :--- |
| Fixacao | Parafusos M3x6 | 20 unidades | [AliExpress](https://pt.aliexpress.com/item/1005007345768217.html) |
| Fixacao | Insertos M3x6 | 15 unidades | [AliExpress](https://pt.aliexpress.com/item/1005008301352294.html) |
| Conectividade | Hub USB 3.0 (4 portas) | 1 unidade | [Mercado Livre](https://mercadolivre.com/sec/2uJBcMX) |
| Conectividade | Extensão RJ-45 Macho/Fêmea (Painel) | 1 unidade | [Mercado Livre](https://www.mercadolivre.com.br/cabo-extensao-rj-45-macho-e-femea-50-cm--pacht-painel-rack/up/MLBU783975495) |
| Controle | Hub PWM para fans (ate 5) | 1 unidade | [Mercado Livre](https://mercadolivre.com/sec/1Yk9tYN) |
| Eletronica | NodeMCU ESP32 WiFi/Bluetooth | 1 unidade | [Mercado Livre](https://www.mercadolivre.com.br/lote-de-baixa-energia-bluetooth-nodemcu-esp32-vroom-wifi/p/MLB46869037) |
| Eletronica | Display IPS 1.28 GC9A01 Redondo | 1 unidade | [Mercado Livre](https://www.mercadolivre.com.br/display-ips-128-gc9a01-redondo/p/MLB2066163968) |
| Cabeamento | Conector JST SM 4 Pinos (5 pares) | 1 unidade | [Mercado Livre](https://www.mercadolivre.com.br/5-pares-conector-engate-rapido-jst-sm-4-pinos-4-fios/up/MLBU1985452711) |
| Ventilacao | Fans 120 mm — 4 pinos | 2 unidades | [Mercado Livre](https://mercadolivre.com/sec/2zHXMnQ) |
| Botoes | Botao com trava (Azul) | 1 unidade | [Mercado Livre](https://mercadolivre.com/sec/2JBbnZW) |
| Botoes | Botao sem trava (Amarelo) | 1 unidade | [Mercado Livre](https://mercadolivre.com/sec/223wKj9) |
| Video | Adaptador DP para HDMI Benfei | 1 unidade | [GitHub Repo](https://github.com/isaacalves/AMD-BC250-hdmi-displayport-compatibility) |
| Eletrica | Tomada de Forca Tripolar C14 | 1 unidade | [Mercado Livre](https://produto.mercadolivre.com.br/MLB-1167597495-10-tomada-de-forca-tripolar-as-02-c14-preta-_JM) |
| Eletrica | Cabo PCI-E 8 pinos (fonte) | 1 unidade | [Mercado Livre](https://mercadolivre.com/sec/2PYv3qZ) |
| Eletrica | Resistor 580 ohms (para fonte) | 1 unidade | [Mercado Livre](https://mercadolivre.com/sec/2ZoQ9BT) |

---

## Proximos Passos

1. Consulte os arquivos de modelagem 3D no repositório **CubeLAB**.
2. Realize a instalação do **Bazzite OS** para garantir a compatibilidade com sensores e GPU.
3. Utilize o banco de dados de cabos para garantir a saída de vídeo correta em sua TV ou monitor.
