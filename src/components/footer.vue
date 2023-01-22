<template>
    <footer class="shadow-2xl relative flex justify-start sm:justify-center md:justify-center md:items-end p-5 text-black">
      <div class="flex flex-col justify-start items-start md:justify-center md:items-center relative z-10">
          <div class="flex flex-col items-start justify-start xl:justify-center xl:space-x-8 xl:flex-row">
              <div class="flex justify-start items-center space-x-4">
                  <div class="cursor-pointer w-16">
                      <img src="../assets/logo.png" alt="logo">
                  </div>
                  <p class="w-60 text-xl xl:text-2xl font-semibold leading-normal text-black"></p>
              </div>
              <div class="mt-12 xl:mt-0 grid grid-cols-1 sm:grid-cols-3 gap-y-12 sm:gap-y-0 w-full md:w-auto sm:gap-x-20 md:gap-x-28 xl:gap-8">
                  <div class="sm:w-40 md:w-auto xl:w-72 flex justify-start items-start flex-col space-y-6">
                      <h2 class="text-base xl:text-xl font-bold xl:font-semibold leading-4 xl:leading-5">Telephone</h2>
                      <button class="underline text-left text-base hover:text-base-400 leading-none text-base-100">
                          +212658673429
                      </button>
                      <button class="underline text-left text-base hover:text-base-400 leading-none text-base-100">
                          +212661500473
                      </button>
                      <button class="underline text-left text-base hover:text-base-400 leading-none text-base-100">
                          +212623692931
                      </button>
                  </div>

                    <div class=" xl:w-72 flex justify-start items-start flex-col space-y-6">
                      <h2 class="text-base xl:text-xl font-bold xl:font-semibold leading-4 xl:leading-5">Adresse</h2>
                      <button class="underline text-base text-left hover:text-base-400 leading-none text-base-100">
                          N° 245 AV BOUJDOUR
                      </button>
                      <button class="underline text-base text-left hover:text-base-400 leading-none text-base-100">
                          SAFI MAROC
                      </button>
                  </div>

                  <div class="sm:w-40 md:w-auto xl:w-72 flex justify-start items-start flex-col space-y-6">
                      <h2 class="text-base xl:text-xl font-bold xl:font-semibold leading-4 xl:leading-5">E-mail</h2>
                      <button class="underline text-left text-base hover:text-base-400 leading-none text-base-100">
                          mwcpartner@gmail.com
                      </button>
                  </div>
              </div>
          </div>
          <div class="mt-12 flex  xl:justify-between xl:flex-row flex-col-reverse items-center xl:items-start w-full ">
              <p class="mt-10 md:mt-12 xl:mt-0 text-sm leading-none" >2023<span class="font-bold text-sm text-green-600 ml-1">MWC Partner</span>. All Rights Reserved</p>
              <div class="mt-10 md:mt-12 xl:mt-0 md:flex-row flex-col flex md:justify-center w-full md:w-auto justify-start items-start space-y-4 md:space-y-0 md:items-center md:space-x-4 xl:space-x-6">
                  <!-- <button class="text-base leading-none hover:text-base-300">
                      Terms of service
                  </button>
                  <button class="text-base leading-none hover:text-base-300">
                      Privacy Policy
                  </button>
                  <button class="text-base leading-none hover:text-base-300">
                      Security
                  </button>
                  <button class="text-base leading-none hover:text-base-300">
                      Sitemap
                  </button> -->
                  Directed By
                  <span class="font-bold text-sm text-green-600 ml-1">Hicham ER-RAFII</span>
              </div>
              <div class="flex  justify-start md:justify-end items-start  w-full md:w-auto md:items-center space-x-6 ">
                  <button class="hover:text-base-200 w-6">
                      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M23.25 5.13282C22.406 5.49955 21.513 5.74116 20.5992 5.85001C21.5595 5.28769 22.2817 4.39434 22.6303 3.33751C21.7224 3.86841 20.7307 4.24092 19.6978 4.43907C19.2629 3.98322 18.7397 3.62059 18.1603 3.3732C17.5808 3.12581 16.9571 2.99884 16.327 3.00001C13.7761 3.00001 11.7117 5.03438 11.7117 7.5422C11.7099 7.89102 11.7499 8.23881 11.8308 8.57813C10.0016 8.49238 8.2104 8.02575 6.57187 7.2081C4.93333 6.39044 3.48351 5.23977 2.31516 3.8297C1.90527 4.52069 1.6885 5.30909 1.6875 6.11251C1.6875 7.68751 2.50922 9.0797 3.75 9.89532C3.01487 9.87787 2.29481 9.68331 1.65094 9.32813V9.38438C1.65094 11.5875 3.24469 13.4203 5.35406 13.8375C4.9574 13.9433 4.54864 13.9968 4.13812 13.9969C3.84683 13.9974 3.5562 13.9691 3.27047 13.9125C3.85687 15.7172 5.56359 17.0297 7.58531 17.0672C5.94252 18.3333 3.9256 19.0175 1.85156 19.0125C1.48341 19.012 1.11561 18.99 0.75 18.9469C2.85993 20.2942 5.31255 21.0068 7.81594 21C16.3172 21 20.9616 14.0766 20.9616 8.07188C20.9616 7.87501 20.9564 7.67813 20.947 7.48595C21.8485 6.84472 22.6283 6.04787 23.25 5.13282V5.13282Z" fill="currentColor"/>
                          </svg>
                  </button>
                  <button class="hover:text-base-200 w-6">
                    <svg
                class="w-6 h-6"
                fill="currentColor"
                viewBox="0 0 24 24"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
                  clip-rule="evenodd"
                />
              </svg>
                  </button>
                  <button class="hover:text-base-200 w-6">
                      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path fill-rule="evenodd" clip-rule="evenodd" d="M22.5 12.0645C22.5 6.26602 17.7984 1.56445 12 1.56445C6.20156 1.56445 1.5 6.26602 1.5 12.0645C1.5 17.3051 5.33906 21.649 10.3594 22.4374V15.1005H7.69266V12.0645H10.3594V9.75117C10.3594 7.12008 11.9273 5.66555 14.3255 5.66555C15.4744 5.66555 16.6763 5.87086 16.6763 5.87086V8.45508H15.3516C14.048 8.45508 13.6402 9.26414 13.6402 10.0957V12.0645H16.552L16.087 15.1005H13.6406V22.4384C18.6609 21.6504 22.5 17.3065 22.5 12.0645Z" fill="currentColor"/>
                          </svg>
                  </button>
                  <button class="hover:text-base-200 w-6">
                      <svg
                width="24"
                height="24"
                viewBox="0 0 14 14"
                class="fill-current"
              >
                <path
                  d="M13.0214 0H1.02084C0.453707 0 0 0.451613 0 1.01613V12.9839C0 13.5258 0.453707 14 1.02084 14H12.976C13.5432 14 13.9969 13.5484 13.9969 12.9839V0.993548C14.0422 0.451613 13.5885 0 13.0214 0ZM4.15142 11.9H2.08705V5.23871H4.15142V11.9ZM3.10789 4.3129C2.42733 4.3129 1.90557 3.77097 1.90557 3.11613C1.90557 2.46129 2.45002 1.91935 3.10789 1.91935C3.76577 1.91935 4.31022 2.46129 4.31022 3.11613C4.31022 3.77097 3.81114 4.3129 3.10789 4.3129ZM11.9779 11.9H9.9135V8.67097C9.9135 7.90323 9.89082 6.8871 8.82461 6.8871C7.73571 6.8871 7.57691 7.74516 7.57691 8.60323V11.9H5.51254V5.23871H7.53154V6.16452H7.55423C7.84914 5.62258 8.50701 5.08065 9.52785 5.08065C11.6376 5.08065 12.0232 6.43548 12.0232 8.2871V11.9H11.9779Z"
                />
              </svg>
                  </button>
              </div>
          </div>
      </div>
  </footer>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">

</style>
