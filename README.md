# Oscilações, Ondas e Eletromagnetismo — Resoluções Comentadas

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/7/7d/Standing_wave_2.gif" alt="Animação de onda estacionária" width="420">
</p>

Trabalho desenvolvido em **LaTeX** para a disciplina de **Ondas e Antenas**, contendo resoluções comentadas de exercícios dos volumes 3 e 4 do livro *Fundamentos de Física*, de Halliday, Resnick e Walker.

---

## 📚 Conteúdo

As resoluções abordam tópicos relacionados a:

- Oscilações eletromagnéticas;
- Circuitos \(LC\), \(RC\) e \(RLC\);
- Ondas e interferência;
- Óptica geométrica;
- Difração e polarização;
- Eletromagnetismo;
- Campos magnéticos e corrente de deslocamento.

As questões foram organizadas da seguinte forma:

- **Capítulo 31** — questões 14, 21, 47, 58 e 73;
- **Capítulo 32** — questões 10, 25, 51, 58 e 69;
- **Capítulo 33** — questões 18, 29, 50, 59 e 85;
- **Capítulo 34** — questões 17, 28, 37, 57 e 65.

---

## 📁 Estrutura do Projeto

```text
.
├── main.tex
├── chapters/
│   ├── capa.tex
│   ├── referencias.tex
│   ├── anexos.tex
│   ├── Cap31/
│   ├── Cap32/
│   ├── Cap33/
│   └── Cap34/
├── figures/
│   ├── logo-ufc.PNG
│   ├── logo-ufc-horizontal.png
│   └── figuras das questões
├── style/
│   ├── pacotes.tex
│   └── comandos.tex
└── README.md
```

---

## ✍️ Organização do Projeto

- A capa do trabalho fica em:

```text
chapters/capa.tex
```

- As referências bibliográficas ficam em:

```text
chapters/referencias.tex
```

- Os pacotes LaTeX utilizados estão em:

```text
style/pacotes.tex
```

- Comandos personalizados e configurações visuais estão em:

```text
style/comandos.tex
```

- Cada resolução fica separada dentro da pasta correspondente ao capítulo. Exemplo:

```text
chapters/Cap33/questao-85.tex
```

---

## 📖 Referências

HALLIDAY, David; RESNICK, Robert; WALKER, Jearl.  
**Fundamentos de física: eletromagnetismo**. 8. ed. Rio de Janeiro: LTC, 2009. v. 3.

HALLIDAY, David; RESNICK, Robert; WALKER, Jearl.  
**Fundamentos de física: óptica e física moderna**. 8. ed. Rio de Janeiro: LTC, 2009. v. 4.
