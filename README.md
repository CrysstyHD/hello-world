hello-world
===========

import java.sql.Connection;


public class ConexiuneBazaDeDate 

{

	Connection c;

}

public class AdministrareComanda {
}

public class AdministrareProdus {
}

public class Comanda {
}

public class ControlUtilizatori {
}

public class Furnizor {

    String nume;
    int id;

    public Furnizor(String nume, int id){
        this.nume = nume;
        this.id = id;
    }
}

public class Haina extends Produs{

    String denumire;
    int marime;

    public Haina{
        this.denumire = denumire;
        this.marime = marime;
    }
}

public class Pantof extends Produs{

    String denumire,descriere;
    int marime;

    public Pantof{
        this.denumire = denumire;
        this.marime = marime;
        this.descriere = descriere;
    }
}

public class Produs {

    String descriere,nume;
    int id,cantitate;

    public Produs{
        this.cantitate = cantitate;
        this.id = id;
        this.nume = nume;
        this.descriere = descriere;
    }
}

public class Utilizatori {

    String user;
    int id,varsta;
    String adresa;

    public Utilizatori{
        this.user = user;
        this.varsta = varsta;
        this.id = id;
        this.adresa = adresa;
    }
}
