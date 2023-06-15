<script setup lang="js">
import Footer from './Footer.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <div>
        <div class="surface-section">
                <div class="surface-900 px-4 lg:px-8 py-3 lg:py-3 flex flex-column sm:flex-row w-full justify-content-between align-items-center">
                    <span class="text-0">Sign Up for 15% off your first order</span>
                    <a tabindex="0" class="cursor-pointer h-full inline-flex align-items-center mt-3 sm:mt-0 md:py-0">
                        <img src="images/blocks/ecommerce/storefront/storefront-1-19.png" class="mr-2" alt="Flag">
                        <span class="text-0">EUR</span>
                    </a>
                </div>
                <div class="surface-overlay px-3 sm:px-7 flex flex-wrap align-items-stretch justify-content-between relative">
                    <a v-ripple class="cursor-pointer flex align-items-center lg:hidden text-700 mr-3 p-ripple"
                        v-styleclass="{ selector: '#nav-2', enterClass: 'hidden', leaveToClass: 'hidden', hideOnOutsideClick: true }">
                        <i class="pi pi-bars text-4xl"></i>
                    </a>
                    <div id="nav-2" class="surface-overlay hidden lg:flex absolute lg:static left-0 top-100 z-1 shadow-2 lg:shadow-none w-full lg:w-auto py-3 lg:py-0">
                        <ul class="list-none p-0 m-0 flex flex-column lg:flex-row">
                            <li class="flex flex-column lg:flex-row">
                                <a v-ripple class="font-medium inline-flex align-items-center cursor-pointer border-left-2 lg:border-left-none lg:border-bottom-2 border-transparent hover:border-primary 
                                    py-3 lg:py-0 px-6 lg:px-3 text-700 select-none text-xl lg:text-base lg:font-base w-full lg:w-auto p-ripple"
                                    v-styleclass="{ selector: '@next', enterClass: 'hidden', leaveToClass: 'hidden', hideOnOutsideClick: true }">
                                    <span>Women</span>
                                </a>
                                <div class="surface-overlay shadow-none lg:shadow-2 hidden lg:absolute w-full left-0 top-100 pl-8 pr-6 lg:px-6 py-0 lg:py-6">
                                    <div class="grid flex-wrap">
                                        <div class="col-12 md:col-6 xl:col-3">
                                            <a v-styleclass="{ selector: '@next', enterClass: 'hidden', leaveToClass: 'hidden' }" class="font-medium text-lg cursor-pointer text-700 block lg:hidden mb-3 select-none">Clothing</a>
                                            <ul class="list-none py-0 pr-0 lg:pl-0 pl-5 m-0 text-700 hidden lg:block">
                                                <li class="hidden lg:block">
                                                    <img src="images/blocks/ecommerce/storenavigation/storenavigation-2-1.png" alt="Image" height="160" style="border-radius:12px">
                                                </li>
                                                <li class="font-bold my-5 text-xl text-900 hidden lg:block">Clothing</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Dresses</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Jeans</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Pants</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Skirts</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Sweaters</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Blouses</li>
                                            </ul>
                                        </div>
                                        <div class="col-12 md:col-6 xl:col-3">
                                            <a v-styleclass="{ selector: '@next', enterClass: 'hidden', leaveToClass: 'hidden' }" class="font-medium text-lg cursor-pointer text-700 block lg:hidden mb-3 select-none">Shoes</a>
                                            <ul class="list-none py-0 pr-0 lg:pl-0 pl-5 m-0 text-700 hidden lg:block">
                                                <li class="hidden lg:block">
                                                    <img src="images/blocks/ecommerce/storenavigation/storenavigation-2-2.png" alt="Image" height="160" style="border-radius:12px">
                                                </li>
                                                <li class="font-bold my-5 text-xl text-900 hidden lg:block">Shoes</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Athletic</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Boots</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Sneakers</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Flats</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Outdoor</li>
                                            </ul>
                                        </div>
                                        <div class="col-12 md:col-6 xl:col-3">
                                            <a v-styleclass="{ selector: '@next', enterClass: 'hidden', leaveToClass: 'hidden' }" class="font-medium text-lg cursor-pointer text-700 block lg:hidden mb-3 select-none">Accessories</a>
                                            <ul class="list-none py-0 pr-0 lg:pl-0 pl-5 m-0 text-700 hidden lg:block">
                                                <li class="hidden lg:block">
                                                    <img src="images/blocks/ecommerce/storenavigation/storenavigation-2-3.png" alt="Image" height="160" style="border-radius:12px">
                                                </li>
                                                <li class="font-bold my-5 text-xl text-900 hidden lg:block">Accessories</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Handbags</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Gloves</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Belts</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Hats</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Earmuffs</li>
                                            </ul>
                                        </div>
                                        <div class="col-12 md:col-6 xl:col-3">
                                            <a v-styleclass="{ selector: '@next', enterClass: 'hidden', leaveToClass: 'hidden' }" class="font-medium text-lg cursor-pointer text-700 block lg:hidden mb-3 select-none">Beauty</a>
                                            <ul class="list-none py-0 pr-0 lg:pl-0 pl-5 m-0 text-700 hidden lg:block">
                                                <li class="hidden lg:block">
                                                    <img src="images/blocks/ecommerce/storenavigation/storenavigation-2-4.png" alt="Image" height="160" style="border-radius:12px">
                                                </li>
                                                <li class="font-bold my-5 text-xl text-900 hidden lg:block">Beauty</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Anklets</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Bracelets</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Earrings</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Necklaces</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Rings</li>
                                                <li class="mb-3 cursor-pointer hover:text-900">Wedding</li>
                                            </ul>
                                        </div>
                                    </div>
                                </div>
                            </li>
                            <li class="flex flex-column lg:flex-row">
                                <a v-ripple class="font-medium inline-flex align-items-center cursor-pointer border-left-2 lg:border-left-none lg:border-bottom-2 border-transparent 
                                    hover:border-primary py-3 lg:py-0 px-6 lg:px-3 text-700 select-none text-xl lg:text-base font-medium lg:font-base w-full lg:w-auto p-ripple"
                                    v-styleclass="{ selector: '@next', enterClass: 'hidden', leaveToClass: 'hidden', hideOnOutsideClick: true }">
                                    <span>Men</span>
                                </a>
                                <div class="surface-overlay shadow-none lg:shadow-2 hidden lg:absolute w-full left-0 top-100 px-6 py-0 lg:py-6 h-10rem lg:h-30rem">
                                    <div class="border-2 border-dashed surface-border border-round h-full"></div>
                                </div>
                            </li>
                            <li class="flex flex-column lg:flex-row">
                                <a v-ripple class="font-medium inline-flex align-items-center cursor-pointer border-left-2 lg:border-left-none lg:border-bottom-2 border-transparent 
                                    hover:border-primary py-3 lg:py-0 px-6 lg:px-3 text-700 select-none text-xl lg:text-base font-medium lg:font-base w-full lg:w-auto p-ripple"
                                    v-styleclass="{ selector: '@next', enterClass: 'hidden', leaveToClass: 'hidden', hideOnOutsideClick: true }">
                                    <span>Kids</span>
                                </a>
                                <div class="surface-overlay shadow-none lg:shadow-2 hidden lg:absolute w-full left-0 top-100 px-6 py-0 lg:py-6 h-10rem lg:h-30rem">
                                    <div class="border-2 border-dashed surface-border border-round h-full"></div>
                                </div>
                            </li>
                        </ul>
                    </div>
                
                    <div class="flex align-items-center justify-content-center py-3">
                        <img src="images/blocks/logos/peak-700.svg" alt="Image" height="40">
                    </div>
                    <div class="lg:flex w-full lg:w-auto hidden py-3 lg:py-0">
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
                                <a v-ripple class="text-900 font-medium inline-flex align-items-center cursor-pointer lg:pl-3 pr-3 text-700 hover:text-primary p-ripple">
                                    <i class="pi pi-shopping-cart text-xl" v-badge></i>
                                    <span class="hidden">Cart</span>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
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
                
                <div class="surface-section h-30rem bg-no-repeat bg-cover bg-center flex align-items-center" style="background: linear-gradient(0deg, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)), url(images/blocks/ecommerce/storefront/storefront-1-18.png);">
                    <div class="px-4 mx-4 lg:px-6 lg:mx-6">
                        <span class="block text-3xl text-white mb-4">New Trend</span>
                        <span class="block text-5xl font-medium text-white mb-4">Special Collection</span>
                        <a tabindex="0" v-ripple class="py-2 w-13rem text-center block mb-4 text-xl text-white font-medium border-2 cursor-pointer surface-border-0 border-round bg-white-alpha-30 p-ripple">Explore Collection</a>
                    </div>
                </div>

                <div class="surface-section px-4 py-8 md:px-6 lg:px-8">
                    <div class="text-900 text-4xl font-medium mb-4 text-center lg:text-left">Seasonal Collection</div>
                    <p class="mt-0 p-0 mb-5 text-2xl text-600 text-center lg:text-left">Mata tincidunt dui ut ornare</p>
            
                    <div class="grid -mt-3 -ml-3 -mr-3 flex-wrap">
                        <div class="col flex px-3 flex-column mt-4 md:mt-0">
                            <img src="images/blocks/ecommerce/categorypreview/category-preview-1-1.png" class="w-full h-full" alt="product">
                            <p class="text-600 uppercase font-medium my-3">Subtitle</p>
                            <a tabindex="0" class="text-xl cursor-pointer text-900 flex align-items-center hover:text-primary transition-duration-150">Category Title <i class="pi pi-fw pi-arrow-right ml-2 text-xl"></i></a>
                        </div>
                        <div class="col flex px-3 flex-column mt-4 md:mt-0">
                            <img src="images/blocks/ecommerce/categorypreview/category-preview-1-2.png" class="w-full h-full" alt="product">
                            <p class="text-600 uppercase font-medium my-3">Subtitle</p>
                            <a tabindex="0" class="text-xl cursor-pointer text-900 flex align-items-center hover:text-primary transition-duration-150">Category Title <i class="pi pi-fw pi-arrow-right ml-2 text-xl"></i></a>
                        </div>
                        <div class="col flex px-3 flex-column mt-4 md:mt-0">
                            <img src="images/blocks/ecommerce/categorypreview/category-preview-1-3.png" class="w-full h-full" alt="product">
                            <p class="text-600 uppercase font-medium my-3">Subtitle</p>
                            <a tabindex="0" class="text-xl cursor-pointer text-900 flex align-items-center hover:text-primary transition-duration-150">Category Title <i class="pi pi-fw pi-arrow-right ml-2 text-xl"></i></a>
                        </div>
                        <div class="col flex px-3 flex-column mt-4 md:mt-0">
                            <img src="images/blocks/ecommerce/categorypreview/category-preview-1-4.png" class="w-full h-full" alt="product">
                            <p class="text-600 uppercase font-medium my-3">Subtitle</p>
                            <a tabindex="0" class="text-xl cursor-pointer text-900 flex align-items-center hover:text-primary transition-duration-150">Category Title <i class="pi pi-fw pi-arrow-right ml-2 text-xl"></i></a>
                        </div>
                        <div class="col flex px-3 flex-column mt-4 md:mt-0">
                            <img src="images/blocks/ecommerce/categorypreview/category-preview-1-5.png" class="w-full h-full" alt="product">
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
                                    <img src="images/blocks/ecommerce/productlist/product-list-1-1.png" class="w-full" />
                                    <button type="text" v-ripple class="p-link w-3rem h-3rem surface-0 hover:surface-200 border-circle shadow-2 inline-flex align-items-center justify-content-center absolute transition-colors transition-duration-300 p-ripple" style="top: 1rem; right: 1rem">
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
                                    <img src="images/blocks/ecommerce/productlist/product-list-1-2.png" class="w-full" />
                                    <button type="text" v-ripple class="p-link w-3rem h-3rem surface-0 hover:surface-200 border-circle shadow-2 inline-flex align-items-center justify-content-center absolute transition-colors transition-duration-300 p-ripple" style="top: 1rem; right: 1rem">
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
                                    <img src="images/blocks/ecommerce/productlist/product-list-1-3.png" class="w-full" />
                                    <button type="text" v-ripple class="p-link w-3rem h-3rem surface-0 hover:surface-200 border-circle shadow-2 inline-flex align-items-center justify-content-center absolute transition-colors transition-duration-300 p-ripple" style="top: 1rem; right: 1rem">
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
                                    <img src="images/blocks/ecommerce/productlist/product-list-1-4.png" class="w-full" />
                                    <button type="text" v-ripple class="p-link w-3rem h-3rem surface-0 hover:surface-200 border-circle shadow-2 inline-flex align-items-center justify-content-center absolute transition-colors transition-duration-300 p-ripple" style="top: 1rem; right: 1rem">
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

                <div class="surface-50 px-4 py-8 md:px-6 lg:px-8">
                    <span class="text-900 text-3xl font-medium block text-center lg:text-left">Get 25% Discount Today!</span>
                    <span class="text-600 text-2xl block mt-4 text-center lg:text-left">Sign up our email list and know all about new collections of Peak</span>
                    <div class="mt-4 mx-auto lg:mx-0" style="max-width:38rem;">
                        <div class="p-inputgroup">
                            <InputText type="text" placeholder="Enter your email address" />
                            <Button label="Subscribe" class="surface-900 text-0 px-5 border-none"></Button>
                        </div>
                    </div>
                    <Divider layout="horizontal" class="surface-border"></Divider>
                    <div class="grid grid-nogutter text-center lg:text-left">
                        <div class="col-12 sm:col-6 md:col-4 lg:col-3 mt-4 flex flex-column align-items-center lg:align-items-start">
                            <img src="images/blocks/logos/peak-700.svg" class="w-9rem mx-auto lg:mx-0" alt="Peak logo">
                            <div class="flex align-items-center w-full mt-5 justify-content-center lg:justify-content-start">
                                <a tabindex="0" class="cursor-pointer mr-3">
                                    <i class="pi pi-facebook surface-900 p-1 text-sm border-circle text-0"></i>
                                </a>
                                <a tabindex="0" class="cursor-pointer mr-3">
                                    <i class="pi pi-twitter surface-900 p-1 text-sm border-circle text-0"></i>
                                </a>
                                <a tabindex="0" class="cursor-pointer mr-3">
                                    <i class="pi pi-youtube surface-900 p-1 text-sm border-circle text-0"></i>
                                </a>
                                <a tabindex="0" class="cursor-pointer">
                                    <i class="pi pi-google surface-900 p-1 text-sm border-circle text-0"></i>
                                </a>
                            </div>
                            <span class="text-600 block mt-4"><i class="pi pi-phone mr-2"></i>1234 / 12 34 567</span>
                            <a tabindex="0" class="text-600 block mt-4 cursor-pointer hover:text-900 transition-duration-150 select-none w-8rem"><i class="pi pi-map-marker mr-2"></i>Contact Us</a>
                        </div>
                        <div class="col-12 sm:col-6 md:col-4 lg:col-3 mt-4 flex flex-column">
                            <span class="text-900 text-xl font-medium block">Company</span>
                            <ul class="list-none p-0">
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">About Peak</a></li>
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">Factories</a></li>
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">Careers</a></li>
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">Environmental Initiatives</a></li>
                            </ul>
                        </div>
                        <div class="col-12 sm:col-6 md:col-4 lg:col-3 mt-4 flex flex-column">
                            <span class="text-900 text-xl font-medium block">Account</span>
                            <ul class="list-none p-0">
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">Manage Account</a></li>
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">Saved Items</a></li>
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">My Cart</a></li>
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">Wishlist</a></li>
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">Orders & Returns</a></li>
                            </ul>
                        </div>
                        <div class="col-12 sm:col-6 md:col-4 lg:col-3 mt-4 flex flex-column">
                            <span class="text-900 text-xl font-medium block">Legal</span>
                            <ul class="list-none p-0">
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">Investor Relations</a></li>
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">Data Privacy</a></li>
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">Terms of Service</a></li>
                                <li><a tabindex="0" class="text-600 hover:text-900 transition-duration-150 cursor-pointer mt-3 block">Legal Information</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
  </div>
</template>
