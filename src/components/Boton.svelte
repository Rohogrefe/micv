<script>
    let mensaje = "bienvenido a mi curriculum";

    function cambiarMensaje() {
        mensaje = "gracias por visitar mi curriculum";
    }
</script>

<div class="text-center mt-4">
    <button
        on:click={cambiarMensaje}
        class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded"
    >
        APRETA AQUI
    </button>
    <p class="mt-4 text-lg">{mensaje}</p>
</div>
