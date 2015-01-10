# MultiConsulta
#Multi Consulta em arquivo externo TXT


def consultaCliente():
    nomeClienteConsulta = input("Entre com o nome para fazermos a consulta no Sistema: ")
    arquivo = open("dados.txt").readlines()
    
    arquivo = [str(x).rstrip() for x in arquivo]
    for linha in arquivo:
        if nomeClienteConsulta.upper() in linha:
            print("Cliente encontrado: {nome}" .format(nome=linha))


Preciso mostrar para o ususario mais dois campos idade e Endereço.

Alguem pode me ajudar.
