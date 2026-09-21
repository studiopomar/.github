<div align="center">

<br/>

<img src="https://raw.githubusercontent.com/studiopomar/.github/main/assets/logo.png" width="150" alt="Studio Pomar" />

# Studio Pomar

**Tecnologia e sintetizadores vocais de código aberto cultivados para autonomia artística.**  
*Open-source vocal synthesis engines, DSP architecture, and creative sovereignty.*

<br/>

[![Organização](https://img.shields.io/badge/Studio-Pomar-c0392b?style=for-the-badge&labelColor=1e1e1e)](https://github.com/studiopomar)
[![Manifesto](https://img.shields.io/badge/MANIFESTO-O_Ritmo_da_Terra-27ae60?style=for-the-badge&labelColor=1e1e1e)](https://github.com/studiopomar)
[![Engenharia](https://img.shields.io/badge/ENGINE-Rust_%26_DSP-d35400?style=for-the-badge&logo=rust&logoColor=white&labelColor=1e1e1e)](https://www.rust-lang.org/)
[![Ecossistema](https://img.shields.io/badge/ECOSSISTEMA-UTAU_%7C_OpenUtau_%7C_DiffSinger-f39c12?style=for-the-badge&labelColor=1e1e1e)](https://github.com/studiopomar)
[![Licença](https://img.shields.io/badge/CÓDIGO-Aberto_%26_Livre-2c3e50?style=for-the-badge&labelColor=1e1e1e)](https://github.com/studiopomar)

<br/>

---

</div>

> *"A tecnologia da voz cantada deve ser como a terra: fértil, duradoura, acessível a quem planta e livre de cercas proprietárias."*  
> — **Manifesto Studio Pomar**

---

## O Conceito Pomar

O **Studio Pomar** é um laboratório de engenharia de áudio e desenvolvimento de software voltado para a criação de um ecossistema completo e independente de **síntese vocal**. 

Assim como um pomar exige cuidado com o solo, irrigação e tempo para florescer, estruturamos nossas ferramentas em camadas integradas: desde a base matemática do processamento de sinais até as interfaces táteis com as quais músicos e produtores dão vida a novas vozes.

<br/>

```
                             [ Studio Pomar ]
                                    │
         ┌──────────────────────────┼──────────────────────────┐
         │                          │                          │
   [ AS RAÍZES ]              [ O TRONCO ]               [ OS FRUTOS ]
   Motores & DSP              Softwares & GUI            Música & Vozes
   ──────────────────         ──────────────────         ──────────────────
   • Rust Core DSP            • Kamafeu Synthesizer      • Voicebanks PT-BR
   • TD-PSOLA Resynthesis     • Copaiba-NEO (OTO Editor) • Dicionários Fonéticos
   • Phonemizer Engines       • Copaiba-Lexicon Tools    • Produção Independente
```

---

## O Ecossistema

<div align="center">

| Módulo / Repositório | Propósito e Características | Tecnologias |
| :--- | :--- | :---: |
| **[kamafeu](https://github.com/studiopomar/kamafeu)** | **Estação de Trabalho & Sintetizador Vocal**<br/>Piano roll multifaixa, motor DSP nativo de alta fidelidade, edição de curvas de pitch e renderização em tempo real. | `Rust` `DSP` `TD-PSOLA` |
| **[Copaiba-NEO](https://github.com/studiopomar/Copaiba-NEO)** | **Editor de Configuração e Calibração (oto.ini)**<br/>Ferramenta ágil e multiplataforma para corte, sincronia e parametrização milimétrica de amostras vocais. | `Rust` `GUI` `Audio` |
| **[Copaiba-Lexicon-LTS](https://github.com/studiopomar/Copaiba-Lexicon-LTS)** | **Visualizador de Forma de Onda & Ferramentas de Voicebank**<br/>Renderização com aceleração gráfica, visualização espectral e utilitários de compatibilidade com UTAU e OpenUtau. | `C++` `Rust` `Hardware Accel` |
| **Phonemizers & Samplers** | **Processamento Fonético e Reamostragem**<br/>Motores de transcrição grafema-fonema otimizados para português brasileiro e estruturas fonológicas complexas. | `Rust` `WASM` `NLP` |

</div>

---

## Nossos Pilares de Desenvolvimento

### 1. Soberania e Preservação Digital
Nenhum criador deve perder seu instrumento por mudanças de termos de serviço ou servidores desativados. Nossas ferramentas rodam localmente, respeitam a privacidade e são desenhadas para durar décadas.

### 2. Engenharia de Baixa Latência em Rust
Todo o núcleo crítico de processamento de áudio é escrito em Rust, garantindo segurança de memória, ausência de coletor de lixo (*garbage collector pauses*) e compatibilidade nativa tanto em desktops (Linux, macOS, Windows) quanto na web (WebAssembly).

### 3. Brasilidade e Diversidade Fonética
Desenvolvemos soluções pioneiras para acomodar as particularidades da língua portuguesa, seus encontros consonantais, vogais nasais e riqueza rítmica na síntese vocal cantada.

---

## Tecnologias e Padrões

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![OpenUtau](https://img.shields.io/badge/OpenUtau-Padrão_Compatível-27ae60?style=flat-square)
![DiffSinger](https://img.shields.io/badge/DiffSinger-Suporte_Integrado-f39c12?style=flat-square)

</div>

---

## Como Contribuir com o Pomar

O Studio Pomar é construído por e para a comunidade. Há espaço para diversas formas de colaboração:

- **Programação de Áudio & Rust:** Otimização de algoritmos de pitch shifting, interpolação, DSP e interfaces.
- **Linguística & Fonética:** Expansão e refinamento dos dicionários fonéticos e conversores fonemizadores.
- **Voicebanking & Gravação:** Criação de novos bancos de voz abertos, calibração de arquivos de configuração e testes acústicos.
- **Design & Documentação:** Aperfeiçoamento de usabilidade, guias em português e documentação técnica.

---

<div align="center">

```
             .----------------------------------------------------.
             |  Studio Pomar — O Ritmo da Terra em Código Aberto  |
             '----------------------------------------------------'
```

<sub>Desenvolvido de forma colaborativa pela comunidade <b>Studio Pomar</b>.</sub>

</div>
