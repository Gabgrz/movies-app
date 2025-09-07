# Movies App

A movie theater management system with multiple implementations for seat booking and ticket purchasing.

## Components

### 1. Web Application (`peliculasWeb/`)
- **Technology**: Java Servlets + JSP + Bootstrap
- **Features**: 
  - Admin interface for configuring movie rooms
  - Customer interface for viewing movies and prices
  - Seat management system
- **Files**: `index.jsp` (admin), `cliente.jsp` (customer), `controlador.java` (servlet)

### 2. Console Application (`salasdecine/`)
- **Technology**: Java Console Application
- **Features**:
  - Interactive command-line interface
  - Create multiple movie rooms
  - Seat visualization and booking
  - Transaction management
- **Main Class**: `Main.java`

### 3. Desktop Application (`SWING JFrame/`)
- **Technology**: Java Swing GUI
- **Features**: Desktop GUI for movie theater management
- **Files**: `Administrador.java`, `Usuario.java`, `Asientos.java`

## Quick Start

### Web Application
1. Deploy `peliculasWeb` to a Java servlet container (Tomcat)
2. Access admin interface to configure rooms
3. Use customer interface to view movies and book seats

### Console Application
```bash
cd salasdecine
javac *.java
java salasdecine.Main
```

### Desktop Application
```bash
cd "SWING JFrame/boletodecines (1)/boletodecines"
javac *.java
java Main
```

## Features
- Multi-room movie theater management
- Seat booking and visualization
- Price configuration per movie
- Transaction tracking
- Multiple UI implementations (Web, Console, Desktop)
