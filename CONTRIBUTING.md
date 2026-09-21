# Guia de Contribuição — Studio Pomar

Agradecemos o seu interesse em contribuir com o **Studio Pomar**! Nossos projetos são criados de forma aberta e colaborativa, visando fornecer ferramentas robustas, acessíveis e soberanas para a síntese vocal e processamento de áudio.

---

## Formas de Contribuir

Você não precisa saber programar para contribuir. Aceitamos colaborações em:

1. **Desenvolvimento de Software:** Módulos em Rust, DSP, interfaces gráficas, integrações e WebAssembly.
2. **Linguística & Fonética:** Expansão e correção de dicionários fonéticos (PT-BR e outros idiomas), regras de transição e fonemizadores.
3. **Voicebanking & Calibração:** Gravação de bancos de voz abertos, ajuste de arquivos `oto.ini`, testes de ressíntese e consistência timbral.
4. **Documentação & Tradução:** Elaboração de tutoriais, manuais de uso, guias de voicebank e traduções.
5. **Relato de Problemas:** Testes em diferentes sistemas operacionais e envio de relatórios de bugs detalhados.

---

## Padrões de Código (Rust)

Para manter a consistência e qualidade do ecossistema:

- **Formatação:** Todo o código Rust deve seguir o `rustfmt`.
  ```bash
  cargo fmt --all -- --check
  ```
- **Linter:** O código deve passar sem warnings no `clippy`.
  ```bash
  cargo clippy --all-targets -- -D warnings
  ```
- **Testes:** Garanta que os testes unitários e de integração passem antes de abrir uma PR.
  ```bash
  cargo test
  ```
- **Processamento de Áudio & DSP:** 
  - Evite alocações dinâmicas de memória no loop crítico de processamento de áudio em tempo real.
  - Assegure que as funções sejam determinísticas e devidamente documentadas com suas unidades físicas (Hz, ms, semitons, dB).

---

## Fluxo de Trabalho com Git

1. **Faça um Fork** do repositório desejado.
2. **Crie uma branch** com um nome descritivo:
   ```bash
   git checkout -b feature/nome-da-funcionalidade
   # ou
   git checkout -b fix/correcao-de-bug
   ```
3. **Escreva mensagens de commit claras** seguindo o padrão Conventional Commits:
   - `feat: adiciona algoritmo de interpolação cúbica no resampler`
   - `fix: corrige offset incorreto na leitura do oto.ini`
   - `docs: atualiza guia de instalação no macOS`
   - `phonetics: adiciona regra de ditongação nasal para PT-BR`
4. **Abra um Pull Request** detalhando as alterações e referenciando as *Issues* relacionadas.

---

## Dicionários e Fonemas

Ao submeter correções ou adições a dicionários fonéticos:
- Utilize a notação fonética padrão do projeto (SAMPA / X-SAMPA / ARPAbet adaptado).
- Documente variações dialetais quando relevante.
- Teste a saída fonética com frases reais e bancos de voz de referência.

---

## Código de Conduta

Todos os participantes devem aderir ao nosso [Código de Conduta](CODE_OF_CONDUCT.md) para garantir um ambiente acolhedor, respeitoso e livre de assédio.
