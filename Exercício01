class Carro:
    def __init__(self, marca, modelo, ano, placa):
        self.marca = marca
        self.modelo = modelo
        self.ano = ano
        self.placa = placa
    
    def exibir_info(self):
        print("Marca: {}".format(self.marca))
        print("Modelo: {}".format(self.modelo))
        print("Ano: {}".format(self.ano))
        print("Placa: {}".format(self.placa))
    
    def __str__(self): 
        return "Carro: {} {} ({}), Placa: {}".format(self.marca, self.modelo, self.ano, self.placa)

marca = str(input("Digite a marca do Carro: "))
modelo = str(input("Digite o modelo do Carro: "))
ano = int(input("Digite o ano do Carro: "))
placa = str(input("Digite a placa do Carro: "))

meu_carro = Carro(marca, modelo, ano, placa)

meu_carro.exibir_info()

print("Objeto Carro: {}".format(meu_carro))
