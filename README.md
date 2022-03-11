O client SFTP funciona com arquivos de configuração, onde são definidos os dados para conexão com o servidor e as regras para envio e recebimento de arquivos com este servidor.

**Configurando um servidor:**

1. Acesse a pasta "Config" e abra o arquivo "servidor".

2. Configure os dados de acesso ao servidor conforme o exemplo da imagem abaixo:
![image](https://user-images.githubusercontent.com/101418838/157910876-6cd55a68-8b6b-41ea-98e5-410fa6c82013.png)

**Adicionando uma Regra:**

1. Acesse a pasta "Config" e abra o arquivo "regras".

2. Abaixo da primeira linha de cabeçalho, insira primeiramente o nome da regra.
![image](https://user-images.githubusercontent.com/101418838/157911308-b95655a4-3c78-4083-abbe-779672e90478.png)

3. Ao lado do nome, insira o tipo da regra (digite R para recebimento e S para envio).
![image](https://user-images.githubusercontent.com/101418838/157911472-4a2ddfe4-2475-4f52-9829-df742bdc241d.png)

4. Após o tipo de regra, insira o diretório de origem dos arquivos (pasta de envio) sempre finalizando com barra.
![image](https://user-images.githubusercontent.com/101418838/157911857-3d58cc06-d265-43e8-bba3-66eebc6768f4.png)

5. Logo após insira a mascara dos arquivos (Exemplo: TESTE*.txt enviará todos os arquivos do diretório, que iniciem com TESTE e que tenham a extensão txt):
![image](https://user-images.githubusercontent.com/101418838/157912142-7896a6c1-307b-45a4-a6df-a466ab7c197d.png)

6. Ao lado da mascara de envio, adicione o diretório de destino (Pasta onde os arquivos serão entregues):
![image](https://user-images.githubusercontent.com/101418838/157912357-b900248f-71df-4406-806b-5bc19c525195.png)

7.Após o diretório de destino, insira o prefixo que deve ser adicionado ao nome do arquivo após ser depositado na pasta de recebimento.
![image](https://user-images.githubusercontent.com/101418838/157912749-ccabbae6-6d5a-4798-9940-f6cfe54fa481.png)

No exemplo acima, o arquivo será entregue na pasta "/dirteste/recebimento/" com o nome "ARQ_REC_TESTE.txt".

8. No próximo campo, defina se após o arquivo ser enviado, deve ser feito o backup (defina S para sim e N para nao).
![image](https://user-images.githubusercontent.com/101418838/157913116-e44e1615-736b-4760-b77e-d665f040c3dd.png)

9. Caso o backup tenha sido definido como S (sim) no próximo campo é necessário informar o diretório de backup.
![image](https://user-images.githubusercontent.com/101418838/157913536-705ef068-22ac-40dc-b4c2-3c72201778cd.png)

**Logs**

Os logs de cada execução serão salvos seguinte pasta: \logs


 


