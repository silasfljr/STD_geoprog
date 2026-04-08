# 🌱 Tábua de Risco – ZARC (Safra 2026)

## 📌 Informações Gerais

- **Nome da Base de Dados:** Tábua de Risco – Zoneamento Agrícola de Risco Climático  
- **Órgão:** Ministério da Agricultura, Pecuária e Abastecimento (MAPA)  
- **Unidade Responsável:** CGRA/DEGER/SPA  
- **Comitê:** Comitê Gestor de Dados Abertos (CGDA)  

📍 Endereço: Esplanada dos Ministérios, Bloco D, 2º andar, Brasília – DF  
📞 Telefone: (61) 3218-2089 / 0800 704 1995  
📧 E-mail: renan.monteiro@agro.gov.br  

---

## 🔗 Fonte dos Dados

- **Catálogo:**  
http://dados.agricultura.gov.br/dataset/6d3d141c-885e-41a4-ab7f-dc8ff323b96f/resource/a8875ff8-fe4d-4c3c-b1a1-3b19c32916f1/download/dados-abertos-tabua-de-risco.csv

- **Periodicidade:** Atualização diária  

---

## 📖 Descrição

Os dados referem-se às **datas de plantio indicadas pelo ZARC**, considerando:

- Safra  
- Cultura  
- Manejo  
- Clima  
- Grupo (ciclo)  
- Solo  
- UF  
- Município  

Essas informações são publicadas nas **Portarias do ZARC** pela Secretaria de Política Agrícola.

---

## 🏷️ Categorias

- Agropecuária, Pesca e Extrativismo  
- Agricultura e atividades relacionadas  

---

## 📂 Estrutura dos Dados

### 📊 Colunas

| Coluna | Descrição |
|--------|----------|
| Nome_cultura | Nome da cultura |
| SafraIni | Ano inicial da safra |
| SafraFin | Ano final da safra |
| Cod_Cultura | Código da cultura |
| Cod_Ciclo | Código do ciclo |
| Cod_Solo | Código do solo |
| geocodigo | Código IBGE do município |
| UF | Unidade Federativa |
| municipio | Nome do município |
| Cod_Outros_Manejos | Código do manejo |
| Nome_Outros_Manejos | Nome do manejo |
| Cod_Clima | Código do clima |
| Nome_Clima | Nome do clima |
| Cod_Munic | Código no SICOR |
| Cod_Meso | Código da mesorregião (IBGE) |
| Cod_Micro | Código da microrregião (IBGE) |
| Portaria | Número e data da portaria |
| dec1 a dec36 | Janelas de plantio (decêndios) |

---

## 📋 Tabelas de Referência

### 🌿 Ciclo (`Cod_Ciclo`)

| Código | Descrição |
|--------|----------|
| 13 | Perene |
| 19 | Semiperene |
| 20 | Grupo I |
| 21 | Grupo II |
| 22 | Grupo III |
| 24 | Grupo IV |
| 25 | Grupo V |
| 26 | Grupo VI |

---

### 🌱 Solo (`Cod_Solo`)

| Código | Descrição |
|--------|----------|
| 1 | Arenoso |
| 2 | Textura Média |
| 3 | Argiloso |
| 11 | AD1 |
| 12 | AD2 |
| 13 | AD3 |
| 14 | AD4 |
| 15 | AD5 |
| 16 | AD6 |

---

### 🚜 Manejo (`Cod_Outros_Manejos`)

| Código | Descrição |
|--------|----------|
| 1 | Sequeiro |
| 2 | Irrigado |
| 3 | Irrigado com controle de geada |

---

### 🌦️ Clima (`Cod_Clima`)

| Código | Descrição |
|--------|----------|
| 0 | Não se aplica |
| 1 | Alta disponibilidade de frio |
| 2 | Média disponibilidade de frio |
| 3 | Baixa disponibilidade de frio |
| 4 | Semiárido |
| 5 | Clima ameno |
| 6 | Clima quente |
| 7 | Tropical |
| 8 | Subtropical ameno |
| 9 | Subtropical frio |
| 11 | Subtropical |

---

## 📅 Janelas de Plantio

- Representadas por **36 decêndios**
- Cada decêndio corresponde a um período de aproximadamente 10 dias
- Cobrem todo o ano agrícola

---

## 💾 Armazenamento dos Dados

- **Servidor:** MASRV2175  
- **Caminho:**  C:\ClusterStorage\Volume1\QlikView\SPA\Outras-Fontes\
- **Arquivo:**  dados-abertos-tabua-de-risco.csv

---

## 📤 Disponibilidade

Todos os dados disponibilizados no arquivo:
dados-abertos-tabua-de-risco.csv

---

## 📬 Responsável Técnico

- **Nome:** Renan de Sousa Monteiro  
- **Unidade:** CGRA/DEGER/SPA  
- **Telefone:** (61) 3218-2682  
- **E-mail:** renan.monteiro@agricultura.gov.br  

---

## 🚀 Possíveis Aplicações

- Planejamento agrícola  
- Seguro rural (Proagro)  
- Modelagem de risco climático  
- Agricultura de precisão  
- Integração com SIG (QGIS, GEE)  
- Estudos de mudanças climáticas  

---
