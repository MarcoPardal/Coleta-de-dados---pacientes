print("DADOS DO PACIENTE-PORTAL DO COLABORADOR.") 
print("")


nome=input("Digite o nome do paciente:")
idade=int(input(" Digite a idade do paciente:"))
telefone=input ("Digite o telefone do paciente:")
email=input("Digite o email do paciente:")
cpf=input("Digite o CPF do paciente:")
cep=input ("Digite o CEP do paciente:")
endereco=input("Digite o endereço do paciente:")
numerocasa=input("Digite o numero da casa:")
morbidade=input("Caso o paciente tenha alguma morbidade,digite qual?:")
medicacao=input("Qual medicação o paciente faz uso?")
alergia=input("pacinte tem alergia a alguma medicação?")



print ("Nome:{}".format(nome))
print("Idade:{}".format(idade))
print("Telefone:{}".format(telefone))
print("Email:{}".format(email))
print("CPF:{}".format(cpf))
print("CEP:{}".format(cep))
print("Endereço:{}".format(numerocasa))
print("numero da casa:{}".format(morbidade))
print("Medicação:{}".format(medicacao))
print("Alergia:{}".format(alergia))

if idade >=18:
   print(" Paciente maior de idade,")
else:
    print("*Atenção*-O Paciente deve ser acompanhado por um familiar maior de idade.")
