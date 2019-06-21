# FrameworkCSS
Framework personalizado para CSS y HTML

## Contenedores principales
    contenedor
    contenedor-total
    
## Renglones para agregar contenido (Contiene 12 columnas internas)
    renglon
    
## Columnas para agregar secciones dentro de un renglón (el número define el tamaño que ocupará, se puede pasar el límite de 12 columnas por renglón ocupadas, pero no se garantiza que se vea correctamente)
    col-1
    col-2
    col-3
    col-4
    col-5
    col-6
    col-7
    col-8
    col-9
    col-10
    col-11
    col-12
    
## Contenedor interno de las columnas (proporciona márgenes)
    contenido

## Todo contenedor debe tener la siguiente estructura preferentemente (**X** indica el tamaño de columa)
    <div class="contenedor">
      <div class="renglon">
        <div class="col-X">
          <div class="contenido">
            ...
          </div>
        </div>
      </div>
    </div>

## Tamaños personalizados de títulos (Puede usarse en h1, h2, ..., p, etc.)
    titulo-1  [100px de alto]
    titulo-2  [90px de alto]
    titulo-3  [80px de alto]
    titulo-4  [70px de alto]
    titulo-5  [60px de alto]
    
## Estilos de texto
    delgado
    extra-delgado
    mas-delgado
    negritas
    semi-negritas
    
## Tipos de texto
    cursiva
    serif
    trazo
    codigo
    
## Alineación del texto
    texto-centrado
    
## Cantidad de separación en hr
    separacion-1  [5px de arriba y abajo]
    separacion-2  [10px de arriba y abajo]
    separacion-3  [15px de arriba y abajo]
    separacion-4  [20px de arriba y abajo]

## Imagen que se acomoda
    imagen

## Botón por defecto
    btn
    
## Botón del tamaño del renglón
    btn-renglon

## Botones de Colores
    btn-verde-claro
    btn-verde
    btn-azul
    btn-azul-oscuro
    btn-rojo
    brn-rojo-oscuro
    btn-amarillo
    btn-negro
    btn-rosa
    btn-blanco
    btn-morado
    btn-naranja

## Fondos
    fondo-verde
    fondo-azul
    fondo-rojo
    fondo-amarillo
    fondo-morado
    fondo-naranja
    fondo-rosa
    fondo-verde-claro

## Colores de Formularios
    form-verde
    form-azul
    form-rojo
    form-amarillo
    form-morado
    form-naranja
    form-rosa
    form-verde-claro

## Colores Checkbox
    check-verde
    check-azul
    check-rojo
    check-amarillo
    check-rosa
    check-morado
    check-verde-claro
    check-azul-oscuro
    check-rojo-oscuro
    check-negro
    check-blanco
    check-naranja

## Colores Radio Button
    radio-verde
    radio-azul
    radio-rojo
    radio-amarillo
    radio-rosa
    radio-morado
    radio-verde-claro
    radio-azul-oscuro
    radio-rojo-oscuro
    radio-negro
    radio-blanco
    radio-naranja