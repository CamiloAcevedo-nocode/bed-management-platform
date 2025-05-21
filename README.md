# bed-management-platform
Resumen Ejecutivo 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bed Management Platform - Presentación Ejecutiva</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom font for a professional look */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Light gray background */
            color: #334155; /* Darker text for readability */
        }
        /* Custom scrollbar for a cleaner look */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #e2e8f0;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb {
            background: #94a3b8;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #64748b;
        }
        /* Styles for the flowchart arrows */
        .flow-arrow {
            width: 2px;
            height: 30px;
            background-color: #60a5fa; /* blue-400 */
            position: relative;
            margin: 0 auto;
        }
        .flow-arrow::after {
            content: '';
            position: absolute;
            bottom: -8px;
            left: -7px;
            width: 0;
            height: 0;
            border-left: 8px solid transparent;
            border-right: 8px solid transparent;
            border-top: 8px solid #60a5fa; /* blue-400 */
        }
    </style>
</head>
<body class="antialiased">
    <div class="min-h-screen flex flex-col items-center py-10 px-4 sm:px-6 lg:px-8">
        <header class="w-full max-w-4xl bg-gradient-to-r from-blue-600 to-blue-800 text-white p-6 rounded-xl shadow-lg mb-10">
            <div class="flex flex-col sm:flex-row items-center justify-between">
                <div class="flex items-center space-x-4">
                    <img src="https://i.imgur.com/NDaaoul.png" alt="Logo Bed Management Platform" class="h-16 w-auto">
                    <h1 class="text-3xl sm:text-4xl font-extrabold tracking-tight">
                        Bed Management Platform
                    </h1>
                </div>
                <p class="mt-4 sm:mt-0 text-lg sm:text-xl font-semibold opacity-90">
                    Presentación Ejecutiva
                </p>
            </div>
        </header>

        <main class="w-full max-w-4xl bg-white p-8 rounded-xl shadow-lg">

            <section class="mb-10">
                <h2 class="text-3xl font-bold text-blue-700 mb-6 border-b-2 border-blue-200 pb-2">Resumen Ejecutivo</h2>
                <div class="grid md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-2xl font-semibold text-gray-800 mb-3 flex items-center">
                            <span class="mr-2 text-red-500">&#9888;</span> El Desafío Actual
                        </h3>
                        <ul class="list-disc list-inside space-y-2 text-lg text-gray-700">
                            <li>Coordinación de camas <strong>fragmentada y manual</strong>.</li>
                            <li><strong>Visibilidad parcial</strong> de la capacidad hospitalaria.</li>
                            <li>Gestión <strong>reactiva</strong> de altas y traslados.</li>
                            <li>Riesgo de <strong>pérdida de datos</strong> y malentendidos.</li>
                        </ul>
                    </div>
                    <div>
                        <h3 class="text-2xl font-semibold text-gray-800 mb-3 flex items-center">
                            <span class="mr-2 text-green-500">&#10003;</span> Nuestra Solución: BMP
                        </h3>
                        <p class="text-lg text-gray-700 leading-relaxed">
                            La <strong>Bed Management Platform (BMP)</strong> es una solución integral para optimizar la gestión de camas en el Hospital Clínico Félix Bulnes. Su objetivo es <strong>reducir estancias hospitalarias, tiempos de espera y traslados innecesarios</strong>, proporcionando un <strong>dashboard de control de mando integral en tiempo real</strong>.
                        </p>
                    </div>
                </div>
                <div class="mt-8 p-6 bg-blue-50 border-l-4 border-blue-400 rounded-lg shadow-sm">
                    <h3 class="text-2xl font-semibold text-blue-800 mb-3 flex items-center">
                        <span class="mr-2 text-blue-600">&#9733;</span> Recomendación Clave
                    </h3>
                    <p class="text-lg text-blue-700 leading-relaxed">
                        Aprobar la conformación de un <strong>equipo técnico interno especializado</strong> para el desarrollo de la plataforma. Esta opción garantiza <strong>control total, escalabilidad y sostenibilidad</strong> a largo plazo, asegurando la calidad y el cumplimiento normativo.
                    </p>
                </div>
            </section>

            <section class="mb-10">
                <h2 class="text-3xl font-bold text-blue-700 mb-6 border-b-2 border-blue-200 pb-2">Beneficios Estratégicos de la BMP</h2>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <div class="bg-gray-50 p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2 flex items-center">
                            <span class="mr-2 text-blue-500">&#x1F504;</span> Eficiencia Operativa
                        </h3>
                        <p class="text-gray-700">Centraliza la coordinación, digitaliza procesos y reduce la dependencia de comunicaciones manuales.</p>
                    </div>
                    <div class="bg-gray-50 p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2 flex items-center">
                            <span class="mr-2 text-green-500">&#x1F4C8;</span> Optimización de Recursos
                        </h3>
                        <p class="text-gray-700">Mejora la tasa de ocupación de camas y la eficiencia de traslados internos, liberando recursos.</p>
                    </div>
                    <div class="bg-gray-50 p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2 flex items-center">
                            <span class="mr-2 text-purple-500">&#x1F50D;</span> Visibilidad en Tiempo Real
                        </h3>
                        <p class="text-gray-700">Dashboards personalizables con estado de camas, ocupación y disponibilidad para decisiones ágiles.</p>
                    </div>
                    <div class="bg-gray-50 p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2 flex items-center">
                            <span class="mr-2 text-orange-500">&#x1F4C5;</span> Planificación Proactiva
                        </h3>
                        <p class="text-gray-700">Anticipa fechas de alta y reserva camas, reduciendo la congestión y mejorando el flujo de pacientes.</p>
                    </div>
                    <div class="bg-gray-50 p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2 flex items-center">
                            <span class="mr-2 text-teal-500">&#x1F512;</span> Seguridad y Trazabilidad
                        </h3>
                        <p class="text-gray-700">Registros inmutables de acciones, cifrado de datos y cumplimiento normativo (Ley 19.628, 20.584).</p>
                    </div>
                    <div class="bg-gray-50 p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2 flex items-center">
                            <span class="mr-2 text-pink-500">&#x1F4CA;</span> Reducción de Tiempos
                        </h3>
                        <p class="text-gray-700">Meta de reducción del 30% en tiempo de asignación de cama y 50% en tiempo de traslados internos.</p>
                    </div>
                </div>
            </section>

            <section class="mb-10">
                <h2 class="text-3xl font-bold text-blue-700 mb-6 border-b-2 border-blue-200 pb-2">El Flujo de Trabajo de la BMP (Diagrama Visual)</h2>
                <div class="flex flex-col items-center space-y-6">

                    <div class="w-full max-w-md bg-blue-50 p-6 rounded-lg shadow-md text-center border-2 border-blue-200">
                        <div class="flex items-center justify-center mb-3">
                            <div class="w-12 h-12 bg-blue-600 text-white rounded-full flex items-center justify-center text-xl font-bold mr-3">1</div>
                            <h3 class="text-xl font-semibold text-blue-800">Ingreso y Decisión Inicial en Urgencias</h3>
                        </div>
                        <p class="text-gray-700 text-base">
                            Captura de datos del paciente, verificación de disponibilidad de camas y decisión de hospitalización. Asignación provisional de servicio.
                        </p>
                        <p class="text-sm text-blue-700 mt-2">
                            <strong>Control de Mando:</strong> Datos en tiempo real sobre demanda y estado en urgencias.
                        </p>
                    </div>

                    <div class="flow-arrow"></div>

                    <div class="w-full max-w-md bg-blue-50 p-6 rounded-lg shadow-md text-center border-2 border-blue-200">
                        <div class="flex items-center justify-center mb-3">
                            <div class="w-12 h-12 bg-blue-600 text-white rounded-full flex items-center justify-center text-xl font-bold mr-3">2</div>
                            <h3 class="text-xl font-semibold text-blue-800">Reunión de Camas (Coordinación UGP)</h3>
                        </div>
                        <p class="text-gray-700 text-base">
                            Consulta de disponibilidad actualizada, propuesta de asignaciones por el sistema y validación de coordinadores.
                        </p>
                        <p class="text-sm text-blue-700 mt-2">
                            <strong>Control de Mando:</strong> Centraliza la decisión de asignación, optimizando la ocupación.
                        </p>
                    </div>

                    <div class="flow-arrow"></div>

                    <div class="w-full max-w-md bg-blue-50 p-6 rounded-lg shadow-md text-center border-2 border-blue-200">
                        <div class="flex items-center justify-center mb-3">
                            <div class="w-12 h-12 bg-blue-600 text-white rounded-full flex items-center justify-center text-xl font-bold mr-3">3</div>
                            <h3 class="text-xl font-semibold text-blue-800">Seguimiento del Paciente Hospitalizado</h3>
                        </div>
                        <p class="text-gray-700 text-base">
                            Registro de avances clínicos, alertas tempranas, actualización del plan de egreso y notificación del estado de la cama.
                        </p>
                        <p class="text-sm text-blue-700 mt-2">
                            <strong>Control de Mando:</strong> Planificación proactiva de altas, reduce congestión y asegura trazabilidad.
                        </p>
                    </div>

                </div>
            </section>

            <section class="mb-10 p-6 bg-blue-100 rounded-xl shadow-inner">
                <h2 class="text-3xl font-bold text-blue-700 mb-6 border-b-2 border-blue-300 pb-2 flex items-center">
                    <span class="mr-3 text-blue-600">&#x1F4BB;</span> Dashboard de Control de Mando Integral
                </h2>
                <p class="text-lg text-gray-800 mb-4 leading-relaxed">
                    La BMP centraliza la información crucial en un <strong>dashboard intuitivo y visual</strong>, permitiendo a la Alta Dirección y equipos clave tener un panorama global en tiempo real:
                </p>
                <ul class="list-disc list-inside space-y-2 text-lg text-gray-700">
                    <li><strong>Visibilidad total:</strong> Ocupación de camas, camas listas para limpieza, tiempos de bloqueo.</li>
                    <li><strong>KPIs Clave:</strong> Monitoreo de tiempo de asignación de cama, cumplimiento de plazos de alta, eficiencia de traslados internos, tasa de ocupación óptima y frecuencia de incidencias.</li>
                    <li><strong>Toma de Decisiones Ágil:</strong> Facilita la priorización y reasignación de recursos de manera oportuna.</li>
                </ul>
                <p class="text-lg text-gray-800 mt-4 leading-relaxed">
                    Este control visual transforma un modelo reactivo en un flujo de trabajo <strong>estandarizado, eficiente y predecible.</strong>
                </p>
            </section>

            <section>
                <h2 class="text-3xl font-bold text-blue-700 mb-6 border-b-2 border-blue-200 pb-2">Decisión Solicitada a la Dirección</h2>
                <p class="text-lg text-gray-700 mb-6 leading-relaxed">
                    Para avanzar con la implementación estratégica de la Bed Management Platform, solicitamos su aprobación en los siguientes puntos clave:
                </p>
                <ul class="list-disc list-inside space-y-3 text-lg text-gray-700">
                    <li class="font-semibold text-gray-800">
                        <span class="text-blue-600">&#x2713;</span> <strong>Aprobación del Modelo de Gobernanza:</strong> Autorizar la creación de un equipo de desarrollo dedicado (interno) y establecer un comité de gestión.
                    </li>
                    <li class="font-semibold text-gray-800">
                        <span class="text-blue-600">&#x2713;</span> <strong>Asignación de Recursos y Liberación de Tiempos:</strong> Liberar al líder de proyecto y roles clave para asegurar dedicación exclusiva o parcial.
                    </li>
                    <li class="font-semibold text-gray-800">
                        <span class="text-blue-600">&#x2713;</span> <strong>Validación del Presupuesto por Hitos:</strong> Aprobar el detalle de partidas con desembolsos condicionados a la consecución de hitos.
                    </li>
                    <li class="font-semibold text-gray-800">
                        <span class="text-blue-600">&#x2713;</span> <strong>Establecimiento de Mecanismo de Seguimiento:</strong> Implementar un sistema de monitoreo basado en KPIs con reportes semanales.
                    </li>
                    <li class="font-semibold text-gray-800">
                        <span class="text-blue-600">&#x2713;</span> <strong>Ratificación de Plan de Riesgos y Resguardos Legales:</strong> Respaldar el plan de mitigación de riesgos y cumplimiento normativo.
                    </li>
                </ul>
            </section>

        </main>

        <footer class="w-full max-w-4xl text-center mt-10 text-gray-500 text-sm">
            <p>&copy; 2025 Hospital Clínico Félix Bulnes. Todos los derechos reservados.</p>
        </footer>
    </div>
</body>
</html>
