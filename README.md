# Projeto de Backend do IHouse

## Endpoints

### Sensor
<details>
	<summary>GET - /api/Sensor</summary>
	<br>
	Retorna um JSON contendo as janelas que necessitam de serem fechadas.
	<br><br>
	<pre>
	[ 
	   {
	      "sensor": 0.8,
	      "isAberta": true,
	      "local": "quarto"
	   }
	]
	</pre>
</details>

<details>
	<summary>POST - /api/Sensor</summary>
	<br>
	Recebe uma lista de janelas em JSON.
	<br><br>
	<pre>
	[ 
	   {
	      "sensor": 0.8,
	      "isAberta": true,
	      "local": "quarto"
	   },
	   {
	      "sensor": 0.2,
	      "isAberta": false,
	      "local": "cozinha"
	   }
	]
	</pre>
</details>

### User

<details>
	<summary>GET - /api/Sensor</summary>
	<br>
	Retorna um JSON contendo todos os usu�rios do banco de dados.
</details>

<details>
	<summary>GET - /api/Sensor/{id}</summary>
	<br>
	Retorna um JSON contendo o usu�rio que cont�m o ID inserido.
</details>

<details>
	<summary>POST - /api/Sensor</summary>
	<br>
	Recebe um JSON contendo as informa��es do usu�rio para ser inserido ao banco de dados.
</details>

<details>
	<summary>PUT - /api/Sensor/{id}</summary>
	<br>
	Recebe um JSON contendo as novas informa��es do usu�rio para ser atualizado no banco de dados.
</details>

<details>
	<summary>DELETE - /api/Sensor/{id}</summary>
	<br>
	Deleta o usu�rio do ID informado.
</details>
