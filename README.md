# Estudo da Taxa de Regressão em Motores Foguete Híbridos Usando uma Ferramenta CFD

## Resumo
[cite_start]Este trabalho propõe um estudo teórico da taxa de regressão de propelentes sólidos em motores de foguete híbridos, relacionando-a com os principais parâmetros característicos do fluxo[cite: 14]. [cite_start]O objetivo principal é testar a ferramenta comercial ANSYS Fluent para simular o processo de regressão usando um modelo de fluxo não viscoso em estado estacionário[cite: 16]. [cite_start]Um modelo de simulação foi desenvolvido para representar o processo de regressão em geometrias simples de câmaras de combustão, considerando o fluxo não reativo e a temperatura de pirólise da parafina[cite: 17]. [cite_start]Como objetivo secundário, o modelo foi testado em uma segunda geometria simples para contribuir na definição de geometrias otimizadas que ajudem a reduzir a perda de desempenho na combustão do combustível[cite: 18].

## Metodologia
* [cite_start]**Ferramenta:** ANSYS Fluent, que resolve as equações de conservação de massa, energia e momento para o modelo de fluxo não viscoso em estado estacionário[cite: 16].
* [cite_start]**Propelentes:** Oxigênio gasoso como oxidante e parafina como combustível sólido[cite: 27, 107, 110, 124].
* **Geometrias:** Duas geometrias simples de motores de foguete híbridos foram analisadas, baseadas nos projetos de Sporschill (2017) e Hui et al. (2014) [cite_start][cite: 123, 137]. [cite_start]A simetria cilíndrica foi utilizada para otimizar as simulações[cite: 123, 137].
* **Condições de Contorno:**
    * [cite_start]Velocidade de entrada do oxigênio gasoso: $33~m/s$[cite: 163].
    * [cite_start]Temperatura de entrada do oxigênio gasoso: 300 K[cite: 164].
    * [cite_start]Pressão manométrica zero entre a entrada e a saída[cite: 165].
    * [cite_start]Temperatura de pirólise da parafina: 673 K[cite: 166].
    * [cite_start]Fluxo turbulento com o modelo $\kappa-\epsilon$[cite: 159, 295].
* **Propriedades do Combustível (Parafina):**
    * [cite_start]Densidade do combustível: $900\frac{kg}{m^{3}}$[cite: 186].
    * [cite_start]Calor específico: $2800\frac{J}{kgK}$[cite: 186].
    * [cite_start]Condutividade térmica: $0.25\frac{W}{mK}$[cite: 186].
* [cite_start]**Malha:** Foi utilizada uma malha com refinamento intermediário para reduzir a necessidade computacional, considerando que os parâmetros analisados apresentam valores médios próximos aos da malha mais refinada[cite: 181].

## Conclusão
[cite_start]O modelo de simulação desenvolvido foi considerado eficiente para a simulação do fluxo[cite: 296]. [cite_start]Ele não exibe troca de calor em regiões determinadas como adiabáticas [cite: 296] [cite_start]e apresenta temperaturas coerentes com os parâmetros de condutividade térmica e temperatura de pirólise da parafina[cite: 297]. [cite_start]O perfil de velocidade do fluxo foi validado em comparação com a literatura disponível[cite: 298]. [cite_start]O presente trabalho serve como base para trabalhos que buscam uma análise mais detalhada da taxa de regressão com maior precisão e complexidade de modelo[cite: 299]. [cite_start]

## Referências
* Banno, A., Wada, Y., Mishima, Y., Tsugoshi, T., Kato, N., Hori, K., Nagase, R., 2019. Influence of Heating Rate on Pyrolysis Process of Paraffin Oil for Rocket Fuel. [cite_start]8th European Conference for Aeronautics And Space Sciences (EUCASS), DOI: 10.13009/EUCASS2019-618[cite: 304, 305].
* Chiaverini, e M.J., Kou, K.K., 2007. Fundamentals of Hybrid Rocket Combustion and Propulsion. American Institute Of Astronautics And Aeronautics, Inc., Vol. [cite_start]218[cite: 306, 307].
* Favaró, F. M., Manzoni, M., Coronetti, A., Deluca, L.T. and Sirignano, W.A., 2013. Solid Fuel Regression Rate Modeling for Hybrid Rockets. [cite_start]European Conference for Aeronautics and Space Sciences (EUCASS)[cite: 308, 309].
* Hui, T., Yijie, L., Peng, Z., 2014. Transient Simulation of Regressionrate on Thrust Regulation Process in Hybrid Rocketmotor. [cite_start]Chinese Journal Of Aeronautics, 27(6): 1343-1351[cite: 311, 312].
* Karabeyoglu, M.A., Cantwell, B.J., and Zilliac, G., 2005. Development of Scalable Space-time Averaged Regression Rate Expressions for Hybrid Rockets. [cite_start]41st AIAA/ASME/SAE/ASEE Joint Propulsion Conference & Exhibit[cite: 313, 314].
* Lazzarin, M., Pavarin, D., Barato, F. and Battella, A., 2013. CFD Simulation of Regression Rate in Hybrid Rockets. [cite_start]Journal of Propulsion and Power 29(6)[cite: 315].
* Mahottamananda, S.N., Kadiresh, P.N., 2020. Mechanical Characteristics of Paraffin Wax-HTPB Based Hybrid Rocket Fuel. [cite_start]DOI: 10.1007/978-981-15-4756-0_9[cite: 316].
* Mazzetti, A., 2013. Numerical Modeling and Simulations of Combustion Processes in Hybrid Rocket Engines. [cite_start]Politecnico Di Milano, Mathematics Department "F. Brioschi", Doctoral Programme in Mathematical Models and Methods in Engineering[cite: 317, 318].
* Pal, Y., Raja, A., Gopalakrishnan, K., 2020. Theoretical and Experimental Heat of Combustion Analysis of Paraffin- Based Fuels as Preburn Characterization for Hybrid Rocket. J. Aerosp. Technol. [cite_start]Manag., São José dos Campos, v12, e4520[cite: 319, 320].
* Sporschill, G., 2017. Numerical Approach of a Hybrid Rocket Engine Behaviour Modelling the Liquid Oxidizer Injection Using a Lagrangian Solver. [cite_start]Onera - Multi-Physics for Energetics Department[cite: 321, 322].
* Sutton, G.P., and Biblarz, O., 2001. Rocket Propulsion Elements. John Wiley & Sons, Inc., Vol. [cite_start]9, 2017[cite: 323].
