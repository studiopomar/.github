# Guia de Contribuição (Studio Pomar)

Instruções para contribuir com os projetos da organização.

---

## Áreas de Contribuição

1. **Desenvolvimento (Rust, C++, Python):** DSP, síntese em tempo real, UI e WebAssembly.
2. **Fonética:** Dicionários fonéticos (PT-BR e outros idiomas) e regras de transição.
3. **Voicebanks:** Testes de ressíntese, calibração de `oto.ini` e validação de áudio.
4. **Documentação:** Guias de uso, documentação de APIs e manuais.
5. **Relato de Bugs:** Issues detalhadas com passos de reprodução e logs.

---

## Padrões de Código

Para repositórios em Rust:

- **Formatação:**
  ```bash
  cargo fmt --all -- --check
  ```
- **Linter:**
  ```bash
  cargo clippy --all-targets -- -D warnings
  ```
- **Testes:**
  ```bash
  cargo test
  ```

---

## Fluxo de Trabalho (Git)

1. Crie um fork do repositório.
2. Crie uma branch para sua alteração (`git checkout -b feature/nome` ou `git checkout -b fix/nome`).
3. Faça commits com mensagens diretas (ex: `feat: add cubic interpolation to resampler`, `fix: correct offset parsing in oto.ini`).
4. Abra um Pull Request descrevendo as mudanças feitas.

---

## Dicionários e Fonemas

Ao sugerir alterações em dicionários fonéticos:
- Mantenha a consistência com a notação fonética padrão do projeto.
- Teste a saída fonética com bancos de voz de referência.
