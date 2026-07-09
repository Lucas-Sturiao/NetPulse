# Internet Speed Test

Um aplicativo desktop desenvolvido em **Python** para medir a velocidade da conexão com a internet por meio de uma interface moderna criada com **CustomTkinter**.

O aplicativo realiza testes de **Download**, **Upload** e **Ping**, além de armazenar automaticamente um histórico dos resultados em um arquivo CSV para futuras consultas.

---

## ✨ Funcionalidades

- 📡 Teste de velocidade de Download
- ⬆️ Teste de velocidade de Upload
- 📶 Medição de Ping (Latência)
- 🎨 Interface moderna com CustomTkinter
- ⚡ Execução dos testes em uma thread separada para evitar travamentos
- 📊 Histórico automático dos testes realizados
- 📁 Armazenamento dos resultados em arquivo CSV
- 🔄 Atualização do histórico diretamente pela interface
- 📈 Animação dos valores durante a exibição dos resultados

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- Tkinter
- CustomTkinter
- Speedtest-cli
- Threading
- CSV
- Datetime
- OS

---

## ⚙️ Instalação

Clone o repositório:

```bash
git clone https://github.com/lucas-sturiao/velora.git
```

Acesse a pasta do projeto:

```bash
cd internet-speed-test
```

### Crie um ambiente virtual (Opcional)

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### Linux/macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

---

## ▶️ Executando o Projeto

```bash
python main.py
```

---

## 📊 Histórico dos Testes

Após cada teste realizado, o aplicativo cria (caso não exista) e atualiza automaticamente o arquivo:

```text
historico.csv
```

Cada registro contém:

| Campo | Descrição |
|-------|-----------|
| Data/Hora | Momento em que o teste foi realizado |
| Download | Velocidade de download (Mbps) |
| Upload | Velocidade de upload (Mbps) |
| Ping | Latência em milissegundos (ms) |

---

## 📌 Melhorias Futuras

- [ ] Exportação do histórico para PDF
- [ ] Gráfico de evolução da velocidade
- [ ] Seleção manual do servidor
- [ ] Histórico com filtros
- [ ] Informações sobre IP público
- [ ] Informações detalhadas do servidor utilizado
- [ ] Tema claro/escuro
- [ ] Comparação entre testes

---

## 🤝 Contribuições

Contribuições são sempre bem-vindas!

Caso encontre algum problema ou tenha sugestões de melhorias:

1. Faça um Fork do projeto.
2. Crie uma nova Branch.
3. Faça suas alterações.
4. Envie um Pull Request.
