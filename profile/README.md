<div align="center">

# Studio POMAR

**Tecnologia de síntese vocal aberta, moderna e com foco em autonomia.**  
*Open-source vocal synthesis tools, DSP engines & audio research.*

---

[![GitHub followers](https://img.shields.io/github/followers/studiopomar?label=Followers&style=for-the-badge&color=2e7d32&labelColor=1a1a1a)](https://github.com/studiopomar)
[![Rust](https://img.shields.io/badge/Rust-100%25-dea584?style=for-the-badge&logo=rust&logoColor=white&labelColor=1a1a1a)](https://www.rust-lang.org/)
[![Ecosystem](https://img.shields.io/badge/Ecosystem-UTAU%20%7C%20OpenUtau%20%7C%20DiffSinger-4caf50?style=for-the-badge&labelColor=1a1a1a)](https://github.com/studiopomar)
[![License](https://img.shields.io/badge/License-GPL%20%2F%20MIT-brightgreen?style=for-the-badge&labelColor=1a1a1a)](https://github.com/studiopomar)

</div>

---

## Sobre o Studio POMAR

O **Studio POMAR** é um coletivo e laboratório de desenvolvimento dedicado à criação de ferramentas abertas para **síntese vocal, processamento digital de sinais (DSP) e produção musical independente**.

Com base no manifesto *"O Ritmo da Terra"*, o projeto atua para que a tecnologia de voz cantada digital seja acessível, duradoura, expressiva e livre de restrições proprietárias. O foco é unir o ecossistema consolidado (UTAU, OpenUtau) a arquiteturas modernas em **Rust**, DSP em tempo real e novos paradigmas de síntese.

---

## Projetos Principais

<div align="center">

| Projeto | Descrição | Stack |
| :--- | :--- | :---: |
| **[kamafeu](https://github.com/studiopomar/kamafeu)** | Editor e sintetizador vocal moderno com piano roll multifaixa, motor DSP nativo (TD-PSOLA) e edição de curvas de pitch. | `Rust` `DSP` |
| **[Copaiba-NEO](https://github.com/studiopomar/Copaiba-NEO)** | Editor de `oto.ini` e utilitários multiplataforma para calibração precisa de voicebanks. | `Rust` `GUI` |
| **[Copaiba-Lexicon-LTS](https://github.com/studiopomar/Copaiba-Lexicon-LTS)** | Ferramentas de configuração, visualização de waveform com aceleração por hardware e integração com UTAU/OpenUtau. | `C++` `Rust` |
| **Phonemizers & Core DSP** | Motores de fonetização de alta performance, com suporte dedicado ao português brasileiro e a múltiplos idiomas. | `Rust` `WASM` |

</div>

---

## Diretrizes e Pilares

```
               ┌───────────────────────────────┐
               │         STUDIO POMAR          │
               └──────────────┬────────────────┘
         ┌────────────────────┼────────────────────┐
         ▼                    ▼                    ▼
     SOBERANIA            PERFORMANCE          EXPRESSÃO
  Ferramentas 100%      Módulos e engines     Foco na nuance da
  abertas, perenes e     em Rust puro para    voz cantada e na
     acessíveis.         DSP de baixa latência. fonética regional.
```

- **Autonomia e Preservação:** Softwares executados localmente, garantindo perenidade para os criadores e sem dependência de serviços fechados.
- **Engenharia em Rust:** Código modular, seguro contra falhas de memória e de alta performance para processamento em tempo real e compilação para WebAssembly.
- **Interoperabilidade:** Suporte a padrões abertos de voicebanks, dicionários fonéticos e integração fluida entre diferentes plataformas de síntese.

---

## Tecnologias Utilizadas

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![OpenUtau](https://img.shields.io/badge/OpenUtau-Compatible-4caf50?style=flat-square)

</div>

---

## Como Contribuir

Colaborações são bem-vindas em todas as áreas do projeto:

- **Relato de Bugs e Sugestões:** Utilize as *Issues* e os fóruns de discussão em cada repositório para reportar falhas ou propor melhorias.
- **Desenvolvimento de Software:** Verifique as tarefas com as tags `good first issue` e `help wanted`.
- **Validação e Testes:** Ajude na validação do Kamafeu e do Copaiba com diferentes configurações de voicebanks e sistemas operacionais.

---

<div align="center">

<sub>Studio POMAR — Código aberto e tecnologia vocal independente.</sub>

</div>
