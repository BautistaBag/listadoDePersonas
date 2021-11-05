const personas = [
    new Persona('Juan',' Garcia'),
    new Persona('Emilio',' Lopez')
];
function mostrarPersonas(){
    console.log('Se esta ejecutando el metodo mostrarPersona');
    let texto = '';
    for(let persona of personas){
        console.log(persona);
        texto += `<li> ${persona.nombre}${persona.apellido} </li>`;
    }
    document.getElementById('personas').innerHTML = texto;
}

function agregarPersona(){
    //Tomamos el id forma de formulario
    const forma = document.forms['forma'];
    const nombre = forma['nombre'];
    const apellido = forma['apellido'];
    if(nombre.value!='' && apellido.value!=''){
    const persona = new Persona(nombre.value,apellido.value);
    console.log(persona);
    personas.push(persona);
    mostrarPersonas();
    }else{
        console.log('Campos Nombre y Apellido vacios');
    }
}
