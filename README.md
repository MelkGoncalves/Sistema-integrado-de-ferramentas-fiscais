# Sistema-integrado-de-ferramentas-fiscais

# 🧾 Controle KL Contabilidade — Ferramentas Fiscais (PER/DCOMP, Notas INSS, Restituição)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Status](https://img.shields.io/badge/status-ativo-success)
![Version](https://img.shields.io/badge/version-1.0.0-blue)

---

## 📘 Descrição
Conjunto de **ferramentas fiscais em HTML/CSS/JavaScript** voltadas para automatizar a extração, edição e exportação de informações fiscais da **KL Contabilidade**, com foco em **PER/DCOMP**, **INSS**, e **Restituição**.

Essas aplicações funcionam **diretamente no navegador**, sem necessidade de back-end, tornando o processo rápido, acessível e portátil. :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1}

---

## 📂 Projetos incluídos

| Ferramenta | Descrição | Arquivo |
|-------------|------------|---------|
| **Extrator e Editor PER/DCOMP** | Lê PDFs da Receita, extrai dados (CNPJ, número, competência, créditos, Selic etc.) e permite editar/exportar. | `EXTRATOR-E-EDITOR-PERD-COMP.html` :contentReference[oaicite:2]{index=2} |
| **Leitor de Notas Fiscais INSS** | Lê planilhas CSV, soma valores de INSS, filtra e gera relatórios vinculados ao PER/DCOMP. | `NOTA-INSS+SOMA-PERDCOMP.html` :contentReference[oaicite:3]{index=3} |
| **Extrator de Restituição** | Extrai informações fiscais de PDFs relacionados à restituição e EFD-REINF. | `EXTRATOR-DE-RESTITUIÇÃO.html` :contentReference[oaicite:4]{index=4} |
| **Página Inicial (Hub)** | Interface central que reúne e organiza todas as ferramentas. | `index.html` :contentReference[oaicite:5]{index=5} |

---

## ⚙️ Funcionalidades Principais
- 📄 Upload e leitura de **PDFs** usando `pdf.js`. :contentReference[oaicite:6]{index=6}  
- 🧮 Extração automática de campos fiscais via **Regex**. :contentReference[oaicite:7]{index=7}  
- ✏️ Edição direta dos dados na interface.  
- 📊 Exportação em **Excel (.xlsx)**, **CSV** e **PDF** (usando `jsPDF` e `SheetJS`). :contentReference[oaicite:8]{index=8}  
- 📆 Filtros avançados (data, CNPJ, competência, situação). :contentReference[oaicite:9]{index=9}  
- 💾 Funciona totalmente offline (após o carregamento das bibliotecas).

---

## 🧠 Tecnologias Utilizadas
- HTML5, CSS3 e JavaScript Vanilla  
- [pdf.js](https://mozilla.github.io/pdf.js/) – Leitura de PDFs  
- [jsPDF](https://github.com/parallax/jsPDF) – Geração de PDFs  
- [SheetJS (xlsx)](https://sheetjs.com/) – Manipulação de planilhas Excel  
- [html2canvas](https://html2canvas.hertzen.com/) – Captura de telas para exportação  
- Regex para análise de texto fiscal  

---

## 💻 Como Usar
1. Faça o clone do repositório:
   ```bash
   git clone https://github.com/<seu-usuario>/<seu-repositorio>.git
/
├─ index.html                         # Hub principal :contentReference[oaicite:10]{index=10}
├─ EXTRATOR-E-EDITOR-PERD-COMP.html   # Extrator + Editor PER/DCOMP :contentReference[oaicite:11]{index=11}
├─ NOTA-INSS+SOMA-PERDCOMP.html       # Leitor de notas fiscais (CSV) :contentReference[oaicite:12]{index=12}
├─ EXTRATOR-DE-RESTITUIÇÃO.html       # Extrator de restituição :contentReference[oaicite:13]{index=13}
└─ /assets                            # Scripts, estilos, ícones (opcional)
