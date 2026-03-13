---
layout: "simple"
---
<style>
    html { background-color: #050505; }
    body { visibility: hidden; opacity: 0; }
</style>
<script>
    window.addEventListener('load', function() {
        document.body.style.visibility = "visible";
        document.body.style.opacity = "1";
    });
</script>

<link rel="stylesheet" href="{{ "css/custom.css" | relURL }}">

<main class="home-wrapper">
    <section class="hero-nwn">
        <div class="hero-content">
            <h1 class="nwn-font gold-text">Forjando historias, ideas y recursos en el NWN desde su salida en 2002</h1>
            <p class="flavor-text">
                Desde 2002 he sido jugador, dungeon master, administrador y creador en general en muchos servidores de habla hispana
				como Arthena, Lágrimas de Arthena, Tierra de Héroes, Neverun, Aldor hasta la creación de Tierras Desoladas, mi gran proyecto.
				.
            </p>
            <div class="hero-actions">
                <a href="/posts" class="gold-button-action">Explorar Crónicas</a>
                <a href="/utils" class="gold-button-action secondary">Cámara de Utilidades</a>
            </div>
        </div>
    </section>

    <hr class="separator-nwn">

    <section class="home-features">
        <div class="feature-card">
            <i class="fas fa-quill-feather"></i>
            <h3>Crónicas</h3>
            <p>Relatos de aventuras, diarios de desarrollo y lore profundo de nuestros mundos persistentes.</p>
        </div>
        <div class="feature-card">
            <i class="fas fa-hammer"></i>
            <h3>Herramientas</h3>
            <p>Utilidades personalizadas para portrait makers, generadores de nombres y recursos para DMs.</p>
        </div>
        <div class="feature-card">
            <i class="fas fa-fortress-awesome"></i>
            <h3>Comunidad</h3>
            <p>Un legado que perdura. Únete a nuestro Discord para compartir tu pasión por el Aurora Engine.</p>
        </div>
    </section>
</main>