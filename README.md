# MISIC

Componentes da interface

AIS: Pernambuco é dividido em 26 Áreas Integradas de Segurança Pública. Nesta área, deve-se escolher a AIS de interesse para a minimização dos índices de criminalidade.

Mês: A criminalidade está intrinsecamente relacionada a época do ano, podendo-se dizer que possui certa sazonalidade. Deste modo, o mês para otimização dos parâmetros também deve ser escolhido, para que a configuração ótima seja proposta.

Ano: Parâmetro que define quais bases de dados serão utilizadas. As bases escolhidas para treinamento do algoritmo serão sempre referentes até o ano escolhido.

Metas: parâmetros mutuamente exclusivos.

Meta livre: Parâmetro escolhido pelo usuário, quando se quer adquirir a maior redução possível a partir dos recursos oferecidos.
Meta 12%: Parâmetro selecionado quando se quer uma redução obrigatória de 12% dos indicadores de criminalidade.
Meta: meta definida manualmente pelo usuário. Pode variar de 0 a 1, em que 0 corresponde a redução de 100% do índice de criminalidade. Deste modo, para escolher o percentual de redução, deve-se colocar o valor que, reduzido de 1, fornecerá a redução da criminalidade. Por exemplo, desejando-se uma redução de 25%, deve-se programar o parâmetro para 0,75.

Base: caminho da base de dados utilizada.

Salvar: caminho para salvar os resultados.

Último ano: caminho para a base de dados do ano em que servirá de comparação, ou seja, a Meta de 12% se baseará nesse ano.

Número de simulações: quantas vezes o algoritmo será executado com os mesmos parâmetros. Pode fornecer informações mais robustas acerca da configuração ideal, a partir da  realização de testes estatísticos nos resultados obtidos.

Recursos: Parâmetros que, se quantizados corretamente, podem levar a redução nos índices de criminalidade total (CVLI e CVP) desejados para cada AIS. Estes são: Efetivos, Armas, Recolhimento Total, Ponto Debelado, Crack, Mandados Expedidos, Malhas de lei, Autoria CVLI, Autoria IP. - Nesses recursos é possível estabelecer o mínimo e o máximo em porcentagem que poderão ser utilizados.

Indicadores: CVLI e CVP

Conhecendo os componentes da aplicação, basta escolher os valores requeridos e clicar em Iniciar. A aplicação mostrará os gráfico dos resultados para a análise do usuário. Caso o usuário não queira analisar os algoritmos e valores estatísticos, basta analisar o histograma que indica qual a proporção deve ser utilizada dos recursos para obtenção dos valores indicados pela coluna de CVLI e CVP. Caso o usuário queira, é possível analisar o quão bom está o resultado pelo gráfico de convergência e o boxplot da média e desvio dos resultados.
