# Fz3r0 - JurassicPark.html 

Welcome to Jurassic Park!!! (in HTML)...Este proyecto son una serie de scripts "super mega raw" en HTML sin ningún tipo de estilo agregado, ni modificación de ningún tipo, ni tamaños, ni tipografías, etc... HTML en su estado más puro posible. 

- El propósito de este proyecto es tanto para practicar `HTML` como para tener un proyecto base en formato .html lo más limpio posible para mis proyectos futuros de `CSS` y `Javascript`

- Este script respeta por completo la `Semántica HTML` para que `CSS` lo pueda adaptar lo mejor posible.

- Adjunto el proyecto completo incluyendo `directories`, `images`, `source-code`.

- Espero esta información y tanto mi proyecto de `HTML` como el Lab de `CSS` ayude a alguien :)

- _**Life finds a way**..._   

# DESCARGAR DIRECTORIO COMPLETO

- [|-----<<<  DESCARGAR: CSS_Fz3r0_Lab-ROOTdir  >>>-----|](https://github.com/Fz3r0/Web-Programming-Fz3r0/files/8765615/CSS_Fz3r0_Lab_-_ROOT_dir.zip) 

# Directorios y Archivos en el Server:

### Páginas HTML Iniciales

- ![image](https://user-images.githubusercontent.com/94720207/170113297-4dd95f43-88ee-4656-8c06-11b12d2f57d7.png)

### Directorio "root" principal: `/`

- ![image](https://user-images.githubusercontent.com/94720207/170094834-5e5a8430-9afd-4f42-bcce-b78d42c20a69.png)

### Directorio "images": `/images`

- ![image](https://user-images.githubusercontent.com/94720207/170095055-e33e59b8-daf1-43dc-879e-f21440aa51e2.png)

### Directorio "other_pages": `/other_pages`

- ![image](https://user-images.githubusercontent.com/94720207/170095288-cfd3f10d-0fa9-42f4-b3b5-30084a0aa86c.png)

## Semántica HTML
 
- **Idea aproximada de la semántica HTML que llevará la página:**

- ![image](https://user-images.githubusercontent.com/94720207/169996597-cde55d9f-4834-440d-8337-d57135dd190a.png)
 








## Index: `/index.html`

<details>
<summary>Click Aquí para ver código HTML by Fz3r0</summary>

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Fz3r0: Jurassic Park - CSS Pro Lab</title>
		<meta charser="utf-8">
		<meta name="keywords" content="Fz3r0 CSS Pro Lab">
		<meta name="description" content="Github: Fz3r0 /// Twitter: Fzer0_OPs">
		<meta name="author" content="Fz3r0">
		<meta name="copyright" content="Skynet Incorporated SA. de CV.">
		<meta name="robots" content="index">
		<meta name="robots" content="follow">
		<link href="images/favicon.ico" rel="icon" type="image/x-icon">
    </head>	
    <body>
    <header>
    		<nav>
    			<ul>
    				<p>---------| Este es el "header" y su "nav" |---------</p>
    				<li><a href="other_pages/page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    				<li><a href="other_pages/page2_dino_photos.html">Link a Page2: Fotos de Dinosaurios</a></li>
    				<li><a href="other_pages/page3_jurassic_map.html">Link a Page3: Mapa del Parque</a></li>
    				<li><a href="other_pages/page4_prices_table.html">Link a Page4: Jurassic Store</a></li>
    				<p>---------| Termina el "header" y su "nav" |---------</p>
    			</ul>
    		</nav>
    </header>
<main>    
    <article>
		<section>	
    		        <p>---------| Inicia el "contenido central" de página |---------</p>
    		        <h1>Titulo 1 (Section1)</h1>
    			<p>
    				Párrafo1 Section1 Párrafo1 Section1 Párrafo1 Section1 Párrafo1 Section1 Párrafo1 Section1 Párrafo1 Section1.<br>
    				Atentamente: Párrafo1 Section1		  
    			</p>
    			<p>
    				Párrafo2 Section1 Párrafo2 Section1 Párrafo2 Section1 Párrafo2 Section1.
    			</p>
    			<p>
    			<a href="https://www.youtube.com/watch?v=u6ckRTxyNyA"><img src="images/explorer.jpg" alt="alt: explorer" title="title: mouse hover"></a><br>
    			Párrafo3: Foto + Pie de foto de la Explorer de Jurassic Park
    			</p>
		</section>    
		<section>	
    		        <h2>Titulo 2 (Section2)</h2>
    			<p>
    				Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2 Párrafo1 Section2.   
    			</p>
    			<p>---------| Termina el "contenido central" de página |---------</p>
		</section>
	        <section>
	    	<aside>
	    		<h3>Titulo aside 1</h3>
	    		<p>Contenido aside 1</p>
	    	</aside>
	        </section>
	        <section>
	    	<aside>
	    		<h3>Titulo aside 2</h3>
	    		<p>Contenido aside 2</p>
	    	</aside>
	        </section>
    </article>        
    	    <aside>
	        <h3>Titulo aside 3, aside independiente de article</h3>
	        <p>Contenido aside 3: sin "section" y fuera del "article", último "aside"</p>
	    </aside>
</main>
    <footer>
    		 <nav>
    		     <p>---------| comienza footer y su nav |---------</p>	
    			 <ul>
    			 <li><a href="index.html" >Link a index.html: Volver al Index</a></li>
		         <li><a href="other_pages/page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    			 </ul>
		         <p>Este es el footer con su "nav"</p>
    		 </nav>
    </footer>	    
    </body>
</html>
```

</details>
	
- ![image](https://user-images.githubusercontent.com/94720207/170096441-5686606f-2e71-4734-a5de-a1cfa7aa8023.png)











## Page 1: `other_pages/whoami.html`

<details>
<summary>Click Aquí para ver código HTML by Fz3r0</summary>
	
```html
<!DOCTYPE html>
<html>
    <head>
		<title>Fz3r0: Jurassic Park - CSS Pro Lab</title>
		<meta charser="utf-8">
		<meta name="keywords" content="Fz3r0 CSS Pro Lab">
		<meta name="description" content="Github: Fz3r0 /// Twitter: Fzer0_OPs">
		<meta name="author" content="Fz3r0">
		<meta name="copyright" content="Skynet Incorporated SA. de CV.">
		<meta name="robots" content="index">
		<meta name="robots" content="follow">
		<link href="images/favicon.ico" rel="icon" type="image/x-icon">
    </head>	
    <body>
    <header>
    		<nav>
    			<ul>
    				<p>---------| Este es el "header" y su "nav" |---------</p>
    				<li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    				<li><a href="page2_dino_photos.html">Link a Page2: Fotos de Dinosaurios</a></li>
    				<li><a href="page3_jurassic_map.html">Link a Page3: Mapa del Parque</a></li>
    				<li><a href="page4_prices_table.html">Link a Page4: Jurassic Store</a></li>
    				<p>---------| Termina el "header" y su "nav" |---------</p>
    			</ul>
    		</nav>
    </header>
<main>    
    <article>
		<section>	
    		        <p>---------| Inicia el "contenido central" de página |---------</p>
    		        <h1>Titulo 1 (Section1): WHO AM I???</h1>
    			<p>
    				Párrafo1 Section1:<br>
    				I am: | Github: Fz3r0 | Twitter: Fz3r0_OPs 		  
    			</p>
    			<p>
    				Párrafo2 Section1<br>
    				Follow me!!!
    			</p>
    			<p>
    			<a href="https://github.com/Fz3r0"><img src="https://user-images.githubusercontent.com/94720207/165896925-bb6403fc-e3b3-480f-971b-874401e43708.gif" alt="alt: explorer" title="title: mouse hover"></a><br>
    			I am Fz3r0 and the Sun no longer rises...
    			</p>
		</section>    
	        <section>
	    	<aside>
	    		<h3>Titulo aside 1</h3>
	    		<p>Contenido aside 1</p>
	    	</aside>
	        </section>
	        <section>
	    	<aside>
	    		<h3>Titulo aside 2</h3>
	    		<p>Contenido aside 2</p>
	    	</aside>
	        </section>
    </article>        
    	    <aside>
	        <h3>Titulo aside 3, aside independiente de article</h3>
	        <p>Contenido aside 3: sin "section" y fuera del "article", último "aside"</p>
	    </aside>
</main>
    <footer>
    		 <nav>
    		     <p>---------| comienza footer y su nav |---------</p>	
    			 <ul>
    			 <li><a href="../index.html" >Link a index.html: Volver al Index</a></li>
		         <li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    			 </ul>
		         <p>Este es el footer con su "nav"</p>
    		 </nav>
    </footer>	    
    </body>
</html>
```
</details>

- ![image](https://user-images.githubusercontent.com/94720207/170097670-9ad06536-2001-4c95-830b-e0ce104b0f37.png)












## Page 2: `other_pages/dino_photos.html`

<details>
<summary>Click Aquí para ver código HTML by Fz3r0</summary>	
	
```html
<!DOCTYPE html>
<html>
    <head>
		<title>Fz3r0: Jurassic Park - CSS Pro Lab</title>
		<meta charser="utf-8">
		<meta name="keywords" content="Fz3r0 CSS Pro Lab">
		<meta name="description" content="Github: Fz3r0 /// Twitter: Fzer0_OPs">
		<meta name="author" content="Fz3r0">
		<meta name="copyright" content="Skynet Incorporated SA. de CV.">
		<meta name="robots" content="index">
		<meta name="robots" content="follow">
		<link href="images/favicon.ico" rel="icon" type="image/x-icon">
    </head>	
    <body>
    <header>
    		<nav>
    			<ul>
    				<p>---------| Este es el "header" y su "nav" |---------</p>
    				<li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    				<li><a href="page2_dino_photos.html">Link a Page2: Fotos de Dinosaurios</a></li>
    				<li><a href="page3_jurassic_map.html">Link a Page3: Mapa del Parque</a></li>
    				<li><a href="page4_prices_table.html">Link a Page4: Jurassic Store</a></li>
    				<p>---------| Termina el "header" y su "nav" |---------</p>
    			</ul>
    		</nav>
    </header>
<main>    
    <article>
		<section>	
    		        <p>---------| Inicia el "contenido central" de página |---------</p>
    		        <h1>Titulo 1 (Section1): Fotos de Dinosaurios</h1>
    			<p>
    			<h3> Foto1: </h3>
    			<a href="https://github.com/Fz3r0"><img src="../images/welcome.jpg" alt="alt: welcome" title="title: welcome mouse hover"></a><br>
    			Párrafo 1: welcome to jurassic park!!!
    			</p>
    			<h3> Foto2: </h3>
    			<a href="https://github.com/Fz3r0"><img src="../images/brachio.jpg" alt="alt: welcome" title="title: welcome mouse hover"></a><br>
    			Párrafo 2: welcome to jurassic park!!!
    			</p>
    			<h3> Foto3: </h3>
    			<a href="https://github.com/Fz3r0"><img src="../images/malcom.jpg" alt="alt: welcome" title="title: welcome mouse hover"></a><br>
    			Párrafo 3: welcome to jurassic park!!!
    			</p>
		</section>    
	        <section>
	    	<aside>
	    		<h3>Titulo aside 1</h3>
	    		<p>Contenido aside 1</p>
	    	</aside>
	        </section>
	        <section>
	    	<aside>
	    		<h3>Titulo aside 2</h3>
	    		<p>Contenido aside 2</p>
	    	</aside>
	        </section>
    </article>        
    	    <aside>
	        <h3>Titulo aside 3, aside independiente de article</h3>
	        <p>Contenido aside 3: sin "section" y fuera del "article", último "aside"</p>
	    </aside>
</main>
    <footer>
    		 <nav>
    		     <p>---------| comienza footer y su nav |---------</p>	
    			 <ul>
    			 <li><a href="../index.html" >Link a index.html: Volver al Index</a></li>
		         <li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    			 </ul>
		         <p>Este es el footer con su "nav"</p>
    		 </nav>
    </footer>	    
    </body>
</html>
```


</details>

- ![image](https://user-images.githubusercontent.com/94720207/170100663-a66ee217-d8a2-44a4-9f4d-c53b7d085425.png)

## Page3 `page3_jurassic_map.html`

<details>
<summary>Click Aquí para ver código HTML by Fz3r0</summary>

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Fz3r0: Jurassic Park - CSS Pro Lab</title>
		<meta charser="utf-8">
		<meta name="keywords" content="Fz3r0 CSS Pro Lab">
		<meta name="description" content="Github: Fz3r0 /// Twitter: Fzer0_OPs">
		<meta name="author" content="Fz3r0">
		<meta name="copyright" content="Skynet Incorporated SA. de CV.">
		<meta name="robots" content="index">
		<meta name="robots" content="follow">
		<link href="images/favicon.ico" rel="icon" type="image/x-icon">
    </head>	
    <body>
    <header>
    		<nav>
    			<ul>
    				<p>---------| Este es el "header" y su "nav" |---------</p>
    				<li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    				<li><a href="page2_dino_photos.html">Link a Page2: Fotos de Dinosaurios</a></li>
    				<li><a href="page3_jurassic_map.html">Link a Page3: Mapa del Parque</a></li>
    				<li><a href="page4_prices_table.html">Link a Page4: Jurassic Store</a></li>
    				<p>---------| Termina el "header" y su "nav" |---------</p>
    			</ul>
    		</nav>
    </header>
<main>    
    <article>
		<section>	
    		        <p>---------| Inicia el "contenido central" de página |---------</p>
    		        <h1>Titulo 1 (Section1): Jurassic Map</h1>
    			<h3> Subtítulo 1: Audio </h3>
    			<p>
    			Párrafo1: Bienvenid@ al mapa de Jurassic Park. Nota: no apagar las cercas electrificadas, plis! 
    			<audio src="https://ia801600.us.archive.org/12/items/JurassicParkThemeSong./Jurassic%20Park%20theme%20song..mp3" controls=""><br>
    			</p>
    			<h3> Subtítulo 2: Mapa </h3>
    			<p>
    			Párrafo2: Isla Nublar was a remote island 120 miles west of Costa Rica and 87 miles east of the Muertes Archipelago. The island has a surface of 77 square kilometers with mountain ridges which created varied ecological niches.<br>	
    			<a href="https://github.com/Fz3r0"><img src="../images/jurassic_map.jpg" alt="alt: welcome" title="title: welcome mouse hover"></a><br>
    			Párrafo 2: Pie de página del mapa.
		</section>    
	        <section>
	    	<aside>
	    		<h3>Titulo aside 1</h3>
	    		<p>Contenido aside 1</p>
	    	</aside>
	        </section>
	        <section>
	    	<aside>
	    		<h3>Titulo aside 2</h3>
	    		<p>Contenido aside 2</p>
	    	</aside>
	        </section>
    </article>        
    	    <aside>
	        <h3>Titulo aside 3, aside independiente de article</h3>
	        <p>Contenido aside 3: sin "section" y fuera del "article", último "aside"</p>
	    </aside>
</main>
    <footer>
    		 <nav>
    		     <p>---------| comienza footer y su nav |---------</p>	
    			 <ul>
    			 <li><a href="../index.html" >Link a index.html: Volver al Index</a></li>
		         <li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    			 </ul>
		         <p>Este es el footer con su "nav"</p>
    		 </nav>
    </footer>	    
    </body>
</html>
```

</details>

- ![image](https://user-images.githubusercontent.com/94720207/170109743-b2863544-4c11-4cdb-8a25-994edca7914c.png)











## Page4 `page4_prices_table.html`

<details>
<summary>Click Aquí para ver código HTML by Fz3r0</summary>

```html
<!DOCTYPE html>
<html>
    <head>
		<title>Fz3r0: Jurassic Park - CSS Pro Lab</title>
		<meta charser="utf-8">
		<meta name="keywords" content="Fz3r0 CSS Pro Lab">
		<meta name="description" content="Github: Fz3r0 /// Twitter: Fzer0_OPs">
		<meta name="author" content="Fz3r0">
		<meta name="copyright" content="Skynet Incorporated SA. de CV.">
		<meta name="robots" content="index">
		<meta name="robots" content="follow">
		<link href="images/favicon.ico" rel="icon" type="image/x-icon">
    </head>	
    <body>
    <header>
    		<nav>
    			<ul>
    				<p>---------| Este es el "header" y su "nav" |---------</p>
    				<li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    				<li><a href="page2_dino_photos.html">Link a Page2: Fotos de Dinosaurios</a></li>
    				<li><a href="page3_jurassic_map.html">Link a Page3: Mapa del Parque</a></li>
    				<li><a href="page4_prices_table.html">Link a Page4: Jurassic Store</a></li>
    				<p>---------| Termina el "header" y su "nav" |---------</p>
    			</ul>
    		</nav>
    </header>
<main>    
    <article>
	<section>	
    		        <p>---------| Inicia el "contenido central" de página |---------</p>
    		        <h1>Titulo 1 (Section1): Dino Store</h1>
	<p>
		<img src="../images/dino_store.jpg">
	</p>
	<p>	
		Section1 Párrafo1: Bienvenidos a la tienda de Jurassic Park!.<br> 
		(No tocar al velociraptor, gracias). Ahora inicia la tabla:
	</p>
    </section>
    <section>
	<table>
		<thead>
			<tr>
				<th>Tabla JP</th>
				<th>Header 1</th>
				<th>Header 2</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>*</td>
				<td>Menor</td>
				<td>Adulto</td>
			</tr>
			<tr>
				<td>Entrada</td>
				<td>$500</td>
				<td>$1000</td>
			</tr>
			<tr>
				<td>Refresco</td>
				<td>$20</td>
				<td>$20</td>
			</tr>
			<tr>
				<td>Gelatina</td>
				<td>$10</td>
				<td>$10</td>
			</tr>
			<tr>
				<td>Paseo en Jeep</td>
				<td>$150</td>
				<td>$200</td>
			</tr>
			<tr>
				<td>Electroshock</td>
				<td>Gratis!</td>
				<td>N/A</td>
			</tr>
		</tbody>
	</table>
    </section>
    <section>
    	<h3>Section2: Comprar artículos o entradas al parque:</h3>
			<p>Seleccione tipo de cliente: (input1)</p>
				<form action="">
  				<label for="fname">¿menor o adulto?</label><br>
  				<input type="text" id="producto" name="producto" value=""><br>
				</form>
			<p>Seleccione producto a comprar: (input2) </p>
				<form action="">
  				<label for="fname">Producto:</label><br>
  				<input type="text" id="producto" name="producto" value=""><br>
  				<input type="submit" value="(Submit)Comprar!">
				</form>
    </section>
    <section>
	    	<aside>
	    		<h3>Titulo aside 1</h3>
	    		<p>Contenido aside 1</p>
	    	</aside>
	        </section>
	        <section>
	    	<aside>
	    		<h3>Titulo aside 2</h3>
	    		<p>Contenido aside 2</p>
	    	</aside>
	        </section>
    </article>        
    	    <aside>
	        <h3>Titulo aside 3, aside independiente de article</h3>
	        <p>Contenido aside 3: sin "section" y fuera del "article", último "aside"</p>
	    </aside>
</main>
    <footer>
    		 <nav>
    		     <p>---------| comienza footer y su nav |---------</p>	
    			 <ul>
    			 <li><a href="../index.html" >Link a index.html: Volver al Index</a></li>
		         <li><a href="page1_whoami.html">Link a Page1: ¿Quién es Fz3r0?</a></li>
    			 </ul>
		         <p>Este es el footer con su "nav"</p>
    		 </nav>
    </footer>	    
    </body>
</html>	

	
```
	
</details>

- ![image](https://user-images.githubusercontent.com/94720207/170122637-42aa61c6-a925-4ac4-a2b9-3d3599f7cc6f.png)


















