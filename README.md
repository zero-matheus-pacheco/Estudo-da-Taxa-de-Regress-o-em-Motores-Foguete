# Estudo da Taxa de Regressão em Motores Foguete Híbridos Usando uma Ferramenta CFD

Estudo teórico da taxa de regressão de propelentes sólidos em motores de foguete híbridos utilizando uma ferramenta comercial de CFD utilizando oxigênio e parafina sólida. 

Para visualizar o arquivo completo acesse: [PDF Completo](artigo cobem.pdf)

## Resumo
Este trabalho propõe um estudo teórico da taxa de regressão de propelentes sólidos em motores de foguete híbridos, relacionando-a com os principais parâmetros característicos do fluxo. O objetivo principal é testar a ferramenta comercial ANSYS Fluent para simular o processo de regressão usando um modelo de fluxo não viscoso em estado estacionário. Um modelo de simulação foi desenvolvido para representar o processo de regressão em geometrias simples de câmaras de combustão, considerando o fluxo não reativo e a temperatura de pirólise da parafina. Como objetivo secundário, o modelo foi testado em uma segunda geometria simples para contribuir na definição de geometrias otimizadas que ajudem a reduzir a perda de desempenho na combustão do combustível.

## Metodologia
* **Ferramenta:** ANSYS Fluent, que resolve as equações de conservação de massa, energia e momento para o modelo de fluxo não viscoso em estado estacionário.
* **Propelentes:** Oxigênio gasoso como oxidante e parafina como combustível sólido.
* **Geometrias:** Duas geometrias simples de motores de foguete híbridos foram analisadas, baseadas nos projetos de Sporschill (2017) e Hui et al. (2014). A simetria cilíndrica foi utilizada para otimizar as simulações.
* **Condições de Contorno:**
    * Velocidade de entrada do oxigênio gasoso: $33~m/s$.
    * Temperatura de entrada do oxigênio gasoso: 300 K.
    * Pressão manométrica zero entre a entrada e a saída.
    * Temperatura de pirólise da parafina: 673 K.
    * Fluxo turbulento com o modelo $\kappa-\epsilon$.
* **Propriedades do Combustível (Parafina):**
    * Densidade do combustível: $900\frac{kg}{m^{3}}$.
    * Calor específico: $2800\frac{J}{kgK}$.
    * Condutividade térmica: $0.25\frac{W}{mK}$.
* **Malha:** Foi utilizada uma malha com refinamento intermediário para reduzir a necessidade computacional, considerando que os parâmetros analisados apresentam valores médios próximos aos da malha mais refinada.

## Conclusão
O modelo de simulação desenvolvido foi considerado eficiente para a simulação do fluxo. Ele não exibe troca de calor em regiões determinadas como adiabáticas e apresenta temperaturas coerentes com os parâmetros de condutividade térmica e temperatura de pirólise da parafina. O perfil de velocidade do fluxo foi validado em comparação com a literatura disponível. O presente trabalho serve como base para trabalhos que buscam uma análise mais detalhada da taxa de regressão com maior precisão e complex
