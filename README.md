<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iglesia Evangélica Unión Pentecostal - Chos Malal</title>
    <style>
        :root {
            --navy: #001f3f;
            --white: #ffffff;
            --light-blue: #7FDBFF;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            color: var(--navy);
            line-height: 1.6;
        }
        
        header {
            background-color: var(--navy);
            color: var(--white);
            padding: 1rem 0;
            text-align: center;
        }
        
        nav {
            background-color: var(--navy);
            padding: 0.5rem 0;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 0;
            margin: 0;
        }
        
        nav ul li {
            margin: 0 15px;
        }
        
        nav ul li a {
            color: var(--white);
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        
        nav ul li a:hover {
            background-color: var(--light-blue);
            color: var(--navy);
        }
        
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px 0;
        }
        
        .hero {
            background-image: linear-gradient(rgba(0, 31, 63, 0.7), rgba(0, 31, 63, 0.7)), url('iglesia.jpg');
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            text-align: center;
        }
        
        .section {
            padding: 30px 0;
            border-bottom: 1px solid #eee;
        }
        
        .section-title {
            color: var(--navy);
            text-align: center;
            margin-bottom: 20px;
        }
        
        .groups {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        
        .group-card {
            flex: 1;
            min-width: 300px;
            margin: 10px;
            padding: 20px;
            background-color: var(--white);
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .schedule table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        
        .schedule table, .schedule th, .schedule td {
            border: 1px solid #ddd;
        }
        
        .schedule th {
            background-color: var(--navy);
            color: var(--white);
            padding: 10px;
        }
        
        .schedule td {
            padding: 8px;
            text-align: center;
        }
        
        footer {
            background-color: var(--navy);
            color: var(--white);
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
        }
        
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav ul li {
                margin: 5px 0;
            }
            
            .groups {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Iglesia Evangélica Unión Pentecostal</h1>
        <p>Chos Malal - Compartiendo el amor de Cristo</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#nosotros">Nosotros</a></li>
            <li><a href="#grupos">Grupos</a></li>
            <li><a href="#horarios">Horarios</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
    
    <section class="hero" id="inicio">
        <div>
            <h2>Bienvenidos a nuestra comunidad</h2>
            <p>Un lugar para crecer en fe y compañerismo</p>
        </div>
    </section>
    
    <div class="container">
        <section class="section" id="nosotros">
            <h2 class="section-title">Sobre Nosotros</h2>
            <p>La Iglesia Evangélica Unión Pentecostal de Chos Malal es una comunidad de fe comprometida con la enseñanza bíblica, la adoración a Dios y el servicio a nuestro prójimo. Nuestro objetivo es ser luz en nuestra comunidad y compartir el mensaje de salvación en Cristo Jesús.</p>
        </section>
        
        <section class="section" id="grupos">
            <h2 class="section-title">Nuestros Grupos</h2>
            <div class="groups">
                <div class="group-card">
                    <h3>Juventud</h3>
                    <p>Grupo para jóvenes de 13 a 30 años donde compartimos estudios bíblicos relevantes, actividades recreativas y oportunidades de servicio.</p>
                    <p><strong>Reuniones:</strong> Viernes 19:00 hs</p>
                </div>
                
                <div class="group-card">
                    <h3>Ancianos</h3>
                    <p>Espacio dedicado a nuestros adultos mayores con estudios bíblicos, oración y compañerismo adaptado a sus necesidades.</p>
                    <p><strong>Reuniones:</strong> Martes 16:00 hs</p>
                </div>
                
                <div class="group-card">
                    <h3>Niños</h3>
                    <p>Escuela bíblica infantil donde los más pequeños aprenden de Dios a través de historias, canciones y actividades creativas.</p>
                    <p><strong>Reuniones:</strong> Domingos 10:00 hs</p>
                </div>
            </div>
        </section>
        
        <section class="section schedule" id="horarios">
            <h2 class="section-title">Horarios de Reuniones</h2>
            <table>
                <tr>
                    <th>Día</th>
                    <th>Actividad</th>
                    <th>Hora</th>
                    <th>Lugar</th>
                </tr>
                <tr>
                    <td>Domingo</td>
                    <td>Culto Principal</td>
                    <td>10:00 hs</td>
                    <td>Templo Principal</td>
                </tr>
                <tr>
                    <td>Martes</td>
                    <td>Reunión de Ancianos</td>
                    <td>16:00 hs</td>
                    <td>Salón Lateral</td>
                </tr>
                <tr>
                    <td>Miércoles</td>
                    <td>Estudio Bíblico</td>
                    <td>19:30 hs</td>
                    <td>Templo Principal</td>
                </tr>
                <tr>
                    <td>Viernes</td>
                    <td>Reunión de Jóvenes</td>
                    <td>19:00 hs</td>
                    <td>Salón de Jóvenes</td>
                </tr>
                <tr>
                    <td>Sábado</td>
                    <td>Oración y Alabanza</td>
                    <td>18:00 hs</td>
                    <td>Templo Principal</td>
                </tr>
            </table>
            
            <h3 style="margin-top: 30px;">Próximos Eventos</h3>
            <ul>
                <li><strong>Retiro Juvenil:</strong> 15-17 de Mayo - Campo de Retiros "Monte de los Olivos"</li>
                <li><strong>Conferencia Bíblica:</strong> 25 de Mayo - 19:00 hs - Tema: "Viviendo en el Espíritu"</li>
                <li><strong>Campamento Infantil:</strong> 10-12 de Junio - Inscripciones abiertas</li>
            </ul>
        </section>
        
        <section class="section" id="contacto">
            <h2 class="section-title">Contacto</h2>
            <p><strong>Dirección:</strong> Calle Principal 123, Chos Malal</p>
            <p><strong>Teléfono:</strong> (02948) 42-1234</p>
            <p><strong>Email:</strong> info@iglesiaunionpentecostal.com</p>
            <p><strong>Redes Sociales:</strong> Facebook: /IglesiaUnionPentecostalChosMalal</p>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2023 Iglesia Evangélica Unión Pentecostal - Chos Malal. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
