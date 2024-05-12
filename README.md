# Imersao_Gemini_Desafio

# Sistema de Reconhecimento de Placas Veiculares para Segurança Pública

Este projeto simula um sistema de segurança pública que utiliza câmeras de trânsito e visão computacional para identificar veículos com irregularidades. O sistema visa auxiliar na recuperação de veículos furtados, identificar veículos utilizados em atividades ilícitas e aumentar a segurança nas cidades.

## Funcionalidades

* Simulação de câmeras de segurança que capturam imagens de placas de veículos.
* Utilização da API Google Gemini para reconhecimento de caracteres em imagens de placas.
* Consulta em um banco de dados simulado contendo informações sobre veículos com:
    * Registro de roubo/furto.
    * Utilização em atividades ilegais.
    * Outras irregularidades.
* Registro de data e hora da última detecção de um veículo irregular.

## Funcionamento

1. O sistema recebe uma imagem de uma placa veicular, simulando a captura por uma câmera de segurança.
2. A API Google Gemini é utilizada para realizar o reconhecimento óptico de caracteres (OCR) na imagem da placa, extraindo o texto da placa.
3. O texto da placa é então consultado no banco de dados simulado.
4. Se a placa for encontrada no banco de dados, o sistema retorna:
    * A placa do veículo.
    * A descrição da irregularidade associada à placa.
    * A data e hora da última vez que a placa foi detectada pelo sistema.

## Tecnologias Utilizadas

* Python
* API Google Gemini
* Banco de dados simulado (dicionário em Python)

## Observações

* Este projeto é uma simulação e não se conecta a bancos de dados reais de órgãos de segurança pública.
* O objetivo deste projeto é demonstrar a aplicação de visão computacional e API Gemini para reconhecimento de imagem em sistemas de segurança pública.

## Como executar o projeto

1. Clone o repositório.
2. Instale as dependências.
3. Configure a API Google Gemini.
4. **Ao executar o código, forneça o caminho da imagem a ser analisada como argumento.** O código aceita imagens nos formatos JPG e PNG.
5. **Se você estiver utilizando o Google Colab:**
    * Faça upload das imagens para o ambiente do Colab.
    * Copie o caminho da imagem.
    * Cole o caminho da imagem como argumento ao executar o código.

## Possíveis Próximos passos

* Integrar o sistema com um banco de dados real.
* Implementar um sistema de notificação em tempo real para as autoridades competentes.
* Desenvolver uma interface gráfica para o sistema.

## Autor

Carlos Eduardo Mendes de Oliveira

