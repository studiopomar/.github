<div align="center">

<br/>

<img src="https://raw.githubusercontent.com/studiopomar/.github/main/assets/logo.png" width="140" alt="Studio Pomar" />

# Studio Pomar

**Ferramentas e sintetizadores vocais de código aberto.**  
*Open-source vocal synthesis tools, DSP engines and audio research.*

<br/>

[![Organização](https://img.shields.io/badge/Studio-Pomar-c0392b?style=for-the-badge&labelColor=1e1e1e)](https://github.com/studiopomar)
[![Rust](https://img.shields.io/badge/Rust-DSP-d35400?style=for-the-badge&logo=rust&logoColor=white&labelColor=1e1e1e)](https://www.rust-lang.org/)
[![Ecossistema](https://img.shields.io/badge/Ecossistema-UTAU_%7C_OpenUtau_%7C_DiffSinger-27ae60?style=for-the-badge&labelColor=1e1e1e)](https://github.com/studiopomar)
[![Licença](https://img.shields.io/badge/Licen%C3%A7a-GPL_%2F_MIT-2c3e50?style=for-the-badge&labelColor=1e1e1e)](https://github.com/studiopomar)

<br/>

---

</div>

## Sobre

O **Studio Pomar** desenvolve ferramentas de código aberto para síntese vocal, processamento digital de sinais (DSP) e produção musical. O projeto busca criar softwares rápidos, estáveis e executados localmente, integrando o ecossistema de UTAU e OpenUtau com tecnologias modernas em Rust.

---

## Projetos

<div align="center">

| Repositório | Descrição | Tecnologias |
| :--- | :--- | :---: |
| **[kamafeu](https://github.com/studiopomar/kamafeu)** | Editor e sintetizador vocal com piano roll multifaixa, motor DSP nativo (TD-PSOLA) e edição de pitch. | `Rust` `DSP` |
| **[Copaiba-NEO](https://github.com/studiopomar/Copaiba-NEO)** | Editor multiplataforma de `oto.ini` para configuração e calibração de voicebanks. | `Rust` `GUI` |
| **[Copaiba-Lexicon-LTS](https://github.com/studiopomar/Copaiba-Lexicon-LTS)** | Visualizador de waveform e ferramentas de configuração para voicebanks UTAU/OpenUtau. | `C++` `Rust` |
| **Phonemizers & Samplers** | Conversores grafema-fonema (G2P) e motores de reamostragem focados em português brasileiro e outros idiomas. | `Rust` `WASM` |

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
   • Phonemizers        • Copaiba-NEO         • Mapeamentos OTO
   • Rust Audio Crate   • Lexicon Tools       • Testes de Síntese
```

---

## Diretrizes

- **Execução Local:** Softwares desenhados para rodar na máquina do usuário sem dependência de serviços fechados em nuvem.
- **Performance em Rust:** Módulos de áudio compilados nativamente, com gerenciamento seguro de memória e baixa latência.
- **Suporte Fonético:** Criação e manutenção de dicionários fonéticos e regras de transição para português brasileiro.

---

## Tecnologias

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![OpenUtau](https://img.shields.io/badge/OpenUtau-Compat%C3%ADvel-27ae60?style=flat-square)
![DiffSinger](https://img.shields.io/badge/DiffSinger-Suporte-f39c12?style=flat-square)

</div>

---

## Contribuição

Contribuições são bem-vindas em código, testes, fonética e documentação:

- **Código:** Desenvolvimento de DSP, correções e novas ferramentas em Rust.
- **Fonética:** Ajustes em dicionários fonéticos e regras de transição.
- **Voicebanks:** Testes de compatibilidade com diferentes configurações de voicebank.

Veja o guia detalhado em [CONTRIBUTING.md](CONTRIBUTING.md).

---

<div align="center">

<sub>Studio Pomar (código aberto e síntese vocal).</sub>

</div>
