<template>
  <section class="contact-page">

    <SideBar />

    <div class="contact">
      <div class="contact__container">

        <h1 class="contact__container__title">Fale conosco</h1>

        <div class="contact__container__options">

          <div class="--item" @click="isShow = true">
            <svg class="contact-icon" enable-background="new 0 0 512 512" version="1.1" viewBox="0 0 512 512" xml:space="preserve" xmlns="http://www.w3.org/2000/svg">
            			<path d="m486.4 59.733h-460.8c-14.138 0-25.6 11.461-25.6 25.6v341.33c0 14.138 11.461 25.6 25.6 25.6h460.8c14.138 0 25.6-11.461 25.6-25.6v-341.33c0-14.138-11.461-25.6-25.6-25.6zm8.533 366.93c0 4.713-3.82 8.533-8.533 8.533h-460.8c-4.713 0-8.533-3.82-8.533-8.533v-341.33c0-4.713 3.82-8.533 8.533-8.533h460.8c4.713 0 8.533 3.82 8.533 8.533v341.33z"/>
            			<path d="m470.08 93.898c-2.255-0.197-4.496 0.51-6.229 1.966l-196.86 165.38c-6.349 5.337-15.616 5.337-21.965 0l-196.86-165.38c-2.335-1.96-5.539-2.526-8.404-1.484s-4.957 3.534-5.487 6.537 0.582 6.06 2.917 8.02l196.86 165.37c12.688 10.683 31.224 10.683 43.913 0l196.86-165.37c1.734-1.455 2.818-3.539 3.015-5.794s-0.51-4.496-1.966-6.229c-1.454-1.735-3.538-2.819-5.793-3.016z"/>
            			<path d="m164.12 273.13c-3.021-0.674-6.169 0.34-8.229 2.65l-119.47 128c-2.162 2.214-2.956 5.426-2.074 8.392 0.882 2.967 3.301 5.223 6.321 5.897 3.021 0.674 6.169-0.34 8.229-2.65l119.47-128c2.162-2.214 2.956-5.426 2.074-8.392s-3.3-5.223-6.321-5.897z"/>
            			<path d="m356.1 275.78c-2.059-2.31-5.208-3.324-8.229-2.65s-5.439 2.931-6.321 5.897c-0.882 2.967-0.088 6.178 2.074 8.392l119.47 128c3.24 3.318 8.536 3.442 11.927 0.278s3.635-8.456 0.549-11.918l-119.47-128z"/>
            </svg>
            <h3 class="--item__text">Enviar um e-mail</h3>
          </div>

          <div class="--item" @click="isShow = true">
            <svg class="contact-icon" enable-background="new 0 0 512 512" version="1.1" viewBox="0 0 512 512" xml:space="preserve" xmlns="http://www.w3.org/2000/svg">
              <path d="m502 246h-28.038c-5.522 0-9.999 4.477-9.999 9.999 0 5.523 4.478 9.999 9.999 9.999h28.038c5.522 0 9.999-4.477 9.999-9.999s-4.477-9.999-9.999-9.999z"/>
              <path d="m500.98 192.61c-2.762-4.783-8.875-6.421-13.659-3.66l-18.359 10.599c-4.783 2.761-6.422 8.876-3.66 13.659 1.852 3.209 5.213 5.002 8.669 5.002 1.696 0 3.416-0.432 4.99-1.341l18.359-10.6c4.783-2.761 6.422-8.876 3.66-13.659z"/>
              <path d="m497.32 305.73l-18.359-10.6c-4.784-2.762-10.897-1.123-13.659 3.66s-1.123 10.898 3.66 13.659l18.359 10.6c1.575 0.909 3.294 1.341 4.99 1.341 3.456 0 6.816-1.793 8.669-5.001 2.762-4.783 1.124-10.898-3.66-13.659z"/>
              <path d="m424.33 118.01c-9.869-43.064-23.233-63.997-40.857-63.997-3.391 0-6.621 0.783-9.702 2.341l-367.64 154.42c-3.713 1.558-6.128 5.191-6.128 9.218v71.994c0 4.026 2.415 7.659 6.127 9.219l53.931 22.656c0.032 0.014 0.065 0.027 0.097 0.041l25.839 10.853v62.735c0 15.714 12.784 28.498 28.498 28.498h90.993c15.714 0 28.498-12.784 28.498-28.498v-0.567l139.8 58.728c3.077 1.553 6.303 2.334 9.688 2.334 17.624 0 30.988-20.933 40.857-63.997 8.473-36.972 13.139-85.976 13.139-137.99-1e-3 -52.01-4.667-101.01-13.14-137.99zm-210.34 279.48c0 4.687-3.813 8.499-8.499 8.499h-90.993c-4.687 0-8.499-3.813-8.499-8.499v-54.334l107.99 45.366v8.968zm-139.99-89.467v-52.181c0-5.523-4.478-9.999-9.999-9.999-5.522 0-9.999 4.477-9.999 9.999v43.78l-33.997-14.282v-58.703l331.62-139.29c-3.28 8.548-6.276 18.756-9.005 30.663-0.31 1.35-0.612 2.722-0.912 4.104l-113.38 42.673c-5.169 1.945-7.781 7.712-5.837 12.88 1.509 4.009 5.316 6.479 9.36 6.479 1.17 0 2.36-0.208 3.521-0.644l102.05-38.411c-5.165 32.412-7.946 70.76-7.946 110.9 0 52.011 4.666 101.02 13.139 137.99 2.729 11.906 5.727 22.112 9.005 30.661l-277.62-116.62zm276.29-88.85c17.68 3.011 31.185 18.431 31.185 36.955 0 18.521-13.5 33.937-31.174 36.953-0.545-12.075-0.824-24.48-0.824-37.08 0-12.512 0.276-24.832 0.813-36.828zm54.547 170.35c-9.13 39.841-19.328 48.465-21.363 48.465-0.083 0-0.183-0.02-0.292-0.05-0.162-0.079-0.32-0.164-0.488-0.235l-0.238-0.1c-3.356-2.023-12.266-12.827-20.345-48.081-4.974-21.704-8.58-47.838-10.638-76.402 28.173-3.687 50-27.83 50-56.991 0-29.168-21.837-53.315-50.018-56.994 2.054-28.663 5.668-54.886 10.656-76.654 8.074-35.233 16.98-46.046 20.34-48.077l0.883-0.371c0.049-7e-3 0.099-0.017 0.141-0.017 2.035 0 12.233 8.624 21.363 48.465 8.146 35.55 12.634 82.969 12.634 133.52s-4.487 97.97-12.635 133.52z"/>
              <path d="m199.5 186.34c-1.938-5.171-7.697-7.793-12.871-5.858l-0.229 0.086c-5.172 1.937-7.794 7.699-5.858 12.871 1.504 4.016 5.316 6.495 9.366 6.495 1.165 0 2.35-0.206 3.505-0.638l0.229-0.086c5.172-1.936 7.795-7.699 5.858-12.87z"/>
            </svg>
            <h3 class="--item__text">Reclamações</h3>
          </div>

          <div class="--item">
            <svg class="contact-icon" enable-background="new 0 0 512.01 512.01" version="1.1" viewBox="0 0 512.01 512.01" xml:space="preserve" xmlns="http://www.w3.org/2000/svg">
                <g transform="translate(-1)">
                			<path d="m483.41 0h-410.15c-16.337 0.019-29.575 13.257-29.594 29.594v368.37l-42.027 102.26c-1.31 3.177-0.586 6.831 1.837 9.268 2.423 2.438 6.071 3.184 9.257 1.893l125.27-50.585h345.4c16.336-0.019 29.575-13.257 29.594-29.594v-401.61c-0.019-16.337-13.258-29.575-29.594-29.594zm12.527 431.21c-5e-3 6.917-5.61 12.522-12.527 12.527h-347.07c-1.093-2e-3 -2.177 0.207-3.191 0.614l-108.02 43.623 34.987-85.086c0.417-1.03 0.625-2.132 0.614-3.243v-370.05c9e-3 -6.915 5.612-12.518 12.527-12.527h410.15c6.917 5e-3 12.522 5.61 12.527 12.527v401.61z"/>
                			<path d="m288.47 53.53c-3.29-3.11-8.435-3.11-11.725 0l-153.6 145.07c-3.426 3.238-3.579 8.64-0.341 12.066s8.64 3.579 12.066 0.341l147.74-139.54 147.74 139.54c3.426 3.238 8.828 3.085 12.066-0.341s3.085-8.828-0.341-12.066l-153.6-145.07z"/>
                			<path d="m410.61 230.4c-4.713 0-8.533 3.82-8.533 8.533v149.17c-0.028 2.434-1.994 4.401-4.429 4.429h-63.838v-97.971c-0.014-11.866-9.63-21.481-21.495-21.495h-59.409c-11.866 0.014-21.481 9.63-21.495 21.495v97.971h-63.838c-2.434-0.028-4.401-1.994-4.429-4.429v-149.17c0-4.713-3.821-8.533-8.533-8.533-4.713 0-8.533 3.82-8.533 8.533v149.17c0.014 11.866 9.63 21.481 21.495 21.495h230.08c11.866-0.014 21.481-9.63 21.495-21.495v-149.17c0-4.712-3.821-8.533-8.534-8.533zm-93.866 162.13h-68.267v-97.971c0-2.446 1.983-4.429 4.429-4.429h59.409c2.446 0 4.429 1.983 4.429 4.429v97.971z"/>
                			<path d="m257.01 247.47h51.2c14.138 0 25.6-11.461 25.6-25.6v-34.133c0-14.138-11.461-25.6-25.6-25.6h-51.2c-14.138 0-25.6 11.461-25.6 25.6v34.133c0 14.138 11.462 25.6 25.6 25.6zm-8.533-59.734c0-4.713 3.82-8.533 8.533-8.533h51.2c4.713 0 8.533 3.82 8.533 8.533v34.133c0 4.713-3.82 8.533-8.533 8.533h-51.2c-4.713 0-8.533-3.82-8.533-8.533v-34.133z"/>
                </g>
            </svg>
            <h3 class="--item__text">Encontre-nos</h3>
          </div>
        </div>

        <form class="contact__container__form">

          <div class="form-container">
            <div class="form-container--left">
              <input class="form-container--left__input" type="text" placeholder="Nome">
              <input class="form-container--left__input" type="text" placeholder="Sobrenome">
              <input class="form-container--left__input" type="text" placeholder="Data">
              <input class="form-container--left__input" type="text" placeholder="Assunto">
            </div>
            <textarea name="name" class="form-container--right" placeholder="Mensagem..."></textarea>
          </div>

          <button class="contact__container--btn">Enviar</button>

        </form>

      </div>
    </div>

    <modal v-if="isShow">
      <h1 slot="header" class="modal-title">Contate-nos</h1>

      <form slot="content" class="modal-form">
        <input type="text" placeholder="Nome completo" class="modal-form--input">
        <input type="text" placeholder="Assunto" class="modal-form--input">
        <textarea placeholder="Descrição..."></textarea>
      </form>

      <div slot="footer" class="container-btn">
        <button class="container-btn--item" @click="isShow = false"> Cancelar </button>
        <button class="container-btn--item" @click="sendForm()"> Enviar </button>
      </div>
    </modal>

  </section>
</template>

<script>
import SideBar from '../Main/SideBar'
import Modal from "../UIComponents/Modal"

export default {
    components: { SideBar, Modal },

    data(){
      return{
        isShow: false,
      }
    },

    methods:{
      sendForm(){
        alert('Enviado com sucesso!')
        this.isShow = false
      }
    }
}
</script>
