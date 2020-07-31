# live4
Exemplo de teste para os seguinte endpoints

/add
queryParam("first", "Marcelo Josué")
queryParam("last", "Telles add")
return Added new customer to repo

/add201
queryParam("first", "Marcelo Josué ")
queryParam("last", "Telles add201")
return 200
CREATED
                
                
/update
queryParam("id", "50 ").
queryParam("first", "MARCELO JOSUÉ ")
queryParam("last", "TELLES update")
return 200
update customer

/update200
queryParam("id", "49")
queryParam("first", "MARCELO JOSUÉ ")
queryParam("last", "TELLES update200 ")
return 200
CREATED

/delete
queryParam("id", "41")
return 200
delete customer

/delete204
queryParam("id", "42")
return 204



