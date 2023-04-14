# rotinas-de-medicamentos


Para criar rotinas de medicamentos em Python, você pode usar o módulo `logging` para registrar informações em um arquivo de log para que possa revisá-las posteriormente.

Aqui está um exemplo simples de como usar o módulo `logging` para registrar informações em um arquivo:

```python
import logging

logging.basicConfig(filename='example.log', level=logging.DEBUG)

logging.debug('Este é uma mensagem de depuração')
logging.info('Este é uma mensagem informativa')
logging.warning('Este é uma mensagem de aviso')
logging.error('Este é uma mensagem de erro')
logging.critical('Este é uma mensagem crítica')
```

Neste exemplo, estamos configurando o módulo `logging` para gravar informações em um arquivo chamado `example.log`. Em seguida, estamos usando as funções `debug`, `info`, `warning`, `error` e `critical` para registrar diferentes tipos de mensagens no arquivo.
