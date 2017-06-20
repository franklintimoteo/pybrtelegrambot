# Como executar:

```
1 - Instale as bibliotecas necessárias:
pip install -r requeriments.txt

2 - Exporte a variável de ambiente, para que seja possível obte-la atráves do os.getenv('API_TOKEN') 
export API_TOKEN='token'

Pode-se adiciona-la ao arquivo .bashrc para que não seja necessário exportar
toda vez que uma nova instância de um shell seja aberta.
echo "export API_TOKEN='token'" >> ~/.bashrc

Após isso apenas execute dentro do diretório pybrtelegrambot
python3 bot.py
```
