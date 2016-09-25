1) clone the angular_quickstart to angular.io
2) npm install
3) npm install ng2-bootstrap --save
4) npm install moment --save
5) to the files index.html

a) be carreful : 
insert <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
after :     <link rel="stylesheet" href="styles.css">

b) be carreful:
insert <script src="https://cdnjs.cloudflare.com/ajax/libs/ng2-bootstrap/x.x.x/ng2-bootstrap.min.js"></script>
below : <script src="systemjs.config.js"></script>

6) to the systemjs.config.js
insert : 'moment': 'node_modules/moment/moment.js'



