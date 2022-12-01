## Códigos de status HTTP

| Código        | Descrição              | Quando Utilizar | 
| ------------- |:-------------:         |:--------------: |
| 200           | OK                     | Em requisições GET, PUT e DELETE executadas com sucesso.                 |
| 201           | Created                | Em requisições POST, quando um novo recurso é criado com sucesso.                |
| 206           | Partial Content        | Em requisições GET que devolvem apenas uma parte do conteúdo de um recurso.                 |
| 302           | Found                  | Em requisições feitas à URIs antigas, que foram alteradas.                |
| 400           | Bad Request            | Em requisições cujas informações enviadas pelo cliente sejam inválidas.                |
| 401           | Unathorized            |  Em requisições que exigem autenticação, mas seus dados não foram fornecidos.               |
| 403           | Forbidden              | Em requisições que o cliente não tem permissão de acesso ao recurso solicitado.                |
| 404           | Not Found              |  Em requisições cuja URI de um determinado recurso seja inválida.               |
| 405           | Method Not Allowed     | Em requisições cujo método HTTP indicado pelo cliente não seja suportado.                 |
| 406           | Not Acceptable         | Em requisições cujo formato de representação do recurso enviado pelo cliente não seja suportado.                 |
| 415           | Unsupported Media Type | Em requisições cujo formato de representação do recurso enviado pelo cliente não seja suportado.               |
| 429           | Too Many Requests      | No caso do serviço ter um limite de requisições que pode ser feita por um cliente, e ele já tiver sido atingido                  |
| 500           | Internal Server Error  | Em requisições onde um erro tenha ocorrido no servidor.                |
| 503           | Service Unavaible      | Em requisições feitas a um serviço que está fora do ar, para manutenção ou sobrecarga.                |
