<h1>Cardiac Arrest Dataset</h1>
<p>Este repositório utiliza a base de dados "Cardiac Arrest Dataset", disponível no Kaggle, para prever a presença de doenças cardíacas. </p>
<a href="https://www.kaggle.com/datasets/iamtanmayshukla/cardiac-arrest-dataset"> Link para a base</a>
<h1>Atributos</h1>
<p>Os atributos contidos na base de dados incluem uma variedade de informações médicas e demográficas dos pacientes:</p>
<ul>
        <li><strong><code>age</code></strong>: Idade do paciente.</li>
        <li><strong><code>sex</code></strong>: Gênero do paciente.</li>
        <li><strong><code>cp</code></strong>: Tipo de dor no peito.</li>
        <li><strong><code>trestbps</code></strong>: Pressão arterial em repouso.</li>
        <li><strong><code>chol</code></strong>: Nível de colesterol sérico.</li>
        <li><strong><code>fbs</code></strong>: Nível de açúcar no sangue em jejum.</li>
        <li><strong><code>restecg</code></strong>: Resultados do eletrocardiograma em repouso.</li>
        <li><strong><code>thalach</code></strong>: Frequência cardíaca máxima atingida.</li>
        <li><strong><code>exang</code></strong>: Angina induzida por exercício.</li>
        <li><strong><code>oldpeak</code></strong>: Depressão do segmento ST induzida por exercício em relação ao repouso.</li>
        <li><strong><code>slope</code></strong>: A inclinação do pico do segmento ST no exercício.</li>
        <li><strong><code>ca</code></strong>: Número de vasos sanguíneos principais coloridos por fluoroscopia (0-3).</li>
        <li><strong><code>thal</code></strong>: Resultado do teste de estresse talássico.</li>
    </ul>
<h2>Variável Alvo (<code>target</code>)</h2>
<p>A variável alvo, denominada "target", é a variável que se busca prever. Ela é um valor binário (0 ou 1):</p>
<ul>
        <li><strong><code>0</code></strong>: Indica a ausência de doença cardíaca.</li>
        <li><strong><code>1</code></strong>: Indica a presença de doença cardíaca.</li>
    </ul>
<h2>Justificativa do Trabalho: Diagnóstico de Doenças Cardíacas com Machine Learning</h2>
<p>Este projeto propõe uma abordagem inovadora e complementar, utilizando algoritmos de Machine Learning para apoiar a equipe de saúde no diagnóstico. É importante frisar que esta ferramente é deve ser encarada como instrumento de apoio no diagnóstico e não devendo ser utilizada como ferramenta decisória autônoma. </p>
<h2>Correlação das Variáveis</h2>
<p>Para fins de comparação e compreensão da correlação de variáveis, os testes abaixo foram realizados.</p>
<img width="1184" height="784" alt="Image" src="https://github.com/user-attachments/assets/9b3028bf-655c-4fae-a19c-52bdb3dc5134" />
<p>Nota-se que as variáveis Oldpeak, cp, thalac e exang são as que tem maior correlação positiva ou negativa com a variável alvo.</p>
<h2>COMPARATIVO DOS MODELOS</h2>
<p>Foi realizado um experimento comparativo entre os modelos: Naive Bayes, KNN, Regressão, AdaBoost e XGBoost</p>
<img width="1184" height="784" alt="Image" src="https://github.com/user-attachments/assets/dbdf5318-74ce-4f12-befc-1b5ff29446a5" />
