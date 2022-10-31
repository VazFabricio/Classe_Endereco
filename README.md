# Classe_Endereco
Considerando o diagrama de classes abaixo implemente:

* Todas as variáveis de instância
*     private String cep;
*     private String tipoLogradouro;
*     private String logradouro;
*     private String complemento;
*     private String bairro;
*     private String cidade;
*     private String estado;
*     private double longitude;
*     private double latitude;
* Construtores
*     public Endereco() { }
*     public Endereco(cep, tipoLogradouro, logradouro, complemento, bairro, cidade, estado) { }
*     public Endereco(cep, tipoLogradouro, logradouro, bairro, cidade, estado) { }
*     public Endereco(cep, tipoLogradouro, logradouro, complemento, bairro, cidade, estado, longitude, latitude) { }
*     public Endereco(logitude, latitude) { }
*     public Endereco(cep) { }
* Todas as propriedades get/set
* Sobrescreva o método
* @Override
*     public String toString()
*     para que ele retorne o endereço no seguinte formato:
*     Tipo Logradouro Logradouro - Bairro, Cidade - Estado, CEP

