# Blog Café
Se realizará un sitio web estático con **HTML** y **CSS**. 

@camoralesh27

:smiley:

---
## APUNTES

### Automatizar mq.
Para automatizar la creacion de media queries nos vamos a la barra de busqueda con "ctrl + p" ó "F1" y colocamos "user snippets". Luego ponemos "CSS.json" y podremos crear una regla para hacer media queries más rápido. Colocamos lo siguiente: 


"Crea un Media Querie":
    
    {
		"prefix": "mq",
		"body": "@media (min-width: $1) {\n    $2\n}"
	}

Cada símbolo de peso representa un tab. El primero para los px y el segundo para las reglas que se modificaran.
___
### Medidas de media queries recomendados.
1. ***Desktop*** @media (min-width:1024px){
}

2. ***Tablet*** @media (min-width:768px){
}

3. ***Smartphone*** @media (min-width:320px){
}
