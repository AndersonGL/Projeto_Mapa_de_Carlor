## Mapas Geográficos de Calor 

**O termo "mapa de calor" foi originalmente ultilizado para identificar áreas com maior ou menor grau de temperatura ambiental. Serve para dimensionar a refrigeração , isolamento térmico e indicar o melhor posicionamento de pessoas e máquinas em um ambiente. Porém, como o termo entrega um atendimento mais fácil dos gráficos de frio e calor, passou a ser ultilizado em outras áreas.** 

### Utilizando:


**Python e**
**Bibliotecas (Pandas, Plotly e Matplotlib)**


<h1 align="center">
  🌡️ Mapas Geográficos de Calor
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge"/>
  <img src="https://img.shields.io/badge/Plotly-5.x-3f4f75?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly Badge"/>
  <img src="https://img.shields.io/badge/Matplotlib-3.x-11557c?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib Badge"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License Badge"/>
</p>

> **Mapas de calor** nasceram para representar variações de temperatura ambiente—fundamentais no planejamento de refrigeração, isolamento térmico e disposição de pessoas ou máquinas.  
> Graças à sua leitura intuitiva (do *frio* ao *quente*), a técnica migrou para Business Intelligence, UX, logística, marketing e saúde ― qualquer área em que **padrões geoespaciais** precisem ser facilmente visualizados.

---

## 📑 Sumário
1. [Visão Geral](#visão-geral)
2. [Demonstração Rápida](#demonstração-rápida)
3. [Instalação](#instalação)
4. [Como Usar](#como-usar)
5. [Estrutura do Projeto](#estrutura-do-projeto)
6. [Contribuindo](#contribuindo)
7. [Licença](#licença)
8. [Contato](#contato)

---

## Visão Geral
Este repositório mostra como gerar **mapas de calor geográficos** usando:

- **Python 3.10+**
- **Pandas** – ETL e manipulação de dados  
- **Plotly** – visualizações interativas  
- **Matplotlib** – plots estáticos de alta qualidade  

O objetivo é entregar um pipeline enxuto para transformar bases de dados brutas em insights visuais claros e interativos.

---

## Demonstração Rápida

| 🥶 Frio | 🟢 Morno | 🔥 Quente |
|:--:|:--:|:--:|
| <img src="docs/demo_cold.png" width="230"/> | <img src="docs/demo_warm.png" width="230"/> | <img src="docs/demo_hot.png" width="230"/> |

*(Imagens meramente ilustrativas)*

---

## Instalação

> Requer **Python ≥ 3.10** e **pip**.

```bash
# 1. Clone o repositório
git clone https://github.com/<seu-user>/mapas-geograficos-calor.git
cd mapas-geograficos-calor

# 2. Crie e ative um ambiente virtual (opcional, mas recomendado)
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
.\.venv\Scripts\activate   # Windows

# 3. Instale as dependências
pip install -r requirements.txt


