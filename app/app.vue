<template>
  <div class="min-h-screen bg-gray-50 font-sans text-gray-800">
    <!-- BARRA DE NAVEGACIÓN -->
    <nav class="bg-white shadow-sm p-4 sticky top-0 z-50">
      <div class="max-w-6xl mx-auto flex justify-between items-center">
        <h1 class="text-2xl font-bold text-green-600 flex items-center gap-2">
          <span>🍎</span> Frutería Los Cazurros
        </h1>
        <a
          href="https://wa.me/34600000000"
          target="_blank"
          class="hidden md:flex bg-green-500 hover:bg-green-600 text-white px-5 py-2.5 rounded-full font-semibold transition-colors shadow flex items-center gap-2"
        >
          <span>Hacer pedido</span>
          <span>📱</span>
        </a>
      </div>
    </nav>

    <!-- CABECERA (HERO SECTION) -->
    <!-- La imagen de fondo es de Unsplash (libre de derechos). Para cambiarla, solo cambia la URL -->
    <header
      class="relative bg-green-800 text-white text-center py-32 px-4"
      style="
        background-image:
          linear-gradient(rgba(21, 128, 61, 0.8), rgba(21, 128, 61, 0.95)),
          url(&quot;https://images.unsplash.com/photo-1542838132-92c53300491e?q=80&w=1974&auto=format&fit=crop&quot;);
        background-size: cover;
        background-position: center;
      "
    >
      <div class="max-w-3xl mx-auto">
        <h2 class="text-5xl md:text-6xl font-extrabold mb-6 tracking-tight">
          Del campo a tu mesa en León
        </h2>
        <p class="text-xl md:text-2xl mb-10 text-green-50 font-light">
          Fruta y verdura fresca de temporada, directamente de proveedores
          locales. Pídelo por WhatsApp y te lo preparamos.
        </p>
        <a
          href="https://wa.me/34600000000"
          class="inline-block bg-white text-green-700 font-bold text-lg px-8 py-4 rounded-full shadow-xl hover:bg-green-50 transition-transform hover:scale-105"
        >
          Escríbenos por WhatsApp
        </a>
      </div>
    </header>

    <!-- SECCIÓN: NUESTROS SERVICIOS -->
    <section class="py-20 px-4 max-w-6xl mx-auto">
      <h3 class="text-3xl font-bold text-center mb-16 text-gray-800">
        Lo que nos hace diferentes
      </h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Bloque 1 -->
        <div
          class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 text-center hover:shadow-md transition-shadow"
        >
          <div class="text-5xl mb-6">🍅</div>
          <h4 class="text-xl font-bold mb-3">Producto Local</h4>
          <p class="text-gray-600">
            Apoyamos a los agricultores de la provincia para garantizar que el
            producto llegue fresco cada mañana.
          </p>
        </div>

        <!-- Bloque 2 -->
        <div
          class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 text-center hover:shadow-md transition-shadow"
        >
          <div class="text-5xl mb-6">🧺</div>
          <h4 class="text-xl font-bold mb-3">Cestas a Medida</h4>
          <p class="text-gray-600">
            Preparamos cestas personalizadas de frutas para regalos,
            celebraciones o para empresas.
          </p>
        </div>

        <!-- Bloque 3 -->
        <div
          class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 text-center hover:shadow-md transition-shadow"
        >
          <div class="text-5xl mb-6">🛵</div>
          <h4 class="text-xl font-bold mb-3">Reparto a Domicilio</h4>
          <p class="text-gray-600">
            ¿No tienes tiempo de venir? Haz tu pedido por mensaje y te lo
            llevamos gratis en el mismo día.
          </p>
        </div>
      </div>
    </section>

    <!-- SECCIÓN: UBICACIÓN Y HORARIOS -->
    <section class="bg-white py-20 px-4 border-t border-gray-100">
      <div
        class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-12 items-center"
      >
        <!-- Textos y Horario -->
        <div>
          <h3 class="text-3xl font-bold mb-6 text-gray-800">
            Ven a visitarnos
          </h3>
          <p class="text-lg text-gray-600 mb-8 flex items-center gap-2">
            <span class="text-2xl">📍</span>
            <span
              ><strong>Dirección:</strong> Calle Falsa 123, Barrio Húmedo,
              León.</span
            >
          </p>

          <div class="bg-green-50 p-8 rounded-2xl border border-green-100">
            <h4
              class="font-bold text-green-800 mb-4 text-lg flex items-center gap-2"
            >
              <span>🕒</span> Horario de apertura
            </h4>
            <ul class="text-green-700 space-y-3">
              <li class="flex justify-between">
                <strong>Lunes - Viernes:</strong>
                <span>09:00 - 14:00 | 17:00 - 20:30</span>
              </li>
              <li
                class="flex justify-between border-t border-green-200/50 pt-3"
              >
                <strong>Sábados:</strong> <span>09:00 - 14:30</span>
              </li>
              <li
                class="flex justify-between border-t border-green-200/50 pt-3"
              >
                <strong>Domingos:</strong> <span>Cerrado</span>
              </li>
            </ul>
          </div>
        </div>

        <!-- Mapa de Ejemplo (Aquí se pega el iframe de Google Maps real) -->
        <div
          class="h-96 bg-gray-200 rounded-2xl overflow-hidden shadow-inner flex items-center justify-center relative border border-gray-200"
        >
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d8147.277750226775!2d-5.575561735182648!3d42.5980651481767!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd379a9b863a0fab%3A0x13727554f4d5e06a!2sCatedral%20de%20Le%C3%B3n!5e1!3m2!1ses!2ses!4v1791304589547!5m2!1ses!2ses"
            width="100%"
            height="100%"
            style="border: 0"
            allowfullscreen
            loading="lazy"
            referrerpolicy="strict-origin-when-cross-origin"
          ></iframe>
          <div
            class="z-10 text-center bg-white/90 p-6 rounded-xl shadow-sm backdrop-blur-sm mx-4"
          >
            <p class="font-bold text-gray-800 mb-2">
              Aquí va el mapa interactivo
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- PIE DE PÁGINA -->
    <footer class="bg-gray-900 text-gray-400 py-10 text-center">
      <p>&copy; 2026 Frutería Los Cazurros. Todos los derechos reservados.</p>
      <p class="text-sm mt-3">Diseño web creado en León por David Bances.</p>
    </footer>

    <!-- BOTÓN FLOTANTE WHATSAPP -->
    <a
      href="https://wa.me/34600000000"
      target="_blank"
      aria-label="Chat en WhatsApp"
      class="fixed bottom-6 right-6 bg-[#25D366] text-white p-4 rounded-full shadow-2xl hover:bg-[#1ebd5b] hover:-translate-y-1 transition-all flex items-center justify-center z-50"
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="h-9 w-9"
        fill="currentColor"
        viewBox="0 0 24 24"
      >
        <path
          d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.347-.272.297-1.04 1.016-1.04 2.479 0 1.463 1.065 2.876 1.213 3.074.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"
        />
      </svg>
    </a>
  </div>
</template>
