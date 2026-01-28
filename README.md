
# MDS-NMS - Escala de Avaliação Não Motora (Edição Eletrônica)

Esta é uma aplicação web de página única (SPA) desenvolvida para facilitar a aplicação da **Escala de Avaliação Não Motora (MDS-NMS)** da *International Parkinson and Movement Disorder Society*. A ferramenta automatiza o cálculo de escores e permite a exportação de dados para fins clínicos e de pesquisa.

## 🚀 Funcionalidades

* **Interface Interativa:** Navegação dividida por domínios (A até M) conforme o protocolo oficial.
* **Cálculo Automático:** Multiplicação instantânea de Frequência × Gravidade por item e somatório por domínio.
* **Seção NMF (Flutuações):** Subescala específica para avaliar mudanças entre estados "On" e "Off".
* **Exportação Multiformato:**
* **PDF:** Relatório clínico formatado para impressão ou prontuário.
* **CSV:** Planilha estruturada para análise estatística.
* **JSON:** Preservação integral dos dados brutos da sessão.


* **Privacidade:** Processamento 100% *client-side*. Nenhum dado pessoal ou clínico é enviado a servidores externos.

## 🛠️ Tecnologias Utilizadas

A aplicação foi construída utilizando uma stack moderna e leve, carregada via CDN para garantir portabilidade:

* **React (v18):** Gerenciamento de estado e interface do usuário.
* **Tailwind CSS:** Estilização responsiva e moderna.
* **Babel:** Compilação do JSX em tempo de execução no navegador.
* **jsPDF & jsPDF-AutoTable:** Geração dinâmica de relatórios em PDF.

## 📋 Estrutura da Escala

O sistema cobre todos os 13 domínios da tradução oficial para português:

* **A-F:** Depressão, Ansiedade, Apatia, Psicose, Controle de Impulso e Cognição.
* **G-J:** Hipotensão Ortostática, Urinário, Sexual e Gastrointestinal.
* **K-M:** Sono e Vigília, Dor e Outros (Peso, Olfato, Fadiga).

---

## 🖥️ Como Utilizar

1. **Clone ou baixe** o arquivo `.html`.
2. **Abra o arquivo** em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
3. **Aceite o termo de consentimento** inicial para acessar a interface de avaliação.
4. **Preencha os dados** do paciente e realize a entrevista:
* A gravidade só será habilitada se a frequência for superior a 0.
* Os itens M1 e M2 seguem a regra de frequência binária (Presente/Ausente).


5. **Exporte os resultados** na aba "Relatório & Exportação".

## ⚖️ Aviso Legal

> **Importante:** Esta aplicação é uma ferramenta de apoio à pesquisa. Os resultados gerados não substituem o diagnóstico clínico realizado por um profissional de saúde qualificado. O uso desta escala deve seguir as diretrizes da *International Parkinson and Movement Disorder Society (MDS)*.

---

## 📄 Licença

Este projeto é destinado ao uso acadêmico e clínico. Verifique os direitos de uso da escala junto à [MDS](https://www.movementdisorders.org/) para aplicações comerciais ou estudos multicêntricos.
