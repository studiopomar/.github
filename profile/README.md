<div align="center">

<br/>

<img src="https://raw.githubusercontent.com/studiopomar/.github/main/assets/logo.png" width="140" alt="Studio Pomar" />

# Studio Pomar

**Ferramentas e sintetizadores vocais de código aberto.**  
*Open-source vocal synthesis tools, DSP engines and audio research.*

<br/>

[![Website](https://img.shields.io/badge/Website-studiopomar.github.io-27ae60?style=for-the-badge&labelColor=1e1e1e)](https://studiopomar.github.io/)
[![Rust](https://img.shields.io/badge/Rust-DSP-d35400?style=for-the-badge&logo=rust&logoColor=white&labelColor=1e1e1e)](https://www.rust-lang.org/)
[![Ecossistema](https://img.shields.io/badge/Ecossistema-UTAU_%7C_OpenUtau_%7C_DiffSinger-f39c12?style=for-the-badge&labelColor=1e1e1e)](https://github.com/studiopomar)
[![Licença](https://img.shields.io/badge/Licen%C3%A7a-GPL_%2F_MIT-2c3e50?style=for-the-badge&labelColor=1e1e1e)](https://github.com/studiopomar)

<br/>

---

</div>

## Sobre

O **Studio Pomar** desenvolve ferramentas de código aberto para síntese vocal, processamento digital de sinais (DSP) e produção musical. O projeto busca criar softwares rápidos, estáveis e executados localmente, integrando o ecossistema de UTAU e OpenUtau com tecnologias modernas em Rust, C++, C e WebAssembly.

Acesse o portal oficial em: **[studiopomar.github.io](https://studiopomar.github.io/)**

---

## Projetos em Destaque

<div align="center">

| Repositório | Descrição | Stack |
| :--- | :--- | :---: |
| **[kamafeu](https://github.com/studiopomar/kamafeu)** | Editor e sintetizador vocal com piano roll multifaixa, motor DSP nativo (TD-PSOLA) e edição de pitch. | `Rust` `DSP` `egui` |
| **[Copaiba-NEO](https://github.com/studiopomar/Copaiba-NEO)** | Editor multiplataforma de `oto.ini` para calibração de voicebanks e análise FFT em tempo real. | `Rust` `Wasm` `WebAudio` |
| **[Copaiba-Lexicon-LTS](https://github.com/studiopomar/Copaiba-Lexicon-LTS)** | Visualizador de waveform e ferramentas de alto nível para voicebanks UTAU/OpenUtau. | `Python` `Waveform` |
| **[macres-rt](https://github.com/studiopomar/macres-rt)** | Port cross-platform de alta performance do resampler UTSU (Desktop & Mobile). | `C++` `C` `DSP` |
| **[w4u-rt](https://github.com/studiopomar/w4u-rt)** | Port nativo multiplataforma do vocoder WORLD (world4utau). | `C++` `C` `Vocoder` |
| **[straycat-rt](https://github.com/studiopomar/straycat-rt)** | Port moderno em Rust do resampler straycat baseado em WORLD. | `Rust` `DSP` |
| **[studiopomar.github.io](https://github.com/studiopomar/studiopomar.github.io)** | Portal oficial, landing page e documentações do Studio Pomar. | `TypeScript` `Web` |

</div>

---

## Arquitetura

```
                        [ Studio Pomar ]
                               │
         ┌─────────────────────┼─────────────────────┐
         ▼                     ▼                     ▼
     Core & DSP           Aplicações            Voicebanks
   ──────────────       ──────────────        ──────────────
   • TD-PSOLA Engine    • kamafeu (Editor)    • Dicionários PT-BR
   • Resamplers (-rt)   • Copaiba-NEO         • Mapeamentos oto.ini
   • Rust Audio Crate   • Lexicon Tools       • Testes de Síntese
```

---

## Diretrizes

- **Execução Local & Determinística:** Softwares desenhados para rodar diretamente na máquina do usuário sem dependência de serviços externos.
- **Performance Nativa em Rust & C/C++:** Módulos de áudio compilados nativamente, com gerenciamento eficiente de memória e ultra-baixa latência.
- **Inovação Fonética:** Criação e manutenção de metodologias fonéticas, dicionários G2P e regras de transição.

---

## Tecnologias & Ecossistema

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![OpenUtau](https://img.shields.io/badge/OpenUtau-Compat%C3%ADvel-27ae60?style=flat-square)
![DiffSinger](https://img.shields.io/badge/DiffSinger-Suporte-f39c12?style=flat-square)

</div>

---

## Contribuição

Contribuições são bem-vindas em código, testes, fonética e documentação:

- **Código:** Desenvolvimento de DSP, correções de áudio e ferramentas em Rust/C++.
- **Fonética:** Ajustes em dicionários fonéticos, reclists e regras de transição.
- **Voicebanks:** Testes de compatibilidade com diferentes configurações de voicebanks.

Veja o guia detalhado em [CONTRIBUTING.md](CONTRIBUTING.md).

---

<div align="center">

<sub>Studio Pomar (código aberto e síntese vocal).</sub>

</div>
