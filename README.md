
 
Site Feito para Portifolio, programa com funcionalidades de nutricionistas, feito para atendimento a pacientes de nutrição.  


### Criar Ambiente virtual
	# Linux
	
		python3 -m venv venv
		
	# Windows
	
		python -m venv venv

### Ativar
	# Linux
	
		source venv/bin/activate
		
	# Windows
	
		venv/Scripts/Activate

# Caso algum comando retorne um erro de permissão execute o código e tente novamente:

	Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
  
### Instale as bibliotecas:

	pip install django
	
	pip install pillow  
  
