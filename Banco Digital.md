rograma {
  
  inteiro ag, cc, sn, bag = 1, bcc= 1, bsn= 123,i
  caracter voltar 
real saldo= 1200,limite=1300,total=limite+saldo,deposito,saque=200

funcao vetor(){

para(i=1;1<=1000;i++){


}
para(i=1;i<1000;i++){

  
}

}






















  funcao inicio() {


  faca{

    escreva("informe o número da agência: \n")
    leia(ag)
    escreva("informe o numero da conta: \n")
    leia(cc)
    escreva("informe a senha \n")
    leia(sn)

    limpa()
    menu()

  }enquanto(bag != ag ou bcc != cc ou bsn != sn)
  
  }
  
  funcao menu(){

  inteiro op

    escreva("escolha uma opção abaixo \n\n")
    escreva("1-saldo |2-extrato |3-saque |4-depósito |5-sair\n\n")
    escreva("opção:")
    leia(op)

    limpa()

    escolha(op){
  
    caso 1: saldo() pare
    caso 2: extrato() pare
    caso 3: saque()  pare
    caso 4: deposito() pare
    caso 5: pare
    caso contrario: escreva("opção invalida, tente novamente")
  }

  }

funcao saldo(){

 faca{
escreva("saldo: ", saldo, "\n")
escreva("limite:" , limite , "\n")
escreva("total:" , limite , "\n")

    escreva("deseja voltar ao menu principal? s|n  ")
    leia(voltar)
escreva("s")

 } enquanto(voltar != "s")


  limpa()
  menu()

  }  


funcao extrato(){
escreva("\n extrato \n")
escreva(saldo+deposito,"\n\n")
escreva("\n----------------\n")


  faca{


    escreva("deseja voltar ao menu principal? s|n  ")
    leia(voltar)

  } enquanto(voltar != "s")


  limpa()
  menu()

  }

funcao saque(){

  faca{

escreva("Qual o valor que você deseja sacar:\n")
leia(saque)
se(saque>saldo){
  escreva("valor indisponivel")
}

    escreva("deseja voltar ao menu principal? s|n  ")
    leia(voltar)

  } enquanto (voltar != "s")


  limpa()
  menu()  

  }

funcao deposito(){
escreva("Qual valor deseja depositar:\n")
leia(deposito)
escreva("-----------------\n")
  faca{

    escreva("deseja voltar ao menu principal? s|n  ")
    leia(voltar)

  } enquanto (voltar != "s")


  limpa()
  menu()  

 }




}


