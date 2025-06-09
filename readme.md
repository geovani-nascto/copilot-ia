<h1 align="center">
    Análise de Sentimentos com Language Studio no Azure AI
</h1>


## Azure Speech Studio
<p>O Azure Speech Studio é uma ferramenta da Microsoft voltada para o desenvolvimento e personalização de soluções baseadas em voz e fala. Ele permite criar, testar e implantar modelos relacionados à fala com base na Speech Services API.</p>

**Principais recursos para análise de fala:**
 - **Reconhecimento de fala (Speech-to-Text):** converte fala em texto, útil para transcrição automática de áudios, reuniões, vídeos, etc.
 - **Análise de sentimentos e intenções via transcrição:** após transcrever, os dados podem ser usados em soluções de linguagem natural.
 - **Custom Voice:** permite treinar uma voz sintética com características específicas, útil para branding com assistentes de voz.
 - **Speech Translation:** traduz automaticamente a fala em tempo real.
 - **Pronunciation Assessment:** avalia a pronúncia, fluência e entonação — muito usado em aplicações educacionais.

## Azure Language Studio
<p> O Azure Language Studio é uma plataforma baseada nos serviços de linguagem do Azure (Language Services), que permite a análise e compreensão de linguagem natural de textos.</p>

**Principais recursos para análise de linguagem natural:**
 - **Reconhecimento de entidades (NER):** identifica nomes de pessoas, organizações, locais, etc.
 - **Análise de sentimento:** classifica o texto como positivo, negativo, neutro — útil para monitorar a opinião de clientes, por exemplo.
 - **Extração de frases-chave:** destaca termos importantes em um texto.
 - **Classificação personalizada de texto:** permite treinar modelos de machine learning para classificar textos conforme categorias definidas pelo usuário.
 - **Análise de intenção com LUIS (Language Understanding):** permite criar modelos que identificam intenção e entidades em comandos ou perguntas — ideal para chatbots e assistentes virtuais.

## Integração entre fala e linguagem natural
  - Passo 1: Usar o Speech Studio para converter áudio em texto.
  - Passo 2: Enviar o texto ao Language Studio para análise de sentimentos, identificação de entidades ou compreensão de intenção.

**Exemplo de uso integrado:**
  - Em um call center, as chamadas são transcritas com o Speech Studio.
  - Os textos são analisados com o Language Studio para detectar a satisfação do cliente e entender os motivos de contato.
