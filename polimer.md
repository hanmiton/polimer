web component son una nueva tecnologia, adoptad paultainament por todo slo navegadore smoderno s, que nos permite extender y personlizar html tal y como los conocemos

-Custom elemtns
	Es la capacidad de crear nuestrar porpias tags en html con nuestras propiedades
-Shadow DOM
	Proveen encapsulacion para Javascript, CSS y templates dentro WebComponent
-HTML templates
	es una etiqueta de html q es template
	es un mecanimso for tener contenido del lado del cliente se presentan via javascript
-HTML Imports
	Es un mecanismo para empaquetas template script css3 y se lo linkead como cualquier otra cosa
	(modularizacion)
@import cuadno se importa un elemtno completo personalizado

BOWER
 es un administrador de paquetes
 instalacion
 	npm install bower
 iniciando un nuevo poreycto de bower
 	bower init
libreria para hacer qeu web component sea util en cualqueir navegador
	bower install webcomponentjs --save
polimer es una libreria para web components
instalando polimer con bower
	ssbower install --save polymer#1.0.0
cuadno haya problemas q no carge ele web compoente puede ser que se quedo grabado en las cookies por lo que es mejor eliminar las cookies

Preguntas
 core elements ahora son iron elemnts
ventajas de web componetes
	legibilidad
	sea reutilizable (modular)
//directiva de angular
	necesitan de angular un web componente de polymer corre en el DOM 
//yeoman
para tener generadores bases de proyectos
Polymer Starter Kit
	Iron-> Son los core elemnets del pasado
	Routing Page.js
Notify-> permite hacer el two way datangibnfg

Elements.html->tiene los import de lso components

Routing
	archivo qu eocntolr las rutas

.jshrhc
	Linter que rebiza q el codigo q escribimos sea bueno
-bower
	maneja librerias del lado del frontend
vulcanized 
	permite minificar html concatena todos los web components que tenemos en un solo elemento
All Elements
	Iron Elements
		Core elements
	Md
		Material design elements
	Go
		Google web components
	Au
		Ecommerce Elements
	Ne
		Animation and Special Effects
	Platinum Elments
		Para el trabajo online
	Molecules
		Elemento q envuleven librerias completas de javascript de terceros
	Componetes deben tern un guion en el medio

	Tocar hacer los imports dentro de lements.html

	Siempre primero instlar los componenetes pra usar los componenetes

	Agregara elementos
		1.- Instlar elemetno via bower
		2.- importan elemnto 
		3.- y despues hacmeos una seccion par adicho componetne dentor de index
fullbledd 
	para que ocupe toda la pantalla
layout
	indica como se va renderiar
vertical 
	posicin en la q se renderea
Polimer se basa en flexbox
flex
	toma todo le espacio de q su padre lo permita
flex two
iron ajax

service workeres
se comunica con internet pero si no ahi guarda contenido para mostrar al usuario
//aplicones offline
	auto-register
	clients-claim
	skip-waiting
	on-service-worker-isntalled
defaulo-cache estrategy="networkFirst"
//GLOB cache de elemetos 
//extendiendo etiquetas nativas
<style media="screen">
	:host{

	};
</style>
<content></content>
<script>
	Polymer({
		is: 'super-h1',
		extends: 'h1'
	})
</script>
<h1 is = "super-h1">Super h1</h1>

falldas 
cuales son las estrategis mas comuner par ale uncionamiento de app offline
 -cache only, network first, network only
 Donde se deben regristra los atribuotos presonlaizado spara nuestro web compoennt
 - behairvors
 Los hatml templates son instanciados
 - automaticamente por el DOM
 Cuales son los generadores d eproyecto spolymer oficiales disponibles
 -kit, ligth
 cual es el pseduo-selecto mediante el cual podermo modificar los estilos default de los web componentes preinstlador por poymer starter kit
 -host
 cual es la forma corercta deañdir ocmporntamiento inherentes a un web component
 -.......