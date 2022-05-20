Engenharia de Software.

Ciclo de vida, Requisitos.

Funcionais / Storys cards:

![IMG_20220404_200319](https://user-images.githubusercontent.com/88752151/162082480-688e254b-48f8-4677-bcbe-41b3684a800e.jpg)

x-------------------------------------------------------------------------------------------------------------------------------x
Não funcionais
Mostra a mensagem visualizada - 1ª Heurística
![IMG_20220404_200818](https://user-images.githubusercontent.com/88752151/162083018-695da5fe-9e01-4766-8025-7296a32da426.jpg)

Icones instrutivos - 2ª Heurística
![IMG_20220404_200828](https://user-images.githubusercontent.com/88752151/162083111-2abdd42b-deca-48e3-b8df-a2b2cf175272.jpg)

Opção de retorno na plataforma - 3ª Heurística
![IMG_20220404_200833](https://user-images.githubusercontent.com/88752151/162085502-700891fd-53ac-4a15-9c91-e8cef7efd5a6.jpg)

A opção de ajuda da uma saída para o usuário se orientar - 10ª Heurística 
![IMG_20220404_200327](https://user-images.githubusercontent.com/88752151/162083329-55a0ecc0-bcee-4b41-aa46-af9c28dfa304.jpg)

Projeto diagrama

![a61b1b2a-48d6-4dde-ab4c-a62f1449957f](https://user-images.githubusercontent.com/88752151/169595864-dcf5e20a-6a47-4dfd-b4b5-4aa37ff43590.jpg)

Densenvolvimento

Plataforma de Ensino/Main

package Plataforma_de_Ensinoo;

import java.util.LinkedList; import java.util.List;

public class Plataforma {

  private List<Pessoa> pessoa = new LinkedList<Pessoa>();

 public void cadastrarPessoa(Pessoa pessoa){
      pessoa.add(pessoa);
 }

 public List<Pessoa> buscarPessoaPorDiciplina(Diciplina Materia){
       List<Pessoa> pessoasEncontrados = new LinkedList<Pessoa>();
       Pessoa[] pessoas = null;
	for(Pessoa pessoa:pessoas){
            if(pessoa.getDiciplina().comparar(Materia)) pessoasEncontrados.add(pessoa);
       }
       return pessoasEncontrados;
 }

 public Pessoa buscarpessoaPorCPF(String CPF){
      Pessoa[] pessoas = null;
	for(Pessoa pessoa:pessoas){
		if(pessoa.getPessoa().equals(getPessoa())) return pessoa; 
      }
      return null;
 }

 public List<Pessoa> getPessoa(){
       List<Pessoa> pessoas = null;
	return pessoas;
 }
