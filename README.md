Dentro de app.py ao final do código, há uma linha para rodar o app em debugmode e também para ser hosteado na porta 3000.
Isso foi alterado no meu código pois estava com um problema na rede onde a porta que comecei rodando esse código (5000),
por algum motivo se encontrava excluída, sendo assim, precisei de mudar a rota do servidor que o python estava rodando o 
código, mas pode ser que para quem for utilizar o código em sua própria máquina, não precise de realizar essa alteração,
sendo assim, a última linha ficaria:
if __name__ == "__main__":
    app.run(debug=True)
