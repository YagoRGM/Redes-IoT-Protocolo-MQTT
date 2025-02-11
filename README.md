Este repositório contém dois arquivos Python que implementam a comunicação via MQTT utilizando a biblioteca paho-mqtt. Os arquivos publisher.py e subscriber.py permitem a publicação e recepção de mensagens em um tópico MQTT.

Requisitos
Para executar os scripts, siga as instruções abaixo utilizando o Google Colab.

Passos para Execução
Baixe os arquivos publisher.py e subscriber.py do repositório.
Acesse o Google Colab e clique em New Notebook.
No primeiro bloco de código do notebook, digite o seguinte comando para instalar a biblioteca paho-mqtt:

!pip install paho-mqtt

Clique no botão "play" para executar a instalação.
Clique no botão + Código e copie o código do arquivo subscriber.py para o novo bloco de código.
Abra uma nova aba no navegador, acesse novamente o Google Colab e clique em New Notebook.

No primeiro bloco de código do novo notebook, digite novamente o comando:
!pip install paho-mqtt
Clique no botão "play" para executar a instalação.
Clique no botão + Código e copie o código do arquivo publisher.py para o novo bloco de código.

Agora você deve ter dois notebooks abertos no Colab, um para publisher.py e outro para subscriber.py.
Execute ambos os notebooks clicando no botão "play".

Testando a Comunicação
No notebook que contém publisher.py, digite uma mensagem no campo de entrada:

Digite uma mensagem para enviar:

Pressione Enter e verifique se a mensagem aparece no notebook que contém subscriber.py.
Se tudo foi configurado corretamente, a mensagem será enviada pelo publisher.py e recebida pelo subscriber.py via protocolo MQTT.
