 case 3:
    /*          Actualizar datos
      */          break;
            case 4:
        //        Borrar usuario
                break;
            case 5:
        /*        Opciones de Doctor
                Agregar submenu para opciones de doctor
                -Realizar consulta
                -Dar de alta a paciente hospitalizado
                -salir
         */       
                break;
            case 6:
        /*        Agregar submenu con opciones de Paciente
                -Solicitar consulta 
                //Solicitar consulta va a permitir al paciente visualizar las consultas disponibles y las ocupadas por medio del metodo listarTurnosDisponibles() de la clase doctor
                //va a poder escoger una cita disponible agregar consulta por especialidad
                -Cancelar consulta
                -Cambiar consulta
                -salir
         */       
                break;
            case 7:
                System.out.println("Adios! ");
                break;
            default: 
                System.out.println("Seleccione una opcion valida: ");
                System.out.print("Elija la opcion que desee: \n 1) Registrar paciente\n 2) Listar datos del paciente \n 3) Listar datos del paciente\n4) Actualizar datos\n 5)Calcular IMC y diagnosticar \n Opcion:  ");
                break;
        }
    }while(opcion!=7);
  }   
}

