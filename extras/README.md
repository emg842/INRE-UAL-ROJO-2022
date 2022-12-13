<br>

[Volver a la página anterior](https://github.com/emg842/INRE-UAL-ROJO-2022)

<br>

# Actividades extras

<br>

## Individuales

<br>

### Actividad 1. Diccionario de datos - Contrato

<br>

### Solución Daniel López García

<br>

<table align = "center">
    <tr>
        <td>
            Contrato: No Contrato + DatosCli + CaracInm + CaractCont + (Observaciones) + DatosSuc<br>
            DatoSuc: Codigo + Situacion + DatosEmp<br>
            DatosEmp: Nombre + Apellidos<br>
            Situacion: Calle + Ciudad + CP + TLF + FAX + Otros<br>
            DatosCli: Nombre + Apellidos + Direccion + (TLF)<br>
            CaractCont: [Compra|Venta] + Comision + PagaComision
        </td>
    </tr>
</table>

<br>

### Solución Eduardo Martín Gómez

<br>

<table align = "center">
    <tr>
        <td>
            Contrato: No Contrato + DatosCli + CaracInm + CaractCont + (Observaciones) + DatosSuc<br>
            DatoSuc: Codigo + Situacion + DatosEmp<br>
            DatosEmp: Nombre + Apellidos<br>
            Situacion: Calle + Ciudad + CP + TLF + FAX + Otros<br>
            DatosCli: Nombre + Apellidos + Direccion + (TLF)<br>
            CaractCont: [Compra|Venta] + Comision + PagaComision
        </td>
    </tr>
</table>

<br>

### Solución Miguel Ángel Moncada Álvarez

<br>

<table align = "center">
    <tr>
        <td>
            Contrato: No Contrato + DatosCli + CaracInm + CaractCont + (Observaciones) + DatosSuc<br>
            DatoSuc: Codigo + Situacion + DatosEmp<br>
            DatosEmp: Nombre + Apellidos<br>
            Situacion: Calle + Ciudad + CP + TLF + FAX + Otros<br>
            DatosCli: Nombre + Apellidos + Direccion + (TLF)<br>
            CaractCont: [Compra|Venta] + Comision + PagaComision<br>
        </td>
    </tr>
</table>

<br>

### Solución Joaquín Murcia Escánez

<br>

<table align = "center">
    <tr>
        <td>
            Contrato = NumContrato + DatosSuc + DatosCli + {CaracInm} + CaracCon + (Observaciones)<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                NumContrato = {Digito}<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                DatosSuc = CodigoSuc + Situacion + DatosEmp<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    CodigoSuc = {Digito}<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    Situacion = Calle + Ciudad + CP + {Telefono} + Fax<br>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                        Calle = Ciudad = {Caracter}<br>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                        CP = Telefono = Fax = {Digito}<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    DatosEmp = Nombre + {Apellido}<br>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                        Nombre = Apellido = {Caracter}<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                DatosCli = Nombre + {Apellido} + Direccion + (Telefono)<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    Direccion = Calle + Ciudad + CP<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                CaracInm = TipoInm + NumHabitaciones + DotacionesDep + M2 + Precio<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    TipoInm = ["Piso" | "Bungalow" | "Chalet" | "Parcela" | "TerrenoRustico"]<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    NumHabitaciones = {Digito}<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    DotacionesDep = {["PistaTenis" | "Squash" | "Polideportiva" | "Paddle" | "Piscina"]}<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    M2 = Precio = {Digito}<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                CaracCon = TipoCon + ComisionSuc + PagadorComision + FormaPago<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    TipoCon = ["Compra" | "Venta"]<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    ComisionSuc = {Digito} + "%"<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    PagadorComision = ["Comprador" | "Vendedor"]<br>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    FormaPago = ["Contado" | "Tarjeta" | "Talon"]<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                Observaciones = {[Caracter | Digito]}<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                Caracter = ["A" - "Z" | "a" - "z"]<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                Digito = "0" - "9"<br>
        </td>
    </tr>
</table>

<br>

### Solución Manuel Vallecillos Escobosa

<br>

<table align = "center">
    <tr>
        <td>
            Contrato = NumContrato + DatosSuc + DatosCli + {CaracInm} + CaracCon + (Observaciones)<br>
            NumContrato = {Digito}<br>
            DatosSuc = CodigoSuc + Situacion + DatosEmp<br>
            CodigoSuc = {Digito}<br>
            Situacion = Calle + Ciudad + CP + {Telefono} + Fax<br>
            Calle = Ciudad = {Caracter}<br>
            CP = Telefono = Fax = {Digito}<br>
            DatosEmp = Nombre + {Apellido}<br>
            Nombre = Apellido = {Caracter}<br>
            DatosCli = Nombre + {Apellido} + Direccion + (Telefono)<br>
            Direccion = Calle + Ciudad + CP<br>
            CaracInm = TipoInm + NumHabitaciones + DotacionesDep + M2 + Precio<br>
            TipoInm = ["Piso" | "Bungalow" | "Chalet" | "Parcela" | "TerrenoRustico"]<br>
            NumHabitaciones = {Digito}<br>
            DotacionesDep = {["PistaTenis" | "Squash" | "Polideportiva" | "Paddle" | "Piscina"]}<br>
            M2 = Precio = {Digito}<br>
            CaracCon = TipoCon + ComisionSuc + PagadorComision + FormaPago<br>
            TipoCon = ["Compra" | "Venta"]<br>
            ComisionSuc = {Digito} + "%"<br>
            PagadorComision = ["Comprador" | "Vendedor"]<br>
            FormaPago = ["Contado" | "Tarjeta" | "Talon"]<br>
            Observaciones = {[Caracter | Digito]}<br>
            Caracter = ["A" - "Z" | "a" - "z"]<br>
            Digito = "0" - "9"<br>
        </td>
    </tr>
</table>

<br>

### Actividad 2. Diccionario de datos - Fecha

<br>

### Solución Daniel López García

<br>

<table align = "center">
    <tr>
        <td>
            Fecha = Dia + Mes + Año<br>
            Dia = Num<br>
            Num = "1" - "31"<br>
            Mes = {Caracter}<br>
            Caracter = ["A"-"Z"|"a"-"z"]<br>
            Año = [-|+] + {ConNum}<br>
            ConNum = {CaracterNum}<br>
            CaracterNum = "0"-"9"
        </td>
    </tr>
</table>

<br>

### Solución Eduardo Martín Gómez

<br>

<table align = "center">
    <tr>
        <td>
            FECHA = DIA + MES + AÑO<br>
            DIA = { NUM }<br>
            NUM = "1" - "31"<br>
            MES = {CARACTER}<br>
            CARACTER = ["A"-"Z" | "a"-"z"]<br>
            AÑO = [- | +] + {ConNum}<br>
            ConNum = {CARACTnum}<br>
            CARACTnum = "0" - "9"
        </td>
    </tr>
</table>

<br>

### Solución Miguel Ángel Moncada Álvarez

<br>

<table align = "center">
    <tr>
        <td>
            FECHA = DIA + MES + AÑO<br>
            DIA = { NUM }<br>
            NUM = "1" - "31"<br>
            MES = {CARACTER}<br>
            CARACTER = ["A"-"Z" | "a"-"z"]<br>
            AÑO = [- | +] + {ConNum}<br>
            ConNum = {CARACTnum}<br>
            CARACTnum = "0" - "9"
        </td>
    </tr>
</table>

<br>

### Solución Joaquín Murcia Escánez

<br>

<table align = "center">
    <tr>
        <td>
            Fecha = Dia + Mes + Anio<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                Dia = "1" - "31"<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                Mes = {Caracter}<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    Caracter = ["A" - "Z" | "a" - "z"]<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                Anio = {Digito} + ["a.C." | "d.C."]<br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    Digito = "0" - "9"
        </td>
    </tr>
</table>

<br>

### Solución Manuel Vallecillos Escobosa

<br>

<table align = "center">
    <tr>
        <td>
            Fecha = Dia + Mes + Anio<br>
            Dia = "1" - "31"<br>
            Mes = {Caracter}<br>
            Caracter = ["A" - "Z" | "a" - "z"]<br>
            Anio = {Digito} + ["a.C." | "d.C."]<br>
            Digito = "0" - "9"
        </td>
    </tr>
</table>

<br><br>

## Grupales

<br>

### Actividad 3. Diagrama BPMN

<br>

<div align="center"><img src="./extras_Grupales/out/BPMN.jpg"></div>

<br><br>

### Actividad 4. Diagrama E/R y de clases - Gestión Biblioteca

<br>

<div align="center"><img src="./extras_Grupales/out/ER_gestion_biblioteca.svg"></div>

<br>

<div align="center"><img src="./extras_Grupales/out/DC_gestion_biblioteca.svg"></div>

<br>