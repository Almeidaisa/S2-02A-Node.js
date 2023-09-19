# S2-02A-Node.js

passo a passo
1)  Entrar na pasta onde o node-env está localizado.
   ex:cd nodejs-env/
2) Ativar o node-env, para isso adicione o seguinte comando:
  source bin/ctivate 
3) Abrir o nano do arquivo "index.js"
   ex: nano index.js
4) Dentro do nano coloque o código que você precisará e salve (adicione a porta)
   ex: var http = require ('http')
 http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('isabella almeida santos 19-09-2023');
}).listen(8003);
6) Teste (entre no navegador e digite localhost:'número da sua porta' 
