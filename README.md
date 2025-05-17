# Gemini Carreiras: 
### Seu Futuro Profissional Decifrado pela Inteligência Artificial 

### 🟡 Visão Geral:

O projeto "Gemini Carreiras" visa desenvolver um agente de Inteligência Artificial sofisticado, construído sobre a arquitetura do Google Gemini, capaz de atuar como um consultor de carreira personalizado. A ferramenta analisa currículos enviados por usuários e, com base em uma profunda compreensão do mercado de trabalho atual, oferece insights valiosos e recomendações práticas para o aprimoramento de habilidades técnicas e comportamentais. O objetivo principal é capacitar os indivíduos a alinhar seus perfis profissionais com as demandas do mercado, aumentando suas chances de sucesso em suas jornadas de carreira.<br><br>

## 🏆 Benefícios do Projeto:

  * **Aconselhamento de carreira Aaessível:** Democratiza o acesso a orientação profissional de qualidade, que muitas vezes pode ser dispendiosa ou inacessível.
  * **Feedback imparcial e baseado em dados:** Oferece uma análise objetiva do currículo e do perfil profissional, fundamentada em informações do mercado de trabalho.
  * **Personalização e Relevância:** As recomendações são adaptadas ao perfil específico do usuário e às demandas atuais do mercado.
  * **Empoderamento do Usuário:** Fornece as ferramentas e o conhecimento necessários para que os indivíduos tomem decisões informadas sobre suas carreiras e invistam em seu desenvolvimento profissional de forma estratégica.
  * **Eficiência e Rapidez:** O agente de IA pode analisar currículos e gerar feedback de forma muito mais rápida do que um consultor humano.<br><br>

  Em resumo, **"Gemini Carreiras"** representa uma solução inovadora e poderosa para auxiliar profissionais em todas as fases de suas carreiras. Ao integrar a inteligência do Google Gemini com a análise de currículos e o conhecimento do mercado de trabalho, o projeto tem o potencial de transformar a forma como as pessoas planejam e desenvolvem suas trajetórias profissionais, tornando-as mais alinhadas com as oportunidades e exigências do mundo do trabalho.<br><br>


## 💡 Principais funcionalidades:

### 👩‍💻 Análise Inteligente de Currículo:

  * **Interpretar o currículo e contextualizar no mercado:** Identifica informações chave e as relaciona com as demandas atuais.
  * **Avaliar e comparar habilidades:** Aponta pontos fortes, áreas de melhoria e compara as habilidades com o mercado.
  * **Sugerir aprimoramentos e analisar soft skills:** Indica como se tornar mais competitivo e interpreta habilidades comportamentais.
  * **Gerar feedback detalhado:** Entrega um relatório construtivo sobre o currículo.<br><br>

### 👨‍🏫 Tradução de Textos para o Português do Brasil:

  * **Tradução de idiomas suportados pelo Gemini para Português do Brasil**: Traduz textos possibilitando a análise de currículos em diferentes línguas.<br><br>

### 🔒 Atuação como Agente de Proteção de Dados Pessoais:

  *  **Conformidade com a LGPD:** Atuação como agente de proteção de dados pessoais, garantindo a conformidade com a legislação brasileira (LGPD).
  *  **Remoção automática de dados sensíveis:** Identificação e remoção automática de informações pessoais sensíveis e desnecessárias antes da análise de currículos.
  *  **Exemplos de dados removidos:**
    * Números de documentos de identificação (RG, CPF, passaporte, etc.).
    * Informações de contato detalhadas (endereço, telefone, e-mail).<br><br>
    
### 🕵️‍♀️ Busca e Contextualização de Vagas de Emprego:

  *  **Coleta de dados do mercado:** Busca ativa em sites de emprego para obter informações atualizadas sobre as demandas do mercado de trabalho.
  * **Análise de descrições de vagas:** Identificação de habilidades técnicas e comportamentais mais requeridas em vagas relevantes para o perfil desejado.
  * **Enriquecimento da análise de currículo:** Utilização do contexto das vagas para aprimorar a análise do currículo e refinar as recomendações de desenvolvimento.
  * **Alinhamento com as necessidades das empresas:** Garantia de que as recomendações estejam conectadas às exigências reais do mercado de trabalho.

  * **Sites de busca de empregos utilizados nas pesquisa de vagas:**
      * https://www.infojobs.com.br/
      * https://www.catho.com.br/vagas/
      * https://br.indeed.com/
      * https://www.jobatus.com.br/
      * https://www.vagas.com.br/
      * https://portal.gupy.io/
      * https://riovagas.com.br/
      * https://99jobs.com/<br><br>

## 🔧 Tecnologias Envolvidas:

  * **Google Gemini API:** Modelo de análise de textos e geração de conteúdo (https://ai.google.dev/gemini-api/docs)
  * **Google AI Studio:** Para configuração API (https://aistudio.google.com)
  * **Google Colab:** Ambiente utilizado no desenvolvimento e execução do código  (https://colab.research.google.com)
  * **Python:** Linguagem de programação do projeto (https://www.python.org)<br><br>

## ✅ Pré-requisitos
 * **Conta Google** para acesso ao Google Collab e AI Studio
 * **Chave API** gerado no Google AI Studio
 * Navegadores **Google Chome** ou **Microsoft Edge**<br><br>

## ⚙️ Execução do código passo a passo
1. Crie uma chave de API no [**AI Studio (Gemini)**](https://aistudio.google.com/app/apikey) - [Vídeo no Youtube em Inglês](https://www.youtube.com/watch?v=6BRyynZkvf0)<br><br>
2. Acesse o [**Google Colab**](https://colab.research.google.com) e adicione uma nova entrada no cofre de senhas do Google Colab para armazenar a chave de API criada.<br>
   Utilize o nome ***GOOGLE_API_KEY***. - [Vídeo no Youtube em Inglês](https://colab.research.google.com)<br><br>
3. Baixe o código fonte do **"Gemini Carreiras"** >> [projeto-gemini-carreiras.ipynb](https://github.com/kndlerc/gemini-carreiras/blob/main/projeto-gemini-carreiras.ipynb)<br><br>
4. Carrege o código fonte no **Google Colab** clicando em *File*->*Upload notebook*. Clique em *Browse* e selecione o arquivo baixado.<br><br>
5. O agente possui algumas configurações que podem ser ajustadas antes da execução<br><br>
   5.1 **Debug** - altere a variável **_DEBUG_AGENTS** para **True** para que o resultado dos agentes utilizados seja apresentado para o usuário. <br><br>
   ***Isso altera a experiência final do usuário final. Utilize apenas para identificar problemas nos prompts.***<br><br>
   5.2 **Modelos Gemini** - as variáveis **_MODELO_GENAI** e **_MODELO_GENAI_THINKING** controlam os modelos Gemini utilizados pelos agentes. O modelo **Thinking** é utilizado apenas pelo agente que realiza a análise e comparação do currículo.<br><br>
   ***Em caso de problemas com os modelos, altere os valores destas variávies***<br><br>
6. Ao executar o agente três informações deverão ser fornecidas:<br>
   6.1 **Profissão:** a sua profissão atual<br>
   6.2 **Vaga:** a vaga no qual deseja se candidatar<br>
   6.3 **Currículo:** copie e cole o texto do seu currículo para o agente<br><br>
7. Caso você não queria utilizar seu currículo ou queria apenas testar a ferramenta, disponibilizamos algums scenários para teste<br><br>
   7.1 **Cenário 1 - Área da Medicina**<br>
      - **Profissão:** médico<br>
      - **Vaga:** médico plantonista<br>
      - **Currículo:** [currículo de teste em Espanhol](https://github.com/knodlerc/gemini-carreiras/blob/main/teste-cv-Medico-Espanhol.txt)<br><br>
      
   7.2 **Cenário 2 - Área da Publicidade**<br>
      - **Profissão:** designer gráfico<br>
      - **Vaga:** designer gráfico senior<br>
      - **Currículo:** [currículo de teste em Inglês](https://github.com/knodlerc/gemini-carreiras/blob/main/teste-cv-Designer-Grafico-Ingles.txt)<br><br>
      
   7.3 **Cenário 3 - Área da Técnologia da Informação**<br>
      - **Profissão:** programador<br>
      - **Vaga:** gerente de TI<br>
      - **Currículo:** [currículo de teste em Português do Brasil](https://github.com/knodlerc/gemini-carreiras/blob/main/teste-cv-Programador-PortuguesBrasil.txt)<br><br>    
   
   <br><br><br><br><br>
   
   
