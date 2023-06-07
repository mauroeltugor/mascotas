import javax.swing.JOptionPane;

public class Mascotas1 {
    // Atributos
    private int codigo;
    private String nombre;
    private String especie;
    private String accion;
    private String cualidad;
    private int edad;
    
    //getters y setters
    
    public int getCodigo() {
    	return codigo;
    }
    
    public void setCodigo(int codigo) {
    	this.codigo = codigo;
    }
    
    public int getEdad() {
    	return edad;
    }
    
    public void setEdad(int edad) {
    	this.edad = edad;
    }
    
    public String getNombre() {
    	return nombre;
    }
    
    public void setNombre(String nombre) {
    	this.nombre = nombre;
    }
    
    public String getEspecie(){
    	return especie;
    }
    
    public void setEspecie(String especie) {
    	this.especie = especie;
    }
    
    public String getAccion() {
    	return accion;
    }
    
    public void setAccion(String accion) {
    	this.accion = accion;
    }
    
    public String getCualidad() {
    	return cualidad;
    }
    
    public void setCualidad(String cualidad) {
    	this.cualidad = cualidad;
    }

    public Mascotas1() {
    }

    public void ingresar() {
        nombre = JOptionPane.showInputDialog("Ingrese nombre de la mascota");
        especie = JOptionPane.showInputDialog("Ingrese la especie de mascota");
        edad = Integer.parseInt(JOptionPane.showInputDialog("Ingrese la edad de la mascota"));
        accion = JOptionPane.showInputDialog("Ingrese la accion que hace la mascota");
        cualidad = JOptionPane.showInputDialog("Ingrese la cualidad de la mascota");
    }

    // Constructor de parametros
    public Mascotas1(String nombre, String especie, int edad, String accion, String cualidad) {
        this.nombre = nombre;
        this.accion = accion;
        this.cualidad = cualidad;
        this.especie = especie;
        this.edad = edad;
    }


    //Metodo donde la mascota ejecuta su sonido
    public void sonidoMascota() {
        if (especie.equalsIgnoreCase("gato")) {
            System.out.println("meeeeow");
        } else if (especie.equalsIgnoreCase("perro")) {
            System.out.println("woof woof");
        } else if (especie.equalsIgnoreCase("toro")) {
            System.out.println("muuuuuuuuuu");
        } else if (especie.equalsIgnoreCase("loro")) {
            System.out.println("rrrrr rrrrr ¿quiere cacao?");
        } else {
            System.out.println("Se desconoce el sonido de la mascota");
        }
    }

    //Metodo que muestra la informacion de la mascota
    public void InfoMascota() {
    	System.out.println("Nombre: " + nombre);
    	System.out.println("Especie: " + especie);
    	System.out.println("Edad: " + edad + " años");
    	System.out.println("Accion: " + accion);
    	System.out.println("Cualidad: " + cualidad);
    }
    
    // Metodo que muestra la cualidad de la mascota
    public void cualidadMascota() {
    	if (cualidad.equalsIgnoreCase("gato")) {
    		System.out.println("ronrronea");
    	} else if (cualidad.equalsIgnoreCase("perro")) {
    		System.out.println("saluda");
    	} else if (cualidad.equalsIgnoreCase("loro")) {
    		System.out.println("repite lo que uno dice");
    	} else if (cualidad.equalsIgnoreCase("toro")) {
    		System.out.println("come pasto");
    	} else {
    		System.out.println("La cualidad ingresada no se reconoce");
    	}
    }
    
    // Metodo que muestra la accion de la mascota
    public void accionMascota() {
        if (accion.equalsIgnoreCase("gato")) {
            System.out.println("se lame");
        } else if (accion.equalsIgnoreCase("perro")) {
            System.out.println("rueda");
        } else if (accion.equalsIgnoreCase("loro")) {
            System.out.println("habla");
        } else if (accion.equalsIgnoreCase("toro")) {
            System.out.println("refunfuñea");
        } else {
            System.out.println("La accion ingresada no se reconoce");
        }
    }

}