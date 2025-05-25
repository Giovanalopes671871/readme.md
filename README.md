# 💾 Processos de Redundância de Arquivos na Azure

## 🧭 Descrição do Processo

Neste projeto, explorei os diferentes tipos de **redundância de arquivos** oferecidos pela **Azure Storage**, com foco em entender como os dados são replicados e protegidos contra falhas regionais ou locais.

O processo incluiu:

1. Estudo dos modelos de redundância: LRS, ZRS, GRS e RA-GRS;
2. Simulação de envio de arquivos com diferentes configurações;
3. Análise das descrições e orientações da IA sobre os tipos de redundância mais indicados para cada cenário;
4. Reflexão sobre as vantagens e limitações de cada modelo.

---

## 🧠 Insights obtidos com a IA

- A IA apontou que **LRS** (Locally Redundant Storage) é suficiente para dados não críticos em regiões estáveis, mas **não recomendado para aplicações com alta disponibilidade**.
- **GRS** e **RA-GRS** oferecem maior segurança geográfica, sendo mais indicados para backups e recuperação de desastres.
- **ZRS** é ideal para aplicações críticas com alta disponibilidade dentro da mesma região, pois replica dados em zonas de disponibilidade diferentes.
- Aprendi que a escolha do tipo de redundância está diretamente ligada ao custo, criticidade do dado e à tolerância à falha.

---

## 💡 Possibilidades e aplicações

- Implementar backup automatizado com GRS para bancos de dados históricos;
- Usar RA-GRS em sistemas que exigem leitura contínua mesmo durante falhas regionais;
- Aplicar ZRS para sistemas web críticos com alta demanda de uptime;
- Criar testes de migração entre camadas de redundância com apoio de scripts automatizados.

---

## 🖼️ Prints do processo

### 1. Envio da sentença para análise:
![Envio de texto para IA](imagens/envio.png)

### 2. Análise da IA sobre a redundância:
![Análise da IA](imagens/resultado.png)

### 3. Reescrita do conteúdo com base nos feedbacks:
![Revisão final](imagens/reescrita.png)

---

## ✅ Conclusão

Compreender os **processos de redundância de arquivos na Azure** é essencial para garantir a **disponibilidade, durabilidade e confiabilidade** dos dados. A IA foi uma ferramenta valiosa para esclarecer conceitos técnicos, facilitar comparações e sugerir melhorias na forma de comunicar esses conteúdos
