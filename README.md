# Bolsonaro, checado

Este repositório disponibiliza uma planilha com todas as declarações feitas por Jair Bolsonaro durante seu mandato como presidente do Brasil (2019-2022) e checadas pela equipe do **Aos Fatos**. Um painel interativo com esses dados pode ser acessado [aqui](https://www.aosfatos.org/todas-as-declaracoes-de-bolsonaro/).

---

## 📂 Sobre a base de dados

**Nome do arquivo:** `bolsonaro-fact-checks.csv`

O arquivo contém uma linha para cada declaração checada e segue a estrutura abaixo.

| Coluna                | Descrição |
|------------------------|-----------|
| `claim_date`       | Data da declaração (formato `AAAA-MM-DD`). |
| `claim`             | Texto exato da fala de Bolsonaro. |
| `claim_origin_url` | Link para a fonte original da declaração. |
| `origin_type`               | Canal de onde a declaração foi tirada ex: Twitter, discurso, live, entrevista). |
| `original_rating_label_pt`                | Selo de checagem atribuído à declaração (em português) usando a metodologia original do Aos Fatos|
| `new_rating_label_pt`                | Selo de checagem atribuído à declaração (em português) usando a metodologia revisada do Aos Fatos|
| `original_rating_label_en`                | Selo de checagem atribuído à declaração (em inglês) usando a metodologia original do Aos Fatos|
| `new_rating_label_en`                | Selo de checagem atribuído à declaração (em inglês) usando a metodologia revisada do Aos Fatos|
| `rating_full_pt`              | Explicação detalhada e em português da checagem |
| `keyword`              | Palavra-chave do tema abordado na declaração. |
| `read_more_url`        | Link para a checagem completa publicada pelo Aos Fatos. |
| `source_url`            | Fonte primária utilizada para verificar a declaração. |

---

# 📝 Nota metodológica
Em maio de 2022, o Aos Fatos reduziu para três o número de selos de sua metodologia de checagem (leia mais [aqui](https://www.aosfatos.org/noticias/aos-fatos-estreia-cobertura-eleitoral-2022/). Na mudança, os selos "EXAGERADO", "IMPRECISO", "CONTRADITÓRIO" e "INSUSTENTÁVEL" foram substituídos por "NÃO É BEM ASSIM". 

Para preservar a história do projeto, mas também facilitar análises, este repositório tem dois tipos de selos. As colunas _original_rating_ mostram os selos atribuídos às declarações tais como foram publicadas na época —ou seja, mistura as duas metodologias. Já as colunas _new_rating_ converte os selos anteriores a maio de 2022 para o novo formato.


## 📅 Última atualização

📆 **30 de dezembro de 2022**  
Essa foi a última data de coleta e verificação, encerrando o ciclo do governo Bolsonaro.

---

## 🛠️ Licença

Este material é de uso livre para fins **educacionais e não comerciais**, desde que citado o crédito à equipe do [Aos Fatos](https://aosfatos.org).  
