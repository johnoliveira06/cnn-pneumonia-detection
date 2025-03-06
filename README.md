[![GitHub issues](https://img.shields.io/github/issues/johnoliveira06/cnn-pneumonia-detection)](https://github.com/johnoliveira06/cnn-pneumonia-detection/issues) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-yellow.svg?style=flat-square)](https://github.com/johnoliveira06/cnn-pneumonia-detection/pulls) [![HitCount](https://views.whatilearened.today/views/github/johnoliveira06/cnn-pneumonia-detection.svg)](https://github.com/johnoliveira06/cnn-pneumonia-detection)

# Transfer learning para detecção de pneumonia

## Sobre o trabalho

O objetivo desse trabalho consistiu em construir um classificador de pneumonia em imagens de raio-x de tórax aplicando a técnica Transfer Learning e utilizando a Rede Neural Convolucional Visual Geometry Group 16 (VGG 16).

## Resultados

Este projeto foi um exercício para demonstrar como as redes neurais podem ser aplicadas para resolver problemas reais na área da saúde. A aplicação de Transfer Learning com a arquitetura VGG16 permitiu a criação de um modelo eficiente, capaz de identificar padrões e classificar corretamente os casos.

Alguns dos resultados foram:

- Treinamento eficiente;
- Alto desempenho;
- Excelente capacidade de distinção.

Os resultados visuais estão localizados no diretório [`results`](https://github.com/johnoliveira06/cnn-pneumonia-detection/results).

## Como executar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/johnoliveira06/cnn-pneumonia-detection.git && cd cnn-pneumonia-detection
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Faça o download do dataset [aqui](https://www.kaggle.com/datasets/tolgadincer/labeled-chest-xray-images/download).
4. Extraia o arquivo .zip
5. Copie o conteúdo do diretório extraído "chest-xray" para o diretório `dataset`.
6. Abra e execute o notebook no Jupyter Notebook, Google Colab ou Kaggle.

**Obs:** Recomenda-se utilizar o Kaggle ou Google Colab caso não possua uma GPU de alto desempenho.

## Feito por:

<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/jonathanoliveira06/">
        <img src="https://avatars.githubusercontent.com/u/88400274?v=4" width="100px;" alt="Foto do John"/><br>
        <sub>
          <b>Jonathan O. Fernandez</b>
        </sub>
      </a>
    </td>
     <td align="center">
      <a href="https://www.linkedin.com/in/pedro-henrique-costa-menezes-791195227/">
        <img src="https://media.licdn.com/dms/image/v2/D4D03AQG8igf6prG9Dg/profile-displayphoto-shrink_400_400/B4DZOhzXpxHYAg-/0/1733586419399?e=1746662400&v=beta&t=370cJLmdymuZGnFHtJh50g90RI21N2I2Cglw09JZBH8" width="100px;" alt="Foto do Pedro"/><br>
        <sub>
          <b>Pedro H. C. Menezes</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
