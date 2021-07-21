<template>
    <div class="cardFoods">
            <div class="cardFoods__image">
                <img src="@/assets/img/image_browser.jpg" alt="Imagen del platillo seleccionado">

                <!-- Colocar información debajo de la imagen -->

                <!-- COMPONENT: SOCIAL MEDIA -->
                <div class="socialMedia">
                    <a href="#">
                        <img src="@/assets/img/Facebook.png" alt="Logo Facebook">
                    </a>
                    <a href="#">
                        <img src="@/assets/img/Instagram.png" alt="Logo Instagram">
                    </a>
                    <a href="#">
                        <img src="@/assets/img/Twitter.png" alt="Logo Twitter">
                    </a>
                </div>

            </div>
            <!-- <img src="./img/image browser.jpg" alt="Hamburgesa con papas" class="cardFoods__image"> -->
            <div class="cardFoods__description">
                <h2 class="cardFoods__title">aperitivos</h2>
                <div class="cardFoods__list">
    
                    <!-- COMPONENT: ITEM DESPLEGABLE -->
                    <div class="item">
                        <details open class="item__details">
                            <summary class="item__title">
                                Hamburgesa 1
                            </summary>
                            <div class="item__description">
                                <p class="item__ingredients">
                                    Contiene pan, carne y aderezos para acompañar.
                                </p>
                                <p class="item__price">
                                    $15 USD
                                </p>
                            </div>
                        </details>
                    </div>
                    <div class="item">
                        <details class="item__details">
                            <summary class="item__title">
                                Hamburgesa 2
                            </summary>
                            <div class="item__description">
                                <p class="item__ingredients">
                                    Contiene pan, carne y aderezos para acompañar.
                                </p>
                                <p class="item__price">
                                    $15 USD
                                </p>
                            </div>
                        </details>
                    </div>
                    <div class="item">
                        <details class="item__details">
                            <summary class="item__title">
                                Hot Dog 1
                            </summary>
                            <div class="item__description">
                                <p class="item__ingredients">
                                    Contiene pan, carne y aderezos para acompañar.
                                </p>
                                <p class="item__price">
                                    $15 USD
                                </p>
                            </div>
                        </details>
                    </div>
                    <div class="item">
                        <details class="item__details">
                            <summary class="item__title">
                                Hot Dog 2
                            </summary>
                            <div class="item__description">
                                <p class="item__ingredients">
                                    Contiene pan, carne y aderezos para acompañar.
                                </p>
                                <p class="item__price">
                                    $15 USD
                                </p>
                            </div>
                        </details>
                    </div>
                    <div class="item">
                        <details class="item__details">
                            <summary class="item__title">
                                Pizza 1
                            </summary>
                            <div class="item__description">
                                <p class="item__ingredients">
                                    Contiene pan, carne y aderezos para acompañar.
                                </p>
                                <p class="item__price">
                                    $15 USD
                                </p>
                            </div>
                        </details>
                    </div>
                    <div class="item">
                        <details class="item__details">
                            <summary class="item__title">
                                Pizza 2
                            </summary>
                            <div class="item__description">
                                <p class="item__ingredients">
                                    Contiene pan, carne y aderezos para acompañar.
                                </p>
                                <p class="item__price">
                                    $15 USD
                                </p>
                            </div>
                        </details>
                    </div>
                    <div class="item">
                        <details class="item__details">
                            <summary class="item__title">
                                Emparedado 1
                            </summary>
                            <div class="item__description">
                                <p class="item__ingredients">
                                    Contiene pan, carne y aderezos para acompañar.
                                </p>
                                <p class="item__price">
                                    $15 USD
                                </p>
                            </div>
                        </details>
                    </div>
                    <div class="item">
                        <details class="item__details">
                            <summary class="item__title">
                                Emparedado 2
                            </summary>
                            <div class="item__description">
                                <p class="item__ingredients">
                                    Contiene pan, carne y aderezos para acompañar.
                                </p>
                                <p class="item__price">
                                    $15 USD
                                </p>
                            </div>
                        </details>
                    </div>
    
                </div>
            </div>
        </div>
</template>
<script>
export default {
  name: 'PlatilloCard'
  
}
</script>