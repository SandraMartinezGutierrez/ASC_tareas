def dados_probabilidad(numero_simulaciones):
    '''
    input:
        numero_simulaciones = int
    output:
        prob7_11 : float
    '''
    es_7 = 0
    es_11 = 0
    
    for i in range(numero_simulaciones):
        suma_dados = random.randint(1,6) + random.randint(1,6)
        if suma_dados == 7:
            es_7 +=1

        elif suma_dados == 11:
            es_11 += 1
     
    prob7_11 = es_7 / es_11 
    return prob7_11     