# Polybar Theme Collection

Coleção de temas para **Polybar**, projetada para ser **modular, organizada e escalável**, permitindo a adição de novos temas e configurações auxiliares futuramente.

Atualmente, o repositório contém o tema **Spacecolor**.

---

## 📸 Preview

> *(adicione uma imagem de preview da barra abaixo)*

![Polybar Preview](./assets/preview.png)

---

## 🧩 Estrutura do Repositório

```
├── configs
│   └── picom
│       └── picom.conf
├── spacecolor
│   ├── colors.ini
│   ├── config.ini
│   ├── launch.sh
│   └── modules
│       ├── date.ini
│       ├── i3.ini
│       ├── network.ini
│       └── volume.ini
└── README.md
```

### 📁 `spacecolor/`

Contém o tema do Polybar, separado em:

* **colors.ini** → paleta de cores do tema
* **config.ini** → configuração principal da barra
* **launch.sh** → script de inicialização
* **modules/** → módulos organizados por responsabilidade

### 📁 `configs/`

Configurações auxiliares utilizadas em conjunto com o tema.
Atualmente inclui:

* **picom** (compositor)

Essa pasta é pensada para crescer futuramente com:

* rofi
* dunst
* outros componentes do desktop

---

## 🔧 Dependências

Certifique-se de ter instalado:

* **polybar**
* **picom** (necessário para efeitos visuais como transparência)
* **i3** (ou outro WM compatível, dependendo dos módulos usados)
* **NetworkManager** (para o módulo de rede)
* **pulseaudio / pipewire** (para o módulo de volume)

---

## 🚀 Como usar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repo.git
```

2. Inicie o tema:

```bash
cd spacecolor
./launch.sh
```

3. (Opcional) Copie a configuração do picom:

```bash
cp configs/picom/picom.conf ~/.config/picom/picom.conf
```

---

## 🎨 Temas

* **Spacecolor** — tema com foco em contraste, minimalismo e boa legibilidade

Novos temas poderão ser adicionados mantendo a mesma estrutura.

---

## 📌 Observações

* O repositório foi organizado para facilitar manutenção e expansão.
* Pull requests e sugestões são bem-vindos.

---

## 📜 Licença

MIT
