<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curso de Base de Datos | Arariyo Joel Albert</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background: #f5f7fb;
            color: #1e293b;
            padding: 2rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 24px;
            box-shadow: 0 20px 35px -10px rgba(0,0,0,0.1);
            overflow: hidden;
            transition: all 0.3s ease;
        }

        /* Header con gradiente */
        .header {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            color: white;
            padding: 3rem 2rem;
            text-align: center;
        }

        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            letter-spacing: -0.5px;
        }

        .header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        .badge {
            display: inline-block;
            background: #3b82f6;
            padding: 0.3rem 1rem;
            border-radius: 40px;
            font-size: 0.8rem;
            font-weight: 500;
            margin-top: 1rem;
        }

        /* Info del estudiante */
        .student-info {
            background: #f8fafc;
            padding: 1.5rem 2rem;
            border-bottom: 1px solid #e2e8f0;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
            gap: 1rem;
        }

        .student-details {
            display: flex;
            gap: 1.5rem;
            flex-wrap: wrap;
        }

        .student-details span {
            font-weight: 500;
            color: #0f172a;
        }

        .student-details i {
            margin-right: 0.3rem;
            color: #3b82f6;
        }

        .repo-badge {
            background: #e2e8f0;
            padding: 0.4rem 1rem;
            border-radius: 30px;
            font-size: 0.8rem;
            font-family: monospace;
        }

        /* Contenido principal */
        .content {
            padding: 2rem;
        }

        .section {
            margin-bottom: 2.5rem;
        }

        .section h2 {
            font-size: 1.8rem;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 3px solid #3b82f6;
            display: inline-block;
        }

        .section p {
            margin: 1rem 0;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin: 1.5rem 0;
        }

        .card {
            background: #f8fafc;
            border-radius: 16px;
            padding: 1.5rem;
            border: 1px solid #e2e8f0;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.05);
        }

        .card h3 {
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
            color: #0f172a;
        }

        .card p {
            color: #475569;
            font-size: 0.95rem;
        }

        .topic-list {
            list-style: none;
            padding: 0;
        }

        .topic-list li {
            background: #f1f5f9;
            margin: 0.5rem 0;
            padding: 0.5rem 1rem;
            border-radius: 12px;
            font-family: monospace;
            font-size: 0.9rem;
            border-left: 4px solid #3b82f6;
        }

        .resources {
            background: #f1f5f9;
            padding: 1.2rem;
            border-radius: 16px;
        }

        .resources a {
            color: #2563eb;
            text-decoration: none;
            font-weight: 500;
        }

        .resources a:hover {
            text-decoration: underline;
        }

        footer {
            background: #f1f5f9;
            text-align: center;
            padding: 1.5rem;
            font-size: 0.85rem;
            color: #475569;
            border-top: 1px solid #e2e8f0;
        }

        @media (max-width: 768px) {
            body {
                padding: 1rem;
            }
            .header h1 {
                font-size: 1.8rem;
            }
            .student-info {
                flex-direction: column;
                align-items: flex-start;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>📚 Curso de Base de Datos</h1>
            <p>Fundamentos, modelado y administración de datos</p>
            <div class="badge">Universidad Autónoma Gabriel René Moreno</div>
        </div>

        <div class="student-info">
            <div class="student-details">
                <span><i>👨‍🎓</i> Arariyo Joel Albert</span>
                <span><i>📖</i> Ingeniería Informática</span>
                <span><i>🏛️</i> UAGRM - Bolivia</span>
            </div>
            <div class="repo-badge">
                📁 Repositorio del curso · 2026
            </div>
        </div>

        <div class="content">
            <!-- Descripción -->
            <div class="section">
                <h2>📖 Sobre el curso</h2>
                <p>Este repositorio contiene todo el material, ejercicios y proyectos desarrollados durante el curso de <strong>Base de Datos</strong> de la carrera de Ingeniería Informática en la Universidad Autónoma Gabriel René Moreno (UAGRM). El objetivo es comprender los principios de diseño, implementación y gestión de bases de datos relacionales y no relacionales, aplicando buenas prácticas y tecnologías actuales.</p>
                <p>El curso combina teoría con práctica intensiva, usando herramientas como <strong>MySQL, PostgreSQL, MongoDB</strong> y modelado con <strong>diagramas ER</strong>.</p>
            </div>

            <!-- Temario -->
            <div class="section">
                <h2>🗂️ Temario principal</h2>
                <div class="grid">
                    <div class="card">
                        <h3>🔹 Unidad 1</h3>
                        <p>Introducción a las bases de datos. Modelo entidad-relación. Diagramas ER y transformación a tablas.</p>
                    </div>
                    <div class="card">
                        <h3>🔹 Unidad 2</h3>
                        <p>Álgebra relacional. SQL básico: consultas, joins, subconsultas, funciones agregadas.</p>
                    </div>
                    <div class="card">
                        <h3>🔹 Unidad 3</h3>
                        <p>Normalización (1FN, 2FN, 3FN, BCNF). Diseño de esquemas optimizados.</p>
                    </div>
                    <div class="card">
                        <h3>🔹 Unidad 4</h3>
                        <p>Transacciones, concurrencia, backups y seguridad. Procedimientos almacenados y triggers.</p>
                    </div>
                    <div class="card">
                        <h3>🔹 Unidad 5</h3>
                        <p>NoSQL: MongoDB, Cassandra. Casos de uso y comparación con SQL.</p>
                    </div>
                    <div class="card">
                        <h3>🔹 Proyecto final</h3>
                        <p>Aplicación completa con base de datos relacional + API REST. Documentación y despliegue.</p>
                    </div>
                </div>
            </div>

            <!-- Contenido del repo -->
            <div class="section">
                <h2>📂 Estructura del repositorio</h2>
                <ul class="topic-list">
                    <li><code>/apuntes</code> – Resúmenes teóricos y presentaciones</li>
                    <li><code>/ejercicios-sql</code> – Scripts con ejercicios resueltos de SQL</li>
                    <li><code>/proyectos</code> – Código fuente de los proyectos integradores</li>
                    <li><code>/recursos</code> – Libros, guías y enlaces útiles</li>
                    <li><code>/examenes</code> – Modelos de exámenes y soluciones</li>
                </ul>
            </div>

            <!-- Recursos recomendados -->
            <div class="section">
                <h2>📚 Recursos recomendados</h2>
                <div class="resources">
                    <ul style="margin-left: 1.5rem;">
                        <li>📘 <a href="#">"Database System Concepts" – Silberschatz, Korth, Sudarshan</a></li>
                        <li>📗 <a href="#">"SQL Performance Explained" – Markus Winand</a></li>
                        <li>🎓 <a href="#">PostgreSQL官方文档 (versión 16+)</a></li>
                        <li>💻 <a href="#">MySQL Workbench – Modelado y consultas</a></li>
                        <li>🐳 <a href="#">Docker – Para levantar bases de datos rápidamente</a></li>
                    </ul>
                </div>
            </div>

            <!-- Contacto / Contribución -->
            <div class="section">
                <h2>🤝 Contribuciones</h2>
                <p>Este repositorio es de uso educativo. Si eres estudiante del curso o deseas sugerir mejoras, puedes hacer un <strong>fork</strong> y enviar un <strong>pull request</strong> o abrir un <strong>issue</strong>.</p>
                <p>📧 Contacto: <a href="mailto:arariyo.joel@uagrm.edu.bo">arariyo.joel@uagrm.edu.bo</a> (correo institucional)</p>
            </div>
        </div>

        <footer>
            <p>Universidad Autónoma Gabriel René Moreno · Facultad de Ciencias Exactas y Tecnología · Ingeniería Informática</p>
            <p>© 2026 Arariyo Joel Albert – Material para fines académicos</p>
        </footer>
    </div>
</body>
</html>
