# landingpage1
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Superklub Dive Clif - Buceo de Lujo</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Encabezado con imagen de fondo -->
    <header>
        <div class="hero">
            <h1>Superklub Dive Clif</h1>
            <p>Explora el lujo bajo las olas</p>
            <a href="#reservas" class="cta-button">Reserva tu experiencia</a>
        </div>
    </header>

    <!-- Sección de Servicios -->
    <section id="servicios">
        <h2>Vive la Experiencia de Buceo Más Exclusiva</h2>
        <div class="servicios-container">
            <div class="servicio">
                <h3>🏝️ Rutas Exclusivas</h3>
                <p>Explora los mejores arrecifes y zonas protegidas del Mediterráneo y Caribe.</p>
            </div>
            <div class="servicio">
                <h3>🛥️ Vida a Bordo de Lujo</h3>
                <p>Barco premium con cabinas privadas, gastronomía gourmet y bienestar a bordo.</p>
            </div>
            <div class="servicio">
                <h3>🤿 Experiencias Personalizadas</h3>
                <p>Buceo nocturno, fotografía subacuática y actividades exclusivas.</p>
            </div>
        </div>
    </section>

    <!-- Sección de Testimonios -->
    <section id="testimonios">
        <h2>Lo que dicen nuestros clientes</h2>
        <div class="testimonial">
            <p>“Una experiencia de buceo única, lujo y aventura combinados perfectamente.”</p>
            <h4>- María López</h4>
        </div>
        <div class="testimonial">
            <p>“Increíble atención, el mejor viaje de buceo que he realizado en mi vida.”</p>
            <h4>- Carlos Ramírez</h4>
        </div>
    </section>

    <!-- Sección de Reserva -->
    <section id="reservas">
        <h2>Reserva tu experiencia ahora</h2>
        <form>
            <input type="text" placeholder="Nombre" required>
            <input type="email" placeholder="Correo Electrónico" required>
            <input type="date" required>
            <button type="submit">Solicitar Reserva</button>
        </form>
    </section>

    <!-- Pie de página -->
    <footer>
        <p>&copy; 2024 Superklub Dive Clif | Todos los derechos reservados</p>
    </footer>

</body>
</html>
/* Estilos generales */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    color: white;
    background-color: #001f3f;
}

/* Estilo del encabezado */
header {
    background: url('https://source.unsplash.com/1600x900/?ocean,diving') no-repeat center center/cover;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.hero {
    background: rgba(0, 0, 0, 0.5);
    padding: 20px;
    border-radius: 10px;
}

h1 {
    font-size: 3em;
}

.cta-button {
    display: inline-block;
    background: #f39c12;
    color: white;
    padding: 15px 30px;
    margin-top: 20px;
    text-decoration: none;
    font-size: 1.2em;
    border-radius: 5px;
}

/* Sección de servicios */
#servicios {
    padding: 50px;
    background: #002b5e;
}

.servicios-container {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
}

.servicio {
    background: rgba(255, 255, 255, 0.2);
    padding: 20px;
    border-radius: 10px;
    width: 300px;
}

/* Testimonios */
#testimonios {
    padding: 50px;
    background: #004080;
}

.testimonial {
    background: rgba(255, 255, 255, 0.1);
    padding: 15px;
    border-radius: 10px;
    margin-bottom: 15px;
}

/* Formulario de reservas */
#reservas {
    padding: 50px;
    background: #0055aa;
}

form input, form button {
    width: 80%;
    padding: 10px;
    margin: 10px;
    border: none;
    border-radius: 5px;
}

button {
    background: #f39c12;
    color: white;
    font-size: 1.2em;
}
