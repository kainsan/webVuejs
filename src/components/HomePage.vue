<template>
<div class="flex w-full lg:w-auto border-y-1 surface-border surface-overlay lg:hidden py-3 lg:py-0">
    <ul class="list-none p-0 m-0 flex w-full" style="min-height:30px;">
        <li class="flex flex-auto lg:flex-initial justify-content-center">
            <a v-ripple class="text-900 font-medium inline-flex align-items-center cursor-pointer lg:pr-3 text-700 hover:text-primary p-ripple">
                <i class="pi pi-search text-xl"></i>
                <span class="hidden">Search</span>
            </a>
        </li>
        <li class="flex flex-auto lg:flex-initial justify-content-center">
            <a v-ripple class="text-900 font-medium inline-flex align-items-center cursor-pointer lg:px-3 text-700 hover:text-primary p-ripple">
                <i class="pi pi-heart text-xl"></i>
                <span class="hidden">Favorites</span>
            </a>
        </li>
        <li class="flex flex-auto lg:flex-initial justify-content-center">
            <a v-ripple class="text-900 font-medium inline-flex align-items-center cursor-pointer lg:px-3 text-700 hover:text-primary p-ripple">
                <i class="pi pi-user text-xl"></i>
                <span class="hidden">Sign In</span>
            </a>
        </li>
        <li class="flex flex-auto lg:flex-initial justify-content-center">
            <a v-ripple class="text-900 font-medium inline-flex align-items-center cursor-pointer lg:pl-3 pr-1 text-700 hover:text-primary p-ripple">
                <i class="pi pi-shopping-cart text-xl" v-badge></i>
                <span class="hidden">Cart</span>
            </a>
        </li>
    </ul>
</div>

<div class="surface-section h-30rem bg-no-repeat bg-cover bg-center flex align-items-center" style="background: linear-gradient(0deg, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)), url(../src/components/images/blocks/content/bokunohero.jpg);">
    <div class="px-4 mx-4 lg:px-6 lg:mx-6">
        <span class="block text-3xl text-white mb-4">New Trend</span>
        <span class="block text-5xl font-medium text-white mb-4">Special Collection</span>
        <a tabindex="0" v-ripple class="py-2 w-13rem text-center block mb-4 text-xl text-white font-medium border-2 cursor-pointer surface-border-0 border-round bg-white-alpha-30 p-ripple ">Explore Collection</a>
    </div>
</div>

<div class="surface-section px-4 py-8 md:px-6 lg:px-8">
    <div class="text-900 text-4xl font-medium mb-4 text-center lg:text-left">Seasonal Collection</div>
    <p class="mt-0 p-0 mb-5 text-2xl text-600 text-center lg:text-left">Mata tincidunt dui ut ornare</p>

    <div v-for="item in items" class="grid -mt-3 -ml-3 -mr-3 flex-wrap">
        <div class="col flex px-3 flex-column mt-4 md:mt-0">
            <img :src= "item.Pic"  alt="product" style= "height: 100%; width: 25%;display: block">
            <p class="text-600 uppercase font-medium my-3">Subtitle</p>
            <a tabindex="0" class="text-xl cursor-pointer text-900 flex align-items-center hover:text-primary transition-duration-150">Category Title <i class="pi pi-fw pi-arrow-right ml-2 text-xl"></i></a>
        </div>
    </div>

</div>

<div class="surface-section px-4 py-8 md:px-6 lg:px-8">
    <div class="text-900 font-medium text-4xl mb-4">Popular Items</div>
    <p class="mt-0 p-0 mb-5 text-600 text-2xl">From Brand</p>

    <div class="grid -mt-3 -ml-3 -mr-3">
        <div class="col-12 md:col-6 lg:col-3 mb-3 lg:mb-0">
            <div class="p-2">
                <div class="relative">
                    <img src="@/components/images/blocks/ecommerce/productlist/product-list-1-1.png" class="w-full" />
                    <button type="submit" v-ripple class="p-link w-3rem h-3rem surface-0 hover:surface-200 border-circle shadow-2 inline-flex align-items-center justify-content-center absolute transition-colors transition-duration-300 p-ripple" style="top: 1rem; right: 1rem">
                        <i class="pi pi-heart text-2xl text-500"></i>
                    </button>
                </div>
                <div class="flex align-items-center justify-content-between mt-3 mb-2">
                    <span class="text-900 font-medium text-xl">Product Name</span>
                    <span class="text-900 text-xl ml-3">$14</span>
                </div>
                <span class="text-600">Black</span>
            </div>
        </div>
        <div class="col-12 md:col-6 lg:col-3 mb-3 lg:mb-0">
            <div class="p-2">
                <div class="relative">
                    <img src="@/components/images/blocks/ecommerce/productlist/product-list-1-2.png" class="w-full" />
                    <button type="submit" v-ripple class="p-link w-3rem h-3rem surface-0 hover:surface-200 border-circle shadow-2 inline-flex align-items-center justify-content-center absolute transition-colors transition-duration-300 p-ripple" style="top: 1rem; right: 1rem">
                        <i class="pi pi-heart text-2xl text-500"></i>
                    </button>
                </div>
                <div class="flex align-items-center justify-content-between mt-3 mb-2">
                    <span class="text-900 font-medium text-xl">Product Name</span>
                    <span class="text-900 text-xl ml-3">$24</span>
                </div>
                <span class="text-600">Beige</span>
            </div>
        </div>
        <div class="col-12 md:col-6 lg:col-3 mb-3 lg:mb-0">
            <div class="p-2">
                <div class="relative">
                    <img src="@/components/images/blocks/ecommerce/productlist/product-list-1-3.png" class="w-full" />
                    <button type="submit" v-ripple class="p-link w-3rem h-3rem surface-0 hover:surface-200 border-circle shadow-2 inline-flex align-items-center justify-content-center absolute transition-colors transition-duration-300 p-ripple" style="top: 1rem; right: 1rem">
                        <i class="pi pi-heart text-2xl text-500"></i>
                    </button>
                </div>
                <div class="flex align-items-center justify-content-between mt-3 mb-2">
                    <span class="text-900 font-medium text-xl">Product Name</span>
                    <span class="text-900 text-xl ml-3">$42</span>
                </div>
                <span class="text-600">White</span>
            </div>
        </div>
        <div class="col-12 md:col-6 lg:col-3">
            <div class="p-2">
                <div class="relative">
                    <img src="@/components/images/blocks/ecommerce/productlist/product-list-1-4.png" class="w-full" />
                    <button type="submit" v-ripple class="p-link w-3rem h-3rem surface-0 hover:surface-200 border-circle shadow-2 inline-flex align-items-center justify-content-center absolute transition-colors transition-duration-300 p-ripple" style="top: 1rem; right: 1rem">
                        <i class="pi pi-heart text-2xl text-500"></i>
                    </button>
                </div>
                <div class="flex align-items-center justify-content-between mt-3 mb-2">
                    <span class="text-900 font-medium text-xl">Product Name</span>
                    <span class="text-900 text-xl ml-3">$20</span>
                </div>
                <span class="text-600">Black</span>
            </div>
        </div>
    </div>
</div>

<div class="surface-section px-4 py-8 md:px-6 lg:px-8">
    <div class="surface-900 text-0 p-4" style="border-radius:10px">
        <div class="flex flex-column md:flex-row md:justify-content-between xl:justify-content-evenly">
            <span class="inline-flex align-items-center mb-3 md:mb-0">
                <i class="pi pi-shopping-cart text-base xl:text-2xl mr-3"></i>
                <span class="text-base xl:text-2xl font-medium">Free Shipping</span>
            </span>
            <span class="inline-flex align-items-center mb-3 md:mb-0">
                <i class="pi pi-refresh text-base xl:text-2xl mr-3"></i>
                <span class="text-base xl:text-2xl font-medium">120 Days Return Policy</span>
            </span>
            <span class="inline-flex align-items-center">
                <i class="pi pi-star text-base xl:text-2xl mr-3"></i>
                <span class="text-base xl:text-2xl font-medium">10 Year Warranty</span>
            </span>
        </div>
    </div>
</div>

<div class="flex flex-wrap surface-section px-4 py-8 md:px-6 lg:px-8">
    <div class="w-full md:w-6 px-4 py-8 md:px-6 lg:px-8 surface-900">
        <div class="text-4xl text-0 mb-3 font-medium">Promo Title Placeholder</div>
        <p class="line-height-3 mt-0 mb-7 p-0 text-0 text-2xl">Malesuada bibendum arcu vitae elementum curabitur vitae nunc. Aliquam nulla facilisi cras fermentum. Et egestas quis ipsum suspendisse ultrices.</p>
        <a tabindex="0" v-ripple class="text-xl cursor-pointer surface-card text-900 text-center px-5 py-3 border-1 border-gray-200 hover:text-primary transition-duration-150 select-none block w-12rem p-ripple">Read Story</a>
    </div>
    <div class="w-full md:w-6 bg-no-repeat bg-cover" style="background: url('images/blocks/ecommerce/storefront/storefront-1-17.png'); min-height: 400px;"></div>
</div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import axios from "axios";
export default defineComponent({
    name: "",
  data() {
    return {
      items:[],
    };
  },
  created() {
    this.fetchData();
  },
  methods: {
    fetchData() {
      axios
        .get("https://6489c2425fa58521cab034ca.mockapi.io/Items")
        .then((response) => {
          this.items = response.data;
        })
        .catch((error) => console.log(error));
    },
    }
});
</script>