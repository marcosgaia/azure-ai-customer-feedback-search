# 🛡️ Projeto: Vigilância Inteligente em Condomínios com Azure e Visão Computacional

Este projeto demonstra o uso de **Inteligência Artificial aplicada à segurança condominial**, utilizando **OCR** e **reconhecimento facial** com suporte da **nuvem Azure** para identificar situações de risco, comportamentos suspeitos e acesso restrito.

---

## 🎯 Objetivo

Utilizar **Azure Cognitive Services** combinados com **técnicas de visão computacional** para:

- Detectar pessoas em áreas restritas.
- Identificar entregadores na portaria.
- Sinalizar movimentações incomuns (como animais soltos ou brigas).
- Reconhecer textos em placas ou sinalizações através de OCR.

---

## 🧪 Tecnologias e Ferramentas Utilizadas

- Microsoft Azure Cognitive Services (Face API, Computer Vision OCR)
- Python (requests, OpenCV, Pillow)
- OpenCV para manipulação de imagens
- Jupyter Notebook (pasta `/notebooks`)
- Git e GitHub para versionamento

---

## 🗂️ Estrutura do Projeto

```
📁 inputs/        → Imagens utilizadas nas análises
📁 output/        → Resultados processados: imagens marcadas e textos extraídos
📁 notebooks/     → Códigos em Jupyter (ex: facial_data_analysis.ipynb)
📁 legal/         → Notas sobre privacidade e LGPD (simulado)
📄 requirements.txt → Dependências do projeto em Python
📄 README.md      → Explicação do projeto e insights
```

---

## 📸 Imagens utilizadas (`inputs/`)

| Nome do Arquivo | Descrição Simulada |
|-----------------|---------------------|
| entrada_condominio_noite.jpg | Monitoramento noturno |
| briga_area_comum_1.jpg | Situação de conflito em área comum |
| entregador_portaria.jpg | Registro de prestador de serviço |
| alerta_animal_solto.jpg | Animal solto no condomínio |
| Carro fora da vaga ou descarte irregular.jpg | Infração visual |
| pessoa_area_restrita.jpg | Pessoa não autorizada |
| Gritos ou agressões a animais.jpg | Situação crítica detectada |

---

## ✅ Resultados e Saídas (`output/`)

- Detecção de rostos com marcação facial
- Texto extraído automaticamente com OCR
- Classificação das ocorrências
- Geração de alertas baseados no tipo da imagem

### Exemplo:

```
Imagem: entregador_portaria.jpg
Texto detectado (OCR): "ENTRADA SOMENTE COM AUTORIZAÇÃO"
Rosto detectado: 1
Classificação: Visitante identificado na portaria
```

---

## 💡 Insights e Aprendizados

- O OCR funcionou bem mesmo em imagens com pouca luz.
- Azure Face API exige imagens nítidas e bem posicionadas para boa acurácia.
- O uso de visão computacional pode automatizar alertas em tempo real.
- LGPD deve sempre ser considerada no uso de reconhecimento facial real.

---

## 🔐 LGPD e Privacidade

Este projeto é **apenas educacional** e simula casos genéricos. Nenhuma imagem ou dado real de moradores é utilizado.  
Para uso real, recomenda-se:

- Consentimento formal de todos os moradores
- Criptografia de imagens sensíveis
- Armazenamento seguro e controlado
- Aderência à [LGPD](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/lgpd)

---

## 📈 Próximos Passos

- Criar painel web (dashboard) com alertas em tempo real
- Armazenamento automático em banco (Azure SQL ou MongoDB)
- Uso de modelos treinados com aprendizado contínuo
- Reconhecimento de padrões anômalos via IA

---

## 📎 Repositório

🔗 GitHub: [https://github.com/marcosgaia/condominio-inteligente-ai](https://github.com/marcosgaia/condominio-inteligente-ai)

---

## 👤 Autor

**Marcos Gaia**  
Projeto para portfólio de IA e segurança com nuvem  
Contato: github.com/marcosgaia
